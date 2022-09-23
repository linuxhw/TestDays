Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 54

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Timi          | A35S                        | Notebook    | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP            | 2B05                        | Desktop     | [c2dcdaa38a](https://linux-hardware.org/?probe=c2dcdaa38a) | Sep 19, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Irbis         | NB264                       | Notebook    | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [247e54458c](https://linux-hardware.org/?probe=247e54458c) | Sep 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [e138435857](https://linux-hardware.org/?probe=e138435857) | Sep 17, 2022 |
| HP            | 3397                        | Desktop     | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [c62891882f](https://linux-hardware.org/?probe=c62891882f) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | Notebook    | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | Desktop     | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [b2b1324db9](https://linux-hardware.org/?probe=b2b1324db9) | Apr 22, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |
| HP            | 0B54h D                     | Desktop     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | Desktop     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| 5.19.8-300.fc37.x86_64                                 | 15        | 31.91%  |
| 5.19.9-300.fc37.x86_64                                 | 10        | 21.28%  |
| 5.19.7-300.fc37.x86_64                                 | 5         | 10.64%  |
| 5.19.10-300.fc37.x86_64                                | 4         | 8.51%   |
| 5.19.0-65.fc37.x86_64                                  | 2         | 4.26%   |
| 5.18.0-0.rc2.23.fc37.x86_64                            | 2         | 4.26%   |
| 5.19.8-501.chinfo.fc37.x86_64                          | 1         | 2.13%   |
| 5.19.6-300.fc37.aarch64                                | 1         | 2.13%   |
| 5.19.4-300.fc37.x86_64                                 | 1         | 2.13%   |
| 5.19.0-xm2.0.fc37.x86_64                               | 1         | 2.13%   |
| 5.19.0-0.rc6.20220714git4a57a8400075.49.fc37.x86_64    | 1         | 2.13%   |
| 5.19.0-0.rc1.20220610git874c8ca1e60b.18.fc37.x86_64    | 1         | 2.13%   |
| 5.18.0-0.rc5.20220505gita7391ad3572431a.43.fc37.x86_64 | 1         | 2.13%   |
| 5.18.0-0.rc3.27.fc37.x86_64                            | 1         | 2.13%   |
| 5.17.0-0.rc6.109.fc37.x86_64                           | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.8  | 16        | 34.04%  |
| 5.19.9  | 10        | 21.28%  |
| 5.19.7  | 5         | 10.64%  |
| 5.19.0  | 5         | 10.64%  |
| 5.19.10 | 4         | 8.51%   |
| 5.18.0  | 4         | 8.51%   |
| 5.19.6  | 1         | 2.13%   |
| 5.19.4  | 1         | 2.13%   |
| 5.17.0  | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 42        | 89.36%  |
| 5.18    | 4         | 8.51%   |
| 5.17    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 46        | 97.87%  |
| aarch64 | 1         | 2.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 34        | 72.34%  |
| KDE5       | 9         | 19.15%  |
| XFCE       | 3         | 6.38%   |
| X-Cinnamon | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 33        | 70.21%  |
| X11     | 13        | 27.66%  |
| Tty     | 1         | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 51.06%  |
| GDM     | 11        | 23.4%   |
| SDDM    | 7         | 14.89%  |
| LightDM | 5         | 10.64%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 22        | 46.81%  |
| en_GB | 4         | 8.51%   |
| pt_BR | 3         | 6.38%   |
| fr_FR | 3         | 6.38%   |
| en_CA | 3         | 6.38%   |
| de_DE | 3         | 6.38%   |
| ru_RU | 2         | 4.26%   |
| ro_RO | 1         | 2.13%   |
| nl_NL | 1         | 2.13%   |
| it_IT | 1         | 2.13%   |
| fi_FI | 1         | 2.13%   |
| es_GT | 1         | 2.13%   |
| es_AR | 1         | 2.13%   |
| en_ZA | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 38        | 80.85%  |
| BIOS | 9         | 19.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 38        | 80.85%  |
| Ext4  | 7         | 14.89%  |
| Xfs   | 2         | 4.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 51.06%  |
| GPT     | 22        | 46.81%  |
| MBR     | 1         | 2.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 89.36%  |
| Yes       | 5         | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 80.85%  |
| Yes       | 9         | 19.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 13        | 27.66%  |
| Lenovo                  | 10        | 21.28%  |
| Hewlett-Packard         | 6         | 12.77%  |
| Gigabyte Technology     | 4         | 8.51%   |
| HUAWEI                  | 3         | 6.38%   |
| Dell                    | 2         | 4.26%   |
| Acer                    | 2         | 4.26%   |
| TUXEDO                  | 1         | 2.13%   |
| Timi                    | 1         | 2.13%   |
| System76                | 1         | 2.13%   |
| Samsung Electronics     | 1         | 2.13%   |
| Raspberry Pi Foundation | 1         | 2.13%   |
| MSI                     | 1         | 2.13%   |
| Irbis                   | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI HVY-WXX9                            | 2         | 4.26%   |
| ASUS TUF Gaming B550M-PLUS                 | 2         | 4.26%   |
| TUXEDO InfinityBook S 15/17 Gen7           | 1         | 2.13%   |
| Timi A35S                                  | 1         | 2.13%   |
| System76 Lemur Pro                         | 1         | 2.13%   |
| Samsung 270E5G/270E5U                      | 1         | 2.13%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 1         | 2.13%   |
| MSI MS-7B47                                | 1         | 2.13%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2.13%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20UAS0X800 | 1         | 2.13%   |
| Lenovo ThinkPad W510 4391F66               | 1         | 2.13%   |
| Lenovo ThinkPad T14 Gen 2a 20XK000YSP      | 1         | 2.13%   |
| Lenovo ThinkPad T14 Gen 1 20UES08Q15       | 1         | 2.13%   |
| Lenovo ThinkPad Edge E540 20C600AKZA       | 1         | 2.13%   |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 2.13%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD           | 1         | 2.13%   |
| Lenovo IdeaPad 5 Pro 14ARH7 82SJ           | 1         | 2.13%   |
| Lenovo IdeaPad 320-15IAP 80XR              | 1         | 2.13%   |
| Irbis NB264                                | 1         | 2.13%   |
| HUAWEI DRC-WXX                             | 1         | 2.13%   |
| HP Z600 Workstation                        | 1         | 2.13%   |
| HP Laptop 17-cp0xxx                        | 1         | 2.13%   |
| HP Laptop 14-dq2xxx                        | 1         | 2.13%   |
| HP EliteBook 820 G1                        | 1         | 2.13%   |
| HP Compaq Elite 8300 SFF                   | 1         | 2.13%   |
| HP 110-516no                               | 1         | 2.13%   |
| Gigabyte X570 I AORUS PRO WIFI             | 1         | 2.13%   |
| Gigabyte X570 AORUS MASTER                 | 1         | 2.13%   |
| Gigabyte B85M-D3V-A                        | 1         | 2.13%   |
| Gigabyte AB350N-Gaming WIFI                | 1         | 2.13%   |
| Dell XPS 9320                              | 1         | 2.13%   |
| Dell OptiPlex 3050                         | 1         | 2.13%   |
| ASUS ZenBook UX425IA_UM425IA               | 1         | 2.13%   |
| ASUS Z170-A                                | 1         | 2.13%   |
| ASUS TUF Gaming X570-PLUS                  | 1         | 2.13%   |
| ASUS T101HA                                | 1         | 2.13%   |
| ASUS ROG Zephyrus M16 GU603ZX_GU603ZX      | 1         | 2.13%   |
| ASUS ProArt Z690-CREATOR WIFI              | 1         | 2.13%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI            | 1         | 2.13%   |
| ASUS PRIME Z270-A                          | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 6         | 12.77%  |
| ASUS TUF               | 3         | 6.38%   |
| Lenovo IdeaPad         | 2         | 4.26%   |
| HUAWEI HVY-WXX9        | 2         | 4.26%   |
| HP Laptop              | 2         | 4.26%   |
| Gigabyte X570          | 2         | 4.26%   |
| ASUS PRIME             | 2         | 4.26%   |
| TUXEDO InfinityBook    | 1         | 2.13%   |
| Timi A35S              | 1         | 2.13%   |
| System76 Lemur         | 1         | 2.13%   |
| Samsung 270E5G         | 1         | 2.13%   |
| RPi Raspberry          | 1         | 2.13%   |
| MSI MS-7B47            | 1         | 2.13%   |
| Lenovo ThinkBook       | 1         | 2.13%   |
| Lenovo Legion          | 1         | 2.13%   |
| Irbis NB264            | 1         | 2.13%   |
| HUAWEI DRC-WXX         | 1         | 2.13%   |
| HP Z600                | 1         | 2.13%   |
| HP EliteBook           | 1         | 2.13%   |
| HP Compaq              | 1         | 2.13%   |
| HP 110-516no           | 1         | 2.13%   |
| Gigabyte B85M-D3V-A    | 1         | 2.13%   |
| Gigabyte AB350N-Gaming | 1         | 2.13%   |
| Dell XPS               | 1         | 2.13%   |
| Dell OptiPlex          | 1         | 2.13%   |
| ASUS ZenBook           | 1         | 2.13%   |
| ASUS Z170-A            | 1         | 2.13%   |
| ASUS T101HA            | 1         | 2.13%   |
| ASUS ROG               | 1         | 2.13%   |
| ASUS ProArt            | 1         | 2.13%   |
| ASUS Pro               | 1         | 2.13%   |
| ASUS P8Z68-V           | 1         | 2.13%   |
| ASUS ASUS              | 1         | 2.13%   |
| Acer Spin              | 1         | 2.13%   |
| Acer Nitro             | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 11        | 23.4%   |
| 2021 | 9         | 19.15%  |
| 2022 | 6         | 12.77%  |
| 2017 | 5         | 10.64%  |
| 2019 | 4         | 8.51%   |
| 2013 | 3         | 6.38%   |
| 2015 | 2         | 4.26%   |
| 2010 | 2         | 4.26%   |
| 2018 | 1         | 2.13%   |
| 2016 | 1         | 2.13%   |
| 2014 | 1         | 2.13%   |
| 2012 | 1         | 2.13%   |
| 2011 | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 25        | 53.19%  |
| Desktop        | 18        | 38.3%   |
| Tablet         | 2         | 4.26%   |
| System on chip | 1         | 2.13%   |
| Convertible    | 1         | 2.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 44        | 93.62%  |
| Enabled  | 3         | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 97.87%  |
| Yes  | 1         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 10        | 21.28%  |
| 16.01-24.0      | 10        | 21.28%  |
| 8.01-16.0       | 10        | 21.28%  |
| 4.01-8.0        | 7         | 14.89%  |
| 3.01-4.0        | 3         | 6.38%   |
| 64.01-256.0     | 3         | 6.38%   |
| 24.01-32.0      | 2         | 4.26%   |
| More than 256.0 | 1         | 2.13%   |
| 1.01-2.0        | 1         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 31.91%  |
| 2.01-3.0   | 10        | 21.28%  |
| 3.01-4.0   | 8         | 17.02%  |
| 8.01-16.0  | 7         | 14.89%  |
| 1.01-2.0   | 6         | 12.77%  |
| 24.01-32.0 | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 59.57%  |
| 2      | 7         | 14.89%  |
| 4      | 5         | 10.64%  |
| 3      | 4         | 8.51%   |
| 0      | 2         | 4.26%   |
| 5      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 78.72%  |
| Yes       | 10        | 21.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 68.09%  |
| No        | 15        | 31.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 78.72%  |
| No        | 10        | 21.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 74.47%  |
| No        | 12        | 25.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 19.15%  |
| Germany      | 4         | 8.51%   |
| France       | 4         | 8.51%   |
| Poland       | 3         | 6.38%   |
| Canada       | 3         | 6.38%   |
| Brazil       | 3         | 6.38%   |
| Sweden       | 2         | 4.26%   |
| South Africa | 2         | 4.26%   |
| Japan        | 2         | 4.26%   |
| UK           | 1         | 2.13%   |
| Spain        | 1         | 2.13%   |
| Russia       | 1         | 2.13%   |
| Norway       | 1         | 2.13%   |
| Netherlands  | 1         | 2.13%   |
| Moldova      | 1         | 2.13%   |
| Mexico       | 1         | 2.13%   |
| Malaysia     | 1         | 2.13%   |
| Italy        | 1         | 2.13%   |
| Indonesia    | 1         | 2.13%   |
| Finland      | 1         | 2.13%   |
| Czechia      | 1         | 2.13%   |
| Belarus      | 1         | 2.13%   |
| Austria      | 1         | 2.13%   |
| Argentina    | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Warsaw             | 3         | 6.38%   |
| New York           | 2         | 4.26%   |
| Goiânia           | 2         | 4.26%   |
| Berlin             | 2         | 4.26%   |
| Zierikzee          | 1         | 2.13%   |
| Wytheville         | 1         | 2.13%   |
| Vaxjo              | 1         | 2.13%   |
| Vancouver          | 1         | 2.13%   |
| Valbonne           | 1         | 2.13%   |
| Tokyo              | 1         | 2.13%   |
| Surabaya           | 1         | 2.13%   |
| Shinagawa          | 1         | 2.13%   |
| Scarborough        | 1         | 2.13%   |
| Sao Paulo          | 1         | 2.13%   |
| San Antonio        | 1         | 2.13%   |
| San Andres Cholula | 1         | 2.13%   |
| Rosario            | 1         | 2.13%   |
| Queens             | 1         | 2.13%   |
| Plancher-les-Mines | 1         | 2.13%   |
| Palaiseau          | 1         | 2.13%   |
| Oslo               | 1         | 2.13%   |
| Orekhovo-Zuyevo    | 1         | 2.13%   |
| Mt. Pleasant       | 1         | 2.13%   |
| Mokena             | 1         | 2.13%   |
| Minsk              | 1         | 2.13%   |
| Matzendorf         | 1         | 2.13%   |
| Málaga            | 1         | 2.13%   |
| Laenghem           | 1         | 2.13%   |
| Kuala Lumpur       | 1         | 2.13%   |
| Kingston           | 1         | 2.13%   |
| Hukvaldy           | 1         | 2.13%   |
| Houston            | 1         | 2.13%   |
| Helsinki           | 1         | 2.13%   |
| Guglionesi         | 1         | 2.13%   |
| Fonsorbes          | 1         | 2.13%   |
| Erfurt             | 1         | 2.13%   |
| Eberswalde         | 1         | 2.13%   |
| Denton             | 1         | 2.13%   |
| Centurion          | 1         | 2.13%   |
| Cape Town          | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 21        | 28     | 32.81%  |
| Seagate                     | 9         | 12     | 14.06%  |
| WDC                         | 7         | 12     | 10.94%  |
| Kingston                    | 7         | 7      | 10.94%  |
| Unknown                     | 3         | 4      | 4.69%   |
| Toshiba                     | 2         | 2      | 3.13%   |
| SanDisk                     | 2         | 2      | 3.13%   |
| Micron Technology           | 2         | 2      | 3.13%   |
| A-DATA Technology           | 2         | 2      | 3.13%   |
| YMTC                        | 1         | 1      | 1.56%   |
| Yangtze Memory Technologies | 1         | 1      | 1.56%   |
| SK hynix                    | 1         | 1      | 1.56%   |
| Silicon Motion              | 1         | 1      | 1.56%   |
| Micron/Crucial Technology   | 1         | 1      | 1.56%   |
| KIOXIA                      | 1         | 1      | 1.56%   |
| Kingston Technology Company | 1         | 1      | 1.56%   |
| Intel                       | 1         | 1      | 1.56%   |
| Crucial                     | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 1TB                | 3         | 4.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 4.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 4.05%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 2.7%    |
| Kingston OM8PCP3512F-AB 512GB                       | 2         | 2.7%    |
| YMTC PC005 512GB                                    | 1         | 1.35%   |
| Yangtze Memory NVMe SSD Drive 512GB                 | 1         | 1.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 1.35%   |
| WDC WDS500G1B0C-00S6U0 500GB                        | 1         | 1.35%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 1         | 1.35%   |
| WDC WD40PURX-64GVNY0 4TB                            | 1         | 1.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1         | 1.35%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1         | 1.35%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1         | 1.35%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.35%   |
| WDC WD10EVDS-63U8B1 1TB                             | 1         | 1.35%   |
| WDC WD10EFRX-68FYTN0 1TB                            | 1         | 1.35%   |
| WDC WD My Passport 25F3 512GB                       | 1         | 1.35%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB                | 1         | 1.35%   |
| Unknown SL64G  64GB                                 | 1         | 1.35%   |
| Unknown MMC Card  64GB                              | 1         | 1.35%   |
| Unknown MMC Card  128GB                             | 1         | 1.35%   |
| Unknown 032GE4  32GB                                | 1         | 1.35%   |
| Toshiba THNSN5256GPU7 256GB                         | 1         | 1.35%   |
| Toshiba DT01ACA200 2TB                              | 1         | 1.35%   |
| SK hynix SHGP31-1000GM 1TB                          | 1         | 1.35%   |
| Silicon Motion PCIe-8 SSD 512GB                     | 1         | 1.35%   |
| Seagate ST4000DM000-1F2168 4TB                      | 1         | 1.35%   |
| Seagate ST3500413AS 500GB                           | 1         | 1.35%   |
| Seagate ST31000528AS 1TB                            | 1         | 1.35%   |
| Seagate ST2000LX001-1RG174 2TB                      | 1         | 1.35%   |
| Seagate ST2000DM008-2UB102 2TB                      | 1         | 1.35%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.35%   |
| Seagate ST1000DM003-1SB102 1TB                      | 1         | 1.35%   |
| Seagate One Touch HDD 5TB                           | 1         | 1.35%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB          | 1         | 1.35%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.35%   |
| SanDisk SDSSDRC032G 32GB                            | 1         | 1.35%   |
| Samsung SSD 970 EVO Plus 500GB                      | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 11     | 57.14%  |
| WDC     | 5         | 8      | 35.71%  |
| Toshiba | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 45.45%  |
| Kingston            | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| SanDisk             | 1         | 1      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 34        | 43     | 55.74%  |
| HDD     | 13        | 20     | 21.31%  |
| SSD     | 10        | 12     | 16.39%  |
| MMC     | 3         | 4      | 4.92%   |
| Unknown | 1         | 1      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 34        | 43     | 57.63%  |
| SATA | 20        | 31     | 33.9%   |
| MMC  | 3         | 4      | 5.08%   |
| SAS  | 2         | 2      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 8         | 11     | 32%     |
| 0.01-0.5   | 7         | 8      | 28%     |
| 1.01-2.0   | 5         | 6      | 20%     |
| 3.01-4.0   | 2         | 4      | 8%      |
| 4.01-10.0  | 2         | 2      | 8%      |
| 2.01-3.0   | 1         | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 13        | 27.66%  |
| 501-1000       | 9         | 19.15%  |
| 251-500        | 6         | 12.77%  |
| 101-250        | 5         | 10.64%  |
| More than 3000 | 4         | 8.51%   |
| 1-20           | 4         | 8.51%   |
| 2001-3000      | 3         | 6.38%   |
| Unknown        | 2         | 4.26%   |
| 21-50          | 1         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 25.53%  |
| 251-500        | 7         | 14.89%  |
| 21-50          | 6         | 12.77%  |
| 101-250        | 5         | 10.64%  |
| 501-1000       | 5         | 10.64%  |
| 1001-2000      | 4         | 8.51%   |
| More than 3000 | 3         | 6.38%   |
| 51-100         | 3         | 6.38%   |
| Unknown        | 2         | 4.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD10EFRX-68FYTN0 1TB                            | 1         | 1      | 50%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 50%     |
| Micron Technology | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 26        | 45     | 53.06%  |
| Works    | 21        | 33     | 42.86%  |
| Malfunc  | 2         | 2      | 4.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 22        | 30.99%  |
| Samsung Electronics          | 18        | 25.35%  |
| AMD                          | 10        | 14.08%  |
| Kingston Technology Company  | 6         | 8.45%   |
| SanDisk                      | 3         | 4.23%   |
| Yangtze Memory Technologies  | 2         | 2.82%   |
| Toshiba America Info Systems | 1         | 1.41%   |
| SK hynix                     | 1         | 1.41%   |
| Silicon Motion               | 1         | 1.41%   |
| Seagate Technology           | 1         | 1.41%   |
| Realtek Semiconductor        | 1         | 1.41%   |
| Micron/Crucial Technology    | 1         | 1.41%   |
| Micron Technology            | 1         | 1.41%   |
| KIOXIA                       | 1         | 1.41%   |
| ASMedia Technology           | 1         | 1.41%   |
| ADATA Technology             | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 10.67%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 10.67%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 9.33%   |
| Kingston Company Company Non-Volatile memory controller                        | 5         | 6.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 5.33%   |
| Yangtze Memory Non-Volatile memory controller                                  | 2         | 2.67%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.67%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.67%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 1.33%   |
| SK hynix Gold P31 SSD                                                          | 1         | 1.33%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 1.33%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 1.33%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.33%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.33%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.33%   |
| Micron/Crucial Non-Volatile memory controller                                  | 1         | 1.33%   |
| Micron Non-Volatile memory controller                                          | 1         | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.33%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.33%   |
| Intel NVMe Optane Memory Series                                                | 1         | 1.33%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.33%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 34        | 50%     |
| SATA | 28        | 41.18%  |
| RAID | 6         | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 61.7%   |
| AMD    | 17        | 36.17%  |
| ARM    | 1         | 2.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 4.26%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 2         | 4.26%   |
| Intel Xeon CPU X5675 @ 3.07GHz             | 1         | 2.13%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 1         | 2.13%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 1         | 2.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 1         | 2.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 1         | 2.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 1         | 2.13%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz          | 1         | 2.13%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 1         | 2.13%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 1         | 2.13%   |
| Intel Core i5-4310U CPU @ 2.00GHz          | 1         | 2.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz          | 1         | 2.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz         | 1         | 2.13%   |
| Intel Core i5-10300H CPU @ 2.50GHz         | 1         | 2.13%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1         | 2.13%   |
| Intel Core i3-4000M CPU @ 2.40GHz          | 1         | 2.13%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 1         | 2.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz          | 1         | 2.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 1         | 2.13%   |
| Intel 12th Gen Core i9-12900K              | 1         | 2.13%   |
| Intel 12th Gen Core i9-12900H              | 1         | 2.13%   |
| Intel 12th Gen Core i7-1260P               | 1         | 2.13%   |
| Intel 12th Gen Core i5-1240P               | 1         | 2.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz    | 1         | 2.13%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz    | 1         | 2.13%   |
| ARM Processor                              | 1         | 2.13%   |
| AMD Ryzen Threadripper PRO 3975WX 32-Cores | 1         | 2.13%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 1         | 2.13%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics | 1         | 2.13%   |
| AMD Ryzen 7 6800HS Creator Edition         | 1         | 2.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 1         | 2.13%   |
| AMD Ryzen 7 5700X 8-Core Processor         | 1         | 2.13%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 1         | 2.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 1         | 2.13%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics | 1         | 2.13%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 10        | 21.28%  |
| Intel Core i5          | 8         | 17.02%  |
| AMD Ryzen 5            | 7         | 14.89%  |
| Intel Core i7          | 6         | 12.77%  |
| AMD Ryzen 7            | 5         | 10.64%  |
| Intel Core i3          | 2         | 4.26%   |
| Intel Celeron          | 2         | 4.26%   |
| Intel Xeon             | 1         | 2.13%   |
| Intel Atom             | 1         | 2.13%   |
| AMD Ryzen Threadripper | 1         | 2.13%   |
| AMD Ryzen 9            | 1         | 2.13%   |
| AMD Ryzen 7 PRO        | 1         | 2.13%   |
| AMD Ryzen 5 PRO        | 1         | 2.13%   |
| AMD A6                 | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 17        | 36.17%  |
| 6       | 9         | 19.15%  |
| 8       | 7         | 14.89%  |
| 2       | 6         | 12.77%  |
| 12      | 4         | 8.51%   |
| 32      | 1         | 2.13%   |
| 16      | 1         | 2.13%   |
| 14      | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 45        | 95.74%  |
| 2       | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 40        | 85.11%  |
| 1       | 6         | 12.77%  |
| Unknown | 1         | 2.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 97.87%  |
| 64-bit         | 1         | 2.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x906a3    | 3         | 6.38%   |
| 0x806c1    | 3         | 6.38%   |
| 0x08600106 | 3         | 6.38%   |
| Unknown    | 3         | 6.38%   |
| 0x906ea    | 2         | 4.26%   |
| 0x906e9    | 2         | 4.26%   |
| 0x806ec    | 2         | 4.26%   |
| 0x306c3    | 2         | 4.26%   |
| 0x306a9    | 2         | 4.26%   |
| 0x0a50000c | 2         | 4.26%   |
| 0x0a201016 | 2         | 4.26%   |
| 0x08701021 | 2         | 4.26%   |
| 0xa0652    | 1         | 2.13%   |
| 0x90672    | 1         | 2.13%   |
| 0x806d1    | 1         | 2.13%   |
| 0x706e5    | 1         | 2.13%   |
| 0x706a8    | 1         | 2.13%   |
| 0x506e3    | 1         | 2.13%   |
| 0x506c9    | 1         | 2.13%   |
| 0x406c4    | 1         | 2.13%   |
| 0x40651    | 1         | 2.13%   |
| 0x206c2    | 1         | 2.13%   |
| 0x206a7    | 1         | 2.13%   |
| 0x0a50000d | 1         | 2.13%   |
| 0x0a404102 | 1         | 2.13%   |
| 0x0a20120a | 1         | 2.13%   |
| 0x08608103 | 1         | 2.13%   |
| 0x08600104 | 1         | 2.13%   |
| 0x0830104d | 1         | 2.13%   |
| 0x0800820d | 1         | 2.13%   |
| 0x0700010b | 1         | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 7         | 14.89%  |
| Zen 3            | 6         | 12.77%  |
| KabyLake         | 6         | 12.77%  |
| TigerLake        | 4         | 8.51%   |
| Alderlake Hybrid | 4         | 8.51%   |
| Haswell          | 3         | 6.38%   |
| Unknown          | 3         | 6.38%   |
| IvyBridge        | 2         | 4.26%   |
| Icelake          | 2         | 4.26%   |
| Zen+             | 1         | 2.13%   |
| Westmere         | 1         | 2.13%   |
| Skylake          | 1         | 2.13%   |
| Silvermont       | 1         | 2.13%   |
| SandyBridge      | 1         | 2.13%   |
| Nehalem          | 1         | 2.13%   |
| Jaguar           | 1         | 2.13%   |
| Goldmont plus    | 1         | 2.13%   |
| Goldmont         | 1         | 2.13%   |
| CometLake        | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 23        | 41.82%  |
| AMD               | 16        | 29.09%  |
| Nvidia            | 15        | 27.27%  |
| ASPEED Technology | 1         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 4         | 7.27%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 5.45%   |
| AMD Cezanne                                                                              | 3         | 5.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.82%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 1.82%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.82%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.82%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 1         | 1.82%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 1.82%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.82%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 1.82%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                                       | 1         | 1.82%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 1.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.82%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.82%   |
| Intel Tiger Lake Iris Xe Graphics                                                        | 1         | 1.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.82%   |
| Intel HD Graphics 630                                                                    | 1         | 1.82%   |
| Intel HD Graphics 500                                                                    | 1         | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.82%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 1.82%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 1.82%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                   | 1         | 1.82%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x AMD                 | 16        | 34.04%  |
| 1 x Intel               | 15        | 31.91%  |
| 1 x Nvidia              | 7         | 14.89%  |
| Intel + Nvidia          | 7         | 14.89%  |
| Other                   | 1         | 2.13%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 78.72%  |
| Proprietary | 8         | 17.02%  |
| Unknown     | 2         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 46.81%  |
| 0.01-0.5   | 7         | 14.89%  |
| 0.51-1.0   | 5         | 10.64%  |
| 7.01-8.0   | 4         | 8.51%   |
| 3.01-4.0   | 4         | 8.51%   |
| 1.01-2.0   | 3         | 6.38%   |
| 8.01-16.0  | 2         | 4.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 10        | 17.54%  |
| Samsung Electronics     | 8         | 14.04%  |
| Hewlett-Packard         | 5         | 8.77%   |
| Chimei Innolux          | 4         | 7.02%   |
| Goldstar                | 3         | 5.26%   |
| Dell                    | 3         | 5.26%   |
| AU Optronics            | 3         | 5.26%   |
| PANDA                   | 2         | 3.51%   |
| Lenovo                  | 2         | 3.51%   |
| CSO                     | 2         | 3.51%   |
| AOC                     | 2         | 3.51%   |
| Ancor Communications    | 2         | 3.51%   |
| ViewSonic               | 1         | 1.75%   |
| Unknown                 | 1         | 1.75%   |
| Toshiba                 | 1         | 1.75%   |
| Sharp                   | 1         | 1.75%   |
| Philips                 | 1         | 1.75%   |
| NEC Computers           | 1         | 1.75%   |
| KTC                     | 1         | 1.75%   |
| InfoVision              | 1         | 1.75%   |
| Chi Mei Optoelectronics | 1         | 1.75%   |
| BenQ                    | 1         | 1.75%   |
| ASUSTek Computer        | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 3.17%   |
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch                | 1         | 1.59%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1         | 1.59%   |
| Toshiba TV TSB0110 1920x1080 706x398mm 31.9-inch                       | 1         | 1.59%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 1.59%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch     | 1         | 1.59%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch     | 1         | 1.59%   |
| Samsung Electronics LS27A800U SAM71A4 3840x2160 597x336mm 27.0-inch    | 1         | 1.59%   |
| Samsung Electronics LS27A800U SAM71A2 3840x2160 600x340mm 27.2-inch    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 950x540mm 43.0-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1         | 1.59%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch     | 1         | 1.59%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 1         | 1.59%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch              | 1         | 1.59%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 1.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 1         | 1.59%   |
| NEC Computers EA231WU NEC2E9F 1920x1200 488x297mm 22.5-inch            | 1         | 1.59%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch             | 1         | 1.59%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 1.59%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                | 1         | 1.59%   |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                        | 1         | 1.59%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch           | 1         | 1.59%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch          | 1         | 1.59%   |
| Hewlett-Packard Z30i HWP3099 2560x1600 641x400mm 29.7-inch             | 1         | 1.59%   |
| Hewlett-Packard OMEN by HP 27 HPN3422 2560x1440 598x336mm 27.0-inch    | 1         | 1.59%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch            | 1         | 1.59%   |
| Hewlett-Packard 24mh HPN366C 1920x1080 527x296mm 23.8-inch             | 1         | 1.59%   |
| Goldstar W2252 GSM567D 1680x1050 490x320mm 23.0-inch                   | 1         | 1.59%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                  | 1         | 1.59%   |
| Goldstar BK550Y GSM5B42 1920x1080 600x340mm 27.2-inch                  | 1         | 1.59%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 1         | 1.59%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                     | 1         | 1.59%   |
| Dell P2714H DELD05E 1920x1080 600x340mm 27.2-inch                      | 1         | 1.59%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                    | 1         | 1.59%   |
| Dell AW2518H DELA0F6 1920x1080 544x303mm 24.5-inch                     | 1         | 1.59%   |
| CSO LCD Monitor CSO1606 2560x1600 345x215mm 16.0-inch                  | 1         | 1.59%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                  | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 47.27%  |
| 1920x1200 (WUXGA)  | 6         | 10.91%  |
| 3840x2160 (4K)     | 4         | 7.27%   |
| 2560x1600          | 4         | 7.27%   |
| 1366x768 (WXGA)    | 4         | 7.27%   |
| 2560x1440 (QHD)    | 3         | 5.45%   |
| 3440x1440          | 2         | 3.64%   |
| 1680x1050 (WSXGA+) | 2         | 3.64%   |
| 3456x2160          | 1         | 1.82%   |
| 2880x1800          | 1         | 1.82%   |
| 2288x1287          | 1         | 1.82%   |
| 1600x900 (HD+)     | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 10        | 16.67%  |
| 27     | 7         | 11.67%  |
| 24     | 7         | 11.67%  |
| 13     | 6         | 10%     |
| 23     | 4         | 6.67%   |
| 16     | 4         | 6.67%   |
| 14     | 4         | 6.67%   |
| 34     | 2         | 3.33%   |
| 21     | 2         | 3.33%   |
| 17     | 2         | 3.33%   |
| 142    | 1         | 1.67%   |
| 54     | 1         | 1.67%   |
| 50     | 1         | 1.67%   |
| 44     | 1         | 1.67%   |
| 43     | 1         | 1.67%   |
| 32     | 1         | 1.67%   |
| 31     | 1         | 1.67%   |
| 29     | 1         | 1.67%   |
| 25     | 1         | 1.67%   |
| 22     | 1         | 1.67%   |
| 20     | 1         | 1.67%   |
| 12     | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 19        | 34.55%  |
| 501-600        | 15        | 27.27%  |
| 401-500        | 4         | 7.27%   |
| 351-400        | 4         | 7.27%   |
| 701-800        | 3         | 5.45%   |
| 201-300        | 3         | 5.45%   |
| 601-700        | 2         | 3.64%   |
| 1001-1500      | 2         | 3.64%   |
| 901-1000       | 2         | 3.64%   |
| More than 2000 | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 68%     |
| 16/10 | 12        | 24%     |
| 21/9  | 2         | 4%      |
| 3/2   | 1         | 2%      |
| 1.00  | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 21.05%  |
| 81-90          | 8         | 14.04%  |
| 201-250        | 8         | 14.04%  |
| 301-350        | 7         | 12.28%  |
| 351-500        | 4         | 7.02%   |
| 251-300        | 4         | 7.02%   |
| More than 1000 | 3         | 5.26%   |
| 71-80          | 2         | 3.51%   |
| 151-200        | 2         | 3.51%   |
| 121-130        | 2         | 3.51%   |
| 111-120        | 2         | 3.51%   |
| 501-1000       | 2         | 3.51%   |
| 61-70          | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 15        | 28.3%   |
| 121-160       | 14        | 26.42%  |
| 101-120       | 11        | 20.75%  |
| 161-240       | 6         | 11.32%  |
| 1-50          | 4         | 7.55%   |
| More than 240 | 3         | 5.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 65.96%  |
| 2     | 10        | 21.28%  |
| 3     | 3         | 6.38%   |
| 0     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 48.44%  |
| Realtek Semiconductor | 24        | 37.5%   |
| Qualcomm Atheros      | 3         | 4.69%   |
| Broadcom              | 2         | 3.13%   |
| TP-Link               | 1         | 1.56%   |
| NetGear               | 1         | 1.56%   |
| Hewlett-Packard       | 1         | 1.56%   |
| Aquantia              | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 17.11%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 13.16%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.95%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 3.95%   |
| Intel I211 Gigabit Network Connection                             | 3         | 3.95%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 3.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 2.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.63%   |
| TP-Link USB 10/100 LAN                                            | 1         | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.32%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.32%   |
| Realtek Realtek Network controller                                | 1         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.32%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]            | 1         | 1.32%   |
| Intel Wireless-AC 9260                                            | 1         | 1.32%   |
| Intel Wireless 7260                                               | 1         | 1.32%   |
| Intel Wireless 3165                                               | 1         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.32%   |
| Intel Ethernet Controller X550                                    | 1         | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.32%   |
| HP lt4112 Gobi 4G Module Network Device                           | 1         | 1.32%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function | 1         | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 66.67%  |
| Realtek Semiconductor | 8         | 20.51%  |
| Qualcomm Atheros      | 3         | 7.69%   |
| NetGear               | 1         | 2.56%   |
| Hewlett-Packard       | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 10        | 25.64%  |
| Intel Wi-Fi 6 AX201                                        | 3         | 7.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 2         | 5.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 2         | 5.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 2.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 2.56%   |
| Realtek Realtek Network controller                         | 1         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1         | 2.56%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]     | 1         | 2.56%   |
| Intel Wireless-AC 9260                                     | 1         | 2.56%   |
| Intel Wireless 7260                                        | 1         | 2.56%   |
| Intel Wireless 3165                                        | 1         | 2.56%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 2.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.56%   |
| HP lt4112 Gobi 4G Module Network Device                    | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 55.56%  |
| Intel                 | 12        | 33.33%  |
| Broadcom              | 2         | 5.56%   |
| TP-Link               | 1         | 2.78%   |
| Aquantia              | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 13        | 35.14%  |
| Realtek RTL8125 2.5GbE Controller                                   | 4         | 10.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3         | 8.11%   |
| Intel I211 Gigabit Network Connection                               | 3         | 8.11%   |
| Intel Ethernet Connection (2) I219-V                                | 3         | 8.11%   |
| TP-Link USB 10/100 LAN                                              | 1         | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1         | 2.7%    |
| Intel Ethernet Controller X550                                      | 1         | 2.7%    |
| Intel Ethernet Controller I225-V                                    | 1         | 2.7%    |
| Intel Ethernet Connection I218-LM                                   | 1         | 2.7%    |
| Intel Ethernet Connection (10) I219-V                               | 1         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                            | 1         | 2.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function   | 1         | 2.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1         | 2.7%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 53.62%  |
| Ethernet | 32        | 46.38%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 59.18%  |
| Ethernet | 20        | 40.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22        | 46.81%  |
| 2     | 16        | 34.04%  |
| 3     | 6         | 12.77%  |
| 0     | 2         | 4.26%   |
| 9     | 1         | 2.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 87.23%  |
| Yes  | 6         | 12.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 71.43%  |
| Realtek Semiconductor           | 6         | 17.14%  |
| Broadcom                        | 2         | 5.71%   |
| Qualcomm Atheros Communications | 1         | 2.86%   |
| IMC Networks                    | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                          | 10        | 28.57%  |
| Intel AX201 Bluetooth                          | 6         | 17.14%  |
| Realtek Bluetooth Radio                        | 4         | 11.43%  |
| Intel Bluetooth Device                         | 4         | 11.43%  |
| Intel Bluetooth wireless interface             | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 5.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 2         | 5.71%   |
| Realtek RTL8821A Bluetooth                     | 1         | 2.86%   |
| Realtek RTL8723B Bluetooth                     | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.86%   |
| IMC Networks Bluetooth Device                  | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 28        | 40.58%  |
| AMD                                  | 18        | 26.09%  |
| Nvidia                               | 14        | 20.29%  |
| C-Media Electronics                  | 2         | 2.9%    |
| Thesycon Systemsoftware & Consulting | 1         | 1.45%   |
| Shure                                | 1         | 1.45%   |
| Razer USA                            | 1         | 1.45%   |
| Logitech                             | 1         | 1.45%   |
| Lenovo                               | 1         | 1.45%   |
| AudioQuest                           | 1         | 1.45%   |
| ASUSTek Computer                     | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 8.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 7.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 4.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 3.57%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 3.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.38%   |
| Nvidia Audio device                                                        | 2         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.38%   |
| Thesycon Systemsoftware & Consulting DX5                                   | 1         | 1.19%   |
| Shure MV7                                                                  | 1         | 1.19%   |
| Razer USA Razer Seiren Mini                                                | 1         | 1.19%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.19%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.19%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.19%   |
| Logitech G635 Gaming Headset                                               | 1         | 1.19%   |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.19%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.19%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 34.48%  |
| SK hynix            | 4         | 13.79%  |
| Kingston            | 3         | 10.34%  |
| G.Skill             | 3         | 10.34%  |
| Micron Technology   | 2         | 6.9%    |
| Corsair             | 2         | 6.9%    |
| GOODRAM             | 1         | 3.45%   |
| Goldkey             | 1         | 3.45%   |
| Crucial             | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |
| Unknown             | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 6.9%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 3.45%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 3.45%   |
| SK hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 3.45%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.45%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 3.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM 4800MT/s              | 1         | 3.45%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s              | 1         | 3.45%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB SODIMM LPDDR4 4266MT/s           | 1         | 3.45%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 1         | 3.45%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 1         | 3.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.45%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 1         | 3.45%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 3.45%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s             | 1         | 3.45%   |
| Goldkey RAM GKE160SO102408-2666 16GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 1         | 3.45%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s            | 1         | 3.45%   |
| G.Skill RAM F4-3200C14-8GTZR 8GB DIMM DDR4 3200MT/s              | 1         | 3.45%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s              | 1         | 3.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 1         | 3.45%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s             | 1         | 3.45%   |
| Unknown                                                          | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 52.17%  |
| DDR3   | 4         | 17.39%  |
| LPDDR4 | 3         | 13.04%  |
| LPDDR5 | 2         | 8.7%    |
| LPDDR3 | 1         | 4.35%   |
| DDR5   | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 9         | 39.13%  |
| SODIMM       | 8         | 34.78%  |
| Row Of Chips | 6         | 26.09%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 48%     |
| 16384 | 5         | 20%     |
| 4096  | 5         | 20%     |
| 32768 | 2         | 8%      |
| 1024  | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 32%     |
| 2667  | 3         | 12%     |
| 6400  | 2         | 8%      |
| 4267  | 2         | 8%      |
| 1600  | 2         | 8%      |
| 4800  | 1         | 4%      |
| 4266  | 1         | 4%      |
| 3600  | 1         | 4%      |
| 3466  | 1         | 4%      |
| 3333  | 1         | 4%      |
| 2133  | 1         | 4%      |
| 1866  | 1         | 4%      |
| 1800  | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson Printer | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 25.81%  |
| IMC Networks                           | 4         | 12.9%   |
| Logitech                               | 3         | 9.68%   |
| Quanta                                 | 2         | 6.45%   |
| Microsoft                              | 2         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.45%   |
| USB Camera CS                          | 1         | 3.23%   |
| Syntek                                 | 1         | 3.23%   |
| Silicon Motion                         | 1         | 3.23%   |
| Samsung Electronics                    | 1         | 3.23%   |
| Luxvisions Innotech Limited            | 1         | 3.23%   |
| Lite-On Technology                     | 1         | 3.23%   |
| Lenovo                                 | 1         | 3.23%   |
| Hewlett-Packard                        | 1         | 3.23%   |
| Goodong Industry                       | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 4         | 12.9%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 6.45%   |
| Chicony USB2.0 Camera                                           | 2         | 6.45%   |
| USB Camera CS USB Camera CS                                     | 1         | 3.23%   |
| Syntek EasyCamera                                               | 1         | 3.23%   |
| Silicon Motion WebCam SC-10HDD12636N                            | 1         | 3.23%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera                                  | 1         | 3.23%   |
| Quanta HD Webcam                                                | 1         | 3.23%   |
| Microsoft LifeCam VX-5000                                       | 1         | 3.23%   |
| Microsoft LifeCam VX-2000                                       | 1         | 3.23%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 3.23%   |
| Logitech HD Pro Webcam C920                                     | 1         | 3.23%   |
| Logitech C922 Pro Stream Webcam                                 | 1         | 3.23%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 3.23%   |
| Lite-On Integrated Camera                                       | 1         | 3.23%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 3.23%   |
| IMC Networks XiaoMi Webcam                                      | 1         | 3.23%   |
| IMC Networks HD Camera                                          | 1         | 3.23%   |
| HP HD-4110 Webcam                                               | 1         | 3.23%   |
| Goodong Industry USB2.0 HD UVC WebCam                           | 1         | 3.23%   |
| Chicony HP HD Webcam                                            | 1         | 3.23%   |
| Chicony HD WebCam                                               | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 1         | 3.23%   |
| Acer Integrated Camera                                          | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 44.44%  |
| Synaptics                  | 3         | 33.33%  |
| Validity Sensors           | 1         | 11.11%  |
| Elan Microelectronics      | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 4         | 44.44%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Elan ELAN:ARM-M4                                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 63.83%  |
| 1     | 13        | 27.66%  |
| 2     | 3         | 6.38%   |
| 3     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 42.86%  |
| Graphics card            | 4         | 19.05%  |
| Net/wireless             | 2         | 9.52%   |
| Multimedia controller    | 2         | 9.52%   |
| Sound                    | 1         | 4.76%   |
| Communication controller | 1         | 4.76%   |
| Card reader              | 1         | 4.76%   |
| Camera                   | 1         | 4.76%   |

