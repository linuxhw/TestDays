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
| Gigabyte  | Z170-D3H-CF                 | Desktop     | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte  | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Framework | Laptop                      | Notebook    | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook  | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| Lenovo    | IdeaPad C340-14API 81N6     | Notebook    | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| ASRock    | B450M-HDV R4.0              | Desktop     | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| Lenovo    | ThinkPad E480 20KNS0MC00    | Notebook    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| ASUSTek   | TUF GAMING B550M-PLUS       | Desktop     | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| HP        | Spectre x360 Convertible... | Convertible | [0b68c3f5c3](https://linux-hardware.org/?probe=0b68c3f5c3) | Sep 20, 2021 |
| Apple     | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP        | G42                         | Notebook    | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
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
| 5.14.0-0.rc5.42.fc35.x86_64                          | 5         | 10.87%  |
| 5.14.0-60.fc35.x86_64                                | 4         | 8.7%    |
| 5.14.7-300.fc35.x86_64                               | 3         | 6.52%   |
| 5.14.6-300.fc35.x86_64                               | 3         | 6.52%   |
| 5.14.0-0.rc6.46.fc35.x86_64                          | 3         | 6.52%   |
| 5.14.3-300.fc35.x86_64                               | 2         | 4.35%   |
| 5.14.1-300.fc35.x86_64                               | 2         | 4.35%   |
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 4.35%   |
| 5.14.8-lqx1.0.fc35.x86_64                            | 1         | 2.17%   |
| 5.14.5-300.fc35.x86_64                               | 1         | 2.17%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 1         | 2.17%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 2.17%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 2.17%   |
| 5.13.7-200.fc34.x86_64                               | 1         | 2.17%   |
| 5.13.4-200.fc34.x86_64                               | 1         | 2.17%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 2.17%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 2.17%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 2.17%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 2.17%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 2.17%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 2.17%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 2.17%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 2.17%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 2.17%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 2.17%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 2.17%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 2.17%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 2.17%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 2.17%   |
| 5.11.18-300.fc34.x86_64                              | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 14        | 34.15%  |
| 5.12.0  | 7         | 17.07%  |
| 5.13.0  | 4         | 9.76%   |
| 5.14.7  | 3         | 7.32%   |
| 5.14.6  | 3         | 7.32%   |
| 5.14.3  | 2         | 4.88%   |
| 5.14.1  | 2         | 4.88%   |
| 5.14.8  | 1         | 2.44%   |
| 5.14.5  | 1         | 2.44%   |
| 5.13.7  | 1         | 2.44%   |
| 5.13.4  | 1         | 2.44%   |
| 5.12.8  | 1         | 2.44%   |
| 5.11.18 | 1         | 2.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 26        | 63.41%  |
| 5.12    | 8         | 19.51%  |
| 5.13    | 6         | 14.63%  |
| 5.11    | 1         | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 30        | 73.17%  |
| KDE     | 5         | 12.2%   |
| MATE    | 3         | 7.32%   |
| Unknown | 2         | 4.88%   |
| KDE5    | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 29        | 72.5%   |
| X11     | 8         | 20%     |
| Tty     | 2         | 5%      |
| Unknown | 1         | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 21        | 52.5%   |
| Unknown | 15        | 37.5%   |
| LightDM | 2         | 5%      |
| TDM     | 1         | 2.5%    |
| SDDM    | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 26        | 63.41%  |
| ru_RU | 3         | 7.32%   |
| pt_BR | 2         | 4.88%   |
| en_CA | 2         | 4.88%   |
| sv_SE | 1         | 2.44%   |
| pl_PL | 1         | 2.44%   |
| nl_NL | 1         | 2.44%   |
| ga_IE | 1         | 2.44%   |
| es_ES | 1         | 2.44%   |
| es_CL | 1         | 2.44%   |
| en_IL | 1         | 2.44%   |
| en_GB | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 85%     |
| BIOS | 6         | 15%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 23        | 56.1%   |
| Ext4  | 15        | 36.59%  |
| Xfs   | 3         | 7.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 25        | 60.98%  |
| Unknown | 13        | 31.71%  |
| MBR     | 3         | 7.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 71.43%  |
| Yes       | 12        | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 80.95%  |
| Yes       | 8         | 19.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 8         | 20%     |
| Lenovo              | 6         | 15%     |
| Hewlett-Packard     | 6         | 15%     |
| ASUSTek Computer    | 5         | 12.5%   |
| Gigabyte Technology | 3         | 7.5%    |
| Notebook            | 2         | 5%      |
| HUAWEI              | 2         | 5%      |
| Acer                | 2         | 5%      |
| Microsoft           | 1         | 2.5%    |
| Framework           | 1         | 2.5%    |
| ECS                 | 1         | 2.5%    |
| AZW                 | 1         | 2.5%    |
| ASRock              | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Notebook P377SM-A                          | 1         | 2.5%    |
| Notebook N2x0WU                            | 1         | 2.5%    |
| Microsoft Surface Pro                      | 1         | 2.5%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 2.5%    |
| Lenovo ThinkPad W541 20EF000UMN            | 1         | 2.5%    |
| Lenovo ThinkPad P51s 20HBCTO1WW            | 1         | 2.5%    |
| Lenovo ThinkPad E480 20KNS0MC00            | 1         | 2.5%    |
| Lenovo IdeaPad C340-14API 81N6             | 1         | 2.5%    |
| Lenovo IdeaPad 530S-14IKB 81EU             | 1         | 2.5%    |
| HUAWEI KLVL-WXX9                           | 1         | 2.5%    |
| HUAWEI BOHK-WAX9X                          | 1         | 2.5%    |
| HP ZBook 15u G5                            | 1         | 2.5%    |
| HP Spectre x360 Convertible 13             | 1         | 2.5%    |
| HP Pavilion x360 Convertible 15-cr0xxx     | 1         | 2.5%    |
| HP Pavilion x360 Convertible 14-dh0xxx     | 1         | 2.5%    |
| HP G42                                     | 1         | 2.5%    |
| HP EliteDesk 800 G2 DM 35W                 | 1         | 2.5%    |
| Gigabyte Z170-D3H                          | 1         | 2.5%    |
| Gigabyte H81M-S2H                          | 1         | 2.5%    |
| Gigabyte F2A88XN-WIFI                      | 1         | 2.5%    |
| Framework Laptop                           | 1         | 2.5%    |
| ECS MCP61M-M3                              | 1         | 2.5%    |
| Dell XPS 17 9700                           | 1         | 2.5%    |
| Dell XPS 15 9570                           | 1         | 2.5%    |
| Dell XPS 15 9550                           | 1         | 2.5%    |
| Dell XPS 13 9380                           | 1         | 2.5%    |
| Dell XPS 13 9310 2-in-1                    | 1         | 2.5%    |
| Dell OptiPlex 9020                         | 1         | 2.5%    |
| Dell OptiPlex 3020                         | 1         | 2.5%    |
| Dell Latitude E5470                        | 1         | 2.5%    |
| AZW GK mini                                | 1         | 2.5%    |
| ASUS TUF GAMING B550M-PLUS                 | 1         | 2.5%    |
| ASUS ROG STRIX B360-I GAMING               | 1         | 2.5%    |
| ASUS PRIME X570-PRO                        | 1         | 2.5%    |
| ASUS Maximus V FORMULA                     | 1         | 2.5%    |
| ASUS G71V                                  | 1         | 2.5%    |
| ASRock B450M-HDV R4.0                      | 1         | 2.5%    |
| Apple MacBook6,1                           | 1         | 2.5%    |
| Acer Aspire ES1-572                        | 1         | 2.5%    |
| Acer Aspire A315-42                        | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell XPS              | 5         | 12.5%   |
| Lenovo ThinkPad       | 4         | 10%     |
| Lenovo IdeaPad        | 2         | 5%      |
| HP Pavilion           | 2         | 5%      |
| Dell OptiPlex         | 2         | 5%      |
| Acer Aspire           | 2         | 5%      |
| Notebook P377SM-A     | 1         | 2.5%    |
| Notebook N2x0WU       | 1         | 2.5%    |
| Microsoft Surface     | 1         | 2.5%    |
| HUAWEI KLVL-WXX9      | 1         | 2.5%    |
| HUAWEI BOHK-WAX9X     | 1         | 2.5%    |
| HP ZBook              | 1         | 2.5%    |
| HP Spectre            | 1         | 2.5%    |
| HP G42                | 1         | 2.5%    |
| HP EliteDesk          | 1         | 2.5%    |
| Gigabyte Z170-D3H     | 1         | 2.5%    |
| Gigabyte H81M-S2H     | 1         | 2.5%    |
| Gigabyte F2A88XN-WIFI | 1         | 2.5%    |
| Framework Laptop      | 1         | 2.5%    |
| ECS MCP61M-M3         | 1         | 2.5%    |
| Dell Latitude         | 1         | 2.5%    |
| AZW GK                | 1         | 2.5%    |
| ASUS TUF              | 1         | 2.5%    |
| ASUS ROG              | 1         | 2.5%    |
| ASUS PRIME            | 1         | 2.5%    |
| ASUS Maximus          | 1         | 2.5%    |
| ASUS G71V             | 1         | 2.5%    |
| ASRock B450M-HDV      | 1         | 2.5%    |
| Apple MacBook6        | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 10        | 25%     |
| 2021 | 8         | 20%     |
| 2019 | 8         | 20%     |
| 2018 | 5         | 12.5%   |
| 2015 | 4         | 10%     |
| 2017 | 1         | 2.5%    |
| 2013 | 1         | 2.5%    |
| 2011 | 1         | 2.5%    |
| 2010 | 1         | 2.5%    |
| 2008 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 22        | 55%     |
| Desktop     | 12        | 30%     |
| Convertible | 4         | 10%     |
| Tablet      | 1         | 2.5%    |
| Mini pc     | 1         | 2.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 31        | 75.61%  |
| Enabled  | 10        | 24.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 31.71%  |
| 16.01-24.0 | 12        | 29.27%  |
| 32.01-64.0 | 6         | 14.63%  |
| 8.01-16.0  | 6         | 14.63%  |
| 3.01-4.0   | 4         | 9.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 17        | 38.64%  |
| 3.01-4.0 | 12        | 27.27%  |
| 1.01-2.0 | 9         | 20.45%  |
| 4.01-8.0 | 4         | 9.09%   |
| 0.51-1.0 | 1         | 2.27%   |
| 0.01-0.5 | 1         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 65%     |
| 2      | 10        | 25%     |
| 3      | 2         | 5%      |
| 5      | 1         | 2.5%    |
| 4      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 82.5%   |
| Yes       | 7         | 17.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 75%     |
| No        | 10        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 87.5%   |
| No        | 5         | 12.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 77.5%   |
| No        | 9         | 22.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 27.5%   |
| Brazil      | 5         | 12.5%   |
| Netherlands | 3         | 7.5%    |
| Canada      | 3         | 7.5%    |
| Turkey      | 2         | 5%      |
| Spain       | 2         | 5%      |
| Belarus     | 2         | 5%      |
| Switzerland | 1         | 2.5%    |
| Sweden      | 1         | 2.5%    |
| Russia      | 1         | 2.5%    |
| Poland      | 1         | 2.5%    |
| Norway      | 1         | 2.5%    |
| Japan       | 1         | 2.5%    |
| Israel      | 1         | 2.5%    |
| Ireland     | 1         | 2.5%    |
| India       | 1         | 2.5%    |
| Hong Kong   | 1         | 2.5%    |
| Germany     | 1         | 2.5%    |
| Chile       | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Yakima         | 2         | 4.76%   |
| Seattle        | 2         | 4.76%   |
| Minsk          | 2         | 4.76%   |
| Laurel         | 2         | 4.76%   |
| Istanbul       | 2         | 4.76%   |
| Atlanta        | 2         | 4.76%   |
| Zurich         | 1         | 2.38%   |
| Wroclaw        | 1         | 2.38%   |
| Whittier       | 1         | 2.38%   |
| Wateringen     | 1         | 2.38%   |
| Vancouver      | 1         | 2.38%   |
| St Petersburg  | 1         | 2.38%   |
| S??o Paulo     | 1         | 2.38%   |
| Salt Lake City | 1         | 2.38%   |
| Royse          | 1         | 2.38%   |
| Raesfeld       | 1         | 2.38%   |
| Porto Ferreira | 1         | 2.38%   |
| Owatonna       | 1         | 2.38%   |
| Osaka          | 1         | 2.38%   |
| Montreal       | 1         | 2.38%   |
| Miami          | 1         | 2.38%   |
| Madrid         | 1         | 2.38%   |
| La Florida     | 1         | 2.38%   |
| Kwu Tung       | 1         | 2.38%   |
| Ja?�n          | 1         | 2.38%   |
| Handen         | 1         | 2.38%   |
| Haifa          | 1         | 2.38%   |
| Guarapuava     | 1         | 2.38%   |
| Goi??nia       | 1         | 2.38%   |
| Fortaleza      | 1         | 2.38%   |
| Dublin         | 1         | 2.38%   |
| Concord        | 1         | 2.38%   |
| Breda          | 1         | 2.38%   |
| Bolszewo       | 1         | 2.38%   |
| Bengaluru      | 1         | 2.38%   |
| Amsterdam      | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 26     | 25%     |
| WDC                 | 11        | 14     | 19.64%  |
| Unknown             | 4         | 4      | 7.14%   |
| Toshiba             | 4         | 4      | 7.14%   |
| Seagate             | 4         | 9      | 7.14%   |
| SK Hynix            | 3         | 4      | 5.36%   |
| SanDisk             | 3         | 4      | 5.36%   |
| LITEON              | 2         | 2      | 3.57%   |
| Kingston            | 2         | 2      | 3.57%   |
| Crucial             | 2         | 2      | 3.57%   |
| USB3.1              | 1         | 1      | 1.79%   |
| SUNEAST             | 1         | 1      | 1.79%   |
| SABRENT             | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| KIOXIA              | 1         | 1      | 1.79%   |
| Hitachi             | 1         | 1      | 1.79%   |
| ASMT                | 1         | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPLX-08ZNTT0 500GB            | 2         | 3.39%   |
| Sandisk NVMe SSD Drive 256GB            | 2         | 3.39%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 3.39%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 1.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 1.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1.69%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 1.69%   |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 1.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 1.69%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1.69%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 1.69%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 1.69%   |
| USB3.1 NVME&SATA 1TB                    | 1         | 1.69%   |
| Unknown USB DISK 3.2 1TB                | 1         | 1.69%   |
| Unknown SSD0240S00 240GB                | 1         | 1.69%   |
| Unknown SD256  249GB                    | 1         | 1.69%   |
| Unknown M.2 SSD 256GB                   | 1         | 1.69%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1.69%   |
| Toshiba MG05ACA800E 8TB                 | 1         | 1.69%   |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 1.69%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 1.69%   |
| SUNEAST SSD SE800 256GB                 | 1         | 1.69%   |
| SK Hynix NVMe SSD Drive 512GB           | 1         | 1.69%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 1.69%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 1.69%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1.69%   |
| Seagate ST9500325AS 500GB               | 1         | 1.69%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.69%   |
| Seagate ST3500630AS 500GB               | 1         | 1.69%   |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 1.69%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 1.69%   |
| SanDisk SDSSDH3512G 512GB               | 1         | 1.69%   |
| Samsung SSD 970 EVO Plus 500GB          | 1         | 1.69%   |
| Samsung SSD 970 EVO 500GB               | 1         | 1.69%   |
| Samsung SSD 860 EVO 500GB               | 1         | 1.69%   |
| Samsung SSD 860 EVO 250GB               | 1         | 1.69%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.69%   |
| Samsung SSD 850 PRO 1TB                 | 1         | 1.69%   |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 1.69%   |
| Samsung SSD 840 EVO 250GB               | 1         | 1.69%   |
| Samsung PM9A1 NVMe 512GB                | 1         | 1.69%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 1.69%   |
| Samsung NVMe SSD Drive 2TB              | 1         | 1.69%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 1         | 1.69%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 1.69%   |
| Samsung MZVLB256HAHQ-000L7 256GB        | 1         | 1.69%   |
| Samsung KUS020203M-B000 128GB           | 1         | 1.69%   |
| SABRENT ASM1153E 512GB                  | 1         | 1.69%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 1.69%   |
| LITEON CX2-8B256-Q11 NVMe 256GB         | 1         | 1.69%   |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 1.69%   |
| KIOXIA KBG40ZPZ512G NVMe 512GB          | 1         | 1.69%   |
| Hitachi HTS545025B9SA02 250GB           | 1         | 1.69%   |
| Crucial CT500MX200SSD4 500GB            | 1         | 1.69%   |
| Crucial CT1024MX200SSD1 1TB             | 1         | 1.69%   |
| ASMT ASM105x 400GB SSD                  | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 41.67%  |
| Seagate | 4         | 9      | 33.33%  |
| Toshiba | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 15     | 23.81%  |
| WDC                 | 4         | 4      | 19.05%  |
| Unknown             | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| SUNEAST             | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 2      | 4.76%   |
| SABRENT             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| ASMT                | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 19        | 24     | 38.78%  |
| SSD     | 17        | 32     | 34.69%  |
| HDD     | 11        | 19     | 22.45%  |
| MMC     | 1         | 1      | 2.04%   |
| Unknown | 1         | 2      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 49     | 50%     |
| NVMe | 19        | 24     | 41.3%   |
| SAS  | 3         | 4      | 6.52%   |
| MMC  | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 27     | 64.29%  |
| 0.51-1.0   | 6         | 15     | 21.43%  |
| 1.01-2.0   | 2         | 2      | 7.14%   |
| 2.01-3.0   | 1         | 6      | 3.57%   |
| 4.01-10.0  | 1         | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 23.81%  |
| 1-20           | 10        | 23.81%  |
| 251-500        | 8         | 19.05%  |
| 501-1000       | 5         | 11.9%   |
| 51-100         | 3         | 7.14%   |
| 1001-2000      | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| 21-50          | 1         | 2.38%   |
| 2001-3000      | 1         | 2.38%   |
| Unknown        | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 20        | 48.78%  |
| 21-50     | 8         | 19.51%  |
| 251-500   | 3         | 7.32%   |
| 101-250   | 3         | 7.32%   |
| 51-100    | 3         | 7.32%   |
| 501-1000  | 2         | 4.88%   |
| 1001-2000 | 1         | 2.44%   |
| Unknown   | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB        | 1         | 1      | 20%     |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 20%     |
| Seagate ST3500630AS 500GB       | 1         | 1      | 20%     |
| LITEON CV8-8E128-HP 128GB SSD   | 1         | 1      | 20%     |
| Hitachi HTS545025B9SA02 250GB   | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| LITEON  | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 75%     |
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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 27        | 33     | 56.25%  |
| Detected | 17        | 40     | 35.42%  |
| Malfunc  | 4         | 5      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 24        | 47.06%  |
| Samsung Electronics          | 9         | 17.65%  |
| AMD                          | 5         | 9.8%    |
| SK Hynix                     | 3         | 5.88%   |
| Sandisk                      | 3         | 5.88%   |
| Toshiba America Info Systems | 2         | 3.92%   |
| Nvidia                       | 2         | 3.92%   |
| Lite-On Technology           | 1         | 1.96%   |
| KIOXIA                       | 1         | 1.96%   |
| ASMedia Technology           | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 11.32%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 9.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 7.55%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 7.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 5.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 5.66%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 3.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 3.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 3.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.89%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.89%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.89%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 1.89%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.89%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.89%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.89%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 1         | 1.89%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.89%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 1         | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 54%     |
| NVMe | 19        | 38%     |
| RAID | 3         | 6%      |
| IDE  | 1         | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 77.5%   |
| AMD    | 9         | 22.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 5%      |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 5%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 5%      |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 2.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 2.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 2.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 2.5%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 2.5%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 2.5%    |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 2.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.5%    |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 2.5%    |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 2.5%    |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 2.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1         | 2.5%    |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 2.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.5%    |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 2.5%    |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1         | 2.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 2.5%    |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 2.5%    |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.5%    |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 1         | 2.5%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 2.5%    |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz            | 1         | 2.5%    |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 2.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 2.5%    |
| AMD Ryzen 5 3600X 6-Core Processor              | 1         | 2.5%    |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 2.5%    |
| AMD Ryzen 5 2600 Six-Core Processor             | 1         | 2.5%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 2.5%    |
| AMD Athlon II X2 250 Processor                  | 1         | 2.5%    |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 13        | 32.5%   |
| Intel Core i5    | 10        | 25%     |
| AMD Ryzen 5      | 6         | 15%     |
| Intel Core i3    | 3         | 7.5%    |
| Other            | 2         | 5%      |
| Intel Core 2 Duo | 2         | 5%      |
| Intel Celeron    | 1         | 2.5%    |
| AMD Ryzen 3      | 1         | 2.5%    |
| AMD Athlon II X2 | 1         | 2.5%    |
| AMD A10          | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 22        | 55%     |
| 2      | 11        | 27.5%   |
| 6      | 7         | 17.5%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 75%     |
| 1      | 10        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ea    | 5         | 12.5%   |
| 0x506e3    | 4         | 10%     |
| 0x306c3    | 4         | 10%     |
| 0x806ec    | 3         | 7.5%    |
| 0x08108109 | 3         | 7.5%    |
| 0x906ea    | 2         | 5%      |
| 0x806e9    | 2         | 5%      |
| 0x806c1    | 2         | 5%      |
| 0x08701021 | 2         | 5%      |
| Unknown    | 2         | 5%      |
| 0xa0652    | 1         | 2.5%    |
| 0x706a8    | 1         | 2.5%    |
| 0x406e3    | 1         | 2.5%    |
| 0x306d4    | 1         | 2.5%    |
| 0x306a9    | 1         | 2.5%    |
| 0x1067a    | 1         | 2.5%    |
| 0x10676    | 1         | 2.5%    |
| 0x08600104 | 1         | 2.5%    |
| 0x08008206 | 1         | 2.5%    |
| 0x06003106 | 1         | 2.5%    |
| 0x010000b6 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 30%     |
| Skylake       | 5         | 12.5%   |
| Haswell       | 5         | 12.5%   |
| Zen+          | 4         | 10%     |
| Zen 2         | 3         | 7.5%    |
| TigerLake     | 2         | 5%      |
| Penryn        | 2         | 5%      |
| Westmere      | 1         | 2.5%    |
| Steamroller   | 1         | 2.5%    |
| K10           | 1         | 2.5%    |
| IvyBridge     | 1         | 2.5%    |
| Goldmont plus | 1         | 2.5%    |
| CometLake     | 1         | 2.5%    |
| Broadwell     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 52.08%  |
| Nvidia | 12        | 25%     |
| AMD    | 11        | 22.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 5         | 10.42%  |
| Intel HD Graphics 530                                                       | 3         | 6.25%   |
| AMD Picasso                                                                 | 3         | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 4.17%   |
| Intel HD Graphics 620                                                       | 2         | 4.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 4.17%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 2.08%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050 3GB]                                         | 1         | 2.08%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 2.08%   |
| Nvidia GM108GLM [Quadro M520 Mobile]                                        | 1         | 2.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 2.08%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 2.08%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 2.08%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1         | 2.08%   |
| Nvidia G96M [GeForce 9700M GT]                                              | 1         | 2.08%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 2.08%   |
| Intel HD Graphics 5500                                                      | 1         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 2.08%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 2.08%   |
| AMD Renoir                                                                  | 1         | 2.08%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                            | 1         | 2.08%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1         | 2.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 42.5%   |
| 1 x AMD        | 9         | 22.5%   |
| 1 x Nvidia     | 7         | 17.5%   |
| Intel + Nvidia | 5         | 12.5%   |
| Intel + AMD    | 2         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 85.37%  |
| Proprietary | 6         | 14.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 57.14%  |
| 1.01-2.0   | 7         | 16.67%  |
| 0.01-0.5   | 4         | 9.52%   |
| 3.01-4.0   | 3         | 7.14%   |
| 0.51-1.0   | 3         | 7.14%   |
| 7.01-8.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 7         | 15.22%  |
| AU Optronics         | 6         | 13.04%  |
| Dell                 | 5         | 10.87%  |
| Chimei Innolux       | 5         | 10.87%  |
| Sharp                | 4         | 8.7%    |
| BOE                  | 4         | 8.7%    |
| Hewlett-Packard      | 3         | 6.52%   |
| Goldstar             | 3         | 6.52%   |
| AOC                  | 2         | 4.35%   |
| Ancor Communications | 2         | 4.35%   |
| Samsung Electronics  | 1         | 2.17%   |
| Philips              | 1         | 2.17%   |
| Lenovo               | 1         | 2.17%   |
| BenQ                 | 1         | 2.17%   |
| Apple                | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                | 1         | 2.13%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 2.13%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 2.13%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 2.13%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 2.13%   |
| Philips LCD Monitor PHL0001 1920x1080 710x400mm 32.1-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 2.13%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch            | 1         | 2.13%   |
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                    | 1         | 2.13%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 2.13%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch             | 1         | 2.13%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1         | 2.13%   |
| Goldstar W2442 GSM56D9 1680x1050 530x300mm 24.0-inch                   | 1         | 2.13%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                  | 1         | 2.13%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch              | 1         | 2.13%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                      | 1         | 2.13%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                      | 1         | 2.13%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                      | 1         | 2.13%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 2.13%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 2.13%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                    | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch       | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch       | 1         | 2.13%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 1         | 2.13%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 2.13%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 2.13%   |
| BOE LCD Monitor BOE0742 1920x1080 309x173mm 13.9-inch                  | 1         | 2.13%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO1088 1920x1200 367x229mm 17.0-inch         | 1         | 2.13%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch                   | 1         | 2.13%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 2.13%   |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1         | 2.13%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 1         | 2.13%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 64.1%   |
| 1920x1200 (WUXGA) | 4         | 10.26%  |
| 3840x2160 (4K)    | 2         | 5.13%   |
| 2560x1440 (QHD)   | 2         | 5.13%   |
| 1366x768 (WXGA)   | 2         | 5.13%   |
| 2736x1824         | 1         | 2.56%   |
| 2256x1504         | 1         | 2.56%   |
| 2160x1440         | 1         | 2.56%   |
| 1280x800 (WXGA)   | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 19.15%  |
| 21     | 7         | 14.89%  |
| 13     | 7         | 14.89%  |
| 14     | 6         | 12.77%  |
| 24     | 5         | 10.64%  |
| 27     | 3         | 6.38%   |
| 23     | 3         | 6.38%   |
| 17     | 3         | 6.38%   |
| 12     | 2         | 4.26%   |
| 40     | 1         | 2.13%   |
| 25     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 37.78%  |
| 501-600     | 10        | 22.22%  |
| 401-500     | 7         | 15.56%  |
| 201-300     | 7         | 15.56%  |
| 351-400     | 3         | 6.67%   |
| 801-900     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 78.38%  |
| 16/10 | 5         | 13.51%  |
| 3/2   | 3         | 8.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 22.22%  |
| 201-250        | 9         | 20%     |
| 101-110        | 9         | 20%     |
| 71-80          | 4         | 8.89%   |
| 301-350        | 3         | 6.67%   |
| 251-300        | 3         | 6.67%   |
| 121-130        | 3         | 6.67%   |
| 151-200        | 2         | 4.44%   |
| 61-70          | 1         | 2.22%   |
| 501-1000       | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 40%     |
| 101-120       | 10        | 22.22%  |
| 51-100        | 9         | 20%     |
| 161-240       | 7         | 15.56%  |
| More than 240 | 1         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 75.61%  |
| 2     | 7         | 17.07%  |
| 3     | 2         | 4.88%   |
| 0     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 39.34%  |
| Realtek Semiconductor    | 23        | 37.7%   |
| Qualcomm Atheros         | 3         | 4.92%   |
| Broadcom                 | 3         | 4.92%   |
| Nvidia                   | 2         | 3.28%   |
| TP-Link                  | 1         | 1.64%   |
| Sierra Wireless          | 1         | 1.64%   |
| Ralink Technology        | 1         | 1.64%   |
| Marvell Technology Group | 1         | 1.64%   |
| Linksys                  | 1         | 1.64%   |
| ASIX Electronics         | 1         | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 15.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 7.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 5.71%   |
| Intel Wireless 7260                                               | 3         | 4.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.86%   |
| Intel Wireless-AC 9260                                            | 2         | 2.86%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.43%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.43%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.43%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.43%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.43%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 1.43%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.43%   |
| Intel Wireless 8260                                               | 1         | 1.43%   |
| Intel Wireless 7265                                               | 1         | 1.43%   |
| Intel Wireless 3165                                               | 1         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.43%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.43%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 19        | 51.35%  |
| Realtek Semiconductor    | 8         | 21.62%  |
| Qualcomm Atheros         | 3         | 8.11%   |
| Broadcom                 | 2         | 5.41%   |
| TP-Link                  | 1         | 2.7%    |
| Sierra Wireless          | 1         | 2.7%    |
| Ralink Technology        | 1         | 2.7%    |
| Marvell Technology Group | 1         | 2.7%    |
| Linksys                  | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 4         | 10.81%  |
| Intel Wireless 7260                                        | 3         | 8.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 5.41%   |
| Intel Wireless-AC 9260                                     | 2         | 5.41%   |
| Intel Wireless 8265 / 8275                                 | 2         | 5.41%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 5.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 2.7%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A        | 1         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                | 1         | 2.7%    |
| Ralink RT5370 Wireless Adapter                             | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.7%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 2.7%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter        | 1         | 2.7%    |
| Intel Wireless 8260                                        | 1         | 2.7%    |
| Intel Wireless 7265                                        | 1         | 2.7%    |
| Intel Wireless 3165                                        | 1         | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.7%    |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 1         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                            | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 53.13%  |
| Intel                 | 11        | 34.38%  |
| Nvidia                | 2         | 6.25%   |
| Broadcom              | 1         | 3.13%   |
| ASIX Electronics      | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 33.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 15.15%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 6.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.03%   |
| Nvidia MCP79 Ethernet                                             | 1         | 3.03%   |
| Nvidia MCP61 Ethernet                                             | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.03%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 53.85%  |
| Ethernet | 30        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 56.6%   |
| Ethernet | 23        | 43.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21        | 52.5%   |
| 2     | 18        | 45%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 70%     |
| Yes  | 12        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 17        | 53.13%  |
| Realtek Semiconductor   | 5         | 15.63%  |
| Realtek                 | 2         | 6.25%   |
| Foxconn / Hon Hai       | 2         | 6.25%   |
| ASUSTek Computer        | 2         | 6.25%   |
| Marvell Semiconductor   | 1         | 3.13%   |
| Lite-On Technology      | 1         | 3.13%   |
| Cambridge Silicon Radio | 1         | 3.13%   |
| Apple                   | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 8         | 25%     |
| Intel Bluetooth wireless interface                  | 4         | 12.5%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 9.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 6.25%   |
| Realtek Bluetooth Radio                             | 2         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 6.25%   |
| Intel AX200 Bluetooth                               | 2         | 6.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 6.25%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 3.13%   |
| Lite-On Bluetooth Device                            | 1         | 3.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 3.13%   |
| ASUS BCM20702A0                                     | 1         | 3.13%   |
| Apple Bluetooth Host Controller                     | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 51.79%  |
| AMD                   | 10        | 17.86%  |
| Nvidia                | 8         | 14.29%  |
| C-Media Electronics   | 3         | 5.36%   |
| Realtek Semiconductor | 2         | 3.57%   |
| Micronas              | 1         | 1.79%   |
| Dell                  | 1         | 1.79%   |
| Creative Labs         | 1         | 1.79%   |
| Conexant Systems      | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 8         | 12.12%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 6.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 4         | 6.06%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 4         | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 4.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 4.55%   |
| Realtek Semiconductor USB Audio                                     | 2         | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 3.03%   |
| C-Media Electronics USB Audio Device                                | 2         | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 3.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2         | 3.03%   |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 1.52%   |
| Nvidia MCP79 High Definition Audio                                  | 1         | 1.52%   |
| Nvidia MCP61 High Definition Audio                                  | 1         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 1.52%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 1.52%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 1.52%   |
| Nvidia GF106 High Definition Audio Controller                       | 1         | 1.52%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 1.52%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 1.52%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.52%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 1.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1         | 1.52%   |
| Dell AC511 Sound Bar                                                | 1         | 1.52%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                  | 1         | 1.52%   |
| Conexant Systems HP Dock Audio                                      | 1         | 1.52%   |
| C-Media Electronics Audio Adapter                                   | 1         | 1.52%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 1.52%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 1.52%   |
| AMD FCH Azalia Controller                                           | 1         | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1         | 1.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 25%     |
| SK Hynix            | 7         | 21.88%  |
| Micron Technology   | 6         | 18.75%  |
| Crucial             | 3         | 9.38%   |
| Corsair             | 3         | 9.38%   |
| Unknown             | 2         | 6.25%   |
| Avant               | 2         | 6.25%   |
| A-DATA Technology   | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                           | 1         | 3.03%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 3.03%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 3.03%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 3.03%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 3.03%   |
| SK Hynix RAM H9CCNNNBLTALAR-NTD 4GB Row Of Chips LPDDR3 1600MT/s | 1         | 3.03%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.03%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 1         | 3.03%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 3.03%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 3.03%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 3.03%   |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s           | 1         | 3.03%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.03%   |
| Micron RAM Module 4GB SODIMM DDR3 1067MT/s                       | 1         | 3.03%   |
| Micron RAM Module 16GB SODIMM DDR4 2400MT/s                      | 1         | 3.03%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 3.03%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 3.03%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s            | 1         | 3.03%   |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s             | 1         | 3.03%   |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s         | 1         | 3.03%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 3000MT/s             | 1         | 3.03%   |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                | 1         | 3.03%   |
| Corsair RAM VS2GB1333D3 2048MB DIMM DDR3 1333MT/s                | 1         | 3.03%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s            | 1         | 3.03%   |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s         | 1         | 3.03%   |
| Avant RAM J642GU42J7240N2 16GB SODIMM DDR4 2400MT/s              | 1         | 3.03%   |
| Avant RAM J642GU42J5213N2 16GB SODIMM DDR4 2133MT/s              | 1         | 3.03%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s          | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 60%     |
| DDR3    | 6         | 20%     |
| LPDDR3  | 3         | 10%     |
| LPDDR4  | 2         | 6.67%   |
| Unknown | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 56.67%  |
| DIMM         | 7         | 23.33%  |
| Row Of Chips | 6         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 41.94%  |
| 4096  | 11        | 35.48%  |
| 16384 | 5         | 16.13%  |
| 2048  | 2         | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 30.3%   |
| 2400  | 4         | 12.12%  |
| 2133  | 4         | 12.12%  |
| 1600  | 4         | 12.12%  |
| 3200  | 2         | 6.06%   |
| 1867  | 2         | 6.06%   |
| 1333  | 2         | 6.06%   |
| 4267  | 1         | 3.03%   |
| 3266  | 1         | 3.03%   |
| 3000  | 1         | 3.03%   |
| 1067  | 1         | 3.03%   |
| 1066  | 1         | 3.03%   |

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
| IMC Networks                  | 5         | 17.24%  |
| Microdia                      | 4         | 13.79%  |
| Chicony Electronics           | 4         | 13.79%  |
| Quanta                        | 3         | 10.34%  |
| Logitech                      | 3         | 10.34%  |
| Acer                          | 3         | 10.34%  |
| Sunplus Innovation Technology | 2         | 6.9%    |
| Suyin                         | 1         | 3.45%   |
| Realtek Semiconductor         | 1         | 3.45%   |
| Microsoft                     | 1         | 3.45%   |
| Lite-On Technology            | 1         | 3.45%   |
| Apple                         | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 4         | 13.33%  |
| IMC Networks Integrated Camera       | 3         | 10%     |
| Quanta HP Wide Vision HD Camera      | 2         | 6.67%   |
| IMC Networks ov9734_azurewave_camera | 2         | 6.67%   |
| Acer Integrated Camera               | 2         | 6.67%   |
| Suyin HP Webcam-101                  | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD         | 1         | 3.33%   |
| Sunplus HP Truevision Full HD        | 1         | 3.33%   |
| Realtek Laptop Camera                | 1         | 3.33%   |
| Quanta VGA WebCam                    | 1         | 3.33%   |
| Microsoft LifeCam Cinema             | 1         | 3.33%   |
| Logitech QuickCam Pro 9000           | 1         | 3.33%   |
| Logitech HD Webcam C615              | 1         | 3.33%   |
| Logitech HD Pro Webcam C920          | 1         | 3.33%   |
| Lite-On HP HD Camera                 | 1         | 3.33%   |
| Chicony VGA Webcam                   | 1         | 3.33%   |
| Chicony USB2.0 2M WebCam             | 1         | 3.33%   |
| Chicony USB 5M WebCam                | 1         | 3.33%   |
| Chicony Integrated Camera            | 1         | 3.33%   |
| Chicony CNF7246                      | 1         | 3.33%   |
| Apple Built-in iSight                | 1         | 3.33%   |
| Acer BisonCam, NB Pro                | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 37.5%   |
| Validity Sensors           | 2         | 25%     |
| Shenzhen Goodix Technology | 2         | 25%     |
| LighTuning Technology      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                   | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 12.5%   |
| Unknown                                           | 1         | 12.5%   |

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
| 0     | 31        | 77.5%   |
| 1     | 9         | 22.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 88.89%  |
| Multimedia controller | 1         | 11.11%  |

