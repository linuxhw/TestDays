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

Total: 73

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF314-41              | Notebook    | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1cc5b6fbc3](https://linux-hardware.org/?probe=1cc5b6fbc3) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
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
| 5.17.1-300.fc36.x86_64                                        | 20        | 38.46%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 7         | 13.46%  |
| 5.17.0-300.fc36.x86_64                                        | 4         | 7.69%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 4         | 7.69%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 2         | 3.85%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2         | 3.85%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1         | 1.92%   |
| 5.16.17-200.fc35.x86_64                                       | 1         | 1.92%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 1.92%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 1.92%   |
| 5.16.0-0.rc2.20211126gita4849f6000e2.21.fc36.x86_64           | 1         | 1.92%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 1.92%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1         | 1.92%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1         | 1.92%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 1.92%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 1.92%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1         | 1.92%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 1.92%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 20        | 39.22%  |
| 5.17.0  | 16        | 31.37%  |
| 5.15.0  | 7         | 13.73%  |
| 5.16.0  | 2         | 3.92%   |
| 5.14.0  | 2         | 3.92%   |
| 5.16.17 | 1         | 1.96%   |
| 5.16.16 | 1         | 1.96%   |
| 5.14.14 | 1         | 1.96%   |
| 5.14.10 | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 36        | 70.59%  |
| 5.15    | 7         | 13.73%  |
| 5.16    | 4         | 7.84%   |
| 5.14    | 4         | 7.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 40        | 80%     |
| KDE5    | 6         | 12%     |
| Unknown | 3         | 6%      |
| i3      | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 38        | 77.55%  |
| X11     | 9         | 18.37%  |
| Tty     | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 25        | 51.02%  |
| Unknown | 16        | 32.65%  |
| SDDM    | 6         | 12.24%  |
| LightDM | 2         | 4.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 25        | 51.02%  |
| en_GB | 5         | 10.2%   |
| pt_BR | 3         | 6.12%   |
| de_DE | 3         | 6.12%   |
| ru_RU | 2         | 4.08%   |
| pl_PL | 2         | 4.08%   |
| fr_FR | 2         | 4.08%   |
| pt_PT | 1         | 2.04%   |
| hr_HR | 1         | 2.04%   |
| fi_FI | 1         | 2.04%   |
| es_ES | 1         | 2.04%   |
| es_AR | 1         | 2.04%   |
| en_CA | 1         | 2.04%   |
| cs_CZ | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 83.67%  |
| BIOS | 8         | 16.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 35        | 71.43%  |
| Ext4  | 11        | 22.45%  |
| Xfs   | 3         | 6.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 31        | 62%     |
| Unknown | 16        | 32%     |
| MBR     | 3         | 6%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 87.76%  |
| Yes       | 6         | 12.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 63.27%  |
| Yes       | 18        | 36.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 13        | 26.53%  |
| Gigabyte Technology    | 7         | 14.29%  |
| Dell                   | 6         | 12.24%  |
| Hewlett-Packard        | 5         | 10.2%   |
| MSI                    | 3         | 6.12%   |
| ASUSTek Computer       | 3         | 6.12%   |
| Acer                   | 2         | 4.08%   |
| VALE                   | 1         | 2.04%   |
| Sony                   | 1         | 2.04%   |
| Positivo               | 1         | 2.04%   |
| Notebook               | 1         | 2.04%   |
| Framework              | 1         | 2.04%   |
| Chuwi                  | 1         | 2.04%   |
| Biostar                | 1         | 2.04%   |
| Avell High Performance | 1         | 2.04%   |
| Apple                  | 1         | 2.04%   |
| Unknown                | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| VALE Notebook Slim S132                     | 1         | 2.04%   |
| Sony VGN-FW21E                              | 1         | 2.04%   |
| Positivo CHT12CP                            | 1         | 2.04%   |
| Notebook PCx0Dx                             | 1         | 2.04%   |
| MSI MS-7D06                                 | 1         | 2.04%   |
| MSI MS-7C95                                 | 1         | 2.04%   |
| MSI MS-7721                                 | 1         | 2.04%   |
| Lenovo ThinkPad X260 20F5S0HK1J             | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00    | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S0P    | 1         | 2.04%   |
| Lenovo ThinkPad P15 Gen 1 20STS0J500        | 1         | 2.04%   |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00        | 1         | 2.04%   |
| Lenovo ThinkPad 10 20C10027SP               | 1         | 2.04%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 1         | 2.04%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 2.04%   |
| Lenovo ThinkBook 13s G3 ACN 20YA            | 1         | 2.04%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 2.04%   |
| Lenovo IdeaPad Yoga 13 20175                | 1         | 2.04%   |
| Lenovo IdeaPad 530S-14ARR 81H1              | 1         | 2.04%   |
| Lenovo IdeaPad 320S-13IKB 81AK              | 1         | 2.04%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 2.04%   |
| HP ProBook 4740s                            | 1         | 2.04%   |
| HP ENVY x360 Convertible 15-cp0xxx          | 1         | 2.04%   |
| HP EliteBook x360 830 G5                    | 1         | 2.04%   |
| HP Compaq 8100 Elite SFF PC                 | 1         | 2.04%   |
| Gigabyte H81M-S2H                           | 1         | 2.04%   |
| Gigabyte H370M-DS3H                         | 1         | 2.04%   |
| Gigabyte EP45-DS3L                          | 1         | 2.04%   |
| Gigabyte B85M-D3V-A                         | 1         | 2.04%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 2.04%   |
| Gigabyte B550 AORUS ELITE                   | 1         | 2.04%   |
| Gigabyte 970A-DS3P                          | 1         | 2.04%   |
| Framework Laptop                            | 1         | 2.04%   |
| Dell XPS 17 9710                            | 1         | 2.04%   |
| Dell XPS 13 9333                            | 1         | 2.04%   |
| Dell XPS 13 9310 2-in-1                     | 1         | 2.04%   |
| Dell OptiPlex 9020                          | 1         | 2.04%   |
| Dell Inspiron 5548                          | 1         | 2.04%   |
| Dell Inspiron 3847                          | 1         | 2.04%   |
| Chuwi Hi10 Go                               | 1         | 2.04%   |
| Biostar H55 HD                              | 1         | 2.04%   |
| Avell High Performance B.ON                 | 1         | 2.04%   |
| ASUS TUF GAMING B550M-PLUS                  | 1         | 2.04%   |
| ASUS ROG Zephyrus Duo 15 SE GX551QS_GX551QS | 1         | 2.04%   |
| ASUS B150M-K                                | 1         | 2.04%   |
| Apple iMac18,2                              | 1         | 2.04%   |
| Acer Swift SF314-41                         | 1         | 2.04%   |
| Acer Aspire A515-45                         | 1         | 2.04%   |
| Unknown                                     | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 6         | 12.24%  |
| Lenovo ThinkBook            | 3         | 6.12%   |
| Lenovo IdeaPad              | 3         | 6.12%   |
| Dell XPS                    | 3         | 6.12%   |
| Dell Inspiron               | 2         | 4.08%   |
| VALE Notebook               | 1         | 2.04%   |
| Sony VGN-FW21E              | 1         | 2.04%   |
| Positivo CHT12CP            | 1         | 2.04%   |
| Notebook PCx0Dx             | 1         | 2.04%   |
| MSI MS-7D06                 | 1         | 2.04%   |
| MSI MS-7C95                 | 1         | 2.04%   |
| MSI MS-7721                 | 1         | 2.04%   |
| Lenovo IdeaPadFlex          | 1         | 2.04%   |
| HP ZBook                    | 1         | 2.04%   |
| HP ProBook                  | 1         | 2.04%   |
| HP ENVY                     | 1         | 2.04%   |
| HP EliteBook                | 1         | 2.04%   |
| HP Compaq                   | 1         | 2.04%   |
| Gigabyte H81M-S2H           | 1         | 2.04%   |
| Gigabyte H370M-DS3H         | 1         | 2.04%   |
| Gigabyte EP45-DS3L          | 1         | 2.04%   |
| Gigabyte B85M-D3V-A         | 1         | 2.04%   |
| Gigabyte B550I              | 1         | 2.04%   |
| Gigabyte B550               | 1         | 2.04%   |
| Gigabyte 970A-DS3P          | 1         | 2.04%   |
| Framework Laptop            | 1         | 2.04%   |
| Dell OptiPlex               | 1         | 2.04%   |
| Chuwi Hi10                  | 1         | 2.04%   |
| Biostar H55                 | 1         | 2.04%   |
| Avell High Performance B.ON | 1         | 2.04%   |
| ASUS TUF                    | 1         | 2.04%   |
| ASUS ROG                    | 1         | 2.04%   |
| ASUS B150M-K                | 1         | 2.04%   |
| Apple iMac18                | 1         | 2.04%   |
| Acer Swift                  | 1         | 2.04%   |
| Acer Aspire                 | 1         | 2.04%   |
| Unknown                     | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 12        | 24.49%  |
| 2020 | 9         | 18.37%  |
| 2018 | 6         | 12.24%  |
| 2013 | 5         | 10.2%   |
| 2019 | 3         | 6.12%   |
| 2015 | 3         | 6.12%   |
| 2017 | 2         | 4.08%   |
| 2014 | 2         | 4.08%   |
| 2012 | 2         | 4.08%   |
| 2008 | 2         | 4.08%   |
| 2016 | 1         | 2.04%   |
| 2010 | 1         | 2.04%   |
| 2009 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 28        | 57.14%  |
| Desktop     | 16        | 32.65%  |
| Convertible | 3         | 6.12%   |
| Tablet      | 1         | 2.04%   |
| All in one  | 1         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 39        | 79.59%  |
| Enabled  | 10        | 20.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 26.53%  |
| 8.01-16.0   | 10        | 20.41%  |
| 3.01-4.0    | 9         | 18.37%  |
| 16.01-24.0  | 9         | 18.37%  |
| 32.01-64.0  | 6         | 12.24%  |
| 64.01-256.0 | 2         | 4.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 20        | 40%     |
| 2.01-3.0  | 13        | 26%     |
| 4.01-8.0  | 10        | 20%     |
| 1.01-2.0  | 5         | 10%     |
| 8.01-16.0 | 1         | 2%      |
| 0.51-1.0  | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 60%     |
| 2      | 12        | 24%     |
| 3      | 5         | 10%     |
| 4      | 3         | 6%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 81.63%  |
| Yes       | 9         | 18.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 65.31%  |
| No        | 17        | 34.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 69.39%  |
| No        | 15        | 30.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 6         | 12.24%  |
| UK          | 5         | 10.2%   |
| Brazil      | 5         | 10.2%   |
| Poland      | 3         | 6.12%   |
| Spain       | 2         | 4.08%   |
| Netherlands | 2         | 4.08%   |
| Italy       | 2         | 4.08%   |
| Germany     | 2         | 4.08%   |
| France      | 2         | 4.08%   |
| Belarus     | 2         | 4.08%   |
| Uzbekistan  | 1         | 2.04%   |
| Turkey      | 1         | 2.04%   |
| Switzerland | 1         | 2.04%   |
| Slovakia    | 1         | 2.04%   |
| Romania     | 1         | 2.04%   |
| Norway      | 1         | 2.04%   |
| Nepal       | 1         | 2.04%   |
| Latvia      | 1         | 2.04%   |
| Indonesia   | 1         | 2.04%   |
| Finland     | 1         | 2.04%   |
| Estonia     | 1         | 2.04%   |
| Czechia     | 1         | 2.04%   |
| Croatia     | 1         | 2.04%   |
| Canada      | 1         | 2.04%   |
| Belgium     | 1         | 2.04%   |
| Bangladesh  | 1         | 2.04%   |
| Austria     | 1         | 2.04%   |
| Argentina   | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Sao Paulo                     | 2         | 4.08%   |
| Minsk                         | 2         | 4.08%   |
| Halstead                      | 2         | 4.08%   |
| Folsom                        | 2         | 4.08%   |
| Zurich                        | 1         | 2.04%   |
| Zagreb                        | 1         | 2.04%   |
| Warsaw                        | 1         | 2.04%   |
| Warrington                    | 1         | 2.04%   |
| Vegarshei                     | 1         | 2.04%   |
| Vancouver                     | 1         | 2.04%   |
| Turku                         | 1         | 2.04%   |
| Trzciel                       | 1         | 2.04%   |
| TorrejÃ³n de Ardoz          | 1         | 2.04%   |
| Tashkent                      | 1         | 2.04%   |
| Tarragona                     | 1         | 2.04%   |
| Tallinn                       | 1         | 2.04%   |
| Solihull                      | 1         | 2.04%   |
| Rozmital pod Tremsinem        | 1         | 2.04%   |
| Riga                          | 1         | 2.04%   |
| Paris                         | 1         | 2.04%   |
| Newport                       | 1         | 2.04%   |
| Mölten                       | 1         | 2.04%   |
| Milicz                        | 1         | 2.04%   |
| Marseille                     | 1         | 2.04%   |
| Macaiba                       | 1         | 2.04%   |
| Kathmandu                     | 1         | 2.04%   |
| Kasten bei Boeheimkirchen     | 1         | 2.04%   |
| Kanne                         | 1         | 2.04%   |
| Joinville                     | 1         | 2.04%   |
| Jakarta                       | 1         | 2.04%   |
| Istanbul                      | 1         | 2.04%   |
| Houston                       | 1         | 2.04%   |
| Hoofddorp                     | 1         | 2.04%   |
| Goiânia                      | 1         | 2.04%   |
| Fort Collins                  | 1         | 2.04%   |
| El Segundo                    | 1         | 2.04%   |
| Dhaka                         | 1         | 2.04%   |
| Delft                         | 1         | 2.04%   |
| Caldaro sulla Strada del Vino | 1         | 2.04%   |
| Buenos Aires                  | 1         | 2.04%   |
| Bucharest                     | 1         | 2.04%   |
| Bratislava                    | 1         | 2.04%   |
| Bonn                          | 1         | 2.04%   |
| Berlin                        | 1         | 2.04%   |
| Beaverton                     | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 27     | 27.54%  |
| WDC                 | 10        | 13     | 14.49%  |
| Kingston            | 8         | 10     | 11.59%  |
| Unknown             | 5         | 7      | 7.25%   |
| Toshiba             | 4         | 4      | 5.8%    |
| Seagate             | 4         | 4      | 5.8%    |
| SK Hynix            | 2         | 2      | 2.9%    |
| Phison              | 2         | 2      | 2.9%    |
| KIOXIA              | 2         | 2      | 2.9%    |
| A-DATA Technology   | 2         | 2      | 2.9%    |
| Unknown             | 2         | 2      | 2.9%    |
| XPG                 | 1         | 1      | 1.45%   |
| Transcend           | 1         | 1      | 1.45%   |
| SanDisk             | 1         | 1      | 1.45%   |
| PNY                 | 1         | 2      | 1.45%   |
| Leven               | 1         | 1      | 1.45%   |
| Hitachi             | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |
| Crucial             | 1         | 1      | 1.45%   |
| Apple               | 1         | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3         | 3.95%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 3.95%   |
| Unknown MMC Card  64GB                 | 2         | 2.63%   |
| Samsung SSD 970 EVO Plus 500GB         | 2         | 2.63%   |
| Samsung SSD 970 EVO 250GB              | 2         | 2.63%   |
| Samsung SSD 870 QVO 2TB                | 2         | 2.63%   |
| Samsung SSD 860 EVO 250GB              | 2         | 2.63%   |
| Samsung NVMe SSD Drive 1TB             | 2         | 2.63%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 2.63%   |
| Unknown                                | 2         | 2.63%   |
| XPG GAMMIX S11 Pro 256GB               | 1         | 1.32%   |
| WDC WDS500G1X0E-00AFY0 500GB           | 1         | 1.32%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 1.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 1.32%   |
| WDC WD6400AAKS-22A7B2 640GB            | 1         | 1.32%   |
| WDC WD5000AAKX-001CA0 500GB            | 1         | 1.32%   |
| WDC WD40EZRZ-00WN9B0 4TB               | 1         | 1.32%   |
| WDC WD30EZRX-00SPEB0 3TB               | 1         | 1.32%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 1         | 1.32%   |
| WDC WD20EZRX-00D8PB0 2TB               | 1         | 1.32%   |
| WDC WD20EARS-00MVWB0 2TB               | 1         | 1.32%   |
| WDC WD10EZEX-00ZF5A0 1TB               | 1         | 1.32%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 1         | 1.32%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB   | 1         | 1.32%   |
| Unknown SU32G  32GB                    | 1         | 1.32%   |
| Unknown MMC64G  64GB                   | 1         | 1.32%   |
| Unknown ED2S5  128GB                   | 1         | 1.32%   |
| Transcend TS240GMTS420S 240GB SSD      | 1         | 1.32%   |
| Toshiba THNSNJ128GCSU 128GB SSD        | 1         | 1.32%   |
| Toshiba MQ01ABD050 500GB               | 1         | 1.32%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 1         | 1.32%   |
| Toshiba HDWD120 2TB                    | 1         | 1.32%   |
| SK Hynix NVMe SSD Drive 256GB          | 1         | 1.32%   |
| SK Hynix HFM256GDHTNG-8310A 256GB      | 1         | 1.32%   |
| Seagate ST3500413AS 500GB              | 1         | 1.32%   |
| Seagate ST2000DM009-2G4100 2TB         | 1         | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB         | 1         | 1.32%   |
| Seagate Expansion 500GB                | 1         | 1.32%   |
| SanDisk DF4032  32GB                   | 1         | 1.32%   |
| Samsung SSD 970 EVO Plus 1TB           | 1         | 1.32%   |
| Samsung SSD 860 EVO mSATA 500GB        | 1         | 1.32%   |
| Samsung SSD 860 EVO 500GB              | 1         | 1.32%   |
| Samsung SSD 860 EVO 1TB                | 1         | 1.32%   |
| Samsung SSD 850 EVO 250GB              | 1         | 1.32%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 1.32%   |
| Samsung NVMe SSD Drive 2TB             | 1         | 1.32%   |
| Samsung NVMe SSD Drive 1024GB          | 1         | 1.32%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD   | 1         | 1.32%   |
| Samsung MZALQ512HBLU-00BL2 512GB       | 1         | 1.32%   |
| PNY CS3040 4TB SSD                     | 1         | 1.32%   |
| Phison Sabrent 1TB                     | 1         | 1.32%   |
| Phison NVMe SSD Drive 512GB            | 1         | 1.32%   |
| Leven JAJS600M256C 256GB               | 1         | 1.32%   |
| KIOXIA NVMe SSD Drive 256GB            | 1         | 1.32%   |
| KIOXIA KXG60ZNV1T02 1TB                | 1         | 1.32%   |
| Kingston SUV500MS240G 240GB SSD        | 1         | 1.32%   |
| Kingston SA400S37960G 960GB SSD        | 1         | 1.32%   |
| Kingston SA400S37480G 480GB SSD        | 1         | 1.32%   |
| Hitachi HTS543232A7A384 320GB          | 1         | 1.32%   |
| Fujitsu MJA2500BH G1 500GB             | 1         | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 40%     |
| Seagate | 4         | 4      | 26.67%  |
| Toshiba | 2         | 2      | 13.33%  |
| Hitachi | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |
| Apple   | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 40.91%  |
| Kingston            | 8         | 10     | 36.36%  |
| WDC                 | 2         | 2      | 9.09%   |
| Transcend           | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| Leven               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 31     | 38.46%  |
| SSD  | 19        | 27     | 29.23%  |
| HDD  | 14        | 17     | 21.54%  |
| MMC  | 7         | 10     | 10.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 31     | 43.86%  |
| SATA | 24        | 43     | 42.11%  |
| MMC  | 7         | 10     | 12.28%  |
| SAS  | 1         | 1      | 1.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 29     | 58.06%  |
| 0.51-1.0   | 6         | 6      | 19.35%  |
| 1.01-2.0   | 5         | 7      | 16.13%  |
| 3.01-4.0   | 1         | 1      | 3.23%   |
| 2.01-3.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 10        | 20.41%  |
| 1-20           | 10        | 20.41%  |
| 101-250        | 9         | 18.37%  |
| 501-1000       | 7         | 14.29%  |
| 1001-2000      | 5         | 10.2%   |
| More than 3000 | 3         | 6.12%   |
| 51-100         | 3         | 6.12%   |
| Unknown        | 2         | 4.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 42.86%  |
| 21-50          | 7         | 14.29%  |
| 101-250        | 6         | 12.24%  |
| 501-1000       | 4         | 8.16%   |
| 51-100         | 4         | 8.16%   |
| 251-500        | 2         | 4.08%   |
| 1001-2000      | 2         | 4.08%   |
| Unknown        | 2         | 4.08%   |
| More than 3000 | 1         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB   | 1         | 1      | 33.33%  |
| WDC WD20EZRX-00D8PB0 2TB   | 1         | 1      | 33.33%  |
| Fujitsu MJA2500BH G1 500GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Fujitsu | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Fujitsu | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Works    | 30        | 47     | 54.55%  |
| Detected | 22        | 35     | 40%     |
| Malfunc  | 3         | 3      | 5.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 25        | 39.06%  |
| Samsung Electronics          | 12        | 18.75%  |
| AMD                          | 9         | 14.06%  |
| Sandisk                      | 3         | 4.69%   |
| Phison Electronics           | 3         | 4.69%   |
| ADATA Technology             | 3         | 4.69%   |
| Toshiba America Info Systems | 2         | 3.13%   |
| SK Hynix                     | 2         | 3.13%   |
| VIA Technologies             | 1         | 1.56%   |
| Micron/Crucial Technology    | 1         | 1.56%   |
| KIOXIA                       | 1         | 1.56%   |
| JMicron Technology           | 1         | 1.56%   |
| ASMedia Technology           | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 11.43%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 5.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.86%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.86%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.86%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 2.86%   |
| ADATA Non-Volatile memory controller                                           | 2         | 2.86%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 1.43%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.43%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 1.43%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.43%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.43%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.43%   |
| JMicron JMB368 IDE controller                                                  | 1         | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.43%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.43%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.43%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.43%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.43%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 30        | 50%     |
| NVMe | 25        | 41.67%  |
| IDE  | 3         | 5%      |
| RAID | 2         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 73.47%  |
| AMD    | 13        | 26.53%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 6.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.08%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 4.08%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 4.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.08%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 4.08%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 2.04%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 2.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2.04%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 2.04%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.04%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 2.04%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 2.04%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 2.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.04%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 2.04%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 2.04%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 2.04%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 1         | 2.04%   |
| Intel Celeron N5100 @ 1.10GHz                 | 1         | 2.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.04%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 2.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.04%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 1         | 2.04%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 2.04%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 1         | 2.04%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 2.04%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 2.04%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 2.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 1         | 2.04%   |
| AMD Phenom II X4 B25 Processor                | 1         | 2.04%   |
| AMD A8-5500 APU with Radeon HD Graphics       | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 12        | 24.49%  |
| Intel Core i7    | 8         | 16.33%  |
| Other            | 7         | 14.29%  |
| AMD Ryzen 5      | 6         | 12.24%  |
| Intel Celeron    | 3         | 6.12%   |
| AMD Ryzen 7      | 3         | 6.12%   |
| Intel Core 2 Duo | 2         | 4.08%   |
| Intel Atom       | 2         | 4.08%   |
| Intel Pentium    | 1         | 2.04%   |
| Intel Core i3    | 1         | 2.04%   |
| AMD Ryzen 9      | 1         | 2.04%   |
| AMD Ryzen 3      | 1         | 2.04%   |
| AMD Phenom II X4 | 1         | 2.04%   |
| AMD A8           | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 46.94%  |
| 2      | 12        | 24.49%  |
| 8      | 8         | 16.33%  |
| 6      | 6         | 12.24%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 35        | 71.43%  |
| 1      | 14        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 5         | 10.2%   |
| 0x306c3    | 4         | 8.16%   |
| 0xa0652    | 3         | 6.12%   |
| 0x806ea    | 3         | 6.12%   |
| 0x40651    | 2         | 4.08%   |
| 0x306a9    | 2         | 4.08%   |
| 0x0a50000c | 2         | 4.08%   |
| 0x08701021 | 2         | 4.08%   |
| 0x0810100b | 2         | 4.08%   |
| 0xa0671    | 1         | 2.04%   |
| 0xa0660    | 1         | 2.04%   |
| 0x906ea    | 1         | 2.04%   |
| 0x906e9    | 1         | 2.04%   |
| 0x906c0    | 1         | 2.04%   |
| 0x806d1    | 1         | 2.04%   |
| 0x706a8    | 1         | 2.04%   |
| 0x506e3    | 1         | 2.04%   |
| 0x506c9    | 1         | 2.04%   |
| 0x406e3    | 1         | 2.04%   |
| 0x406c4    | 1         | 2.04%   |
| 0x306d4    | 1         | 2.04%   |
| 0x30678    | 1         | 2.04%   |
| 0x20655    | 1         | 2.04%   |
| 0x20652    | 1         | 2.04%   |
| 0x1067a    | 1         | 2.04%   |
| 0x10676    | 1         | 2.04%   |
| 0x08608103 | 1         | 2.04%   |
| 0x08608102 | 1         | 2.04%   |
| 0x08108109 | 1         | 2.04%   |
| 0x0800820d | 1         | 2.04%   |
| 0x06001119 | 1         | 2.04%   |
| 0x010000c6 | 1         | 2.04%   |
| Unknown    | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 6         | 12.24%  |
| TigerLake     | 5         | 10.2%   |
| KabyLake      | 5         | 10.2%   |
| CometLake     | 4         | 8.16%   |
| Zen 3         | 3         | 6.12%   |
| Zen+          | 2         | 4.08%   |
| Zen 2         | 2         | 4.08%   |
| Zen           | 2         | 4.08%   |
| Westmere      | 2         | 4.08%   |
| Skylake       | 2         | 4.08%   |
| Silvermont    | 2         | 4.08%   |
| Penryn        | 2         | 4.08%   |
| IvyBridge     | 2         | 4.08%   |
| Icelake       | 2         | 4.08%   |
| Unknown       | 2         | 4.08%   |
| Tremont       | 1         | 2.04%   |
| Piledriver    | 1         | 2.04%   |
| K10           | 1         | 2.04%   |
| Goldmont plus | 1         | 2.04%   |
| Goldmont      | 1         | 2.04%   |
| Broadwell     | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 51.72%  |
| AMD    | 17        | 29.31%  |
| Nvidia | 11        | 18.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 8.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 6.9%    |
| Intel UHD Graphics 620                                                                   | 3         | 5.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 5.17%   |
| AMD Cezanne                                                                              | 3         | 5.17%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 3.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 3.45%   |
| AMD Lucienne                                                                             | 2         | 3.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 1.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.72%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 1.72%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.72%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 1.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.72%   |
| Intel HD Graphics 530                                                                    | 1         | 1.72%   |
| Intel HD Graphics 500                                                                    | 1         | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.72%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.72%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.72%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.72%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1         | 1.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 44.9%   |
| 1 x AMD        | 15        | 30.61%  |
| Intel + Nvidia | 6         | 12.24%  |
| 1 x Nvidia     | 4         | 8.16%   |
| Intel + AMD    | 1         | 2.04%   |
| AMD + Nvidia   | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 88%     |
| Proprietary | 5         | 10%     |
| Unknown     | 1         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 53.06%  |
| 3.01-4.0   | 7         | 14.29%  |
| 1.01-2.0   | 7         | 14.29%  |
| 0.01-0.5   | 5         | 10.2%   |
| 7.01-8.0   | 2         | 4.08%   |
| 0.51-1.0   | 2         | 4.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 8         | 15.38%  |
| BOE                  | 6         | 11.54%  |
| LG Display           | 5         | 9.62%   |
| Ancor Communications | 5         | 9.62%   |
| AOC                  | 4         | 7.69%   |
| Sharp                | 3         | 5.77%   |
| InfoVision           | 3         | 5.77%   |
| Hewlett-Packard      | 3         | 5.77%   |
| Goldstar             | 3         | 5.77%   |
| Dell                 | 3         | 5.77%   |
| Chimei Innolux       | 3         | 5.77%   |
| Samsung Electronics  | 2         | 3.85%   |
| Philips              | 1         | 1.92%   |
| Lenovo               | 1         | 1.92%   |
| Gigabyte Technology  | 1         | 1.92%   |
| Apple                | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 2         | 3.77%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 1.89%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.89%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch               | 1         | 1.89%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 1.89%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch  | 1         | 1.89%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.89%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 1.89%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 1.89%   |
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                   | 1         | 1.89%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch          | 1         | 1.89%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch          | 1         | 1.89%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch          | 1         | 1.89%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch            | 1         | 1.89%   |
| Hewlett-Packard E223 HPN345B 1920x1080 480x270mm 21.7-inch            | 1         | 1.89%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 1         | 1.89%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                  | 1         | 1.89%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1         | 1.89%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                 | 1         | 1.89%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 1.89%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1         | 1.89%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 1         | 1.89%   |
| Dell E2216H DELF069 1920x1080 480x270mm 21.7-inch                     | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1345 1920x1080 293x165mm 13.2-inch      | 1         | 1.89%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE0922 1920x550                                      | 1         | 1.89%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE06FA 1920x1080 294x165mm 13.3-inch                 | 1         | 1.89%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO572D 1920x1080 293x165mm 13.2-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 216x136mm 10.0-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO22ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch         | 1         | 1.89%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                      | 1         | 1.89%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                      | 1         | 1.89%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 1         | 1.89%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1         | 1.89%   |
| AOC 2043 AOC2043 1600x900 443x249mm 20.0-inch                         | 1         | 1.89%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 1         | 1.89%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 1         | 1.89%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 60.42%  |
| 1920x1200 (WUXGA)  | 4         | 8.33%   |
| 1366x768 (WXGA)    | 4         | 8.33%   |
| 1600x900 (HD+)     | 3         | 6.25%   |
| 2560x1440 (QHD)    | 2         | 4.17%   |
| 3840x2400          | 1         | 2.08%   |
| 3840x2160 (4K)     | 1         | 2.08%   |
| 3840x1600          | 1         | 2.08%   |
| 2256x1504          | 1         | 2.08%   |
| 1920x550           | 1         | 2.08%   |
| 1680x1050 (WSXGA+) | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 11        | 21.15%  |
| 15      | 9         | 17.31%  |
| 24      | 7         | 13.46%  |
| 23      | 5         | 9.62%   |
| 21      | 5         | 9.62%   |
| 27      | 3         | 5.77%   |
| 14      | 3         | 5.77%   |
| 17      | 2         | 3.85%   |
| 37      | 1         | 1.92%   |
| 31      | 1         | 1.92%   |
| 20      | 1         | 1.92%   |
| 12      | 1         | 1.92%   |
| 11      | 1         | 1.92%   |
| 10      | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 29.41%  |
| 501-600     | 13        | 25.49%  |
| 201-300     | 11        | 21.57%  |
| 401-500     | 7         | 13.73%  |
| 351-400     | 2         | 3.92%   |
| 801-900     | 1         | 1.96%   |
| 601-700     | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 78.26%  |
| 16/10 | 6         | 13.04%  |
| 3/2   | 2         | 4.35%   |
| 32/9  | 1         | 2.17%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 11        | 22%     |
| 101-110        | 9         | 18%     |
| 81-90          | 7         | 14%     |
| 71-80          | 7         | 14%     |
| 301-350        | 3         | 6%      |
| 151-200        | 3         | 6%      |
| 351-500        | 2         | 4%      |
| 251-300        | 2         | 4%      |
| 121-130        | 2         | 4%      |
| 61-70          | 1         | 2%      |
| 51-60          | 1         | 2%      |
| 41-50          | 1         | 2%      |
| Unknown        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 33.33%  |
| 51-100        | 16        | 31.37%  |
| 161-240       | 9         | 17.65%  |
| 101-120       | 7         | 13.73%  |
| More than 240 | 1         | 1.96%   |
| Unknown       | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 76%     |
| 2     | 7         | 14%     |
| 0     | 4         | 8%      |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 30        | 43.48%  |
| Realtek Semiconductor             | 23        | 33.33%  |
| Qualcomm Atheros                  | 4         | 5.8%    |
| Microsoft                         | 2         | 2.9%    |
| MEDIATEK                          | 2         | 2.9%    |
| Broadcom                          | 2         | 2.9%    |
| Belkin Components                 | 2         | 2.9%    |
| Ralink Technology                 | 1         | 1.45%   |
| MicroPython                       | 1         | 1.45%   |
| Marvell Technology Group          | 1         | 1.45%   |
| Ericsson Business Mobile Networks | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 16        | 20.25%  |
| Intel Wi-Fi 6 AX200                                                | 5         | 6.33%   |
| Intel Wi-Fi 6 AX201                                                | 4         | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                  | 3         | 3.8%    |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 3.8%    |
| Microsoft Xbox 360 Wireless Adapter                                | 2         | 2.53%   |
| Intel Wireless 8265 / 8275                                         | 2         | 2.53%   |
| Intel Wireless 7260                                                | 2         | 2.53%   |
| Intel Wireless 3165                                                | 2         | 2.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 2.53%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 2.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.27%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.27%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.27%   |
| MicroPython Board in FS mode                                       | 1         | 1.27%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1         | 1.27%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 1.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 1.27%   |
| Intel Wireless 8260                                                | 1         | 1.27%   |
| Intel Wireless 3160                                                | 1         | 1.27%   |
| Intel WiFi Link 5100                                               | 1         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 1.27%   |
| Intel Ethernet Controller I225-V                                   | 1         | 1.27%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection I217-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                               | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 1.27%   |
| Intel 82578DM Gigabit Network Connection                           | 1         | 1.27%   |
| Ericsson Business Mobile Networks N5321 gw                         | 1         | 1.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                  | 1         | 1.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 1.27%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 61.36%  |
| Realtek Semiconductor | 4         | 9.09%   |
| Qualcomm Atheros      | 4         | 9.09%   |
| Microsoft             | 2         | 4.55%   |
| MEDIATEK              | 2         | 4.55%   |
| Broadcom              | 2         | 4.55%   |
| Belkin Components     | 2         | 4.55%   |
| Ralink Technology     | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                | 5         | 11.36%  |
| Intel Wi-Fi 6 AX201                                                | 4         | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 6.82%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2         | 4.55%   |
| Intel Wireless 8265 / 8275                                         | 2         | 4.55%   |
| Intel Wireless 7260                                                | 2         | 4.55%   |
| Intel Wireless 3165                                                | 2         | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 4.55%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 2.27%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 2.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 2.27%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 2.27%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1         | 2.27%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 2.27%   |
| Intel Wireless 8260                                                | 1         | 2.27%   |
| Intel Wireless 3160                                                | 1         | 2.27%   |
| Intel WiFi Link 5100                                               | 1         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 2.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 2.27%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 62.5%   |
| Intel                    | 10        | 31.25%  |
| Marvell Technology Group | 1         | 3.13%   |
| Broadcom                 | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 48.48%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 3.03%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 3.03%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.03%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 3.03%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 3.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 54.05%  |
| Ethernet | 32        | 43.24%  |
| Modem    | 2         | 2.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 66.04%  |
| Ethernet | 18        | 33.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 46.94%  |
| 1     | 23        | 46.94%  |
| 0     | 3         | 6.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 63.27%  |
| Yes  | 18        | 36.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 70.59%  |
| Qualcomm Atheros Communications | 3         | 8.82%   |
| Realtek Semiconductor           | 2         | 5.88%   |
| Lite-On Technology              | 2         | 5.88%   |
| MediaTek                        | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |
| Apple                           | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 11        | 32.35%  |
| Intel Bluetooth wireless interface                  | 5         | 14.71%  |
| Intel AX200 Bluetooth                               | 5         | 14.71%  |
| Intel AX210 Bluetooth                               | 2         | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.94%   |
| Realtek Bluetooth Radio                             | 1         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.94%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 2.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.94%   |
| MediaTek Wireless_Device                            | 1         | 2.94%   |
| Lite-On Wireless_Device                             | 1         | 2.94%   |
| Lite-On Bluetooth Device                            | 1         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 51.52%  |
| AMD                      | 17        | 25.76%  |
| Nvidia                   | 10        | 15.15%  |
| C-Media Electronics      | 2         | 3.03%   |
| Texas Instruments        | 1         | 1.52%   |
| Plantronics              | 1         | 1.52%   |
| Micro Star International | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 7         | 8.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 5         | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                     | 4         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 5%      |
| AMD Renoir Radeon High Definition Audio Controller                  | 4         | 5%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 4         | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 3         | 3.75%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 3.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 3         | 3.75%   |
| Nvidia Audio device                                                 | 2         | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 2.5%    |
| Intel 8 Series HD Audio Controller                                  | 2         | 2.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 2.5%    |
| Texas Instruments PCM2903B Audio CODEC                              | 1         | 1.25%   |
| Plantronics Blackwire 325.1                                         | 1         | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 1.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.25%   |
| Micro Star International USB Audio                                  | 1         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 1.25%   |
| Intel Jasper Lake HD Audio                                          | 1         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.25%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 1.25%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 1.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 1.25%   |
| C-Media Electronics MAXTER 7.1                                      | 1         | 1.25%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 1.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                | 1         | 1.25%   |
| AMD FCH Azalia Controller                                           | 1         | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 18.6%   |
| SK Hynix            | 7         | 16.28%  |
| Micron Technology   | 7         | 16.28%  |
| Unknown             | 4         | 9.3%    |
| Crucial             | 4         | 9.3%    |
| Kingston            | 3         | 6.98%   |
| Unknown (ABCD)      | 2         | 4.65%   |
| V-GeN               | 1         | 2.33%   |
| Silicon Power       | 1         | 2.33%   |
| Sesame              | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Mushkin             | 1         | 2.33%   |
| GOODRAM             | 1         | 2.33%   |
| G.Skill             | 1         | 2.33%   |
| A-DATA Technology   | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.55%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s                    | 1         | 2.27%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 2.27%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 2.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 2.27%   |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 2.27%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.27%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| SK Hynix RAM H5TC8G63AMR-PBR 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s     | 1         | 2.27%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                | 1         | 2.27%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 2.27%   |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.27%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s              | 1         | 2.27%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.27%   |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s               | 1         | 2.27%   |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s            | 1         | 2.27%   |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 2.27%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                       | 1         | 2.27%   |
| Micron RAM Module 3GB Row Of Chips LPDDR4 1867MT/s               | 1         | 2.27%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 2.27%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s              | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.27%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.27%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 1         | 2.27%   |
| Kingston RAM 99U5471-034.A 4GB DIMM DDR3 667MT/s                 | 1         | 2.27%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 2.27%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s             | 1         | 2.27%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s         | 1         | 2.27%   |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s            | 1         | 2.27%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s         | 1         | 2.27%   |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s        | 1         | 2.27%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s        | 1         | 2.27%   |
| A-DATA RAM AD4S3200J4G22-B 4GB SODIMM DDR4 3200MT/s              | 1         | 2.27%   |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                  | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 44.12%  |
| DDR3    | 10        | 29.41%  |
| LPDDR4  | 5         | 14.71%  |
| LPDDR3  | 2         | 5.88%   |
| DDR2    | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 51.43%  |
| DIMM         | 11        | 31.43%  |
| Row Of Chips | 6         | 17.14%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 15        | 39.47%  |
| 8192  | 12        | 31.58%  |
| 2048  | 4         | 10.53%  |
| 32768 | 3         | 7.89%   |
| 16384 | 3         | 7.89%   |
| 3072  | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 7         | 18.42%  |
| 3200    | 6         | 15.79%  |
| 2133    | 5         | 13.16%  |
| 2667    | 4         | 10.53%  |
| 2400    | 4         | 10.53%  |
| 4267    | 2         | 5.26%   |
| 1333    | 2         | 5.26%   |
| 3866    | 1         | 2.63%   |
| 3266    | 1         | 2.63%   |
| 2933    | 1         | 2.63%   |
| 1867    | 1         | 2.63%   |
| 1066    | 1         | 2.63%   |
| 800     | 1         | 2.63%   |
| 667     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

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
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 200 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 6         | 18.75%  |
| Acer                        | 4         | 12.5%   |
| Realtek Semiconductor       | 3         | 9.38%   |
| IMC Networks                | 3         | 9.38%   |
| Syntek                      | 2         | 6.25%   |
| Microdia                    | 2         | 6.25%   |
| USB Camera                  | 1         | 3.13%   |
| Samsung Electronics         | 1         | 3.13%   |
| Ricoh                       | 1         | 3.13%   |
| Quanta                      | 1         | 3.13%   |
| Primax Electronics          | 1         | 3.13%   |
| Microsoft                   | 1         | 3.13%   |
| Luxvisions Innotech Limited | 1         | 3.13%   |
| Logitech                    | 1         | 3.13%   |
| Lite-On Technology          | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |
| Apple                       | 1         | 3.13%   |
| Alcor Micro                 | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 3         | 9.09%   |
| Microdia Integrated_Webcam_HD                    | 2         | 6.06%   |
| IMC Networks Integrated Camera                   | 2         | 6.06%   |
| Acer Integrated Camera                           | 2         | 6.06%   |
| USB Camera USB Camera                            | 1         | 3.03%   |
| Syntek Lenovo EasyCamera                         | 1         | 3.03%   |
| Syntek Integrated Camera                         | 1         | 3.03%   |
| Samsung Galaxy A5 (MTP)                          | 1         | 3.03%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                     | 1         | 3.03%   |
| Realtek Integrated Webcam                        | 1         | 3.03%   |
| Realtek Front Camera                             | 1         | 3.03%   |
| Realtek Back Camera                              | 1         | 3.03%   |
| Quanta HD User Facing                            | 1         | 3.03%   |
| Primax HP HD Webcam [Fixed]                      | 1         | 3.03%   |
| Microsoft LifeCam Cinema                         | 1         | 3.03%   |
| Luxvisions Innotech Limited HP HD Camera         | 1         | 3.03%   |
| Logitech QuickCam Communicate Deluxe             | 1         | 3.03%   |
| Lite-On Integrated Camera                        | 1         | 3.03%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1         | 3.03%   |
| IMC Networks EasyCamera                          | 1         | 3.03%   |
| Chicony HP Wide Vision FHD Camera                | 1         | 3.03%   |
| Chicony HP HD Camera                             | 1         | 3.03%   |
| Chicony HD WebCam                                | 1         | 3.03%   |
| Apple FaceTime HD Camera (Built-in)              | 1         | 3.03%   |
| Alcor Micro USB 2.0 Camera                       | 1         | 3.03%   |
| Acer Lenovo EasyCamera                           | 1         | 3.03%   |
| Acer BisonCam,NB Pro                             | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 60%     |
| Validity Sensors           | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| LighTuning Technology      | 1         | 10%     |
| DigitalPersona             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 10%     |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 10%     |
| DigitalPersona Fingerprint Reader                          | 1         | 10%     |
| Unknown                                                    | 1         | 10%     |

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
| 0     | 29        | 58%     |
| 1     | 16        | 32%     |
| 2     | 3         | 6%      |
| 3     | 2         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 43.48%  |
| Graphics card         | 6         | 26.09%  |
| Multimedia controller | 3         | 13.04%  |
| Net/wireless          | 2         | 8.7%    |
| Sound                 | 1         | 4.35%   |
| Card reader           | 1         | 4.35%   |

