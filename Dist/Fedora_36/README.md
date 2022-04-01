Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 57

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7879818528](https://linux-hardware.org/?probe=7879818528) | Mar 30, 2022 |
| HP            | EliteBook x360 830 G5       | Convertible | [d384ca307e](https://linux-hardware.org/?probe=d384ca307e) | Mar 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [fd1c735c98](https://linux-hardware.org/?probe=fd1c735c98) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [927252e84e](https://linux-hardware.org/?probe=927252e84e) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [be2a3fd33b](https://linux-hardware.org/?probe=be2a3fd33b) | Mar 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [efdb29ff92](https://linux-hardware.org/?probe=efdb29ff92) | Mar 07, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0efde9a187](https://linux-hardware.org/?probe=0efde9a187) | Mar 03, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [841ab4ffe2](https://linux-hardware.org/?probe=841ab4ffe2) | Mar 01, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [809200ad60](https://linux-hardware.org/?probe=809200ad60) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [f09a7c7125](https://linux-hardware.org/?probe=f09a7c7125) | Dec 06, 2021 |
| Lenovo        | ThinkPad 10 20C10027SP      | Tablet      | [1c4e6ab62b](https://linux-hardware.org/?probe=1c4e6ab62b) | Nov 29, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a072a33607](https://linux-hardware.org/?probe=a072a33607) | Oct 12, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [95229554a9](https://linux-hardware.org/?probe=95229554a9) | Sep 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [d235dcf0d1](https://linux-hardware.org/?probe=d235dcf0d1) | Sep 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ad5f2b8ea5](https://linux-hardware.org/?probe=ad5f2b8ea5) | Sep 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f191342fa8](https://linux-hardware.org/?probe=f191342fa8) | Sep 02, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [270961aa02](https://linux-hardware.org/?probe=270961aa02) | Aug 30, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [1257d6c6f4](https://linux-hardware.org/?probe=1257d6c6f4) | Aug 27, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [373f7e6861](https://linux-hardware.org/?probe=373f7e6861) | Aug 22, 2021 |
| HP            | 304Ah                       | Desktop     | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                       | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 8         | 22.22%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 6         | 16.67%  |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 4         | 11.11%  |
| 5.17.0-300.fc36.x86_64                                        | 3         | 8.33%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 2         | 5.56%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2         | 5.56%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1         | 2.78%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 2.78%   |
| 5.16.0-0.rc2.20211126gita4849f6000e2.21.fc36.x86_64           | 1         | 2.78%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 2.78%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1         | 2.78%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1         | 2.78%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 2.78%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 2.78%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1         | 2.78%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 2.78%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.0  | 14        | 40%     |
| 5.17.1  | 8         | 22.86%  |
| 5.15.0  | 7         | 20%     |
| 5.16.0  | 2         | 5.71%   |
| 5.14.0  | 2         | 5.71%   |
| 5.14.14 | 1         | 2.86%   |
| 5.14.10 | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 22        | 62.86%  |
| 5.15    | 7         | 20%     |
| 5.14    | 4         | 11.43%  |
| 5.16    | 2         | 5.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 27        | 79.41%  |
| KDE5    | 4         | 11.76%  |
| Unknown | 3         | 8.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 25        | 75.76%  |
| X11     | 6         | 18.18%  |
| Tty     | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 14        | 42.42%  |
| Unknown | 14        | 42.42%  |
| SDDM    | 4         | 12.12%  |
| LightDM | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 15        | 45.45%  |
| en_GB | 4         | 12.12%  |
| de_DE | 3         | 9.09%   |
| ru_RU | 2         | 6.06%   |
| pt_BR | 2         | 6.06%   |
| pl_PL | 2         | 6.06%   |
| pt_PT | 1         | 3.03%   |
| hr_HR | 1         | 3.03%   |
| fr_FR | 1         | 3.03%   |
| es_ES | 1         | 3.03%   |
| es_AR | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 26        | 78.79%  |
| BIOS | 7         | 21.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 24        | 72.73%  |
| Ext4  | 8         | 24.24%  |
| Xfs   | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 17        | 50%     |
| Unknown | 14        | 41.18%  |
| MBR     | 3         | 8.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 90.91%  |
| Yes       | 3         | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 60.61%  |
| Yes       | 13        | 39.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 8         | 24.24%  |
| Hewlett-Packard        | 4         | 12.12%  |
| Gigabyte Technology    | 4         | 12.12%  |
| MSI                    | 3         | 9.09%   |
| Dell                   | 3         | 9.09%   |
| ASUSTek Computer       | 2         | 6.06%   |
| VALE                   | 1         | 3.03%   |
| Sony                   | 1         | 3.03%   |
| Positivo               | 1         | 3.03%   |
| Notebook               | 1         | 3.03%   |
| Framework              | 1         | 3.03%   |
| Biostar                | 1         | 3.03%   |
| Avell High Performance | 1         | 3.03%   |
| Apple                  | 1         | 3.03%   |
| Unknown                | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| VALE Notebook Slim S132                     | 1         | 3.03%   |
| Sony VGN-FW21E                              | 1         | 3.03%   |
| Positivo CHT12CP                            | 1         | 3.03%   |
| Notebook PCx0Dx                             | 1         | 3.03%   |
| MSI MS-7D06                                 | 1         | 3.03%   |
| MSI MS-7C95                                 | 1         | 3.03%   |
| MSI MS-7721                                 | 1         | 3.03%   |
| Lenovo ThinkPad X260 20F5S0HK1J             | 1         | 3.03%   |
| Lenovo ThinkPad P15 Gen 1 20STS0J500        | 1         | 3.03%   |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00        | 1         | 3.03%   |
| Lenovo ThinkPad 10 20C10027SP               | 1         | 3.03%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 1         | 3.03%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 3.03%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 3.03%   |
| Lenovo IdeaPad 530S-14ARR 81H1              | 1         | 3.03%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 3.03%   |
| HP ProBook 4740s                            | 1         | 3.03%   |
| HP EliteBook x360 830 G5                    | 1         | 3.03%   |
| HP Compaq 8100 Elite SFF PC                 | 1         | 3.03%   |
| Gigabyte H370M-DS3H                         | 1         | 3.03%   |
| Gigabyte EP45-DS3L                          | 1         | 3.03%   |
| Gigabyte B85M-D3V-A                         | 1         | 3.03%   |
| Gigabyte B550 AORUS ELITE                   | 1         | 3.03%   |
| Framework Laptop                            | 1         | 3.03%   |
| Dell XPS 17 9710                            | 1         | 3.03%   |
| Dell XPS 13 9310 2-in-1                     | 1         | 3.03%   |
| Dell OptiPlex 9020                          | 1         | 3.03%   |
| Biostar H55 HD                              | 1         | 3.03%   |
| Avell High Performance B.ON                 | 1         | 3.03%   |
| ASUS TUF GAMING B550M-PLUS                  | 1         | 3.03%   |
| ASUS ROG Zephyrus Duo 15 SE GX551QS_GX551QS | 1         | 3.03%   |
| Apple iMac18,2                              | 1         | 3.03%   |
| Unknown                                     | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 4         | 12.12%  |
| Lenovo ThinkBook            | 2         | 6.06%   |
| Dell XPS                    | 2         | 6.06%   |
| VALE Notebook               | 1         | 3.03%   |
| Sony VGN-FW21E              | 1         | 3.03%   |
| Positivo CHT12CP            | 1         | 3.03%   |
| Notebook PCx0Dx             | 1         | 3.03%   |
| MSI MS-7D06                 | 1         | 3.03%   |
| MSI MS-7C95                 | 1         | 3.03%   |
| MSI MS-7721                 | 1         | 3.03%   |
| Lenovo IdeaPadFlex          | 1         | 3.03%   |
| Lenovo IdeaPad              | 1         | 3.03%   |
| HP ZBook                    | 1         | 3.03%   |
| HP ProBook                  | 1         | 3.03%   |
| HP EliteBook                | 1         | 3.03%   |
| HP Compaq                   | 1         | 3.03%   |
| Gigabyte H370M-DS3H         | 1         | 3.03%   |
| Gigabyte EP45-DS3L          | 1         | 3.03%   |
| Gigabyte B85M-D3V-A         | 1         | 3.03%   |
| Gigabyte B550               | 1         | 3.03%   |
| Framework Laptop            | 1         | 3.03%   |
| Dell OptiPlex               | 1         | 3.03%   |
| Biostar H55                 | 1         | 3.03%   |
| Avell High Performance B.ON | 1         | 3.03%   |
| ASUS TUF                    | 1         | 3.03%   |
| ASUS ROG                    | 1         | 3.03%   |
| Apple iMac18                | 1         | 3.03%   |
| Unknown                     | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 27.27%  |
| 2020 | 8         | 24.24%  |
| 2018 | 3         | 9.09%   |
| 2017 | 2         | 6.06%   |
| 2015 | 2         | 6.06%   |
| 2013 | 2         | 6.06%   |
| 2008 | 2         | 6.06%   |
| 2016 | 1         | 3.03%   |
| 2014 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |
| 2010 | 1         | 3.03%   |
| 2009 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 18        | 54.55%  |
| Desktop     | 11        | 33.33%  |
| Convertible | 2         | 6.06%   |
| Tablet      | 1         | 3.03%   |
| All in one  | 1         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 27        | 81.82%  |
| Enabled  | 6         | 18.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 9         | 27.27%  |
| 4.01-8.0    | 6         | 18.18%  |
| 32.01-64.0  | 6         | 18.18%  |
| 16.01-24.0  | 6         | 18.18%  |
| 8.01-16.0   | 4         | 12.12%  |
| 64.01-256.0 | 2         | 6.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 13        | 38.24%  |
| 2.01-3.0  | 11        | 32.35%  |
| 4.01-8.0  | 5         | 14.71%  |
| 1.01-2.0  | 3         | 8.82%   |
| 8.01-16.0 | 1         | 2.94%   |
| 0.51-1.0  | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 64.71%  |
| 2      | 8         | 23.53%  |
| 3      | 3         | 8.82%   |
| 4      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 81.82%  |
| Yes       | 6         | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 72.73%  |
| No        | 9         | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 81.82%  |
| No        | 6         | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 63.64%  |
| No        | 12        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| UK          | 5         | 15.15%  |
| USA         | 3         | 9.09%   |
| Poland      | 3         | 9.09%   |
| Brazil      | 3         | 9.09%   |
| Netherlands | 2         | 6.06%   |
| Germany     | 2         | 6.06%   |
| Belarus     | 2         | 6.06%   |
| Uzbekistan  | 1         | 3.03%   |
| Turkey      | 1         | 3.03%   |
| Switzerland | 1         | 3.03%   |
| Spain       | 1         | 3.03%   |
| Romania     | 1         | 3.03%   |
| Norway      | 1         | 3.03%   |
| Latvia      | 1         | 3.03%   |
| Indonesia   | 1         | 3.03%   |
| France      | 1         | 3.03%   |
| Croatia     | 1         | 3.03%   |
| Bangladesh  | 1         | 3.03%   |
| Austria     | 1         | 3.03%   |
| Argentina   | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Minsk                     | 2         | 6.06%   |
| Halstead                  | 2         | 6.06%   |
| Zurich                    | 1         | 3.03%   |
| Zagreb                    | 1         | 3.03%   |
| Warsaw                    | 1         | 3.03%   |
| Warrington                | 1         | 3.03%   |
| Vegarshei                 | 1         | 3.03%   |
| Trzciel                   | 1         | 3.03%   |
| TorrejÃ³n de Ardoz      | 1         | 3.03%   |
| Tashkent                  | 1         | 3.03%   |
| Solihull                  | 1         | 3.03%   |
| Sao Paulo                 | 1         | 3.03%   |
| Riga                      | 1         | 3.03%   |
| Paris                     | 1         | 3.03%   |
| Newport                   | 1         | 3.03%   |
| Milicz                    | 1         | 3.03%   |
| Kasten bei Boeheimkirchen | 1         | 3.03%   |
| Joinville                 | 1         | 3.03%   |
| Jakarta                   | 1         | 3.03%   |
| Istanbul                  | 1         | 3.03%   |
| Houston                   | 1         | 3.03%   |
| Hoofddorp                 | 1         | 3.03%   |
| Goiânia                  | 1         | 3.03%   |
| Fort Collins              | 1         | 3.03%   |
| Dhaka                     | 1         | 3.03%   |
| Delft                     | 1         | 3.03%   |
| Buenos Aires              | 1         | 3.03%   |
| Bucharest                 | 1         | 3.03%   |
| Bonn                      | 1         | 3.03%   |
| Berlin                    | 1         | 3.03%   |
| Beaverton                 | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 26.67%  |
| WDC                 | 6         | 8      | 13.33%  |
| Kingston            | 5         | 7      | 11.11%  |
| Unknown             | 3         | 5      | 6.67%   |
| Toshiba             | 3         | 3      | 6.67%   |
| Seagate             | 2         | 2      | 4.44%   |
| KIOXIA              | 2         | 2      | 4.44%   |
| XPG                 | 1         | 1      | 2.22%   |
| Transcend           | 1         | 1      | 2.22%   |
| SK Hynix            | 1         | 1      | 2.22%   |
| SanDisk             | 1         | 1      | 2.22%   |
| PNY                 | 1         | 2      | 2.22%   |
| Phison              | 1         | 1      | 2.22%   |
| Leven               | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB         | 3         | 6.25%   |
| Unknown MMC Card  64GB               | 2         | 4.17%   |
| Samsung SSD 860 EVO 250GB            | 2         | 4.17%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 4.17%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 4.17%   |
| XPG GAMMIX S11 Pro 256GB             | 1         | 2.08%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 2.08%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 2.08%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 2.08%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 2.08%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 2.08%   |
| WDC WD20EARS-00MVWB0 2TB             | 1         | 2.08%   |
| WDC WD10EZEX-00ZF5A0 1TB             | 1         | 2.08%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 2.08%   |
| Unknown MMC64G  64GB                 | 1         | 2.08%   |
| Transcend TS240GMTS420S 240GB SSD    | 1         | 2.08%   |
| Toshiba THNSNJ128GCSU 128GB SSD      | 1         | 2.08%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 2.08%   |
| Toshiba HDWD120 2TB                  | 1         | 2.08%   |
| SK Hynix HFM256GDHTNG-8310A 256GB    | 1         | 2.08%   |
| Seagate ST3500413AS 500GB            | 1         | 2.08%   |
| Seagate Expansion 320GB              | 1         | 2.08%   |
| SanDisk DF4032  32GB                 | 1         | 2.08%   |
| Samsung SSD 970 EVO 250GB            | 1         | 2.08%   |
| Samsung SSD 870 QVO 2TB              | 1         | 2.08%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 2.08%   |
| Samsung NVMe SSD Drive 2TB           | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 2.08%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 2.08%   |
| PNY CS3040 4TB SSD                   | 1         | 2.08%   |
| Phison NVMe SSD Drive 512GB          | 1         | 2.08%   |
| Leven JAJS600M256C 256GB             | 1         | 2.08%   |
| KIOXIA NVMe SSD Drive 256GB          | 1         | 2.08%   |
| KIOXIA KXG60ZNV1T02 1TB              | 1         | 2.08%   |
| Kingston SUV500MS240G 240GB SSD      | 1         | 2.08%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 2.08%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.08%   |
| Hitachi HTS543232A7A384 320GB        | 1         | 2.08%   |
| Fujitsu MJA2500BH G1 500GB           | 1         | 2.08%   |
| Apple HDD HTS541010A9E632 1TB        | 1         | 2.08%   |
| A-DATA IM2P33F8ABR1-256GB            | 1         | 2.08%   |
| Unknown                              | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 6      | 40%     |
| Seagate | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |
| Apple   | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 7      | 45.45%  |
| Samsung Electronics | 3         | 5      | 27.27%  |
| Transcend           | 1         | 1      | 9.09%   |
| Toshiba             | 1         | 1      | 9.09%   |
| Leven               | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 22     | 40.48%  |
| SSD  | 10        | 15     | 23.81%  |
| HDD  | 10        | 12     | 23.81%  |
| MMC  | 5         | 7      | 11.9%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 22     | 44.74%  |
| SATA | 15        | 26     | 39.47%  |
| MMC  | 5         | 7      | 13.16%  |
| SAS  | 1         | 1      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 18     | 61.11%  |
| 0.51-1.0   | 4         | 4      | 22.22%  |
| 1.01-2.0   | 3         | 5      | 16.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 27.27%  |
| 251-500    | 6         | 18.18%  |
| 1-20       | 6         | 18.18%  |
| 501-1000   | 5         | 15.15%  |
| 1001-2000  | 3         | 9.09%   |
| 51-100     | 2         | 6.06%   |
| Unknown    | 2         | 6.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 39.39%  |
| 21-50     | 6         | 18.18%  |
| 101-250   | 4         | 12.12%  |
| 51-100    | 4         | 12.12%  |
| 251-500   | 2         | 6.06%   |
| Unknown   | 2         | 6.06%   |
| 1001-2000 | 1         | 3.03%   |
| 501-1000  | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB   | 1         | 1      | 50%     |
| Fujitsu MJA2500BH G1 500GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Fujitsu | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Fujitsu | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 18        | 28     | 48.65%  |
| Works    | 17        | 26     | 45.95%  |
| Malfunc  | 2         | 2      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 38.64%  |
| Samsung Electronics          | 9         | 20.45%  |
| AMD                          | 5         | 11.36%  |
| Toshiba America Info Systems | 2         | 4.55%   |
| Sandisk                      | 2         | 4.55%   |
| Phison Electronics           | 2         | 4.55%   |
| ADATA Technology             | 2         | 4.55%   |
| VIA Technologies             | 1         | 2.27%   |
| SK Hynix                     | 1         | 2.27%   |
| KIOXIA                       | 1         | 2.27%   |
| JMicron Technology           | 1         | 2.27%   |
| ASMedia Technology           | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6%      |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 6%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 4%      |
| Samsung NVMe SSD Controller 980                                                | 2         | 4%      |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 4%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 4%      |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 4%      |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 2%      |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 2%      |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 2%      |
| Sandisk Non-Volatile memory controller                                         | 1         | 2%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 2%      |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 2%      |
| Phison E12 NVMe Controller                                                     | 1         | 2%      |
| KIOXIA Non-Volatile memory controller                                          | 1         | 2%      |
| JMicron JMB368 IDE controller                                                  | 1         | 2%      |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 2%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 2%      |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 2%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 2%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 2%      |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 2%      |
| ADATA Non-Volatile memory controller                                           | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18        | 45%     |
| NVMe | 17        | 42.5%   |
| IDE  | 3         | 7.5%    |
| RAID | 2         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 78.79%  |
| AMD    | 7         | 21.21%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 9.09%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 6.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 6.06%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 3.03%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 3.03%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 3.03%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 3.03%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.03%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 3.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 3.03%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 3.03%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 3.03%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 1         | 3.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.03%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 1         | 3.03%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 3.03%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 1         | 3.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 3.03%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 3.03%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 3.03%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD A8-5500 APU with Radeon HD Graphics       | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 7         | 21.21%  |
| Intel Core i5    | 6         | 18.18%  |
| Intel Core i7    | 5         | 15.15%  |
| AMD Ryzen 5      | 3         | 9.09%   |
| Intel Core 2 Duo | 2         | 6.06%   |
| Intel Celeron    | 2         | 6.06%   |
| Intel Atom       | 2         | 6.06%   |
| AMD Ryzen 7      | 2         | 6.06%   |
| Intel Pentium    | 1         | 3.03%   |
| Intel Core i3    | 1         | 3.03%   |
| AMD Ryzen 9      | 1         | 3.03%   |
| AMD A8           | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 39.39%  |
| 2      | 9         | 27.27%  |
| 8      | 7         | 21.21%  |
| 6      | 4         | 12.12%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 24        | 72.73%  |
| 1      | 9         | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 5         | 15.15%  |
| 0xa0652    | 3         | 9.09%   |
| 0x306c3    | 2         | 6.06%   |
| 0x08701021 | 2         | 6.06%   |
| 0xa0671    | 1         | 3.03%   |
| 0x906ea    | 1         | 3.03%   |
| 0x906e9    | 1         | 3.03%   |
| 0x806ea    | 1         | 3.03%   |
| 0x806d1    | 1         | 3.03%   |
| 0x706a8    | 1         | 3.03%   |
| 0x506c9    | 1         | 3.03%   |
| 0x406e3    | 1         | 3.03%   |
| 0x406c4    | 1         | 3.03%   |
| 0x40651    | 1         | 3.03%   |
| 0x306a9    | 1         | 3.03%   |
| 0x30678    | 1         | 3.03%   |
| 0x20655    | 1         | 3.03%   |
| 0x20652    | 1         | 3.03%   |
| 0x1067a    | 1         | 3.03%   |
| 0x10676    | 1         | 3.03%   |
| 0x0a50000c | 1         | 3.03%   |
| 0x08608103 | 1         | 3.03%   |
| 0x0810100b | 1         | 3.03%   |
| 0x0800820d | 1         | 3.03%   |
| 0x06001119 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| TigerLake     | 5         | 15.15%  |
| KabyLake      | 3         | 9.09%   |
| Haswell       | 3         | 9.09%   |
| CometLake     | 3         | 9.09%   |
| Zen 2         | 2         | 6.06%   |
| Westmere      | 2         | 6.06%   |
| Silvermont    | 2         | 6.06%   |
| Penryn        | 2         | 6.06%   |
| Icelake       | 2         | 6.06%   |
| Zen+          | 1         | 3.03%   |
| Zen 3         | 1         | 3.03%   |
| Zen           | 1         | 3.03%   |
| Skylake       | 1         | 3.03%   |
| Piledriver    | 1         | 3.03%   |
| IvyBridge     | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| Goldmont      | 1         | 3.03%   |
| Unknown       | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 55%     |
| Nvidia | 9         | 22.5%   |
| AMD    | 9         | 22.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 12.5%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 7.5%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 5%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 5%      |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 5%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 5%      |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 2.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 2.5%    |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 2.5%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.5%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 2.5%    |
| Intel HD Graphics 500                                                                    | 1         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.5%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 2.5%    |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.5%    |
| AMD Lucienne                                                                             | 1         | 2.5%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 2.5%    |
| AMD Cezanne                                                                              | 1         | 2.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 48.48%  |
| 1 x AMD        | 7         | 21.21%  |
| Intel + Nvidia | 5         | 15.15%  |
| 1 x Nvidia     | 3         | 9.09%   |
| Intel + AMD    | 1         | 3.03%   |
| AMD + Nvidia   | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 29        | 85.29%  |
| Proprietary | 4         | 11.76%  |
| Unknown     | 1         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 57.58%  |
| 3.01-4.0   | 5         | 15.15%  |
| 1.01-2.0   | 4         | 12.12%  |
| 0.01-0.5   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 4         | 11.76%  |
| AU Optronics         | 4         | 11.76%  |
| Sharp                | 3         | 8.82%   |
| LG Display           | 3         | 8.82%   |
| Goldstar             | 3         | 8.82%   |
| AOC                  | 3         | 8.82%   |
| Ancor Communications | 3         | 8.82%   |
| Samsung Electronics  | 2         | 5.88%   |
| InfoVision           | 2         | 5.88%   |
| Hewlett-Packard      | 2         | 5.88%   |
| Chimei Innolux       | 2         | 5.88%   |
| Philips              | 1         | 2.94%   |
| Dell                 | 1         | 2.94%   |
| Apple                | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 2         | 5.71%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 2.86%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 2.86%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch              | 1         | 2.86%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 2.86%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 2.86%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1         | 2.86%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 1         | 2.86%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch         | 1         | 2.86%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 2.86%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch           | 1         | 2.86%   |
| Hewlett-Packard E223 HPN345B 1920x1080 480x270mm 21.7-inch           | 1         | 2.86%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                 | 1         | 2.86%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch             | 1         | 2.86%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                | 1         | 2.86%   |
| Dell E2216H DELF069 1920x1080 480x270mm 21.7-inch                    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 2.86%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE0922 1920x550                                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO572D 1920x1080 293x165mm 13.2-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 216x136mm 10.0-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 1         | 2.86%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                     | 1         | 2.86%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                     | 1         | 2.86%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1         | 2.86%   |
| AOC 2043 AOC2043 1600x900 443x249mm 20.0-inch                        | 1         | 2.86%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 56.25%  |
| 1366x768 (WXGA)    | 3         | 9.38%   |
| 1920x1200 (WUXGA)  | 2         | 6.25%   |
| 1600x900 (HD+)     | 2         | 6.25%   |
| 3840x2400          | 1         | 3.13%   |
| 3840x2160 (4K)     | 1         | 3.13%   |
| 3840x1600          | 1         | 3.13%   |
| 2560x1440 (QHD)    | 1         | 3.13%   |
| 2256x1504          | 1         | 3.13%   |
| 1920x550           | 1         | 3.13%   |
| 1680x1050 (WSXGA+) | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 6         | 17.65%  |
| 13      | 6         | 17.65%  |
| 24      | 4         | 11.76%  |
| 21      | 4         | 11.76%  |
| 23      | 3         | 8.82%   |
| 27      | 2         | 5.88%   |
| 17      | 2         | 5.88%   |
| 37      | 1         | 2.94%   |
| 20      | 1         | 2.94%   |
| 14      | 1         | 2.94%   |
| 12      | 1         | 2.94%   |
| 11      | 1         | 2.94%   |
| 10      | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 26.47%  |
| 501-600     | 8         | 23.53%  |
| 201-300     | 7         | 20.59%  |
| 401-500     | 6         | 17.65%  |
| 351-400     | 2         | 5.88%   |
| 801-900     | 1         | 2.94%   |
| Unknown     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 76.67%  |
| 16/10 | 3         | 10%     |
| 3/2   | 2         | 6.67%   |
| 32/9  | 1         | 3.33%   |
| 21/9  | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 8         | 24.24%  |
| 101-110        | 6         | 18.18%  |
| 81-90          | 4         | 12.12%  |
| 71-80          | 3         | 9.09%   |
| 151-200        | 3         | 9.09%   |
| 301-350        | 2         | 6.06%   |
| 121-130        | 2         | 6.06%   |
| 61-70          | 1         | 3.03%   |
| 51-60          | 1         | 3.03%   |
| 351-500        | 1         | 3.03%   |
| 41-50          | 1         | 3.03%   |
| Unknown        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 32.35%  |
| 51-100        | 10        | 29.41%  |
| 161-240       | 6         | 17.65%  |
| 101-120       | 5         | 14.71%  |
| More than 240 | 1         | 2.94%   |
| Unknown       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 76.47%  |
| 2     | 4         | 11.76%  |
| 0     | 3         | 8.82%   |
| 3     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 22        | 45.83%  |
| Realtek Semiconductor             | 15        | 31.25%  |
| Qualcomm Atheros                  | 2         | 4.17%   |
| Broadcom                          | 2         | 4.17%   |
| Belkin Components                 | 2         | 4.17%   |
| Ralink Technology                 | 1         | 2.08%   |
| Microsoft                         | 1         | 2.08%   |
| MicroPython                       | 1         | 2.08%   |
| Marvell Technology Group          | 1         | 2.08%   |
| Ericsson Business Mobile Networks | 1         | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 11        | 19.64%  |
| Intel Wi-Fi 6 AX201                                                | 4         | 7.14%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 5.36%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                  | 2         | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 3.57%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1         | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.79%   |
| Realtek 802.11n                                                    | 1         | 1.79%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.79%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1         | 1.79%   |
| MicroPython Board in FS mode                                       | 1         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 1.79%   |
| Intel Wireless 8265 / 8275                                         | 1         | 1.79%   |
| Intel Wireless 8260                                                | 1         | 1.79%   |
| Intel Wireless 7260                                                | 1         | 1.79%   |
| Intel Wireless 3165                                                | 1         | 1.79%   |
| Intel WiFi Link 5100                                               | 1         | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 1.79%   |
| Intel Ethernet Controller I225-V                                   | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                  | 1         | 1.79%   |
| Intel Ethernet Connection (7) I219-V                               | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 1.79%   |
| Intel 82578DM Gigabit Network Connection                           | 1         | 1.79%   |
| Ericsson Business Mobile Networks N5321 gw                         | 1         | 1.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                  | 1         | 1.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 1.79%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1         | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 19        | 63.33%  |
| Realtek Semiconductor             | 2         | 6.67%   |
| Qualcomm Atheros                  | 2         | 6.67%   |
| Broadcom                          | 2         | 6.67%   |
| Belkin Components                 | 2         | 6.67%   |
| Ralink Technology                 | 1         | 3.33%   |
| Microsoft                         | 1         | 3.33%   |
| Ericsson Business Mobile Networks | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                | 4         | 13.33%  |
| Intel Wi-Fi 6 AX200                                                | 3         | 10%     |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 10%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 6.67%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 3.33%   |
| Realtek 802.11n                                                    | 1         | 3.33%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 3.33%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1         | 3.33%   |
| Intel Wireless 8265 / 8275                                         | 1         | 3.33%   |
| Intel Wireless 8260                                                | 1         | 3.33%   |
| Intel Wireless 7260                                                | 1         | 3.33%   |
| Intel Wireless 3165                                                | 1         | 3.33%   |
| Intel WiFi Link 5100                                               | 1         | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 3.33%   |
| Ericsson Business Mobile Networks N5321 gw                         | 1         | 3.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 3.33%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 58.33%  |
| Intel                    | 8         | 33.33%  |
| Marvell Technology Group | 1         | 4.17%   |
| Broadcom                 | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 44%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 8%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4%      |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 4%      |
| Intel Ethernet Controller I225-V                                  | 1         | 4%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 4%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1         | 4%      |
| Intel Ethernet Connection (13) I219-V                             | 1         | 4%      |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 4%      |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 4%      |
| Intel 82578DM Gigabit Network Connection                          | 1         | 4%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 51.92%  |
| Ethernet | 24        | 46.15%  |
| Modem    | 1         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 62.16%  |
| Ethernet | 14        | 37.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 51.52%  |
| 1     | 14        | 42.42%  |
| 0     | 2         | 6.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18        | 54.55%  |
| Yes  | 15        | 45.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 76.19%  |
| Qualcomm Atheros Communications | 2         | 9.52%   |
| Realtek Semiconductor           | 1         | 4.76%   |
| Cambridge Silicon Radio         | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 7         | 33.33%  |
| Intel Bluetooth wireless interface                  | 3         | 14.29%  |
| Intel AX200 Bluetooth                               | 3         | 14.29%  |
| Intel AX210 Bluetooth                               | 2         | 9.52%   |
| Realtek Bluetooth Radio                             | 1         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 4.76%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.76%   |
| Apple Bluetooth USB Host Controller                 | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 52.17%  |
| Nvidia                   | 9         | 19.57%  |
| AMD                      | 9         | 19.57%  |
| Texas Instruments        | 1         | 2.17%   |
| Plantronics              | 1         | 2.17%   |
| Micro Star International | 1         | 2.17%   |
| C-Media Electronics      | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 5         | 9.43%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 5.66%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 5.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 3.77%   |
| Nvidia Audio device                                                 | 2         | 3.77%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 3.77%   |
| Intel Sunrise Point-LP HD Audio                                     | 2         | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 3.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2         | 3.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2         | 3.77%   |
| Texas Instruments PCM2903B Audio CODEC                              | 1         | 1.89%   |
| Plantronics Blackwire 325.1                                         | 1         | 1.89%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 1.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1         | 1.89%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.89%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.89%   |
| Micro Star International USB Audio                                  | 1         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 1.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 1.89%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 1.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 1.89%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                | 1         | 1.89%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 1.89%   |
| AMD FCH Azalia Controller                                           | 1         | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 20%     |
| Unknown             | 4         | 16%     |
| Micron Technology   | 4         | 16%     |
| SK Hynix            | 3         | 12%     |
| Crucial             | 3         | 12%     |
| Unknown (ABCD)      | 2         | 8%      |
| V-GeN               | 1         | 4%      |
| Silicon Power       | 1         | 4%      |
| Mushkin             | 1         | 4%      |
| GOODRAM             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 8%      |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s                       | 1         | 4%      |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 4%      |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 4%      |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 1         | 4%      |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s                        | 1         | 4%      |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                       | 1         | 4%      |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 4%      |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 4%      |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 4%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 4%      |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 4%      |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s               | 1         | 4%      |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                          | 1         | 4%      |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 1         | 4%      |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s                 | 1         | 4%      |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 4%      |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s                | 1         | 4%      |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s               | 1         | 4%      |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s               | 1         | 4%      |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s           | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 50%     |
| DDR3    | 5         | 25%     |
| LPDDR4  | 3         | 15%     |
| DDR2    | 1         | 5%      |
| Unknown | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 57.14%  |
| DIMM         | 7         | 33.33%  |
| Row Of Chips | 2         | 9.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 33.33%  |
| 8192  | 6         | 28.57%  |
| 2048  | 4         | 19.05%  |
| 32768 | 3         | 14.29%  |
| 16384 | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 5         | 22.73%  |
| 2400    | 3         | 13.64%  |
| 1600    | 3         | 13.64%  |
| 2667    | 2         | 9.09%   |
| 2133    | 2         | 9.09%   |
| 1333    | 2         | 9.09%   |
| 4267    | 1         | 4.55%   |
| 3266    | 1         | 4.55%   |
| 1066    | 1         | 4.55%   |
| 800     | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| Brother Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 3         | 15.79%  |
| Syntek                      | 2         | 10.53%  |
| Microdia                    | 2         | 10.53%  |
| IMC Networks                | 2         | 10.53%  |
| USB Camera                  | 1         | 5.26%   |
| Ricoh                       | 1         | 5.26%   |
| Primax Electronics          | 1         | 5.26%   |
| Microsoft                   | 1         | 5.26%   |
| Luxvisions Innotech Limited | 1         | 5.26%   |
| Logitech                    | 1         | 5.26%   |
| Lite-On Technology          | 1         | 5.26%   |
| Apple                       | 1         | 5.26%   |
| Alcor Micro                 | 1         | 5.26%   |
| Acer                        | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 2         | 10.53%  |
| IMC Networks Integrated Camera           | 2         | 10.53%  |
| Chicony Integrated Camera                | 2         | 10.53%  |
| USB Camera USB Camera                    | 1         | 5.26%   |
| Syntek Lenovo EasyCamera                 | 1         | 5.26%   |
| Syntek Integrated Camera                 | 1         | 5.26%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 5.26%   |
| Primax HP HD Webcam [Fixed]              | 1         | 5.26%   |
| Microsoft LifeCam Cinema                 | 1         | 5.26%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 5.26%   |
| Logitech QuickCam Communicate Deluxe     | 1         | 5.26%   |
| Lite-On Integrated Camera                | 1         | 5.26%   |
| Chicony HP HD Camera                     | 1         | 5.26%   |
| Apple FaceTime HD Camera (Built-in)      | 1         | 5.26%   |
| Alcor Micro USB 2.0 PC cam               | 1         | 5.26%   |
| Acer BisonCam,NB Pro                     | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 66.67%  |
| Validity Sensors           | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 16.67%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 16.67%  |
| Unknown                                                    | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 52.94%  |
| 1     | 11        | 32.35%  |
| 2     | 3         | 8.82%   |
| 3     | 2         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 33.33%  |
| Graphics card         | 5         | 27.78%  |
| Multimedia controller | 3         | 16.67%  |
| Net/wireless          | 2         | 11.11%  |
| Sound                 | 1         | 5.56%   |
| Card reader           | 1         | 5.56%   |

