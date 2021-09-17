Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35.

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
| HP        | ZBook 15u G5                | Notebook    | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell      | XPS 17 9700                 | Notebook    | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek   | ROG STRIX B360-I GAMING     | Desktop     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek   | ROG STRIX B360-I GAMING     | Desktop     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| ASUSTek   | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Dell      | XPS 13 9310 2-in-1          | Convertible | [2766de5f8a](https://linux-hardware.org/?probe=2766de5f8a) | Sep 08, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 8... | Notebook    | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
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
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 14.29%  |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 3         | 8.57%   |
| 5.14.3-300.fc35.x86_64                               | 2         | 5.71%   |
| 5.14.1-300.fc35.x86_64                               | 2         | 5.71%   |
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 5.71%   |
| 5.14.0-60.fc35.x86_64                                | 1         | 2.86%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 2.86%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 2.86%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 2.86%   |
| 5.13.7-200.fc34.x86_64                               | 1         | 2.86%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 2.86%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 2.86%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 2.86%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 2.86%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 2.86%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 2.86%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 2.86%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 2.86%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 2.86%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 2.86%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 2.86%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 2.86%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 2.86%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 2.86%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 2.86%   |
| 5.11.18-300.fc34.x86_64                              | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 11        | 36.67%  |
| 5.12.0  | 7         | 23.33%  |
| 5.13.0  | 4         | 13.33%  |
| 5.14.3  | 2         | 6.67%   |
| 5.14.1  | 2         | 6.67%   |
| 5.13.7  | 1         | 3.33%   |
| 5.13.4  | 1         | 3.33%   |
| 5.12.8  | 1         | 3.33%   |
| 5.11.18 | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 15        | 50%     |
| 5.12    | 8         | 26.67%  |
| 5.13    | 6         | 20%     |
| 5.11    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 21        | 70%     |
| KDE     | 5         | 16.67%  |
| MATE    | 3         | 10%     |
| Unknown | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 21        | 72.41%  |
| X11     | 6         | 20.69%  |
| Tty     | 2         | 6.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 17        | 58.62%  |
| Unknown | 9         | 31.03%  |
| LightDM | 2         | 6.9%    |
| TDM     | 1         | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 21        | 70%     |
| ru_RU | 2         | 6.67%   |
| en_CA | 2         | 6.67%   |
| sv_SE | 1         | 3.33%   |
| pl_PL | 1         | 3.33%   |
| es_ES | 1         | 3.33%   |
| es_CL | 1         | 3.33%   |
| en_GB | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 26        | 89.66%  |
| BIOS | 3         | 10.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 14        | 46.67%  |
| Btrfs | 14        | 46.67%  |
| Xfs   | 2         | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 20        | 66.67%  |
| Unknown | 8         | 26.67%  |
| MBR     | 2         | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 64.52%  |
| Yes       | 11        | 35.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 8         | 27.59%  |
| Lenovo              | 4         | 13.79%  |
| Hewlett-Packard     | 4         | 13.79%  |
| ASUSTek Computer    | 4         | 13.79%  |
| HUAWEI              | 2         | 6.9%    |
| Acer                | 2         | 6.9%    |
| Notebook            | 1         | 3.45%   |
| Microsoft           | 1         | 3.45%   |
| Gigabyte Technology | 1         | 3.45%   |
| ECS                 | 1         | 3.45%   |
| AZW                 | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Notebook P377SM-A                          | 1         | 3.45%   |
| Microsoft Surface Pro                      | 1         | 3.45%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 3.45%   |
| Lenovo ThinkPad W541 20EF000UMN            | 1         | 3.45%   |
| Lenovo ThinkPad P51s 20HBCTO1WW            | 1         | 3.45%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 1         | 3.45%   |
| HUAWEI KLVL-WXX9                           | 1         | 3.45%   |
| HUAWEI BOHK-WAX9X                          | 1         | 3.45%   |
| HP ZBook 15u G5                            | 1         | 3.45%   |
| HP Pavilion x360 Convertible 15-cr0xxx     | 1         | 3.45%   |
| HP Pavilion x360 Convertible 14-dh0xxx     | 1         | 3.45%   |
| HP EliteDesk 800 G2 DM 35W                 | 1         | 3.45%   |
| Gigabyte F2A88XN-WIFI                      | 1         | 3.45%   |
| ECS MCP61M-M3                              | 1         | 3.45%   |
| Dell XPS 17 9700                           | 1         | 3.45%   |
| Dell XPS 15 9570                           | 1         | 3.45%   |
| Dell XPS 15 9550                           | 1         | 3.45%   |
| Dell XPS 13 9380                           | 1         | 3.45%   |
| Dell XPS 13 9310 2-in-1                    | 1         | 3.45%   |
| Dell OptiPlex 9020                         | 1         | 3.45%   |
| Dell OptiPlex 3020                         | 1         | 3.45%   |
| Dell Latitude E5470                        | 1         | 3.45%   |
| AZW GK mini                                | 1         | 3.45%   |
| ASUS ROG STRIX B360-I GAMING               | 1         | 3.45%   |
| ASUS PRIME X570-PRO                        | 1         | 3.45%   |
| ASUS Maximus V FORMULA                     | 1         | 3.45%   |
| ASUS G71V                                  | 1         | 3.45%   |
| Acer Aspire ES1-572                        | 1         | 3.45%   |
| Acer Aspire A315-42                        | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell XPS              | 5         | 17.24%  |
| Lenovo ThinkPad       | 3         | 10.34%  |
| HP Pavilion           | 2         | 6.9%    |
| Dell OptiPlex         | 2         | 6.9%    |
| Acer Aspire           | 2         | 6.9%    |
| Notebook P377SM-A     | 1         | 3.45%   |
| Microsoft Surface     | 1         | 3.45%   |
| Lenovo IdeaPad        | 1         | 3.45%   |
| HUAWEI KLVL-WXX9      | 1         | 3.45%   |
| HUAWEI BOHK-WAX9X     | 1         | 3.45%   |
| HP ZBook              | 1         | 3.45%   |
| HP EliteDesk          | 1         | 3.45%   |
| Gigabyte F2A88XN-WIFI | 1         | 3.45%   |
| ECS MCP61M-M3         | 1         | 3.45%   |
| Dell Latitude         | 1         | 3.45%   |
| AZW GK                | 1         | 3.45%   |
| ASUS ROG              | 1         | 3.45%   |
| ASUS PRIME            | 1         | 3.45%   |
| ASUS Maximus          | 1         | 3.45%   |
| ASUS G71V             | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 9         | 31.03%  |
| 2021 | 6         | 20.69%  |
| 2019 | 5         | 17.24%  |
| 2018 | 3         | 10.34%  |
| 2015 | 3         | 10.34%  |
| 2013 | 1         | 3.45%   |
| 2010 | 1         | 3.45%   |
| 2008 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 16        | 55.17%  |
| Desktop     | 8         | 27.59%  |
| Convertible | 3         | 10.34%  |
| Tablet      | 1         | 3.45%   |
| Mini pc     | 1         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 23        | 76.67%  |
| Enabled  | 7         | 23.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 36.67%  |
| 16.01-24.0 | 7         | 23.33%  |
| 8.01-16.0  | 5         | 16.67%  |
| 32.01-64.0 | 4         | 13.33%  |
| 3.01-4.0   | 3         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 11        | 33.33%  |
| 3.01-4.0 | 9         | 27.27%  |
| 1.01-2.0 | 8         | 24.24%  |
| 4.01-8.0 | 3         | 9.09%   |
| 0.51-1.0 | 1         | 3.03%   |
| 0.01-0.5 | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 6         | 20.69%  |
| 5      | 1         | 3.45%   |
| 4      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 82.76%  |
| Yes       | 5         | 17.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 72.41%  |
| No        | 8         | 27.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 89.66%  |
| No        | 3         | 10.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 79.31%  |
| No        | 6         | 20.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 34.48%  |
| Canada      | 3         | 10.34%  |
| Brazil      | 2         | 6.9%    |
| Turkey      | 1         | 3.45%   |
| Switzerland | 1         | 3.45%   |
| Sweden      | 1         | 3.45%   |
| Spain       | 1         | 3.45%   |
| Russia      | 1         | 3.45%   |
| Poland      | 1         | 3.45%   |
| Norway      | 1         | 3.45%   |
| Netherlands | 1         | 3.45%   |
| Japan       | 1         | 3.45%   |
| India       | 1         | 3.45%   |
| Hong Kong   | 1         | 3.45%   |
| Germany     | 1         | 3.45%   |
| Chile       | 1         | 3.45%   |
| Belarus     | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Yakima         | 2         | 6.45%   |
| Laurel         | 2         | 6.45%   |
| Atlanta        | 2         | 6.45%   |
| Zurich         | 1         | 3.23%   |
| Wroclaw        | 1         | 3.23%   |
| Whittier       | 1         | 3.23%   |
| Wateringen     | 1         | 3.23%   |
| Vancouver      | 1         | 3.23%   |
| St Petersburg  | 1         | 3.23%   |
| Seattle        | 1         | 3.23%   |
| S??o Paulo     | 1         | 3.23%   |
| Salt Lake City | 1         | 3.23%   |
| Royse          | 1         | 3.23%   |
| Raesfeld       | 1         | 3.23%   |
| Porto Ferreira | 1         | 3.23%   |
| Owatonna       | 1         | 3.23%   |
| Osaka          | 1         | 3.23%   |
| Montreal       | 1         | 3.23%   |
| Minsk          | 1         | 3.23%   |
| Miami          | 1         | 3.23%   |
| Madrid         | 1         | 3.23%   |
| La Florida     | 1         | 3.23%   |
| Kwu Tung       | 1         | 3.23%   |
| Istanbul       | 1         | 3.23%   |
| Handen         | 1         | 3.23%   |
| Concord        | 1         | 3.23%   |
| Bolszewo       | 1         | 3.23%   |
| Bengaluru      | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 22     | 26.32%  |
| WDC                 | 7         | 10     | 18.42%  |
| Unknown             | 3         | 3      | 7.89%   |
| Toshiba             | 3         | 3      | 7.89%   |
| SanDisk             | 3         | 4      | 7.89%   |
| SK Hynix            | 2         | 3      | 5.26%   |
| Seagate             | 2         | 7      | 5.26%   |
| LITEON              | 2         | 2      | 5.26%   |
| SUNEAST             | 1         | 1      | 2.63%   |
| SABRENT             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| KIOXIA              | 1         | 1      | 2.63%   |
| Kingston            | 1         | 1      | 2.63%   |
| ASMT                | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 256GB            | 2         | 4.88%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 2.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 2.44%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.44%   |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 2.44%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2.44%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 2.44%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 2.44%   |
| Unknown SSD0240S00 240GB                | 1         | 2.44%   |
| Unknown SD256  249GB                    | 1         | 2.44%   |
| Unknown M.2 SSD 256GB                   | 1         | 2.44%   |
| Toshiba MG05ACA800E 8TB                 | 1         | 2.44%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 2.44%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 2.44%   |
| SUNEAST SSD SE800 256GB                 | 1         | 2.44%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 2.44%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 2.44%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 2.44%   |
| Seagate ST3500630AS 500GB               | 1         | 2.44%   |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 2.44%   |
| SanDisk SDSSDH3512G 512GB               | 1         | 2.44%   |
| Samsung SSD 970 EVO 500GB               | 1         | 2.44%   |
| Samsung SSD 860 EVO 250GB               | 1         | 2.44%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 2.44%   |
| Samsung SSD 850 PRO 1TB                 | 1         | 2.44%   |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 2.44%   |
| Samsung SSD 840 EVO 250GB               | 1         | 2.44%   |
| Samsung PM9A1 NVMe 512GB                | 1         | 2.44%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 2.44%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 1         | 2.44%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 2.44%   |
| Samsung KUS020203M-B000 128GB           | 1         | 2.44%   |
| SABRENT ASM1153E 512GB                  | 1         | 2.44%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 2.44%   |
| LITEON CX2-8B256-Q11 NVMe 256GB         | 1         | 2.44%   |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 2.44%   |
| KIOXIA KBG40ZPZ512G NVMe 512GB          | 1         | 2.44%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 2.44%   |
| ASMT ASM105x 400GB SSD                  | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 5      | 50%     |
| Seagate | 2         | 7      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 14     | 26.67%  |
| WDC                 | 2         | 2      | 13.33%  |
| Unknown             | 2         | 2      | 13.33%  |
| SUNEAST             | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 2      | 6.67%   |
| SABRENT             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| LITEON              | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| ASMT                | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 20     | 45.45%  |
| SSD  | 12        | 26     | 36.36%  |
| HDD  | 5         | 13     | 15.15%  |
| MMC  | 1         | 1      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 20     | 45.45%  |
| SATA | 15        | 37     | 45.45%  |
| SAS  | 2         | 2      | 6.06%   |
| MMC  | 1         | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 18     | 57.89%  |
| 0.51-1.0   | 4         | 9      | 21.05%  |
| 1.01-2.0   | 2         | 5      | 10.53%  |
| 2.01-3.0   | 1         | 6      | 5.26%   |
| 4.01-10.0  | 1         | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 29.03%  |
| 1-20       | 8         | 25.81%  |
| 251-500    | 7         | 22.58%  |
| 501-1000   | 2         | 6.45%   |
| 51-100     | 2         | 6.45%   |
| 21-50      | 1         | 3.23%   |
| 2001-3000  | 1         | 3.23%   |
| 1001-2000  | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 53.33%  |
| 21-50     | 5         | 16.67%  |
| 251-500   | 3         | 10%     |
| 101-250   | 2         | 6.67%   |
| 51-100    | 2         | 6.67%   |
| 1001-2000 | 1         | 3.33%   |
| 501-1000  | 1         | 3.33%   |

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
| Works    | 22        | 27     | 61.11%  |
| Detected | 12        | 30     | 33.33%  |
| Malfunc  | 2         | 3      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 47.37%  |
| Samsung Electronics          | 6         | 15.79%  |
| Sandisk                      | 3         | 7.89%   |
| AMD                          | 3         | 7.89%   |
| Toshiba America Info Systems | 2         | 5.26%   |
| SK Hynix                     | 2         | 5.26%   |
| Nvidia                       | 1         | 2.63%   |
| Lite-On Technology           | 1         | 2.63%   |
| KIOXIA                       | 1         | 2.63%   |
| ASMedia Technology           | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 10.26%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 7.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 7.69%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 5.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 5.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 2.56%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 2.56%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 2.56%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 2.56%   |
| Nvidia MCP61 IDE                                                                 | 1         | 2.56%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 2.56%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18        | 48.65%  |
| NVMe | 15        | 40.54%  |
| RAID | 3         | 8.11%   |
| IDE  | 1         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 79.31%  |
| AMD    | 6         | 20.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 6.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 3.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 3.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 3.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 3.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 3.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 3.45%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 3.45%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 3.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 3.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 3.45%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 3.45%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 3.45%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 3.45%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 3.45%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 3.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1         | 3.45%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 3.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 3.45%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 3.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 3.45%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 3.45%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 3.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 3.45%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 3.45%   |
| AMD Athlon II X2 250 Processor                  | 1         | 3.45%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 11        | 37.93%  |
| Intel Core i5    | 7         | 24.14%  |
| AMD Ryzen 5      | 3         | 10.34%  |
| Intel Core i3    | 2         | 6.9%    |
| Other            | 1         | 3.45%   |
| Intel Core 2 Duo | 1         | 3.45%   |
| Intel Celeron    | 1         | 3.45%   |
| AMD Ryzen 3      | 1         | 3.45%   |
| AMD Athlon II X2 | 1         | 3.45%   |
| AMD A10          | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 55.17%  |
| 2      | 8         | 27.59%  |
| 6      | 5         | 17.24%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 75.86%  |
| 1      | 7         | 24.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 13.79%  |
| 0x806ec    | 3         | 10.34%  |
| 0x806ea    | 3         | 10.34%  |
| 0x506e3    | 3         | 10.34%  |
| 0x906ea    | 2         | 6.9%    |
| 0x806e9    | 2         | 6.9%    |
| 0x08108109 | 2         | 6.9%    |
| 0xa0652    | 1         | 3.45%   |
| 0x806c1    | 1         | 3.45%   |
| 0x706a8    | 1         | 3.45%   |
| 0x406e3    | 1         | 3.45%   |
| 0x306a9    | 1         | 3.45%   |
| 0x10676    | 1         | 3.45%   |
| 0x08701021 | 1         | 3.45%   |
| 0x08600104 | 1         | 3.45%   |
| 0x06003106 | 1         | 3.45%   |
| 0x010000b6 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 34.48%  |
| Skylake       | 4         | 13.79%  |
| Haswell       | 4         | 13.79%  |
| Zen+          | 2         | 6.9%    |
| Zen 2         | 2         | 6.9%    |
| TigerLake     | 1         | 3.45%   |
| Steamroller   | 1         | 3.45%   |
| Penryn        | 1         | 3.45%   |
| K10           | 1         | 3.45%   |
| IvyBridge     | 1         | 3.45%   |
| Goldmont plus | 1         | 3.45%   |
| CometLake     | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 55.56%  |
| Nvidia | 9         | 25%     |
| AMD    | 7         | 19.44%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 3         | 8.33%   |
| Intel HD Graphics 530                                                       | 3         | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 5.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 5.56%   |
| Intel HD Graphics 620                                                       | 2         | 5.56%   |
| AMD Picasso                                                                 | 2         | 5.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 2.78%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 2.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 2.78%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 2.78%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                        | 1         | 2.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 2.78%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 2.78%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 2.78%   |
| Nvidia G96M [GeForce 9700M GT]                                              | 1         | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 2.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 2.78%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 2.78%   |
| AMD Renoir                                                                  | 1         | 2.78%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1         | 2.78%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 2.78%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 44.83%  |
| 1 x AMD        | 6         | 20.69%  |
| Intel + Nvidia | 5         | 17.24%  |
| 1 x Nvidia     | 4         | 13.79%  |
| Intel + AMD    | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 25        | 83.33%  |
| Proprietary | 5         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 58.06%  |
| 1.01-2.0   | 5         | 16.13%  |
| 0.01-0.5   | 3         | 9.68%   |
| 3.01-4.0   | 2         | 6.45%   |
| 0.51-1.0   | 2         | 6.45%   |
| 7.01-8.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 6         | 19.35%  |
| LG Display           | 5         | 16.13%  |
| Dell                 | 5         | 16.13%  |
| Sharp                | 4         | 12.9%   |
| Chimei Innolux       | 3         | 9.68%   |
| Hewlett-Packard      | 2         | 6.45%   |
| BOE                  | 2         | 6.45%   |
| AOC                  | 2         | 6.45%   |
| Goldstar             | 1         | 3.23%   |
| Ancor Communications | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                | 1         | 3.13%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 3.13%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 3.13%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 3.13%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 3.13%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 3.13%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 3.13%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch             | 1         | 3.13%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch              | 1         | 3.13%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                      | 1         | 3.13%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                      | 1         | 3.13%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                      | 1         | 3.13%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 3.13%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 3.13%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                    | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch       | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 3.13%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 3.13%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO1088 1920x1200 367x229mm 17.0-inch         | 1         | 3.13%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 3.13%   |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1         | 3.13%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 17        | 60.71%  |
| 1920x1200 (WUXGA) | 4         | 14.29%  |
| 3840x2160 (4K)    | 2         | 7.14%   |
| 2560x1440 (QHD)   | 2         | 7.14%   |
| 2736x1824         | 1         | 3.57%   |
| 2160x1440         | 1         | 3.57%   |
| 1366x768 (WXGA)   | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 28.13%  |
| 21     | 5         | 15.63%  |
| 14     | 4         | 12.5%   |
| 27     | 3         | 9.38%   |
| 17     | 3         | 9.38%   |
| 13     | 3         | 9.38%   |
| 24     | 2         | 6.25%   |
| 25     | 1         | 3.13%   |
| 23     | 1         | 3.13%   |
| 12     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 40.63%  |
| 501-600     | 7         | 21.88%  |
| 401-500     | 5         | 15.63%  |
| 201-300     | 4         | 12.5%   |
| 351-400     | 3         | 9.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 77.78%  |
| 16/10 | 4         | 14.81%  |
| 3/2   | 2         | 7.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 28.13%  |
| 81-90          | 5         | 15.63%  |
| 201-250        | 5         | 15.63%  |
| 71-80          | 3         | 9.38%   |
| 301-350        | 3         | 9.38%   |
| 251-300        | 3         | 9.38%   |
| 121-130        | 3         | 9.38%   |
| 151-200        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 43.75%  |
| 101-120       | 7         | 21.88%  |
| 161-240       | 5         | 15.63%  |
| 51-100        | 5         | 15.63%  |
| More than 240 | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 80%     |
| 2     | 4         | 13.33%  |
| 3     | 1         | 3.33%   |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 40%     |
| Realtek Semiconductor    | 15        | 33.33%  |
| Qualcomm Atheros         | 3         | 6.67%   |
| Broadcom                 | 2         | 4.44%   |
| TP-Link                  | 1         | 2.22%   |
| Sierra Wireless          | 1         | 2.22%   |
| Ralink Technology        | 1         | 2.22%   |
| Nvidia                   | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| Linksys                  | 1         | 2.22%   |
| ASIX Electronics         | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 13.73%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.88%   |
| Intel Wireless 7260                                               | 3         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 3.92%   |
| Intel Wireless-AC 9260                                            | 2         | 3.92%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.92%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.96%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.96%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.96%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.96%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 1.96%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.96%   |
| Intel Wireless 8260                                               | 1         | 1.96%   |
| Intel Wireless 3165                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.96%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 50%     |
| Realtek Semiconductor    | 5         | 17.86%  |
| Qualcomm Atheros         | 3         | 10.71%  |
| TP-Link                  | 1         | 3.57%   |
| Sierra Wireless          | 1         | 3.57%   |
| Ralink Technology        | 1         | 3.57%   |
| Marvell Technology Group | 1         | 3.57%   |
| Linksys                  | 1         | 3.57%   |
| Broadcom                 | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                        | 3         | 10.71%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 7.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 7.14%   |
| Intel Wireless-AC 9260                                     | 2         | 7.14%   |
| Intel Wireless 8265 / 8275                                 | 2         | 7.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 3.57%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A        | 1         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.57%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 3.57%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter        | 1         | 3.57%   |
| Intel Wireless 8260                                        | 1         | 3.57%   |
| Intel Wireless 3165                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.57%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 1         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 3.57%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 43.48%  |
| Intel                 | 10        | 43.48%  |
| Nvidia                | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |
| ASIX Electronics      | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 30.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 13.04%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 8.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 8.7%    |
| Nvidia MCP61 Ethernet                                             | 1         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 4.35%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 4.35%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 4.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 55.32%  |
| Ethernet | 21        | 44.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 55.26%  |
| Ethernet | 17        | 44.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 16        | 55.17%  |
| 2     | 12        | 41.38%  |
| 3     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20        | 68.97%  |
| Yes  | 9         | 31.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 12        | 50%     |
| Realtek Semiconductor   | 3         | 12.5%   |
| Realtek                 | 2         | 8.33%   |
| Foxconn / Hon Hai       | 2         | 8.33%   |
| ASUSTek Computer        | 2         | 8.33%   |
| Marvell Semiconductor   | 1         | 4.17%   |
| Lite-On Technology      | 1         | 4.17%   |
| Cambridge Silicon Radio | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 7         | 29.17%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 8.33%   |
| Realtek Bluetooth Radio                             | 2         | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 8.33%   |
| Intel Bluetooth wireless interface                  | 2         | 8.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 8.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 4.17%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 4.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 4.17%   |
| ASUS BCM20702A0                                     | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 57.5%   |
| AMD                   | 6         | 15%     |
| Nvidia                | 5         | 12.5%   |
| Realtek Semiconductor | 2         | 5%      |
| Micronas              | 1         | 2.5%    |
| Dell                  | 1         | 2.5%    |
| Conexant Systems      | 1         | 2.5%    |
| C-Media Electronics   | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 6         | 12.5%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 6.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 6.25%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 3         | 6.25%   |
| Realtek Semiconductor USB Audio                                     | 2         | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 4.17%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 4.17%   |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 2.08%   |
| Nvidia MCP61 High Definition Audio                                  | 1         | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 2.08%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 2.08%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 2.08%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 2.08%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 2.08%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 2.08%   |
| Dell AC511 Sound Bar                                                | 1         | 2.08%   |
| Conexant Systems HP Dock Audio                                      | 1         | 2.08%   |
| C-Media Electronics Audio Adapter                                   | 1         | 2.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.08%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 2.08%   |
| AMD FCH Azalia Controller                                           | 1         | 2.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 32%     |
| SK Hynix            | 5         | 20%     |
| Micron Technology   | 4         | 16%     |
| Corsair             | 3         | 12%     |
| Unknown             | 2         | 8%      |
| Crucial             | 2         | 8%      |
| A-DATA Technology   | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                           | 1         | 3.85%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 3.85%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 3.85%   |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s           | 1         | 3.85%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.85%   |
| Micron RAM Module 16GB SODIMM DDR4 2400MT/s                      | 1         | 3.85%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 3.85%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 3.85%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s            | 1         | 3.85%   |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s         | 1         | 3.85%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                | 1         | 3.85%   |
| Corsair RAM VS2GB1333D3 2048MB DIMM DDR3 1333MT/s                | 1         | 3.85%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s            | 1         | 3.85%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s            | 1         | 3.85%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s          | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 58.33%  |
| DDR3    | 5         | 20.83%  |
| LPDDR4  | 2         | 8.33%   |
| LPDDR3  | 2         | 8.33%   |
| Unknown | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 58.33%  |
| Row Of Chips | 5         | 20.83%  |
| DIMM         | 5         | 20.83%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 48%     |
| 4096  | 9         | 36%     |
| 16384 | 2         | 8%      |
| 2048  | 2         | 8%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 9         | 34.62%  |
| 2400  | 3         | 11.54%  |
| 1600  | 3         | 11.54%  |
| 3200  | 2         | 7.69%   |
| 2133  | 2         | 7.69%   |
| 1867  | 2         | 7.69%   |
| 1333  | 2         | 7.69%   |
| 4267  | 1         | 3.85%   |
| 3266  | 1         | 3.85%   |
| 1066  | 1         | 3.85%   |

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
| Microdia                      | 4         | 19.05%  |
| IMC Networks                  | 4         | 19.05%  |
| Chicony Electronics           | 4         | 19.05%  |
| Quanta                        | 3         | 14.29%  |
| Logitech                      | 2         | 9.52%   |
| Sunplus Innovation Technology | 1         | 4.76%   |
| Microsoft                     | 1         | 4.76%   |
| Lite-On Technology            | 1         | 4.76%   |
| Acer                          | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 4         | 18.18%  |
| Quanta HP Wide Vision HD Camera      | 2         | 9.09%   |
| IMC Networks Integrated Camera       | 2         | 9.09%   |
| Sunplus Dell E5570 integrated webcam | 1         | 4.55%   |
| Quanta VGA WebCam                    | 1         | 4.55%   |
| Microsoft LifeCam Cinema             | 1         | 4.55%   |
| Logitech QuickCam Pro 9000           | 1         | 4.55%   |
| Logitech HD Pro Webcam C920          | 1         | 4.55%   |
| Lite-On HP HD Camera                 | 1         | 4.55%   |
| IMC Networks ov9734_azurewave_camera | 1         | 4.55%   |
| IMC Networks HD Camera               | 1         | 4.55%   |
| Chicony VGA Webcam                   | 1         | 4.55%   |
| Chicony USB2.0 2M WebCam             | 1         | 4.55%   |
| Chicony USB 5M WebCam                | 1         | 4.55%   |
| Chicony Integrated Camera            | 1         | 4.55%   |
| Chicony CNF7246                      | 1         | 4.55%   |
| Acer Integrated Camera               | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 33.33%  |
| Synaptics                  | 1         | 16.67%  |
| LighTuning Technology      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                   | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 16.67%  |

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
| 0     | 22        | 75.86%  |
| 1     | 7         | 24.14%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 85.71%  |
| Multimedia controller | 1         | 14.29%  |

