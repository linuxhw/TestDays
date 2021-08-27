Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-35

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | 0WMJ54 A01                  | Desktop     | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell      | Latitude E5470              | Notebook    | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell      | 0WMJ54 A01                  | Desktop     | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| AZW       | GK mini                     | Mini pc     | [995cc09b8d](https://linux-hardware.org/?probe=995cc09b8d) | Aug 22, 2021 |
| AZW       | GK mini                     | Mini pc     | [2024a6712e](https://linux-hardware.org/?probe=2024a6712e) | Aug 22, 2021 |
| Dell      | XPS 15 9550                 | Notebook    | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer      | Aspire A315-42              | Notebook    | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer      | Aspire ES1-572              | Notebook    | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell      | XPS 15 9570                 | Notebook    | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell      | XPS 13 9380                 | Notebook    | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo    | IdeaPad 530S-14IKB 81EU     | Notebook    | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| HP        | 8055                        | Desktop     | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte  | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [89892d4957](https://linux-hardware.org/?probe=89892d4957) | Apr 18, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [97c124c8a3](https://linux-hardware.org/?probe=97c124c8a3) | Apr 18, 2021 |
| ECS       | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek   | PRIME X570-PRO              | Desktop     | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |
| Lenovo    | ThinkPad W541 20EF000UMN    | Notebook    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [c0901f4607](https://linux-hardware.org/?probe=c0901f4607) | Mar 29, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                              | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 17.86%  |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 3         | 10.71%  |
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 7.14%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 3.57%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 3.57%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 3.57%   |
| 5.13.7-200.fc34.x86_64                               | 1         | 3.57%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 3.57%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 3.57%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 3.57%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 3.57%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 3.57%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 3.57%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 3.57%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 3.57%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 3.57%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 3.57%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 3.57%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 3.57%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 3.57%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 10        | 43.48%  |
| 5.12.0  | 7         | 30.43%  |
| 5.13.0  | 4         | 17.39%  |
| 5.13.7  | 1         | 4.35%   |
| 5.12.8  | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 10        | 43.48%  |
| 5.12    | 8         | 34.78%  |
| 5.13    | 5         | 21.74%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 15        | 65.22%  |
| KDE     | 5         | 21.74%  |
| MATE    | 2         | 8.7%    |
| Unknown | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 16        | 72.73%  |
| X11     | 4         | 18.18%  |
| Tty     | 2         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 12        | 54.55%  |
| Unknown | 8         | 36.36%  |
| TDM     | 1         | 4.55%   |
| LightDM | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 14        | 60.87%  |
| ru_RU | 2         | 8.7%    |
| en_CA | 2         | 8.7%    |
| sv_SE | 1         | 4.35%   |
| pl_PL | 1         | 4.35%   |
| es_ES | 1         | 4.35%   |
| es_CL | 1         | 4.35%   |
| en_GB | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 90.91%  |
| BIOS | 2         | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 11        | 47.83%  |
| Ext4  | 10        | 43.48%  |
| Xfs   | 2         | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 15        | 65.22%  |
| Unknown | 7         | 30.43%  |
| MBR     | 1         | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 66.67%  |
| Yes       | 8         | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 83.33%  |
| Yes       | 4         | 16.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 6         | 27.27%  |
| Hewlett-Packard     | 3         | 13.64%  |
| Lenovo              | 2         | 9.09%   |
| HUAWEI              | 2         | 9.09%   |
| ASUSTek Computer    | 2         | 9.09%   |
| Acer                | 2         | 9.09%   |
| Notebook            | 1         | 4.55%   |
| Microsoft           | 1         | 4.55%   |
| Gigabyte Technology | 1         | 4.55%   |
| ECS                 | 1         | 4.55%   |
| AZW                 | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Notebook P377SM-A                      | 1         | 4.55%   |
| Microsoft Surface Pro                  | 1         | 4.55%   |
| Lenovo ThinkPad W541 20EF000UMN        | 1         | 4.55%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 1         | 4.55%   |
| HUAWEI KLVL-WXX9                       | 1         | 4.55%   |
| HUAWEI BOHK-WAX9X                      | 1         | 4.55%   |
| HP Pavilion x360 Convertible 15-cr0xxx | 1         | 4.55%   |
| HP Pavilion x360 Convertible 14-dh0xxx | 1         | 4.55%   |
| HP EliteDesk 800 G2 DM 35W             | 1         | 4.55%   |
| Gigabyte F2A88XN-WIFI                  | 1         | 4.55%   |
| ECS MCP61M-M3                          | 1         | 4.55%   |
| Dell XPS 15 9570                       | 1         | 4.55%   |
| Dell XPS 15 9550                       | 1         | 4.55%   |
| Dell XPS 13 9380                       | 1         | 4.55%   |
| Dell OptiPlex 9020                     | 1         | 4.55%   |
| Dell OptiPlex 3020                     | 1         | 4.55%   |
| Dell Latitude E5470                    | 1         | 4.55%   |
| AZW GK mini                            | 1         | 4.55%   |
| ASUS PRIME X570-PRO                    | 1         | 4.55%   |
| ASUS Maximus V FORMULA                 | 1         | 4.55%   |
| Acer Aspire ES1-572                    | 1         | 4.55%   |
| Acer Aspire A315-42                    | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell XPS              | 3         | 13.64%  |
| HP Pavilion           | 2         | 9.09%   |
| Dell OptiPlex         | 2         | 9.09%   |
| Acer Aspire           | 2         | 9.09%   |
| Notebook P377SM-A     | 1         | 4.55%   |
| Microsoft Surface     | 1         | 4.55%   |
| Lenovo ThinkPad       | 1         | 4.55%   |
| Lenovo IdeaPad        | 1         | 4.55%   |
| HUAWEI KLVL-WXX9      | 1         | 4.55%   |
| HUAWEI BOHK-WAX9X     | 1         | 4.55%   |
| HP EliteDesk          | 1         | 4.55%   |
| Gigabyte F2A88XN-WIFI | 1         | 4.55%   |
| ECS MCP61M-M3         | 1         | 4.55%   |
| Dell Latitude         | 1         | 4.55%   |
| AZW GK                | 1         | 4.55%   |
| ASUS PRIME            | 1         | 4.55%   |
| ASUS Maximus          | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 36.36%  |
| 2019 | 5         | 22.73%  |
| 2021 | 3         | 13.64%  |
| 2015 | 3         | 13.64%  |
| 2018 | 1         | 4.55%   |
| 2013 | 1         | 4.55%   |
| 2010 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 11        | 50%     |
| Desktop     | 7         | 31.82%  |
| Convertible | 2         | 9.09%   |
| Tablet      | 1         | 4.55%   |
| Mini pc     | 1         | 4.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 17        | 73.91%  |
| Enabled  | 6         | 26.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 47.83%  |
| 8.01-16.0  | 4         | 17.39%  |
| 32.01-64.0 | 3         | 13.04%  |
| 3.01-4.0   | 3         | 13.04%  |
| 16.01-24.0 | 2         | 8.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 38.46%  |
| 3.01-4.0 | 7         | 26.92%  |
| 1.01-2.0 | 5         | 19.23%  |
| 4.01-8.0 | 2         | 7.69%   |
| 0.51-1.0 | 1         | 3.85%   |
| 0.01-0.5 | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 15        | 68.18%  |
| 2      | 5         | 22.73%  |
| 5      | 1         | 4.55%   |
| 4      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 63.64%  |
| No        | 8         | 36.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 86.36%  |
| No        | 3         | 13.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 72.73%  |
| No        | 6         | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 6         | 27.27%  |
| Canada      | 3         | 13.64%  |
| Brazil      | 2         | 9.09%   |
| Turkey      | 1         | 4.55%   |
| Switzerland | 1         | 4.55%   |
| Sweden      | 1         | 4.55%   |
| Spain       | 1         | 4.55%   |
| Russia      | 1         | 4.55%   |
| Poland      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| Japan       | 1         | 4.55%   |
| Hong Kong   | 1         | 4.55%   |
| Germany     | 1         | 4.55%   |
| Chile       | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Yakima         | 2         | 8.33%   |
| Laurel         | 2         | 8.33%   |
| Zurich         | 1         | 4.17%   |
| Wroclaw        | 1         | 4.17%   |
| Whittier       | 1         | 4.17%   |
| Wateringen     | 1         | 4.17%   |
| Vancouver      | 1         | 4.17%   |
| St Petersburg  | 1         | 4.17%   |
| Seattle        | 1         | 4.17%   |
| S??o Paulo     | 1         | 4.17%   |
| Raesfeld       | 1         | 4.17%   |
| Porto Ferreira | 1         | 4.17%   |
| Owatonna       | 1         | 4.17%   |
| Osaka          | 1         | 4.17%   |
| Montreal       | 1         | 4.17%   |
| Madrid         | 1         | 4.17%   |
| La Florida     | 1         | 4.17%   |
| Kwu Tung       | 1         | 4.17%   |
| Istanbul       | 1         | 4.17%   |
| Handen         | 1         | 4.17%   |
| Concord        | 1         | 4.17%   |
| Bolszewo       | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 18     | 22.58%  |
| WDC                 | 6         | 9      | 19.35%  |
| Unknown             | 3         | 3      | 9.68%   |
| Toshiba             | 3         | 3      | 9.68%   |
| SK Hynix            | 2         | 3      | 6.45%   |
| Seagate             | 2         | 7      | 6.45%   |
| SanDisk             | 2         | 3      | 6.45%   |
| LITEON              | 2         | 2      | 6.45%   |
| SUNEAST             | 1         | 1      | 3.23%   |
| SABRENT             | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| ASMT                | 1         | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 2.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 2.94%   |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 2.94%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2.94%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 2.94%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 2.94%   |
| Unknown SSD0240S00 240GB                | 1         | 2.94%   |
| Unknown SD256  249GB                    | 1         | 2.94%   |
| Unknown M.2 SSD 256GB                   | 1         | 2.94%   |
| Toshiba MG05ACA800E 8TB                 | 1         | 2.94%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 2.94%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 2.94%   |
| SUNEAST SSD SE800 256GB                 | 1         | 2.94%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 2.94%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 2.94%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 2.94%   |
| Seagate ST3500630AS 500GB               | 1         | 2.94%   |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 2.94%   |
| SanDisk SDSSDH3512G 512GB               | 1         | 2.94%   |
| Sandisk NVMe SSD Drive 256GB            | 1         | 2.94%   |
| Samsung SSD 860 EVO 250GB               | 1         | 2.94%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 2.94%   |
| Samsung SSD 850 PRO 1TB                 | 1         | 2.94%   |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 2.94%   |
| Samsung SSD 840 EVO 250GB               | 1         | 2.94%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 2.94%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 1         | 2.94%   |
| Samsung KUS020203M-B000 128GB           | 1         | 2.94%   |
| SABRENT ASM1153E 512GB                  | 1         | 2.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 2.94%   |
| LITEON CX2-8B256-Q11 NVMe 256GB         | 1         | 2.94%   |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 2.94%   |
| ASMT ASM105x 250GB                      | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 4      | 33.33%  |
| Seagate | 2         | 7      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| ASMT    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 14     | 30.77%  |
| WDC                 | 2         | 2      | 15.38%  |
| Unknown             | 2         | 2      | 15.38%  |
| SUNEAST             | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 2      | 7.69%   |
| SABRENT             | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| LITEON              | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 10        | 14     | 38.46%  |
| SSD  | 10        | 24     | 38.46%  |
| HDD  | 5         | 13     | 19.23%  |
| MMC  | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 35     | 50%     |
| NVMe | 10        | 14     | 38.46%  |
| SAS  | 2         | 2      | 7.69%   |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 16     | 56.25%  |
| 0.51-1.0   | 4         | 13     | 25%     |
| 2.01-3.0   | 1         | 6      | 6.25%   |
| 1.01-2.0   | 1         | 1      | 6.25%   |
| 4.01-10.0  | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 25%     |
| 1-20       | 6         | 25%     |
| 101-250    | 5         | 20.83%  |
| 501-1000   | 2         | 8.33%   |
| 51-100     | 2         | 8.33%   |
| 21-50      | 1         | 4.17%   |
| 2001-3000  | 1         | 4.17%   |
| 1001-2000  | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 12        | 52.17%  |
| 21-50     | 4         | 17.39%  |
| 251-500   | 2         | 8.7%    |
| 101-250   | 2         | 8.7%    |
| 1001-2000 | 1         | 4.35%   |
| 501-1000  | 1         | 4.35%   |
| 51-100    | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB      | 1         | 1      | 33.33%  |
| Seagate ST3500630AS 500GB     | 1         | 1      | 33.33%  |
| LITEON CV8-8E128-HP 128GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| LITEON  | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 2      | 50%     |

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
| Works    | 16        | 20     | 55.17%  |
| Detected | 11        | 29     | 37.93%  |
| Malfunc  | 2         | 3      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 14        | 48.28%  |
| Samsung Electronics          | 3         | 10.34%  |
| AMD                          | 3         | 10.34%  |
| Toshiba America Info Systems | 2         | 6.9%    |
| SK Hynix                     | 2         | 6.9%    |
| Sandisk                      | 2         | 6.9%    |
| Nvidia                       | 1         | 3.45%   |
| Lite-On Technology           | 1         | 3.45%   |
| ASMedia Technology           | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 10%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 10%     |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 6.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 6.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 6.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 3.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 3.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.33%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 3.33%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 3.33%   |
| Nvidia MCP61 IDE                                                                 | 1         | 3.33%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 3.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 3.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15        | 53.57%  |
| NVMe | 10        | 35.71%  |
| RAID | 2         | 7.14%   |
| IDE  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 72.73%  |
| AMD    | 6         | 27.27%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 9.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 4.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 4.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 4.55%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 4.55%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 4.55%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 4.55%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 4.55%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 4.55%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 4.55%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 4.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1         | 4.55%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 4.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 4.55%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 4.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 4.55%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 4.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 4.55%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 4.55%   |
| AMD Athlon II X2 250 Processor                  | 1         | 4.55%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 7         | 31.82%  |
| Intel Core i7    | 6         | 27.27%  |
| AMD Ryzen 5      | 3         | 13.64%  |
| Intel Core i3    | 2         | 9.09%   |
| Intel Celeron    | 1         | 4.55%   |
| AMD Ryzen 3      | 1         | 4.55%   |
| AMD Athlon II X2 | 1         | 4.55%   |
| AMD A10          | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 59.09%  |
| 2      | 6         | 27.27%  |
| 6      | 3         | 13.64%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 72.73%  |
| 1      | 6         | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 18.18%  |
| 0x506e3    | 3         | 13.64%  |
| 0x806ec    | 2         | 9.09%   |
| 0x806ea    | 2         | 9.09%   |
| 0x08108109 | 2         | 9.09%   |
| 0x906ea    | 1         | 4.55%   |
| 0x806e9    | 1         | 4.55%   |
| 0x706a8    | 1         | 4.55%   |
| 0x406e3    | 1         | 4.55%   |
| 0x306a9    | 1         | 4.55%   |
| 0x08701021 | 1         | 4.55%   |
| 0x08600104 | 1         | 4.55%   |
| 0x06003106 | 1         | 4.55%   |
| 0x010000b6 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 27.27%  |
| Skylake       | 4         | 18.18%  |
| Haswell       | 4         | 18.18%  |
| Zen+          | 2         | 9.09%   |
| Zen 2         | 2         | 9.09%   |
| Steamroller   | 1         | 4.55%   |
| K10           | 1         | 4.55%   |
| IvyBridge     | 1         | 4.55%   |
| Goldmont plus | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 15        | 57.69%  |
| AMD    | 6         | 23.08%  |
| Nvidia | 5         | 19.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                       | 3         | 11.54%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 7.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 7.69%   |
| Intel UHD Graphics 620                                                      | 2         | 7.69%   |
| AMD Picasso                                                                 | 2         | 7.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 3.85%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 3.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 3.85%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 3.85%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 3.85%   |
| Intel HD Graphics 620                                                       | 1         | 3.85%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 3.85%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 3.85%   |
| AMD Renoir                                                                  | 1         | 3.85%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 3.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 50%     |
| 1 x AMD        | 6         | 27.27%  |
| Intel + Nvidia | 3         | 13.64%  |
| 1 x Nvidia     | 2         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 21        | 91.3%   |
| Proprietary | 2         | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 54.17%  |
| 1.01-2.0   | 4         | 16.67%  |
| 3.01-4.0   | 2         | 8.33%   |
| 0.51-1.0   | 2         | 8.33%   |
| 0.01-0.5   | 2         | 8.33%   |
| 7.01-8.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 5         | 25%     |
| LG Display           | 3         | 15%     |
| Sharp                | 2         | 10%     |
| Dell                 | 2         | 10%     |
| Chimei Innolux       | 2         | 10%     |
| BOE                  | 2         | 10%     |
| AOC                  | 2         | 10%     |
| Hewlett-Packard      | 1         | 5%      |
| Ancor Communications | 1         | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 4.76%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 4.76%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 4.76%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 4.76%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 4.76%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 4.76%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                      | 1         | 4.76%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 4.76%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 4.76%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 4.76%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch         | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 1         | 4.76%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 4.76%   |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1         | 4.76%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 68.42%  |
| 3840x2160 (4K)    | 1         | 5.26%   |
| 2736x1824         | 1         | 5.26%   |
| 2560x1440 (QHD)   | 1         | 5.26%   |
| 2160x1440         | 1         | 5.26%   |
| 1920x1200 (WUXGA) | 1         | 5.26%   |
| 1366x768 (WXGA)   | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 7         | 35%     |
| 21     | 4         | 20%     |
| 14     | 3         | 15%     |
| 13     | 2         | 10%     |
| 27     | 1         | 5%      |
| 25     | 1         | 5%      |
| 17     | 1         | 5%      |
| 12     | 1         | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 50%     |
| 401-500     | 4         | 20%     |
| 201-300     | 3         | 15%     |
| 501-600     | 2         | 10%     |
| 351-400     | 1         | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 84.21%  |
| 3/2   | 2         | 10.53%  |
| 16/10 | 1         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 35%     |
| 81-90          | 4         | 20%     |
| 201-250        | 3         | 15%     |
| 71-80          | 2         | 10%     |
| 301-350        | 1         | 5%      |
| 251-300        | 1         | 5%      |
| 151-200        | 1         | 5%      |
| 121-130        | 1         | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 10        | 50%     |
| 101-120       | 6         | 30%     |
| 161-240       | 2         | 10%     |
| More than 240 | 1         | 5%      |
| 51-100        | 1         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21        | 91.3%   |
| 3     | 1         | 4.35%   |
| 0     | 1         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 11        | 35.48%  |
| Intel                    | 11        | 35.48%  |
| Qualcomm Atheros         | 3         | 9.68%   |
| TP-Link                  | 1         | 3.23%   |
| Ralink Technology        | 1         | 3.23%   |
| Nvidia                   | 1         | 3.23%   |
| Marvell Technology Group | 1         | 3.23%   |
| Broadcom                 | 1         | 3.23%   |
| ASIX Electronics         | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 18.18%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 6.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 6.06%   |
| Intel Wireless-AC 9260                                            | 2         | 6.06%   |
| Intel Wireless 7260                                               | 2         | 6.06%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 6.06%   |
| TP-Link TL WN823N RTL8192EU                                       | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.03%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 3.03%   |
| Nvidia MCP61 Ethernet                                             | 1         | 3.03%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 3.03%   |
| Intel Wireless 8260                                               | 1         | 3.03%   |
| Intel Wireless 3165                                               | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 7         | 36.84%  |
| Realtek Semiconductor    | 5         | 26.32%  |
| Qualcomm Atheros         | 3         | 15.79%  |
| TP-Link                  | 1         | 5.26%   |
| Ralink Technology        | 1         | 5.26%   |
| Marvell Technology Group | 1         | 5.26%   |
| Broadcom                 | 1         | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 10.53%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 10.53%  |
| Intel Wireless-AC 9260                                     | 2         | 10.53%  |
| Intel Wireless 7260                                        | 2         | 10.53%  |
| TP-Link TL WN823N RTL8192EU                                | 1         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 5.26%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 5.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 5.26%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 5.26%   |
| Intel Wireless 8260                                        | 1         | 5.26%   |
| Intel Wireless 3165                                        | 1         | 5.26%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 1         | 5.26%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 42.86%  |
| Intel                 | 6         | 42.86%  |
| Nvidia                | 1         | 7.14%   |
| ASIX Electronics      | 1         | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 42.86%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 14.29%  |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 14.29%  |
| Nvidia MCP61 Ethernet                                             | 1         | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 1         | 7.14%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 7.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 7.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 57.58%  |
| Ethernet | 14        | 42.42%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 55.17%  |
| Ethernet | 13        | 44.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 63.64%  |
| 2     | 8         | 36.36%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16        | 72.73%  |
| Yes  | 6         | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 6         | 35.29%  |
| Realtek Semiconductor   | 3         | 17.65%  |
| Realtek                 | 2         | 11.76%  |
| Foxconn / Hon Hai       | 2         | 11.76%  |
| Marvell Semiconductor   | 1         | 5.88%   |
| Lite-On Technology      | 1         | 5.88%   |
| Cambridge Silicon Radio | 1         | 5.88%   |
| ASUSTek Computer        | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 17.65%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 11.76%  |
| Realtek Bluetooth Radio                             | 2         | 11.76%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 11.76%  |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 11.76%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 5.88%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 5.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 5.88%   |
| Intel Bluetooth Device                              | 1         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.88%   |
| ASUS BCM20702A0                                     | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 16        | 55.17%  |
| AMD                 | 6         | 20.69%  |
| Nvidia              | 4         | 13.79%  |
| Micronas            | 1         | 3.45%   |
| Dell                | 1         | 3.45%   |
| C-Media Electronics | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 4         | 10.81%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 10.81%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 8.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 8.11%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 8.11%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 5.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 5.41%   |
| Nvidia MCP61 High Definition Audio                                  | 1         | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 2.7%    |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 2.7%    |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 2.7%    |
| Micronas BLUE USB Audio 2.0                                         | 1         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                          | 1         | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 2.7%    |
| Dell AC511 Sound Bar                                                | 1         | 2.7%    |
| C-Media Electronics Audio Adapter                                   | 1         | 2.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.7%    |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 2.7%    |
| AMD FCH Azalia Controller                                           | 1         | 2.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 36.84%  |
| SK Hynix            | 5         | 26.32%  |
| Micron Technology   | 2         | 10.53%  |
| Crucial             | 2         | 10.53%  |
| Corsair             | 2         | 10.53%  |
| A-DATA Technology   | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 5%      |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 5%      |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 5%      |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 1         | 5%      |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 5%      |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 5%      |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 1         | 5%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 1         | 5%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 5%      |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 1         | 5%      |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                 | 1         | 5%      |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 5%      |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 1         | 5%      |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s               | 1         | 5%      |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s            | 1         | 5%      |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s       | 1         | 5%      |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                   | 1         | 5%      |
| Corsair RAM VS2GB1333D3 2GB DIMM DDR3 1333MT/s                      | 1         | 5%      |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s               | 1         | 5%      |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s                | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 55.56%  |
| DDR3   | 5         | 27.78%  |
| LPDDR3 | 2         | 11.11%  |
| LPDDR4 | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 55.56%  |
| Row Of Chips | 4         | 22.22%  |
| DIMM         | 4         | 22.22%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 47.37%  |
| 4096  | 8         | 42.11%  |
| 16384 | 1         | 5.26%   |
| 2048  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 9         | 45%     |
| 1600  | 3         | 15%     |
| 2400  | 2         | 10%     |
| 2133  | 2         | 10%     |
| 1867  | 2         | 10%     |
| 1333  | 2         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-3200 Series | 1         | 100%    |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Quanta                        | 3         | 21.43%  |
| IMC Networks                  | 3         | 21.43%  |
| Chicony Electronics           | 3         | 21.43%  |
| Microdia                      | 2         | 14.29%  |
| Sunplus Innovation Technology | 1         | 7.14%   |
| Microsoft                     | 1         | 7.14%   |
| Logitech                      | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Quanta HP Wide Vision HD Camera      | 2         | 13.33%  |
| Microdia Integrated_Webcam_HD        | 2         | 13.33%  |
| Sunplus Dell E5570 integrated webcam | 1         | 6.67%   |
| Quanta VGA WebCam                    | 1         | 6.67%   |
| Microsoft LifeCam Cinema             | 1         | 6.67%   |
| Logitech QuickCam Pro 9000           | 1         | 6.67%   |
| IMC Networks ov9734_azurewave_camera | 1         | 6.67%   |
| IMC Networks Integrated Camera       | 1         | 6.67%   |
| IMC Networks HD Camera               | 1         | 6.67%   |
| Chicony VGA Webcam                   | 1         | 6.67%   |
| Chicony USB2.0 2M WebCam             | 1         | 6.67%   |
| Chicony USB 5M WebCam                | 1         | 6.67%   |
| Chicony Integrated Camera            | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| LighTuning EgisTec_ES603                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 17        | 77.27%  |
| 1     | 5         | 22.73%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 80%     |
| Multimedia controller | 1         | 20%     |

