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
| Lenovo    | ThinkPad P51s 20HBCTO1WW    | Notebook    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 17.24%  |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 3         | 10.34%  |
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 6.9%    |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 3.45%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 3.45%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 3.45%   |
| 5.13.7-200.fc34.x86_64                               | 1         | 3.45%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 3.45%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 3.45%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 3.45%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 3.45%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 3.45%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 3.45%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 3.45%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 3.45%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 3.45%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 3.45%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 3.45%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 3.45%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 3.45%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 3.45%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 10        | 41.67%  |
| 5.12.0  | 7         | 29.17%  |
| 5.13.0  | 4         | 16.67%  |
| 5.13.7  | 1         | 4.17%   |
| 5.13.4  | 1         | 4.17%   |
| 5.12.8  | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 10        | 41.67%  |
| 5.12    | 8         | 33.33%  |
| 5.13    | 6         | 25%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 23        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 16        | 66.67%  |
| KDE     | 5         | 20.83%  |
| MATE    | 2         | 8.33%   |
| Unknown | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 16        | 69.57%  |
| X11     | 5         | 21.74%  |
| Tty     | 2         | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 13        | 56.52%  |
| Unknown | 8         | 34.78%  |
| TDM     | 1         | 4.35%   |
| LightDM | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 15        | 62.5%   |
| ru_RU | 2         | 8.33%   |
| en_CA | 2         | 8.33%   |
| sv_SE | 1         | 4.17%   |
| pl_PL | 1         | 4.17%   |
| es_ES | 1         | 4.17%   |
| es_CL | 1         | 4.17%   |
| en_GB | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 21        | 91.3%   |
| BIOS | 2         | 8.7%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 11        | 45.83%  |
| Btrfs | 11        | 45.83%  |
| Xfs   | 2         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 16        | 66.67%  |
| Unknown | 7         | 29.17%  |
| MBR     | 1         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 17        | 68%     |
| Yes       | 8         | 32%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 80%     |
| Yes       | 5         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 6         | 26.09%  |
| Lenovo              | 3         | 13.04%  |
| Hewlett-Packard     | 3         | 13.04%  |
| HUAWEI              | 2         | 8.7%    |
| ASUSTek Computer    | 2         | 8.7%    |
| Acer                | 2         | 8.7%    |
| Notebook            | 1         | 4.35%   |
| Microsoft           | 1         | 4.35%   |
| Gigabyte Technology | 1         | 4.35%   |
| ECS                 | 1         | 4.35%   |
| AZW                 | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Notebook P377SM-A                      | 1         | 4.35%   |
| Microsoft Surface Pro                  | 1         | 4.35%   |
| Lenovo ThinkPad W541 20EF000UMN        | 1         | 4.35%   |
| Lenovo ThinkPad P51s 20HBCTO1WW        | 1         | 4.35%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 1         | 4.35%   |
| HUAWEI KLVL-WXX9                       | 1         | 4.35%   |
| HUAWEI BOHK-WAX9X                      | 1         | 4.35%   |
| HP Pavilion x360 Convertible 15-cr0xxx | 1         | 4.35%   |
| HP Pavilion x360 Convertible 14-dh0xxx | 1         | 4.35%   |
| HP EliteDesk 800 G2 DM 35W             | 1         | 4.35%   |
| Gigabyte F2A88XN-WIFI                  | 1         | 4.35%   |
| ECS MCP61M-M3                          | 1         | 4.35%   |
| Dell XPS 15 9570                       | 1         | 4.35%   |
| Dell XPS 15 9550                       | 1         | 4.35%   |
| Dell XPS 13 9380                       | 1         | 4.35%   |
| Dell OptiPlex 9020                     | 1         | 4.35%   |
| Dell OptiPlex 3020                     | 1         | 4.35%   |
| Dell Latitude E5470                    | 1         | 4.35%   |
| AZW GK mini                            | 1         | 4.35%   |
| ASUS PRIME X570-PRO                    | 1         | 4.35%   |
| ASUS Maximus V FORMULA                 | 1         | 4.35%   |
| Acer Aspire ES1-572                    | 1         | 4.35%   |
| Acer Aspire A315-42                    | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell XPS              | 3         | 13.04%  |
| Lenovo ThinkPad       | 2         | 8.7%    |
| HP Pavilion           | 2         | 8.7%    |
| Dell OptiPlex         | 2         | 8.7%    |
| Acer Aspire           | 2         | 8.7%    |
| Notebook P377SM-A     | 1         | 4.35%   |
| Microsoft Surface     | 1         | 4.35%   |
| Lenovo IdeaPad        | 1         | 4.35%   |
| HUAWEI KLVL-WXX9      | 1         | 4.35%   |
| HUAWEI BOHK-WAX9X     | 1         | 4.35%   |
| HP EliteDesk          | 1         | 4.35%   |
| Gigabyte F2A88XN-WIFI | 1         | 4.35%   |
| ECS MCP61M-M3         | 1         | 4.35%   |
| Dell Latitude         | 1         | 4.35%   |
| AZW GK                | 1         | 4.35%   |
| ASUS PRIME            | 1         | 4.35%   |
| ASUS Maximus          | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 34.78%  |
| 2019 | 5         | 21.74%  |
| 2021 | 4         | 17.39%  |
| 2015 | 3         | 13.04%  |
| 2018 | 1         | 4.35%   |
| 2013 | 1         | 4.35%   |
| 2010 | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 12        | 52.17%  |
| Desktop     | 7         | 30.43%  |
| Convertible | 2         | 8.7%    |
| Tablet      | 1         | 4.35%   |
| Mini pc     | 1         | 4.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 18        | 75%     |
| Enabled  | 6         | 25%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 45.83%  |
| 8.01-16.0  | 4         | 16.67%  |
| 32.01-64.0 | 3         | 12.5%   |
| 3.01-4.0   | 3         | 12.5%   |
| 16.01-24.0 | 3         | 12.5%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 37.04%  |
| 3.01-4.0 | 8         | 29.63%  |
| 1.01-2.0 | 5         | 18.52%  |
| 4.01-8.0 | 2         | 7.41%   |
| 0.51-1.0 | 1         | 3.7%    |
| 0.01-0.5 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 16        | 69.57%  |
| 2      | 5         | 21.74%  |
| 5      | 1         | 4.35%   |
| 4      | 1         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 82.61%  |
| Yes       | 4         | 17.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 65.22%  |
| No        | 8         | 34.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 86.96%  |
| No        | 3         | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 73.91%  |
| No        | 6         | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 6         | 26.09%  |
| Canada      | 3         | 13.04%  |
| Brazil      | 2         | 8.7%    |
| Turkey      | 1         | 4.35%   |
| Switzerland | 1         | 4.35%   |
| Sweden      | 1         | 4.35%   |
| Spain       | 1         | 4.35%   |
| Russia      | 1         | 4.35%   |
| Poland      | 1         | 4.35%   |
| Netherlands | 1         | 4.35%   |
| Japan       | 1         | 4.35%   |
| India       | 1         | 4.35%   |
| Hong Kong   | 1         | 4.35%   |
| Germany     | 1         | 4.35%   |
| Chile       | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Yakima         | 2         | 8%      |
| Laurel         | 2         | 8%      |
| Zurich         | 1         | 4%      |
| Wroclaw        | 1         | 4%      |
| Whittier       | 1         | 4%      |
| Wateringen     | 1         | 4%      |
| Vancouver      | 1         | 4%      |
| St Petersburg  | 1         | 4%      |
| Seattle        | 1         | 4%      |
| S??o Paulo     | 1         | 4%      |
| Raesfeld       | 1         | 4%      |
| Porto Ferreira | 1         | 4%      |
| Owatonna       | 1         | 4%      |
| Osaka          | 1         | 4%      |
| Montreal       | 1         | 4%      |
| Madrid         | 1         | 4%      |
| La Florida     | 1         | 4%      |
| Kwu Tung       | 1         | 4%      |
| Istanbul       | 1         | 4%      |
| Handen         | 1         | 4%      |
| Concord        | 1         | 4%      |
| Bolszewo       | 1         | 4%      |
| Bengaluru      | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 10     | 21.88%  |
| Samsung Electronics | 7         | 18     | 21.88%  |
| Unknown             | 3         | 3      | 9.38%   |
| Toshiba             | 3         | 3      | 9.38%   |
| SK Hynix            | 2         | 3      | 6.25%   |
| Seagate             | 2         | 7      | 6.25%   |
| Sandisk             | 2         | 3      | 6.25%   |
| LITEON              | 2         | 2      | 6.25%   |
| SUNEAST             | 1         | 1      | 3.13%   |
| SABRENT             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| ASMT                | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 2.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 2.86%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.86%   |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 2.86%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2.86%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 2.86%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 2.86%   |
| Unknown SSD0240S00 240GB                | 1         | 2.86%   |
| Unknown SD256  249GB                    | 1         | 2.86%   |
| Unknown M.2 SSD 256GB                   | 1         | 2.86%   |
| Toshiba MG05ACA800E 8TB                 | 1         | 2.86%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 2.86%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 2.86%   |
| SUNEAST SSD SE800 256GB                 | 1         | 2.86%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 2.86%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 2.86%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 2.86%   |
| Seagate ST3500630AS 500GB               | 1         | 2.86%   |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 2.86%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 2.86%   |
| SanDisk SDSSDH3512G 512GB               | 1         | 2.86%   |
| Sandisk NVMe SSD Drive 256GB            | 1         | 2.86%   |
| Samsung SSD 860 EVO 250GB               | 1         | 2.86%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 2.86%   |
| Samsung SSD 850 PRO 1TB                 | 1         | 2.86%   |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 2.86%   |
| Samsung SSD 840 EVO 250GB               | 1         | 2.86%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 2.86%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 1         | 2.86%   |
| Samsung KUS020203M-B000 128GB           | 1         | 2.86%   |
| SABRENT ASM1153E 512GB                  | 1         | 2.86%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 2.86%   |
| LITEON CX2-8B256-Q11 NVMe 256GB         | 1         | 2.86%   |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 2.86%   |
| ASMT ASM105x 500GB                      | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 5      | 42.86%  |
| Seagate | 2         | 7      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |
| ASMT    | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 10        | 14     | 37.04%  |
| SSD  | 10        | 24     | 37.04%  |
| HDD  | 6         | 14     | 22.22%  |
| MMC  | 1         | 1      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 36     | 51.85%  |
| NVMe | 10        | 14     | 37.04%  |
| SAS  | 2         | 2      | 7.41%   |
| MMC  | 1         | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 17     | 58.82%  |
| 0.51-1.0   | 4         | 13     | 23.53%  |
| 2.01-3.0   | 1         | 6      | 5.88%   |
| 1.01-2.0   | 1         | 1      | 5.88%   |
| 4.01-10.0  | 1         | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 24%     |
| 101-250    | 6         | 24%     |
| 1-20       | 6         | 24%     |
| 501-1000   | 2         | 8%      |
| 51-100     | 2         | 8%      |
| 21-50      | 1         | 4%      |
| 2001-3000  | 1         | 4%      |
| 1001-2000  | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 12        | 50%     |
| 21-50     | 5         | 20.83%  |
| 251-500   | 2         | 8.33%   |
| 101-250   | 2         | 8.33%   |
| 1001-2000 | 1         | 4.17%   |
| 501-1000  | 1         | 4.17%   |
| 51-100    | 1         | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB      | 1         | 1      | 33.33%  |
| Seagate ST3500630AS 500GB     | 1         | 1      | 33.33%  |
| LITEON CV8-8E128-HP 128GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| LITEON  | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17        | 21     | 56.67%  |
| Detected | 11        | 29     | 36.67%  |
| Malfunc  | 2         | 3      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 15        | 50%     |
| Samsung Electronics          | 3         | 10%     |
| AMD                          | 3         | 10%     |
| Toshiba America Info Systems | 2         | 6.67%   |
| SK Hynix                     | 2         | 6.67%   |
| Sandisk                      | 2         | 6.67%   |
| Nvidia                       | 1         | 3.33%   |
| Lite-On Technology           | 1         | 3.33%   |
| ASMedia Technology           | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 12.9%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 9.68%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 6.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 6.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 6.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 3.23%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.23%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 3.23%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 3.23%   |
| Nvidia MCP61 IDE                                                                 | 1         | 3.23%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 3.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 16        | 55.17%  |
| NVMe | 10        | 34.48%  |
| RAID | 2         | 6.9%    |
| IDE  | 1         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 17        | 73.91%  |
| AMD    | 6         | 26.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 8.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 4.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 4.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 4.35%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 4.35%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 4.35%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 4.35%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 4.35%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 4.35%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 4.35%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 4.35%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 4.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1         | 4.35%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 4.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 4.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 4.35%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 4.35%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 4.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 4.35%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 4.35%   |
| AMD Athlon II X2 250 Processor                  | 1         | 4.35%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 7         | 30.43%  |
| Intel Core i5    | 7         | 30.43%  |
| AMD Ryzen 5      | 3         | 13.04%  |
| Intel Core i3    | 2         | 8.7%    |
| Intel Celeron    | 1         | 4.35%   |
| AMD Ryzen 3      | 1         | 4.35%   |
| AMD Athlon II X2 | 1         | 4.35%   |
| AMD A10          | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 56.52%  |
| 2      | 7         | 30.43%  |
| 6      | 3         | 13.04%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 73.91%  |
| 1      | 6         | 26.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 17.39%  |
| 0x506e3    | 3         | 13.04%  |
| 0x806ec    | 2         | 8.7%    |
| 0x806ea    | 2         | 8.7%    |
| 0x806e9    | 2         | 8.7%    |
| 0x08108109 | 2         | 8.7%    |
| 0x906ea    | 1         | 4.35%   |
| 0x706a8    | 1         | 4.35%   |
| 0x406e3    | 1         | 4.35%   |
| 0x306a9    | 1         | 4.35%   |
| 0x08701021 | 1         | 4.35%   |
| 0x08600104 | 1         | 4.35%   |
| 0x06003106 | 1         | 4.35%   |
| 0x010000b6 | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 30.43%  |
| Skylake       | 4         | 17.39%  |
| Haswell       | 4         | 17.39%  |
| Zen+          | 2         | 8.7%    |
| Zen 2         | 2         | 8.7%    |
| Steamroller   | 1         | 4.35%   |
| K10           | 1         | 4.35%   |
| IvyBridge     | 1         | 4.35%   |
| Goldmont plus | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 57.14%  |
| Nvidia | 6         | 21.43%  |
| AMD    | 6         | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                       | 3         | 10.71%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 7.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 7.14%   |
| Intel UHD Graphics 620                                                      | 2         | 7.14%   |
| Intel HD Graphics 620                                                       | 2         | 7.14%   |
| AMD Picasso                                                                 | 2         | 7.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 3.57%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 3.57%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                        | 1         | 3.57%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 3.57%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 3.57%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 3.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 3.57%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 3.57%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 3.57%   |
| AMD Renoir                                                                  | 1         | 3.57%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 3.57%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 47.83%  |
| 1 x AMD        | 6         | 26.09%  |
| Intel + Nvidia | 4         | 17.39%  |
| 1 x Nvidia     | 2         | 8.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 21        | 87.5%   |
| Proprietary | 3         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 56%     |
| 1.01-2.0   | 4         | 16%     |
| 3.01-4.0   | 2         | 8%      |
| 0.51-1.0   | 2         | 8%      |
| 0.01-0.5   | 2         | 8%      |
| 7.01-8.0   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 5         | 22.73%  |
| LG Display           | 3         | 13.64%  |
| Chimei Innolux       | 3         | 13.64%  |
| Sharp                | 2         | 9.09%   |
| Dell                 | 2         | 9.09%   |
| BOE                  | 2         | 9.09%   |
| AOC                  | 2         | 9.09%   |
| Hewlett-Packard      | 1         | 4.55%   |
| Goldstar             | 1         | 4.55%   |
| Ancor Communications | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 4.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 4.35%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 4.35%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 4.35%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch              | 1         | 4.35%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                      | 1         | 4.35%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 4.35%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch       | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 4.35%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 4.35%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 1         | 4.35%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 4.35%   |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1         | 4.35%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 70%     |
| 3840x2160 (4K)    | 1         | 5%      |
| 2736x1824         | 1         | 5%      |
| 2560x1440 (QHD)   | 1         | 5%      |
| 2160x1440         | 1         | 5%      |
| 1920x1200 (WUXGA) | 1         | 5%      |
| 1366x768 (WXGA)   | 1         | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 8         | 36.36%  |
| 21     | 5         | 22.73%  |
| 14     | 3         | 13.64%  |
| 13     | 2         | 9.09%   |
| 27     | 1         | 4.55%   |
| 25     | 1         | 4.55%   |
| 17     | 1         | 4.55%   |
| 12     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 50%     |
| 401-500     | 5         | 22.73%  |
| 201-300     | 3         | 13.64%  |
| 501-600     | 2         | 9.09%   |
| 351-400     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 85%     |
| 3/2   | 2         | 10%     |
| 16/10 | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 36.36%  |
| 81-90          | 4         | 18.18%  |
| 201-250        | 4         | 18.18%  |
| 71-80          | 2         | 9.09%   |
| 301-350        | 1         | 4.55%   |
| 251-300        | 1         | 4.55%   |
| 151-200        | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 50%     |
| 101-120       | 7         | 31.82%  |
| 161-240       | 2         | 9.09%   |
| More than 240 | 1         | 4.55%   |
| 51-100        | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21        | 87.5%   |
| 3     | 1         | 4.17%   |
| 2     | 1         | 4.17%   |
| 0     | 1         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 12        | 35.29%  |
| Intel                    | 12        | 35.29%  |
| Qualcomm Atheros         | 3         | 8.82%   |
| TP-Link                  | 1         | 2.94%   |
| Sierra Wireless          | 1         | 2.94%   |
| Ralink Technology        | 1         | 2.94%   |
| Nvidia                   | 1         | 2.94%   |
| Marvell Technology Group | 1         | 2.94%   |
| Broadcom                 | 1         | 2.94%   |
| ASIX Electronics         | 1         | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 16.22%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 5.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 5.41%   |
| Intel Wireless-AC 9260                                            | 2         | 5.41%   |
| Intel Wireless 7260                                               | 2         | 5.41%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 5.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 2.7%    |
| Sierra Wireless EM7455                                            | 1         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.7%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.7%    |
| Nvidia MCP61 Ethernet                                             | 1         | 2.7%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                        | 1         | 2.7%    |
| Intel Wireless 8260                                               | 1         | 2.7%    |
| Intel Wireless 3165                                               | 1         | 2.7%    |
| Intel I211 Gigabit Network Connection                             | 1         | 2.7%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 2.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 8         | 38.1%   |
| Realtek Semiconductor    | 5         | 23.81%  |
| Qualcomm Atheros         | 3         | 14.29%  |
| TP-Link                  | 1         | 4.76%   |
| Sierra Wireless          | 1         | 4.76%   |
| Ralink Technology        | 1         | 4.76%   |
| Marvell Technology Group | 1         | 4.76%   |
| Broadcom                 | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 9.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 9.52%   |
| Intel Wireless-AC 9260                                     | 2         | 9.52%   |
| Intel Wireless 7260                                        | 2         | 9.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 4.76%   |
| Sierra Wireless EM7455                                     | 1         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 4.76%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 4.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 4.76%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 4.76%   |
| Intel Wireless 8265 / 8275                                 | 1         | 4.76%   |
| Intel Wireless 8260                                        | 1         | 4.76%   |
| Intel Wireless 3165                                        | 1         | 4.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 1         | 4.76%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 43.75%  |
| Intel                 | 7         | 43.75%  |
| Nvidia                | 1         | 6.25%   |
| ASIX Electronics      | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 37.5%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 12.5%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.25%   |
| Nvidia MCP61 Ethernet                                             | 1         | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 1         | 6.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 6.25%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 6.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 57.14%  |
| Ethernet | 15        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 56.67%  |
| Ethernet | 13        | 43.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 60.87%  |
| 2     | 9         | 39.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 73.91%  |
| Yes  | 6         | 26.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 7         | 38.89%  |
| Realtek Semiconductor   | 3         | 16.67%  |
| Realtek                 | 2         | 11.11%  |
| Foxconn / Hon Hai       | 2         | 11.11%  |
| Marvell Semiconductor   | 1         | 5.56%   |
| Lite-On Technology      | 1         | 5.56%   |
| Cambridge Silicon Radio | 1         | 5.56%   |
| ASUSTek Computer        | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 22.22%  |
| Realtek Bluetooth Radio                             | 2         | 11.11%  |
| Intel Bluetooth Device                              | 2         | 11.11%  |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 11.11%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5.56%   |
| Realtek Bluetooth Radio                             | 1         | 5.56%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 5.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| ASUS BCM20702A0                                     | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 54.84%  |
| AMD                   | 6         | 19.35%  |
| Nvidia                | 4         | 12.9%   |
| Realtek Semiconductor | 1         | 3.23%   |
| Micronas              | 1         | 3.23%   |
| Dell                  | 1         | 3.23%   |
| C-Media Electronics   | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 5         | 12.82%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 10.26%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 7.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 7.69%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 7.69%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 5.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 5.13%   |
| Realtek Semiconductor USB Audio                                     | 1         | 2.56%   |
| Nvidia MCP61 High Definition Audio                                  | 1         | 2.56%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 2.56%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 2.56%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 2.56%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 2.56%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 2.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 2.56%   |
| Dell AC511 Sound Bar                                                | 1         | 2.56%   |
| C-Media Electronics Audio Adapter                                   | 1         | 2.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.56%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 2.56%   |
| AMD FCH Azalia Controller                                           | 1         | 2.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 40%     |
| SK Hynix            | 5         | 25%     |
| Micron Technology   | 2         | 10%     |
| Crucial             | 2         | 10%     |
| Corsair             | 2         | 10%     |
| A-DATA Technology   | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 4.76%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 4.76%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s         | 1         | 4.76%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 4.76%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 4.76%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 4.76%   |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s           | 1         | 4.76%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.76%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 4.76%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s            | 1         | 4.76%   |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s         | 1         | 4.76%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s       | 1         | 4.76%   |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                | 1         | 4.76%   |
| Corsair RAM VS2GB1333D3 2048MB DIMM DDR3 1333MT/s                | 1         | 4.76%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s            | 1         | 4.76%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 57.89%  |
| DDR3   | 5         | 26.32%  |
| LPDDR3 | 2         | 10.53%  |
| LPDDR4 | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 57.89%  |
| Row Of Chips | 4         | 21.05%  |
| DIMM         | 4         | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 50%     |
| 4096  | 8         | 40%     |
| 16384 | 1         | 5%      |
| 2048  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 47.62%  |
| 1600  | 3         | 14.29%  |
| 2400  | 2         | 9.52%   |
| 2133  | 2         | 9.52%   |
| 1867  | 2         | 9.52%   |
| 1333  | 2         | 9.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| IMC Networks                  | 4         | 26.67%  |
| Quanta                        | 3         | 20%     |
| Chicony Electronics           | 3         | 20%     |
| Microdia                      | 2         | 13.33%  |
| Sunplus Innovation Technology | 1         | 6.67%   |
| Microsoft                     | 1         | 6.67%   |
| Logitech                      | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Quanta HP Wide Vision HD Camera      | 2         | 12.5%   |
| Microdia Integrated_Webcam_HD        | 2         | 12.5%   |
| IMC Networks Integrated Camera       | 2         | 12.5%   |
| Sunplus Dell E5570 integrated webcam | 1         | 6.25%   |
| Quanta VGA WebCam                    | 1         | 6.25%   |
| Microsoft LifeCam Cinema             | 1         | 6.25%   |
| Logitech QuickCam Pro 9000           | 1         | 6.25%   |
| IMC Networks ov9734_azurewave_camera | 1         | 6.25%   |
| IMC Networks HD Camera               | 1         | 6.25%   |
| Chicony VGA Webcam                   | 1         | 6.25%   |
| Chicony USB2.0 2M WebCam             | 1         | 6.25%   |
| Chicony USB 5M WebCam                | 1         | 6.25%   |
| Chicony Integrated Camera            | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Shenzhen Goodix Technology | 2         | 40%     |
| LighTuning Technology      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 20%     |
| Validity Sensors Synaptics WBDI              | 1         | 20%     |
| LighTuning ES603 Swipe Fingerprint Sensor    | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 17        | 73.91%  |
| 1     | 6         | 26.09%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 83.33%  |
| Multimedia controller | 1         | 16.67%  |

