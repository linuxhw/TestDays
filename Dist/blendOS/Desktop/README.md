blendOS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for blendOS.

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

Total: 50

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | B450M-A PRO MAX II          | [dd3e786ebe](https://linux-hardware.org/?probe=dd3e786ebe) | Jul 15, 2024 |
| Gigabyte  | B550M AORUS PRO-P           | [5a85b71894](https://linux-hardware.org/?probe=5a85b71894) | Jun 13, 2024 |
| Gigabyte  | B550M AORUS PRO-P           | [b3e1342003](https://linux-hardware.org/?probe=b3e1342003) | May 12, 2024 |
| MSI       | B550M-A PRO                 | [7101b53f84](https://linux-hardware.org/?probe=7101b53f84) | May 11, 2024 |
| Lenovo    | 36E7 SDK0J40700 WIN 3258... | [03d6226580](https://linux-hardware.org/?probe=03d6226580) | May 01, 2024 |
| ASUSTek   | H81M-C                      | [a13bfac287](https://linux-hardware.org/?probe=a13bfac287) | Feb 10, 2024 |
| Gigabyte  | X99P-SLI-CF                 | [95705bca92](https://linux-hardware.org/?probe=95705bca92) | Feb 01, 2024 |
| Fujitsu   | D3603-A1 S26361-D3603-A1    | [f6ed1d1cc4](https://linux-hardware.org/?probe=f6ed1d1cc4) | Jan 15, 2024 |
| ASUSTek   | ROG STRIX B450-E GAMING     | [cf1d697418](https://linux-hardware.org/?probe=cf1d697418) | Jan 12, 2024 |
| ASUSTek   | PRIME A520M-A II            | [c37a18c186](https://linux-hardware.org/?probe=c37a18c186) | Dec 25, 2023 |
| Unknown   | Unknown                     | [beca2cade6](https://linux-hardware.org/?probe=beca2cade6) | Nov 26, 2023 |
| MSI       | B650 GAMING PLUS WIFI       | [c25e140976](https://linux-hardware.org/?probe=c25e140976) | Nov 26, 2023 |
| Unknown   | Unknown                     | [f90c57452a](https://linux-hardware.org/?probe=f90c57452a) | Nov 21, 2023 |
| Apple     | Mac-F221BEC8                | [9cdba3ee40](https://linux-hardware.org/?probe=9cdba3ee40) | Nov 12, 2023 |
| ASUSTek   | Pro WS X570-ACE             | [6ba3f1daa1](https://linux-hardware.org/?probe=6ba3f1daa1) | Oct 30, 2023 |
| ASUSTek   | Pro WS X570-ACE             | [e2c02539ce](https://linux-hardware.org/?probe=e2c02539ce) | Oct 29, 2023 |
| Alienware | 0K9TKY A00                  | [a51d4611f8](https://linux-hardware.org/?probe=a51d4611f8) | Oct 23, 2023 |
| Dell      | 0GY6Y8 A03                  | [1ddd96bd4e](https://linux-hardware.org/?probe=1ddd96bd4e) | Oct 15, 2023 |
| Dell      | 0RW199                      | [6fc37ef3c1](https://linux-hardware.org/?probe=6fc37ef3c1) | Sep 24, 2023 |
| Acer      | Veriton X4618G              | [a34419120b](https://linux-hardware.org/?probe=a34419120b) | Sep 19, 2023 |
| ASUSTek   | ROG STRIX Z370-H GAMING     | [93356dbebb](https://linux-hardware.org/?probe=93356dbebb) | Sep 17, 2023 |
| Gigabyte  | B650 AORUS PRO AX           | [b771d7b475](https://linux-hardware.org/?probe=b771d7b475) | Sep 10, 2023 |
| Gigabyte  | B650 AORUS PRO AX           | [6002a35e23](https://linux-hardware.org/?probe=6002a35e23) | Sep 10, 2023 |
| Pegatron  | 2ACD                        | [4f61dd9a7a](https://linux-hardware.org/?probe=4f61dd9a7a) | Sep 10, 2023 |
| ASRock    | X570 Taichi                 | [6515c97b89](https://linux-hardware.org/?probe=6515c97b89) | Sep 05, 2023 |
| ASRock    | 970 Extreme4                | [4196acbe15](https://linux-hardware.org/?probe=4196acbe15) | Sep 05, 2023 |
| ASRock    | 970 Extreme4                | [4cec633c85](https://linux-hardware.org/?probe=4cec633c85) | Aug 20, 2023 |
| Intel     | DG41RQ AAE54511-203         | [646d098c58](https://linux-hardware.org/?probe=646d098c58) | Aug 10, 2023 |
| ASUSTek   | TUF B450M-PRO GAMING        | [b8f1735d23](https://linux-hardware.org/?probe=b8f1735d23) | Aug 04, 2023 |
| ASUSTek   | TUF B450M-PRO GAMING        | [6a6f453881](https://linux-hardware.org/?probe=6a6f453881) | Aug 02, 2023 |
| ASUSTek   | Z87-A                       | [603bee8812](https://linux-hardware.org/?probe=603bee8812) | Aug 01, 2023 |
| ASUSTek   | Z87-A                       | [64bc1caf41](https://linux-hardware.org/?probe=64bc1caf41) | Aug 01, 2023 |
| Google    | Sumo                        | [71a7167d22](https://linux-hardware.org/?probe=71a7167d22) | Jul 25, 2023 |
| MAXSUN    | MS-Terminator B660M VER:... | [5cf65783b2](https://linux-hardware.org/?probe=5cf65783b2) | Jul 25, 2023 |
| Gigabyte  | GA-970A-UD3                 | [fa192badba](https://linux-hardware.org/?probe=fa192badba) | Jul 12, 2023 |
| MSI       | X470 GAMING PLUS MAX        | [4d33bb92ce](https://linux-hardware.org/?probe=4d33bb92ce) | Jul 09, 2023 |
| MSI       | G41M-P33 Combo              | [07ab83bef1](https://linux-hardware.org/?probe=07ab83bef1) | Jun 30, 2023 |
| MSI       | G41M-P33 Combo              | [fcf9a0fd47](https://linux-hardware.org/?probe=fcf9a0fd47) | Jun 30, 2023 |
| ASUSTek   | PRIME H270-PLUS             | [017c7fd564](https://linux-hardware.org/?probe=017c7fd564) | Jun 11, 2023 |
| Dell      | 0GXM1W A02                  | [9c252c8688](https://linux-hardware.org/?probe=9c252c8688) | May 30, 2023 |
| ASUSTek   | K30BF_M32BF_A_F_K31BF_6     | [2c3689440a](https://linux-hardware.org/?probe=2c3689440a) | May 26, 2023 |
| Biostar   | NF520D3                     | [806beba322](https://linux-hardware.org/?probe=806beba322) | May 20, 2023 |
| Dell      | 0YXT71 A03                  | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| Apple     | Mac-F221BEC8                | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| Dell      | 0GY6Y8 A02                  | [f80f9b0671](https://linux-hardware.org/?probe=f80f9b0671) | Apr 28, 2023 |
| Gigabyte  | B550M DS3H AC               | [a8f4a6f058](https://linux-hardware.org/?probe=a8f4a6f058) | Apr 27, 2023 |
| Apple     | Mac-F221BEC8                | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| ASUSTek   | AM1M-A                      | [b4e51d0af3](https://linux-hardware.org/?probe=b4e51d0af3) | Apr 17, 2023 |
| ASUSTek   | AM1M-A                      | [a6ba0d9290](https://linux-hardware.org/?probe=a6ba0d9290) | Apr 17, 2023 |
| ASRock    | X670E Steel Legend          | [e197bd2a4b](https://linux-hardware.org/?probe=e197bd2a4b) | Jan 30, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| blendOS         | 36       | 92.31%  |
| blendOS Rolling | 3        | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| blendOS | 39       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Desktops | Percent |
|------------------|----------|---------|
| 6.3.9-zen1-1-zen | 20       | 50%     |
| 6.5.5-zen1-1-zen | 5        | 12.5%   |
| 6.2.12-arch1-1   | 3        | 7.5%    |
| 6.3.6-zen1-1-zen | 2        | 5%      |
| 6.3.4-arch1-1    | 2        | 5%      |
| 6.9.9-zen1-1-zen | 1        | 2.5%    |
| 6.4.5-arch1-1    | 1        | 2.5%    |
| 6.3.5-zen1-1-zen | 1        | 2.5%    |
| 6.3.2-arch1-1    | 1        | 2.5%    |
| 6.3.1-arch1-1    | 1        | 2.5%    |
| 6.2.8-arch1-1-t2 | 1        | 2.5%    |
| 6.2.13-arch1-1   | 1        | 2.5%    |
| 6.1.8-zen1-1-zen | 1        | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.9   | 20       | 50%     |
| 6.5.5   | 5        | 12.5%   |
| 6.2.12  | 3        | 7.5%    |
| 6.3.6   | 2        | 5%      |
| 6.3.4   | 2        | 5%      |
| 6.9.9   | 1        | 2.5%    |
| 6.4.5   | 1        | 2.5%    |
| 6.3.5   | 1        | 2.5%    |
| 6.3.2   | 1        | 2.5%    |
| 6.3.1   | 1        | 2.5%    |
| 6.2.8   | 1        | 2.5%    |
| 6.2.13  | 1        | 2.5%    |
| 6.1.8   | 1        | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3     | 27       | 69.23%  |
| 6.5     | 5        | 12.82%  |
| 6.2     | 4        | 10.26%  |
| 6.9     | 1        | 2.56%   |
| 6.4     | 1        | 2.56%   |
| 6.1     | 1        | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 39       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE5          | 20       | 50%     |
| GNOME         | 19       | 47.5%   |
| GNOME Classic | 1        | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 32       | 76.19%  |
| X11     | 8        | 19.05%  |
| Unknown | 2        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 92.31%  |
| GDM     | 2        | 5.13%   |
| SDDM    | 1        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 21       | 53.85%  |
| de_DE | 4        | 10.26%  |
| it_IT | 3        | 7.69%   |
| fr_FR | 3        | 7.69%   |
| sv_SE | 1        | 2.56%   |
| ro_RO | 1        | 2.56%   |
| pt_BR | 1        | 2.56%   |
| es_MX | 1        | 2.56%   |
| es_ES | 1        | 2.56%   |
| es_CL | 1        | 2.56%   |
| en_GB | 1        | 2.56%   |
| en_AU | 1        | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 36       | 92.31%  |
| EFI  | 3        | 7.69%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 31       | 79.49%  |
| Tmpfs | 5        | 12.82%  |
| Btrfs | 2        | 5.13%   |
| Xfs   | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 92.31%  |
| GPT     | 3        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 97.44%  |
| Yes       | 1        | 2.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 23.08%  |
| MSI                 | 5        | 12.82%  |
| Gigabyte Technology | 5        | 12.82%  |
| Dell                | 5        | 12.82%  |
| ASRock              | 3        | 7.69%   |
| Apple               | 2        | 5.13%   |
| Pegatron            | 1        | 2.56%   |
| MAXSUN              | 1        | 2.56%   |
| Lenovo              | 1        | 2.56%   |
| Intel               | 1        | 2.56%   |
| Google              | 1        | 2.56%   |
| Fujitsu             | 1        | 2.56%   |
| Biostar             | 1        | 2.56%   |
| Alienware           | 1        | 2.56%   |
| Acer                | 1        | 2.56%   |
| Unknown             | 1        | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell OptiPlex 7010                   | 4        | 10.26%  |
| ASUS All Series                      | 2        | 5.13%   |
| Apple MacPro5,1                      | 2        | 5.13%   |
| Pegatron p7-1154                     | 1        | 2.56%   |
| MSI MS-7E26                          | 1        | 2.56%   |
| MSI MS-7C52                          | 1        | 2.56%   |
| MSI MS-7B79                          | 1        | 2.56%   |
| MSI MS-7592                          | 1        | 2.56%   |
| MSI MAG B550 META 5 (MS-B930)        | 1        | 2.56%   |
| MAXSUN MS-Terminator B660M VER:H4.2G | 1        | 2.56%   |
| Lenovo Legion C530-19ICB 90JX0040GE  | 1        | 2.56%   |
| Intel DG41RQ AAE54511-203            | 1        | 2.56%   |
| Google Sumo                          | 1        | 2.56%   |
| Gigabyte X99P-SLI-CF                 | 1        | 2.56%   |
| Gigabyte GA-970A-UD3                 | 1        | 2.56%   |
| Gigabyte CUSTOM                      | 1        | 2.56%   |
| Gigabyte B550M DS3H AC               | 1        | 2.56%   |
| Gigabyte B550M AORUS PRO-P           | 1        | 2.56%   |
| Fujitsu ESPRIMO Q558                 | 1        | 2.56%   |
| Dell Precision WorkStation T7400     | 1        | 2.56%   |
| Biostar NF520D3                      | 1        | 2.56%   |
| ASUS TUF B450M-PRO GAMING            | 1        | 2.56%   |
| ASUS ROG STRIX Z370-H GAMING         | 1        | 2.56%   |
| ASUS ROG STRIX B450-E GAMING         | 1        | 2.56%   |
| ASUS Pro WS X570-ACE                 | 1        | 2.56%   |
| ASUS PRIME H270-PLUS                 | 1        | 2.56%   |
| ASUS PRIME A520M-A II                | 1        | 2.56%   |
| ASUS K30BF_M32BF_A_F_K31BF_6         | 1        | 2.56%   |
| ASRock X670E Steel Legend            | 1        | 2.56%   |
| ASRock X570 Taichi                   | 1        | 2.56%   |
| ASRock 970 Extreme4                  | 1        | 2.56%   |
| Alienware Aurora Ryzen Edition R14   | 1        | 2.56%   |
| Acer Veriton X4618G                  | 1        | 2.56%   |
| Unknown                              | 1        | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 4        | 10.26%  |
| Gigabyte B550M       | 2        | 5.13%   |
| ASUS ROG             | 2        | 5.13%   |
| ASUS PRIME           | 2        | 5.13%   |
| ASUS All             | 2        | 5.13%   |
| Apple MacPro5        | 2        | 5.13%   |
| Pegatron p7-1154     | 1        | 2.56%   |
| MSI MS-7E26          | 1        | 2.56%   |
| MSI MS-7C52          | 1        | 2.56%   |
| MSI MS-7B79          | 1        | 2.56%   |
| MSI MS-7592          | 1        | 2.56%   |
| MSI MAG              | 1        | 2.56%   |
| MAXSUN MS-Terminator | 1        | 2.56%   |
| Lenovo Legion        | 1        | 2.56%   |
| Intel DG41RQ         | 1        | 2.56%   |
| Google Sumo          | 1        | 2.56%   |
| Gigabyte X99P-SLI-CF | 1        | 2.56%   |
| Gigabyte GA-970A-UD3 | 1        | 2.56%   |
| Gigabyte CUSTOM      | 1        | 2.56%   |
| Fujitsu ESPRIMO      | 1        | 2.56%   |
| Dell Precision       | 1        | 2.56%   |
| Biostar NF520D3      | 1        | 2.56%   |
| ASUS TUF             | 1        | 2.56%   |
| ASUS Pro             | 1        | 2.56%   |
| ASUS K30BF           | 1        | 2.56%   |
| ASRock X670E         | 1        | 2.56%   |
| ASRock X570          | 1        | 2.56%   |
| ASRock 970           | 1        | 2.56%   |
| Alienware Aurora     | 1        | 2.56%   |
| Acer Veriton         | 1        | 2.56%   |
| Unknown              | 1        | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 6        | 15.38%  |
| 2011 | 5        | 12.82%  |
| 2023 | 4        | 10.26%  |
| 2022 | 4        | 10.26%  |
| 2021 | 4        | 10.26%  |
| 2013 | 4        | 10.26%  |
| 2015 | 2        | 5.13%   |
| 2010 | 2        | 5.13%   |
| 2009 | 2        | 5.13%   |
| 2018 | 1        | 2.56%   |
| 2017 | 1        | 2.56%   |
| 2016 | 1        | 2.56%   |
| 2014 | 1        | 2.56%   |
| 2012 | 1        | 2.56%   |
| 2008 | 1        | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 39       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 39       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 97.44%  |
| Yes  | 1        | 2.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 9        | 23.08%  |
| 8.01-16.0   | 9        | 23.08%  |
| 16.01-24.0  | 8        | 20.51%  |
| 4.01-8.0    | 5        | 12.82%  |
| 3.01-4.0    | 3        | 7.69%   |
| 64.01-256.0 | 3        | 7.69%   |
| 24.01-32.0  | 2        | 5.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 13       | 31.71%  |
| 4.01-8.0  | 12       | 29.27%  |
| 3.01-4.0  | 11       | 26.83%  |
| 1.01-2.0  | 4        | 9.76%   |
| 8.01-16.0 | 1        | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 35%     |
| 3      | 10       | 25%     |
| 2      | 9        | 22.5%   |
| 4      | 5        | 12.5%   |
| 6      | 1        | 2.5%    |
| 0      | 1        | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 71.79%  |
| Yes       | 11       | 28.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 64.1%   |
| No        | 14       | 35.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 53.85%  |
| No        | 18       | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 30.77%  |
| Germany     | 4        | 10.26%  |
| Italy       | 3        | 7.69%   |
| Mexico      | 2        | 5.13%   |
| India       | 2        | 5.13%   |
| France      | 2        | 5.13%   |
| Brazil      | 2        | 5.13%   |
| UK          | 1        | 2.56%   |
| Switzerland | 1        | 2.56%   |
| Sweden      | 1        | 2.56%   |
| Spain       | 1        | 2.56%   |
| Russia      | 1        | 2.56%   |
| Romania     | 1        | 2.56%   |
| Czechia     | 1        | 2.56%   |
| Cyprus      | 1        | 2.56%   |
| Chile       | 1        | 2.56%   |
| Belgium     | 1        | 2.56%   |
| Australia   | 1        | 2.56%   |
| Argentina   | 1        | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Rome                      | 2        | 5%      |
| Treillieres               | 1        | 2.5%    |
| Somerset                  | 1        | 2.5%    |
| Skövde                   | 1        | 2.5%    |
| Sete Lagoas               | 1        | 2.5%    |
| Seraing                   | 1        | 2.5%    |
| San Nicolás de los Garza | 1        | 2.5%    |
| Salvador Escalante        | 1        | 2.5%    |
| Saint Cloud               | 1        | 2.5%    |
| Prague                    | 1        | 2.5%    |
| Piatra Neamţ             | 1        | 2.5%    |
| Perth                     | 1        | 2.5%    |
| Persan                    | 1        | 2.5%    |
| Palma                     | 1        | 2.5%    |
| Odessa                    | 1        | 2.5%    |
| Nicosia                   | 1        | 2.5%    |
| Milpitas                  | 1        | 2.5%    |
| Milan                     | 1        | 2.5%    |
| Kuznetsk                  | 1        | 2.5%    |
| Karlsruhe                 | 1        | 2.5%    |
| Hyderabad                 | 1        | 2.5%    |
| Hancock                   | 1        | 2.5%    |
| Halle                     | 1        | 2.5%    |
| Guarulhos                 | 1        | 2.5%    |
| Flushing                  | 1        | 2.5%    |
| Empalme Lobos             | 1        | 2.5%    |
| Durham                    | 1        | 2.5%    |
| Delhi                     | 1        | 2.5%    |
| Chillan                   | 1        | 2.5%    |
| Cadenazzo                 | 1        | 2.5%    |
| Bielefeld                 | 1        | 2.5%    |
| Biedenkopf                | 1        | 2.5%    |
| Bellflower                | 1        | 2.5%    |
| Baltimore                 | 1        | 2.5%    |
| Asheville                 | 1        | 2.5%    |
| Arcanum                   | 1        | 2.5%    |
| Albuquerque               | 1        | 2.5%    |
| Albertville               | 1        | 2.5%    |
| Aberdeen                  | 1        | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 15       | 23     | 20.55%  |
| Seagate                   | 11       | 15     | 15.07%  |
| Samsung Electronics       | 8        | 9      | 10.96%  |
| Sandisk                   | 6        | 6      | 8.22%   |
| Phison Electronics        | 3        | 4      | 4.11%   |
| Kingston                  | 3        | 4      | 4.11%   |
| Hitachi                   | 3        | 4      | 4.11%   |
| China                     | 3        | 3      | 4.11%   |
| ADATA Technology          | 3        | 3      | 4.11%   |
| Unknown                   | 2        | 2      | 2.74%   |
| Toshiba                   | 2        | 3      | 2.74%   |
| Silicon Motion            | 2        | 3      | 2.74%   |
| Micron/Crucial Technology | 2        | 2      | 2.74%   |
| Crucial                   | 2        | 2      | 2.74%   |
| SPCC                      | 1        | 2      | 1.37%   |
| SK hynix                  | 1        | 1      | 1.37%   |
| MOVESPEED                 | 1        | 1      | 1.37%   |
| Micron Technology         | 1        | 1      | 1.37%   |
| LaCie                     | 1        | 1      | 1.37%   |
| HUAWEI                    | 1        | 1      | 1.37%   |
| Hikvision                 | 1        | 1      | 1.37%   |
| EVM                       | 1        | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3        | 3.66%   |
| WDC WD Blue SA510 2.5 500GB                                       | 2        | 2.44%   |
| Toshiba DT01ACA100 1TB                                            | 2        | 2.44%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 2        | 2.44%   |
| Seagate ST1000DM003-1SB102 1TB                                    | 2        | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 2        | 2.44%   |
| Phison PS5013 E13 NVMe Controller 512GB                           | 2        | 2.44%   |
| Phison E16 PCIe4 NVMe Controller 1TB                              | 2        | 2.44%   |
| China SSD 240GB                                                   | 2        | 2.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 1        | 1.22%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                    | 1        | 1.22%   |
| WDC WD7500AAVS-00D7B1 752GB                                       | 1        | 1.22%   |
| WDC WD6002FRYZ-01WD5B0 6TB                                        | 1        | 1.22%   |
| WDC WD5000AZRX-00L4HB0 500GB                                      | 1        | 1.22%   |
| WDC WD40EFRX-68WT0N0 4TB                                          | 1        | 1.22%   |
| WDC WD4005FZBX-00K5WB0 4TB                                        | 1        | 1.22%   |
| WDC WD3200AAKS-00V1A0 320GB                                       | 1        | 1.22%   |
| WDC WD3200AAJS-08L7A0 320GB                                       | 1        | 1.22%   |
| WDC WD3000HLFS-01G6U3 304GB                                       | 1        | 1.22%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 1        | 1.22%   |
| WDC WD20EZRX-00D8PB0 2TB                                          | 1        | 1.22%   |
| WDC WD10EZEX-22MFCA0 1TB                                          | 1        | 1.22%   |
| WDC WD10EZEX-21M2NA0 1TB                                          | 1        | 1.22%   |
| WDC WD10EZEX-00WN4A0 1TB                                          | 1        | 1.22%   |
| WDC WD10EARS-00Y5B1 1TB                                           | 1        | 1.22%   |
| WDC WD10EARS-00MVWB0 1TB                                          | 1        | 1.22%   |
| WDC WD10EADS-00M2B0 1TB                                           | 1        | 1.22%   |
| Unknown NVMe SSD Drive 1024GB                                     | 1        | 1.22%   |
| Unknown MMC Card  32GB                                            | 1        | 1.22%   |
| SPCC Solid State Disk 512GB                                       | 1        | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                       | 1        | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 1        | 1.22%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB                 | 1        | 1.22%   |
| Seagate ST500LT012-9WS142 500GB                                   | 1        | 1.22%   |
| Seagate ST4000NM0033-9ZM170 4TB                                   | 1        | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 1        | 1.22%   |
| Seagate ST3320413AS 320GB                                         | 1        | 1.22%   |
| Seagate ST3250318AS 250GB                                         | 1        | 1.22%   |
| Seagate ST320LT007-9ZV142 320GB                                   | 1        | 1.22%   |
| Seagate ST3120811AS 120GB                                         | 1        | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 13       | 17     | 44.83%  |
| Seagate | 11       | 15     | 37.93%  |
| Hitachi | 3        | 4      | 10.34%  |
| Toshiba | 2        | 3      | 6.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 22.73%  |
| WDC                 | 4        | 6      | 18.18%  |
| China               | 3        | 3      | 13.64%  |
| Kingston            | 2        | 3      | 9.09%   |
| Crucial             | 2        | 2      | 9.09%   |
| SPCC                | 1        | 2      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| MOVESPEED           | 1        | 1      | 4.55%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| Hikvision           | 1        | 1      | 4.55%   |
| EVM                 | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 23       | 39     | 36.51%  |
| SSD     | 20       | 27     | 31.75%  |
| NVMe    | 17       | 23     | 26.98%  |
| Unknown | 2        | 2      | 3.17%   |
| MMC     | 1        | 1      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 64     | 59.26%  |
| NVMe | 17       | 23     | 31.48%  |
| SAS  | 4        | 4      | 7.41%   |
| MMC  | 1        | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 32     | 43.48%  |
| 0.51-1.0   | 16       | 23     | 34.78%  |
| 3.01-4.0   | 5        | 5      | 10.87%  |
| 1.01-2.0   | 3        | 3      | 6.52%   |
| 10.01-20.0 | 1        | 1      | 2.17%   |
| 4.01-10.0  | 1        | 2      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 13       | 33.33%  |
| 101-250        | 8        | 20.51%  |
| 251-500        | 7        | 17.95%  |
| 1001-2000      | 6        | 15.38%  |
| More than 3000 | 3        | 7.69%   |
| 51-100         | 2        | 5.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 17       | 42.5%   |
| 1-20           | 10       | 25%     |
| 251-500        | 4        | 10%     |
| 501-1000       | 3        | 7.5%    |
| 51-100         | 3        | 7.5%    |
| More than 3000 | 1        | 2.5%    |
| 101-250        | 1        | 2.5%    |
| 1001-2000      | 1        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10EARS-00MVWB0 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 37       | 88     | 92.5%   |
| Works    | 2        | 3      | 5%      |
| Malfunc  | 1        | 1      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 18       | 31.58%  |
| Intel                       | 17       | 29.82%  |
| Sandisk                     | 5        | 8.77%   |
| Samsung Electronics         | 3        | 5.26%   |
| Phison Electronics          | 3        | 5.26%   |
| ADATA Technology            | 3        | 5.26%   |
| Silicon Motion              | 2        | 3.51%   |
| Micron/Crucial Technology   | 2        | 3.51%   |
| Solidigm                    | 1        | 1.75%   |
| SK hynix                    | 1        | 1.75%   |
| Nvidia                      | 1        | 1.75%   |
| Kingston Technology Company | 1        | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 10.45%  |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 7.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 5.97%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 5.97%   |
| AMD 600 Series Chipset SATA Controller                                         | 3        | 4.48%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 4.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.99%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 2.99%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 2.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 2.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 2.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 2.99%   |
| Solidigm P44 Pro NVMe SSD [Hollywood Beach]                                    | 1        | 1.49%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 1.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 1.49%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 1.49%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.49%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 1        | 1.49%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 1.49%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1        | 1.49%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                          | 1        | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.49%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.49%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 1.49%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 1.49%   |
| Kingston Company NV2 NVMe SSD [E19T] (DRAM-less)                               | 1        | 1.49%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.49%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.49%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 1.49%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 32       | 56.14%  |
| NVMe | 17       | 29.82%  |
| IDE  | 7        | 12.28%  |
| RAID | 1        | 1.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 20       | 51.28%  |
| Intel  | 19       | 48.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 10.26%  |
| AMD Ryzen 5 3600 6-Core Processor              | 3        | 7.69%   |
| AMD Ryzen 9 7950X 16-Core Processor            | 2        | 5.13%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 1        | 2.56%   |
| Intel Xeon CPU X5660 @ 2.80GHz                 | 1        | 2.56%   |
| Intel Xeon CPU X3220 @ 2.40GHz                 | 1        | 2.56%   |
| Intel Xeon CPU E5430 @ 2.66GHz                 | 1        | 2.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 2.56%   |
| Intel Core i7-6950X CPU @ 3.00GHz              | 1        | 2.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 2.56%   |
| Intel Core i5-9400T CPU @ 1.80GHz              | 1        | 2.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 2.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 2.56%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz          | 1        | 2.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1        | 2.56%   |
| Intel Celeron CPU N2930 @ 1.83GHz              | 1        | 2.56%   |
| Intel 12th Gen Core i5-12400F                  | 1        | 2.56%   |
| AMD Sempron 2650 APU with Radeon R3            | 1        | 2.56%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 7 5800X3D 8-Core Processor           | 1        | 2.56%   |
| AMD Ryzen 7 5800 8-Core Processor              | 1        | 2.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2.56%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 2.56%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 1        | 2.56%   |
| AMD Ryzen 5 3600X 6-Core Processor             | 1        | 2.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 2.56%   |
| AMD Phenom II X4 975 Processor                 | 1        | 2.56%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 2.56%   |
| AMD Athlon II X2 260 Processor                 | 1        | 2.56%   |
| AMD A6-3600 APU with Radeon HD Graphics        | 1        | 2.56%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 7        | 17.95%  |
| AMD Ryzen 5       | 6        | 15.38%  |
| AMD Ryzen 7       | 5        | 12.82%  |
| Intel Xeon        | 4        | 10.26%  |
| Intel Core i7     | 4        | 10.26%  |
| Intel Celeron     | 2        | 5.13%   |
| AMD Ryzen 9       | 2        | 5.13%   |
| Other             | 1        | 2.56%   |
| Intel Core 2 Quad | 1        | 2.56%   |
| AMD Sempron       | 1        | 2.56%   |
| AMD Ryzen 3       | 1        | 2.56%   |
| AMD Phenom II X4  | 1        | 2.56%   |
| AMD FX            | 1        | 2.56%   |
| AMD Athlon II X2  | 1        | 2.56%   |
| AMD A6            | 1        | 2.56%   |
| AMD A10           | 1        | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 14       | 35.9%   |
| 6      | 10       | 25.64%  |
| 8      | 6        | 15.38%  |
| 2      | 4        | 10.26%  |
| 16     | 2        | 5.13%   |
| 12     | 2        | 5.13%   |
| 10     | 1        | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 92.31%  |
| 2      | 3        | 7.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 53.85%  |
| 1      | 18       | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 39       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 97.44%  |
| 0x06003106 | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 3         | 5        | 12.82%  |
| Zen 2         | 4        | 10.26%  |
| KabyLake      | 4        | 10.26%  |
| IvyBridge     | 4        | 10.26%  |
| Unknown       | 4        | 10.26%  |
| Westmere      | 2        | 5.13%   |
| Penryn        | 2        | 5.13%   |
| K10           | 2        | 5.13%   |
| Zen+          | 1        | 2.56%   |
| Zen           | 1        | 2.56%   |
| Steamroller   | 1        | 2.56%   |
| Silvermont    | 1        | 2.56%   |
| SandyBridge   | 1        | 2.56%   |
| Piledriver    | 1        | 2.56%   |
| K10 Llano     | 1        | 2.56%   |
| Jaguar        | 1        | 2.56%   |
| Haswell       | 1        | 2.56%   |
| Goldmont plus | 1        | 2.56%   |
| Core          | 1        | 2.56%   |
| Broadwell     | 1        | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 19       | 47.5%   |
| Nvidia | 13       | 32.5%   |
| Intel  | 8        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 3        | 6.82%   |
| AMD Raphael                                                               | 3        | 6.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 6.82%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 3        | 6.82%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 2        | 4.55%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                   | 2        | 4.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 4.55%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                        | 1        | 2.27%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 2.27%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                     | 1        | 2.27%   |
| Nvidia TU104 [GeForce RTX 2060]                                           | 1        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 2.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 2.27%   |
| Nvidia GA104 [GeForce RTX 3060]                                           | 1        | 2.27%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                        | 1        | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1        | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1        | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.27%   |
| AMD Turks PRO [Radeon HD 7570]                                            | 1        | 2.27%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                         | 1        | 2.27%   |
| AMD RV710 [Radeon HD 4350/4550]                                           | 1        | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 2.27%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                 | 1        | 2.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 1        | 2.27%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1        | 2.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 1        | 2.27%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1        | 2.27%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 1        | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 14       | 35.9%   |
| 1 x Nvidia   | 12       | 30.77%  |
| 1 x Intel    | 8        | 20.51%  |
| 2 x AMD      | 4        | 10.26%  |
| AMD + Nvidia | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 69.23%  |
| Proprietary | 12       | 30.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 82.5%   |
| 8.01-16.0  | 3        | 7.5%    |
| 7.01-8.0   | 1        | 2.5%    |
| 5.01-6.0   | 1        | 2.5%    |
| 1.01-2.0   | 1        | 2.5%    |
| 0.51-1.0   | 1        | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 22.92%  |
| Dell                 | 6        | 12.5%   |
| Acer                 | 4        | 8.33%   |
| Vizio                | 3        | 6.25%   |
| Goldstar             | 3        | 6.25%   |
| Lenovo               | 2        | 4.17%   |
| Iiyama               | 2        | 4.17%   |
| Fujitsu Siemens      | 2        | 4.17%   |
| AOC                  | 2        | 4.17%   |
| Ancor Communications | 2        | 4.17%   |
| Sony                 | 1        | 2.08%   |
| Sceptre Tech         | 1        | 2.08%   |
| PRI                  | 1        | 2.08%   |
| Pixio                | 1        | 2.08%   |
| Philips              | 1        | 2.08%   |
| Onkyo                | 1        | 2.08%   |
| MStar                | 1        | 2.08%   |
| HUAWEI               | 1        | 2.08%   |
| CEN                  | 1        | 2.08%   |
| BenQ                 | 1        | 2.08%   |
| AOpen                | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                     | 2        | 4.08%   |
| Vizio V505-G9 VIZ1033 3840x2160 1096x616mm 49.5-inch                    | 1        | 2.04%   |
| Sony TV SNYF500 1360x768                                                | 1        | 2.04%   |
| Sceptre Tech Sceptre K27 SPT0AA4 1920x1080 597x336mm 27.0-inch          | 1        | 2.04%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch       | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1        | 2.04%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 2.04%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 1872x1053mm 84.6-inch | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0F09 3840x2160 1872x1053mm 84.6-inch | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1210x680mm 54.6-inch  | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 480x270mm 21.7-inch   | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch   | 1        | 2.04%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 2.04%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 1        | 2.04%   |
| PRI BBY LCD TV PRI0032 1360x768 700x390mm 31.5-inch                     | 1        | 2.04%   |
| Pixio HDMI WAM2700 2560x1440 597x336mm 27.0-inch                        | 1        | 2.04%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 2.04%   |
| Onkyo TX-NR636 ONK0E61 1920x1080 800x450mm 36.1-inch                    | 1        | 2.04%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 1        | 2.04%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch                | 1        | 2.04%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch              | 1        | 2.04%   |
| Iiyama PL2480H IVM610B 1920x1080 521x293mm 23.5-inch                    | 1        | 2.04%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                   | 1        | 2.04%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                     | 1        | 2.04%   |
| Goldstar TV GSMC468 1920x1080 700x390mm 31.5-inch                       | 1        | 2.04%   |
| Goldstar L1753T GSM4433 1280x1024 338x270mm 17.0-inch                   | 1        | 2.04%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 1        | 2.04%   |
| Fujitsu Siemens B22W-5 FUS06AF 1680x1050 473x296mm 22.0-inch            | 1        | 2.04%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch        | 1        | 2.04%   |
| Dell U3421WE DELA18B 1920x1080 400x335mm 20.5-inch                      | 1        | 2.04%   |
| Dell U3419W DELA12E 3440x1440 800x335mm 34.1-inch                       | 1        | 2.04%   |
| Dell SE198WFP DELF004 1440x900 408x255mm 18.9-inch                      | 1        | 2.04%   |
| Dell E1913S DELD050 1280x1024 376x301mm 19.0-inch                       | 1        | 2.04%   |
| Dell E178FP DELA027 1280x1024 338x270mm 17.0-inch                       | 1        | 2.04%   |
| Dell AW3420DW DELA149 3440x1440 798x335mm 34.1-inch                     | 1        | 2.04%   |
| Dell AW2523HF DEL42B9 1920x1080 543x302mm 24.5-inch                     | 1        | 2.04%   |
| CEN EVGA XR1 Pro CEN9320 1920x1080 521x293mm 23.5-inch                  | 1        | 2.04%   |
| BenQ GL2250 BNQ789B 1920x1080 477x268mm 21.5-inch                       | 1        | 2.04%   |
| AOpen RTD2136R-FHD AOP2136 1920x1080 473x296mm 22.0-inch                | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 50%     |
| 3840x2160 (4K)     | 8        | 19.05%  |
| 1680x1050 (WSXGA+) | 3        | 7.14%   |
| 1280x1024 (SXGA)   | 3        | 7.14%   |
| 3440x1440          | 2        | 4.76%   |
| 1360x768           | 2        | 4.76%   |
| 2560x1080          | 1        | 2.38%   |
| 1720x1440          | 1        | 2.38%   |
| 1440x900 (WXGA+)   | 1        | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 14.58%  |
| 24     | 6        | 12.5%   |
| 31     | 4        | 8.33%   |
| 22     | 4        | 8.33%   |
| 21     | 4        | 8.33%   |
| 84     | 3        | 6.25%   |
| 34     | 3        | 6.25%   |
| 23     | 3        | 6.25%   |
| 54     | 2        | 4.17%   |
| 49     | 2        | 4.17%   |
| 19     | 2        | 4.17%   |
| 17     | 2        | 4.17%   |
| 72     | 1        | 2.08%   |
| 69     | 1        | 2.08%   |
| 52     | 1        | 2.08%   |
| 48     | 1        | 2.08%   |
| 40     | 1        | 2.08%   |
| 20     | 1        | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 31.91%  |
| 401-500     | 8        | 17.02%  |
| 1001-1500   | 6        | 12.77%  |
| 601-700     | 5        | 10.64%  |
| 1501-2000   | 5        | 10.64%  |
| 701-800     | 3        | 6.38%   |
| 351-400     | 2        | 4.26%   |
| 301-350     | 2        | 4.26%   |
| 801-900     | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 28       | 70%     |
| 16/10 | 5        | 12.5%   |
| 5/4   | 3        | 7.5%    |
| 21/9  | 3        | 7.5%    |
| 6/5   | 1        | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 27.27%  |
| More than 1000 | 11       | 25%     |
| 351-500        | 7        | 15.91%  |
| 301-350        | 7        | 15.91%  |
| 151-200        | 3        | 6.82%   |
| 141-150        | 2        | 4.55%   |
| 251-300        | 1        | 2.27%   |
| 501-1000       | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 60.47%  |
| 101-120 | 9        | 20.93%  |
| 1-50    | 7        | 16.28%  |
| 121-160 | 1        | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 71.79%  |
| 2     | 7        | 17.95%  |
| 3     | 3        | 7.69%   |
| 0     | 1        | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 27       | 44.26%  |
| Intel                           | 21       | 34.43%  |
| MediaTek                        | 3        | 4.92%   |
| Broadcom                        | 3        | 4.92%   |
| TP-Link                         | 2        | 3.28%   |
| VIA Technologies                | 1        | 1.64%   |
| Ralink                          | 1        | 1.64%   |
| Qualcomm Atheros Communications | 1        | 1.64%   |
| Huawei Technologies             | 1        | 1.64%   |
| ASUSTek Computer                | 1        | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller               | 19       | 27.14%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 6        | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 5        | 7.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 3        | 4.29%   |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 4.29%   |
| Intel I211 Gigabit Network Connection                                                | 3        | 4.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 2        | 2.86%   |
| Intel Ethernet Controller I225-V                                                     | 2        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2        | 2.86%   |
| Intel 82574L Gigabit Network Connection                                              | 2        | 2.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                               | 2        | 2.86%   |
| VIA VT86C100A [Rhine]                                                                | 1        | 1.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 1.43%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 1        | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.43%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 1        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1        | 1.43%   |
| Intel Wireless 7260                                                                  | 1        | 1.43%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 1        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                                                 | 1        | 1.43%   |
| Intel Ethernet Connection (2) I218-V                                                 | 1        | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1        | 1.43%   |
| Huawei E353/E3131                                                                    | 1        | 1.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                              | 1        | 1.43%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                     | 1        | 1.43%   |
| ASUS 802.11ac NIC                                                                    | 1        | 1.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 42.31%  |
| Realtek Semiconductor           | 5        | 19.23%  |
| MediaTek                        | 3        | 11.54%  |
| TP-Link                         | 2        | 7.69%   |
| Broadcom                        | 2        | 7.69%   |
| Ralink                          | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| ASUSTek Computer                | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 3        | 11.54%  |
| Intel Wi-Fi 6 AX200                                                                  | 3        | 11.54%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 2        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2        | 7.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                               | 2        | 7.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 3.85%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 3.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 3.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 3.85%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 3.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 1        | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1        | 3.85%   |
| Intel Wireless 7260                                                                  | 1        | 3.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1        | 3.85%   |
| ASUS 802.11ac NIC                                                                    | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 25       | 59.52%  |
| Intel                 | 14       | 33.33%  |
| VIA Technologies      | 1        | 2.38%   |
| Huawei Technologies   | 1        | 2.38%   |
| Broadcom              | 1        | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19       | 43.18%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 13.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 11.36%  |
| Intel I211 Gigabit Network Connection                                  | 3        | 6.82%   |
| Intel Ethernet Controller I225-V                                       | 2        | 4.55%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 4.55%   |
| VIA VT86C100A [Rhine]                                                  | 1        | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 2.27%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.27%   |
| Huawei E353/E3131                                                      | 1        | 2.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 2.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 60.94%  |
| WiFi     | 25       | 39.06%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 70.73%  |
| WiFi     | 12       | 29.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 48.72%  |
| 2     | 15       | 38.46%  |
| 3     | 4        | 10.26%  |
| 4     | 1        | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 53.85%  |
| Yes  | 18       | 46.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 50%     |
| Cambridge Silicon Radio | 2        | 9.09%   |
| Apple                   | 2        | 9.09%   |
| TP-Link                 | 1        | 4.55%   |
| SINO WEALTH             | 1        | 4.55%   |
| Realtek Semiconductor   | 1        | 4.55%   |
| MediaTek                | 1        | 4.55%   |
| IMC Networks            | 1        | 4.55%   |
| Foxconn / Hon Hai       | 1        | 4.55%   |
| Actions                 | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 3        | 13.64%  |
| Intel AX200 Bluetooth                               | 3        | 13.64%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 9.09%   |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 9.09%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2        | 9.09%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1        | 4.55%   |
| SINO WEALTH Bluetooth Keyboard                      | 1        | 4.55%   |
| Realtek Bluetooth Radio                             | 1        | 4.55%   |
| MediaTek Wireless_Device                            | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.55%   |
| IMC Networks Bluetooth Radio                        | 1        | 4.55%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1        | 4.55%   |
| Actions general adapter                             | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| AMD                    | 25       | 36.23%  |
| Intel                  | 18       | 26.09%  |
| Nvidia                 | 14       | 20.29%  |
| C-Media Electronics    | 3        | 4.35%   |
| Logitech               | 2        | 2.9%    |
| Texas Instruments      | 1        | 1.45%   |
| SteelSeries ApS        | 1        | 1.45%   |
| Razer USA              | 1        | 1.45%   |
| Medeli Electronics     | 1        | 1.45%   |
| M-Audio                | 1        | 1.45%   |
| Blue Microphones       | 1        | 1.45%   |
| AKAI Professional M.I. | 1        | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 8.05%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 6        | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 4.6%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 3.45%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 3.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 3.45%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 3        | 3.45%   |
| AMD FCH Azalia Controller                                                  | 3        | 3.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.3%    |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.3%    |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.3%    |
| Texas Instruments PCM2902C Audio CODEC                                     | 1        | 1.15%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1        | 1.15%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.15%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.15%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.15%   |
| Nvidia AD104 High Definition Audio Controller                              | 1        | 1.15%   |
| Medeli Electronics SHEM-BOY                                                | 1        | 1.15%   |
| M-Audio Trigger Finger Pro                                                 | 1        | 1.15%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1        | 1.15%   |
| Logitech G635 Gaming Headset                                               | 1        | 1.15%   |
| Intel USB2.0 Device                                                        | 1        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 1.15%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 1        | 50%     |
| SK hynix | 1        | 50%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 50%     |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s | 1        | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 2        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| SODIMM | 1        | 50%     |
| DIMM   | 1        | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 1        | 50%     |
| 2048 | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 2        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Kyocera         | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Kyocera FS-C5150DN   | 1        | 50%     |
| HP Deskjet 2050 J510 | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 22.22%  |
| Logitech            | 2        | 22.22%  |
| YGTek               | 1        | 11.11%  |
| Suyin               | 1        | 11.11%  |
| Microdia            | 1        | 11.11%  |
| IMC Networks        | 1        | 11.11%  |
| Cubeternet          | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)                             | 2        | 22.22%  |
| Logitech HD Pro Webcam C920                                         | 2        | 22.22%  |
| YGTek Webcam                                                        | 1        | 11.11%  |
| Suyin Integrated_Webcam_HD                                          | 1        | 11.11%  |
| Microdia MSI Starcam Racer                                          | 1        | 11.11%  |
| IMC Networks HD Camera                                              | 1        | 11.11%  |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 34       | 87.18%  |
| 1     | 5        | 12.82%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 33.33%  |
| Net/wireless     | 2        | 33.33%  |
| Graphics card    | 2        | 33.33%  |

