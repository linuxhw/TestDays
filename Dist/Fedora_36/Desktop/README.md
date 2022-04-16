Fedora 36 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 51

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte | Z170-D3H-CF                 | [6a9e2b3174](https://linux-hardware.org/?probe=6a9e2b3174) | Apr 16, 2022 |
| Gigabyte | H110M-H-CF                  | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Acer     | Aspire TC-895 V:1.0         | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Gigabyte | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| Gigabyte | B550 AORUS ELITE            | [abe538f1ed](https://linux-hardware.org/?probe=abe538f1ed) | Apr 14, 2022 |
| ASUSTek  | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI      | FM2-A75IA-E53               | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Gigabyte | Z170MX-Gaming 5             | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Gigabyte | B450 AORUS M                | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte | B450 AORUS M                | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| Dell     | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| Gigabyte | Z170-D3H-CF                 | [33b4ba0b02](https://linux-hardware.org/?probe=33b4ba0b02) | Apr 13, 2022 |
| Gigabyte | Z170-D3H-CF                 | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| MSI      | B450M PRO-VDH PLUS          | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte | Z490 UD                     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar  | B550MH                      | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI      | Z170A XPOWER GAMING TITA... | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| Gigabyte | Z170N-Gaming 5              | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte | Z170N-Gaming 5              | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| ASUSTek  | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Gigabyte | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| Gigabyte | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Dell     | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Gigabyte | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI      | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Gigabyte | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Gigabyte | EP45-DS3L                   | [7879818528](https://linux-hardware.org/?probe=7879818528) | Mar 30, 2022 |
| Gigabyte | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Gigabyte | EP45-DS3L                   | [efdb29ff92](https://linux-hardware.org/?probe=efdb29ff92) | Mar 07, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte | EP45-DS3L                   | [0efde9a187](https://linux-hardware.org/?probe=0efde9a187) | Mar 03, 2022 |
| Gigabyte | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Biostar  | H55 HD                      | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar  | H55 HD                      | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| MSI      | B550M PRO-VDH WIFI          | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell     | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Dell     | 0KC9NP A01                  | [a072a33607](https://linux-hardware.org/?probe=a072a33607) | Oct 12, 2021 |
| MSI      | FM2-A55M-E33                | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI      | FM2-A55M-E33                | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Dell     | 0KC9NP A01                  | [95229554a9](https://linux-hardware.org/?probe=95229554a9) | Sep 19, 2021 |
| Dell     | 0KC9NP A01                  | [d235dcf0d1](https://linux-hardware.org/?probe=d235dcf0d1) | Sep 18, 2021 |
| Dell     | 0KC9NP A01                  | [ad5f2b8ea5](https://linux-hardware.org/?probe=ad5f2b8ea5) | Sep 04, 2021 |
| Dell     | 0KC9NP A01                  | [f191342fa8](https://linux-hardware.org/?probe=f191342fa8) | Sep 02, 2021 |
| Dell     | 0KC9NP A01                  | [270961aa02](https://linux-hardware.org/?probe=270961aa02) | Aug 30, 2021 |
| Dell     | 0KC9NP A01                  | [1257d6c6f4](https://linux-hardware.org/?probe=1257d6c6f4) | Aug 27, 2021 |
| Dell     | 0KC9NP A01                  | [373f7e6861](https://linux-hardware.org/?probe=373f7e6861) | Aug 22, 2021 |
| HP       | 304Ah                       | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell     | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.17.2-300.fc36.x86_64                                        | 11       | 33.33%  |
| 5.17.1-300.fc36.x86_64                                        | 10       | 30.3%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 2        | 6.06%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2        | 6.06%   |
| 5.17.0-300.fc36.x86_64                                        | 1        | 3.03%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 1        | 3.03%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1        | 3.03%   |
| 5.16.17-200.fc35.x86_64                                       | 1        | 3.03%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1        | 3.03%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1        | 3.03%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1        | 3.03%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1        | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.2  | 11       | 34.38%  |
| 5.17.1  | 10       | 31.25%  |
| 5.17.0  | 5        | 15.63%  |
| 5.15.0  | 3        | 9.38%   |
| 5.14.0  | 2        | 6.25%   |
| 5.16.17 | 1        | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 25       | 80.65%  |
| 5.15    | 3        | 9.68%   |
| 5.14    | 2        | 6.45%   |
| 5.16    | 1        | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 30       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 27       | 90%     |
| KDE5    | 2        | 6.67%   |
| Unknown | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 23       | 76.67%  |
| X11     | 5        | 16.67%  |
| Tty     | 2        | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 17       | 56.67%  |
| Unknown | 11       | 36.67%  |
| SDDM    | 2        | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 12       | 40%     |
| en_GB | 5        | 16.67%  |
| ru_RU | 4        | 13.33%  |
| de_DE | 2        | 6.67%   |
| pt_BR | 1        | 3.33%   |
| pl_PL | 1        | 3.33%   |
| it_IT | 1        | 3.33%   |
| fr_FR | 1        | 3.33%   |
| fi_FI | 1        | 3.33%   |
| es_AR | 1        | 3.33%   |
| cs_CZ | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 22       | 73.33%  |
| BIOS | 8        | 26.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 22       | 73.33%  |
| Ext4  | 7        | 23.33%  |
| Xfs   | 1        | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 17       | 56.67%  |
| Unknown | 11       | 36.67%  |
| MBR     | 2        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 93.33%  |
| Yes       | 2        | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 53.33%  |
| Yes       | 14       | 46.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 14       | 46.67%  |
| MSI                 | 6        | 20%     |
| Dell                | 3        | 10%     |
| ASUSTek Computer    | 3        | 10%     |
| Biostar             | 2        | 6.67%   |
| Hewlett-Packard     | 1        | 3.33%   |
| Acer                | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Gigabyte B450 AORUS M       | 2        | 6.67%   |
| MSI MS-7D06                 | 1        | 3.33%   |
| MSI MS-7C95                 | 1        | 3.33%   |
| MSI MS-7A38                 | 1        | 3.33%   |
| MSI MS-7968                 | 1        | 3.33%   |
| MSI MS-7792                 | 1        | 3.33%   |
| MSI MS-7721                 | 1        | 3.33%   |
| HP Compaq 8100 Elite SFF PC | 1        | 3.33%   |
| Gigabyte Z490 UD            | 1        | 3.33%   |
| Gigabyte Z170N-Gaming 5     | 1        | 3.33%   |
| Gigabyte Z170MX-Gaming 5    | 1        | 3.33%   |
| Gigabyte Z170-D3H           | 1        | 3.33%   |
| Gigabyte H81M-S2H           | 1        | 3.33%   |
| Gigabyte H370M-DS3H         | 1        | 3.33%   |
| Gigabyte H110M-H            | 1        | 3.33%   |
| Gigabyte EP45-DS3L          | 1        | 3.33%   |
| Gigabyte B85M-D3V-A         | 1        | 3.33%   |
| Gigabyte B550I AORUS PRO AX | 1        | 3.33%   |
| Gigabyte B550 AORUS ELITE   | 1        | 3.33%   |
| Gigabyte 970A-DS3P          | 1        | 3.33%   |
| Dell Precision Tower 7810   | 1        | 3.33%   |
| Dell OptiPlex 9020          | 1        | 3.33%   |
| Dell Inspiron 3847          | 1        | 3.33%   |
| Biostar H55 HD              | 1        | 3.33%   |
| Biostar B550MH              | 1        | 3.33%   |
| ASUS TUF GAMING B550M-PLUS  | 1        | 3.33%   |
| ASUS P8P67 LE               | 1        | 3.33%   |
| ASUS B150M-K                | 1        | 3.33%   |
| Acer Aspire TC-895          | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B450          | 2        | 6.67%   |
| MSI MS-7D06            | 1        | 3.33%   |
| MSI MS-7C95            | 1        | 3.33%   |
| MSI MS-7A38            | 1        | 3.33%   |
| MSI MS-7968            | 1        | 3.33%   |
| MSI MS-7792            | 1        | 3.33%   |
| MSI MS-7721            | 1        | 3.33%   |
| HP Compaq              | 1        | 3.33%   |
| Gigabyte Z490          | 1        | 3.33%   |
| Gigabyte Z170N-Gaming  | 1        | 3.33%   |
| Gigabyte Z170MX-Gaming | 1        | 3.33%   |
| Gigabyte Z170-D3H      | 1        | 3.33%   |
| Gigabyte H81M-S2H      | 1        | 3.33%   |
| Gigabyte H370M-DS3H    | 1        | 3.33%   |
| Gigabyte H110M-H       | 1        | 3.33%   |
| Gigabyte EP45-DS3L     | 1        | 3.33%   |
| Gigabyte B85M-D3V-A    | 1        | 3.33%   |
| Gigabyte B550I         | 1        | 3.33%   |
| Gigabyte B550          | 1        | 3.33%   |
| Gigabyte 970A-DS3P     | 1        | 3.33%   |
| Dell Precision         | 1        | 3.33%   |
| Dell OptiPlex          | 1        | 3.33%   |
| Dell Inspiron          | 1        | 3.33%   |
| Biostar H55            | 1        | 3.33%   |
| Biostar B550MH         | 1        | 3.33%   |
| ASUS TUF               | 1        | 3.33%   |
| ASUS P8P67             | 1        | 3.33%   |
| ASUS B150M-K           | 1        | 3.33%   |
| Acer Aspire            | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 20%     |
| 2016 | 4        | 13.33%  |
| 2015 | 4        | 13.33%  |
| 2013 | 4        | 13.33%  |
| 2018 | 3        | 10%     |
| 2022 | 1        | 3.33%   |
| 2021 | 1        | 3.33%   |
| 2019 | 1        | 3.33%   |
| 2017 | 1        | 3.33%   |
| 2014 | 1        | 3.33%   |
| 2011 | 1        | 3.33%   |
| 2010 | 1        | 3.33%   |
| 2009 | 1        | 3.33%   |
| 2008 | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 96.67%  |
| Enabled  | 1        | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 8        | 26.67%  |
| 16.01-24.0  | 7        | 23.33%  |
| 32.01-64.0  | 6        | 20%     |
| 4.01-8.0    | 3        | 10%     |
| 3.01-4.0    | 3        | 10%     |
| 64.01-256.0 | 3        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 8        | 25.81%  |
| 2.01-3.0  | 8        | 25.81%  |
| 3.01-4.0  | 7        | 22.58%  |
| 8.01-16.0 | 4        | 12.9%   |
| 1.01-2.0  | 3        | 9.68%   |
| 0.51-1.0  | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 26.67%  |
| 3      | 7        | 23.33%  |
| 1      | 7        | 23.33%  |
| 4      | 6        | 20%     |
| 5      | 2        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 60%     |
| Yes       | 12       | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 56.67%  |
| No        | 13       | 43.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 63.33%  |
| Yes       | 11       | 36.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 6        | 20%     |
| Belarus     | 3        | 10%     |
| UK          | 2        | 6.67%   |
| Germany     | 2        | 6.67%   |
| Brazil      | 2        | 6.67%   |
| Switzerland | 1        | 3.33%   |
| Sweden      | 1        | 3.33%   |
| Spain       | 1        | 3.33%   |
| Russia      | 1        | 3.33%   |
| Poland      | 1        | 3.33%   |
| Netherlands | 1        | 3.33%   |
| Italy       | 1        | 3.33%   |
| Indonesia   | 1        | 3.33%   |
| India       | 1        | 3.33%   |
| France      | 1        | 3.33%   |
| Finland     | 1        | 3.33%   |
| Czechia     | 1        | 3.33%   |
| Belgium     | 1        | 3.33%   |
| Bangladesh  | 1        | 3.33%   |
| Argentina   | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Minsk         | 3        | 10%     |
| Allen         | 2        | 6.67%   |
| Zurich        | 1        | 3.33%   |
| Warsaw        | 1        | 3.33%   |
| Vigodarzere   | 1        | 3.33%   |
| Turku         | 1        | 3.33%   |
| Tarragona     | 1        | 3.33%   |
| St Petersburg | 1        | 3.33%   |
| Sollentuna    | 1        | 3.33%   |
| Soddy-Daisy   | 1        | 3.33%   |
| Sao Paulo     | 1        | 3.33%   |
| Liverpool     | 1        | 3.33%   |
| Kanne         | 1        | 3.33%   |
| Jakarta       | 1        | 3.33%   |
| Houston       | 1        | 3.33%   |
| Halstead      | 1        | 3.33%   |
| Goiânia      | 1        | 3.33%   |
| Folsom        | 1        | 3.33%   |
| Dhaka         | 1        | 3.33%   |
| Delft         | 1        | 3.33%   |
| Buenos Aires  | 1        | 3.33%   |
| Brooklyn      | 1        | 3.33%   |
| Brno          | 1        | 3.33%   |
| Brest         | 1        | 3.33%   |
| Bonn          | 1        | 3.33%   |
| Blankenburg   | 1        | 3.33%   |
| Bhopal        | 1        | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 31     | 29.03%  |
| WDC                 | 11       | 15     | 17.74%  |
| Seagate             | 11       | 12     | 17.74%  |
| Kingston            | 7        | 7      | 11.29%  |
| Toshiba             | 6        | 6      | 9.68%   |
| Phison              | 2        | 2      | 3.23%   |
| XPG                 | 1        | 2      | 1.61%   |
| Unknown             | 1        | 1      | 1.61%   |
| PNY                 | 1        | 2      | 1.61%   |
| Intel               | 1        | 1      | 1.61%   |
| HGST                | 1        | 1      | 1.61%   |
| Crucial             | 1        | 1      | 1.61%   |
| China               | 1        | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 3        | 4.17%   |
| Samsung SSD 870 QVO 2TB             | 3        | 4.17%   |
| Samsung SSD 850 EVO 250GB           | 3        | 4.17%   |
| Kingston SA400S37240G 240GB SSD     | 3        | 4.17%   |
| Samsung SSD 970 EVO 250GB           | 2        | 2.78%   |
| Samsung SSD 860 EVO 500GB           | 2        | 2.78%   |
| Samsung SSD 850 EVO 500GB           | 2        | 2.78%   |
| Samsung NVMe SSD Drive 500GB        | 2        | 2.78%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 2.78%   |
| XPG GAMMIX S11 Pro 512GB            | 1        | 1.39%   |
| WDC WDS500G1B0C-00S6U0 500GB        | 1        | 1.39%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1        | 1.39%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1        | 1.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 1.39%   |
| WDC WD6400AAKS-22A7B2 640GB         | 1        | 1.39%   |
| WDC WD5000LPLX-75ZNTT0 500GB        | 1        | 1.39%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1.39%   |
| WDC WD40EZRZ-00WN9B0 4TB            | 1        | 1.39%   |
| WDC WD30EZRX-00SPEB0 3TB            | 1        | 1.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1.39%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1.39%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.39%   |
| WDC WD10EZEX-00ZF5A0 1TB            | 1        | 1.39%   |
| Unknown SD/MMC/MS PRO 394GB         | 1        | 1.39%   |
| Toshiba TR200 240GB SSD             | 1        | 1.39%   |
| Toshiba THNSNJ128GCSU 128GB SSD     | 1        | 1.39%   |
| Toshiba MQ04ABF100 1TB              | 1        | 1.39%   |
| Toshiba MQ01ABD050 500GB            | 1        | 1.39%   |
| Toshiba HDWD120 2TB                 | 1        | 1.39%   |
| Toshiba HDWD110 1TB                 | 1        | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1.39%   |
| Seagate ST4000DM005-2DP166 4TB      | 1        | 1.39%   |
| Seagate ST4000DM000-1F2168 4TB      | 1        | 1.39%   |
| Seagate ST3500413AS 500GB           | 1        | 1.39%   |
| Seagate ST31000528AS 1TB            | 1        | 1.39%   |
| Seagate ST2000DM009-2G4100 2TB      | 1        | 1.39%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1.39%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1.39%   |
| Samsung SSD SM871 2.5 7mm 256GB     | 1        | 1.39%   |
| Samsung SSD 970 EVO Plus 500GB      | 1        | 1.39%   |
| Samsung SSD 870 EVO 2TB             | 1        | 1.39%   |
| Samsung SSD 860 EVO 2TB             | 1        | 1.39%   |
| Samsung SSD 860 EVO 250GB           | 1        | 1.39%   |
| Samsung SSD 850 EVO 1TB             | 1        | 1.39%   |
| Samsung SSD 840 EVO 250GB           | 1        | 1.39%   |
| Samsung SSD 840 EVO 1TB             | 1        | 1.39%   |
| Samsung NVMe SSD Drive 512GB        | 1        | 1.39%   |
| Samsung NVMe SSD Drive 2TB          | 1        | 1.39%   |
| PNY CS900 500GB SSD                 | 1        | 1.39%   |
| PNY CS900 240GB SSD                 | 1        | 1.39%   |
| Phison NVMe SSD Drive 512GB         | 1        | 1.39%   |
| Phison NVMe SSD Drive 240GB         | 1        | 1.39%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1.39%   |
| Kingston NVMe SSD Drive 2TB         | 1        | 1.39%   |
| Intel NVMe SSD Drive 128GB          | 1        | 1.39%   |
| HGST HUS726T6TALE6L4 6TB            | 1        | 1.39%   |
| Crucial CT1000MX500SSD1 1TB         | 1        | 1.39%   |
| China SATA SSD 240GB                | 1        | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 12     | 44%     |
| WDC     | 8        | 11     | 32%     |
| Toshiba | 4        | 4      | 16%     |
| Unknown | 1        | 1      | 4%      |
| HGST    | 1        | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 23     | 48.15%  |
| Kingston            | 6        | 6      | 22.22%  |
| WDC                 | 3        | 3      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| PNY                 | 1        | 2      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |
| China               | 1        | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 22       | 38     | 40.74%  |
| HDD  | 22       | 29     | 40.74%  |
| NVMe | 10       | 15     | 18.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 66     | 71.05%  |
| NVMe | 10       | 15     | 26.32%  |
| SAS  | 1        | 1      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 31     | 41.3%   |
| 0.51-1.0   | 14       | 17     | 30.43%  |
| 1.01-2.0   | 8        | 13     | 17.39%  |
| 3.01-4.0   | 3        | 4      | 6.52%   |
| 2.01-3.0   | 1        | 1      | 2.17%   |
| 4.01-10.0  | 1        | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 6        | 20%     |
| 501-1000       | 6        | 20%     |
| 251-500        | 5        | 16.67%  |
| 101-250        | 5        | 16.67%  |
| 2001-3000      | 3        | 10%     |
| 1001-2000      | 3        | 10%     |
| 1-20           | 1        | 3.33%   |
| Unknown        | 1        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 5        | 16.67%  |
| 1001-2000      | 5        | 16.67%  |
| 1-20           | 5        | 16.67%  |
| 251-500        | 4        | 13.33%  |
| 101-250        | 4        | 13.33%  |
| More than 3000 | 2        | 6.67%   |
| 501-1000       | 2        | 6.67%   |
| 2001-3000      | 1        | 3.33%   |
| 51-100         | 1        | 3.33%   |
| Unknown        | 1        | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB            | 1        | 1      | 25%     |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1      | 25%     |
| Seagate ST31000528AS 1TB            | 1        | 1      | 25%     |
| Samsung Electronics SSD 870 EVO 2TB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 50%     |
| Seagate             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Works    | 18       | 48     | 54.55%  |
| Detected | 11       | 30     | 33.33%  |
| Malfunc  | 4        | 4      | 12.12%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 19       | 41.3%   |
| AMD                         | 11       | 23.91%  |
| Samsung Electronics         | 6        | 13.04%  |
| Phison Electronics          | 2        | 4.35%   |
| ASMedia Technology          | 2        | 4.35%   |
| VIA Technologies            | 1        | 2.17%   |
| Sandisk                     | 1        | 2.17%   |
| Marvell Technology Group    | 1        | 2.17%   |
| Kingston Technology Company | 1        | 2.17%   |
| JMicron Technology          | 1        | 2.17%   |
| ADATA Technology            | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 11.11%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 9.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 9.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 7.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 5.56%   |
| Phison E12 NVMe Controller                                                     | 2        | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 3.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 3.7%    |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 1.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.85%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.85%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 1.85%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 1.85%   |
| Kingston Company KC2000 NVMe SSD                                               | 1        | 1.85%   |
| JMicron JMB368 IDE controller                                                  | 1        | 1.85%   |
| Intel SSD 600P Series                                                          | 1        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.85%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 65.85%  |
| NVMe | 10       | 24.39%  |
| IDE  | 4        | 9.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 63.33%  |
| AMD    | 11       | 36.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-6600K CPU @ 3.50GHz       | 2        | 6.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 2        | 6.67%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 6.67%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 1        | 3.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 3.33%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1        | 3.33%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 3.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 3.33%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1        | 3.33%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1        | 3.33%   |
| Intel Core i5-10600K CPU @ 4.10GHz      | 1        | 3.33%   |
| Intel Core i3-7100 CPU @ 3.90GHz        | 1        | 3.33%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 3.33%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 1        | 3.33%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 1        | 3.33%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1        | 3.33%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 1        | 3.33%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1        | 3.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 1        | 3.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 3.33%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 1        | 3.33%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 1        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1        | 3.33%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 1        | 3.33%   |
| AMD Phenom II X4 B25 Processor          | 1        | 3.33%   |
| AMD Athlon X4 760K Quad Core Processor  | 1        | 3.33%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 10       | 33.33%  |
| AMD Ryzen 5      | 4        | 13.33%  |
| Intel Core i7    | 3        | 10%     |
| Intel Core i3    | 3        | 10%     |
| AMD Ryzen 7      | 3        | 10%     |
| Other            | 1        | 3.33%   |
| Intel Xeon       | 1        | 3.33%   |
| Intel Core 2 Duo | 1        | 3.33%   |
| AMD Ryzen 9      | 1        | 3.33%   |
| AMD Phenom II X4 | 1        | 3.33%   |
| AMD Athlon X4    | 1        | 3.33%   |
| AMD A8           | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 36.67%  |
| 2      | 7        | 23.33%  |
| 6      | 6        | 20%     |
| 8      | 4        | 13.33%  |
| 16     | 1        | 3.33%   |
| 12     | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 96.67%  |
| 2      | 1        | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 70%     |
| 1      | 9        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 30       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 4        | 13.33%  |
| 0x306c3    | 4        | 13.33%  |
| 0x906e9    | 2        | 6.67%   |
| 0x08701021 | 2        | 6.67%   |
| 0x0800820d | 2        | 6.67%   |
| Unknown    | 2        | 6.67%   |
| 0xa0671    | 1        | 3.33%   |
| 0xa0655    | 1        | 3.33%   |
| 0xa0653    | 1        | 3.33%   |
| 0x906ea    | 1        | 3.33%   |
| 0x306f2    | 1        | 3.33%   |
| 0x206a7    | 1        | 3.33%   |
| 0x20655    | 1        | 3.33%   |
| 0x20652    | 1        | 3.33%   |
| 0x1067a    | 1        | 3.33%   |
| 0x0a50000c | 1        | 3.33%   |
| 0x0a201205 | 1        | 3.33%   |
| 0x0a201016 | 1        | 3.33%   |
| 0x06001119 | 1        | 3.33%   |
| 0x010000c6 | 1        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 5        | 16.67%  |
| Zen 3       | 4        | 13.33%  |
| Skylake     | 4        | 13.33%  |
| KabyLake    | 3        | 10%     |
| Zen+        | 2        | 6.67%   |
| Zen 2       | 2        | 6.67%   |
| Westmere    | 2        | 6.67%   |
| Piledriver  | 2        | 6.67%   |
| CometLake   | 2        | 6.67%   |
| SandyBridge | 1        | 3.33%   |
| Penryn      | 1        | 3.33%   |
| K10         | 1        | 3.33%   |
| Icelake     | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 39.39%  |
| AMD    | 12       | 36.36%  |
| Intel  | 8        | 24.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 18.18%  |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 6.06%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 6.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 6.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 3.03%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 3.03%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 3.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.03%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 3.03%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 3.03%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.03%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 3.03%   |
| Intel HD Graphics 530                                                       | 1        | 3.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.03%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 3.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.03%   |
| AMD Cezanne                                                                 | 1        | 3.03%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.03%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 12       | 40%     |
| 1 x AMD        | 12       | 40%     |
| 1 x Intel      | 5        | 16.67%  |
| Intel + Nvidia | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 73.33%  |
| Proprietary | 8        | 26.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 36.67%  |
| 3.01-4.0   | 8        | 26.67%  |
| 7.01-8.0   | 5        | 16.67%  |
| 1.01-2.0   | 2        | 6.67%   |
| 0.51-1.0   | 2        | 6.67%   |
| 5.01-6.0   | 1        | 3.33%   |
| 8.01-16.0  | 1        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 6        | 16.67%  |
| AOC                  | 5        | 13.89%  |
| Samsung Electronics  | 4        | 11.11%  |
| Philips              | 4        | 11.11%  |
| Ancor Communications | 3        | 8.33%   |
| Marantz              | 2        | 5.56%   |
| Hewlett-Packard      | 2        | 5.56%   |
| BenQ                 | 2        | 5.56%   |
| Acer                 | 2        | 5.56%   |
| Medion               | 1        | 2.78%   |
| Lenovo               | 1        | 2.78%   |
| Iiyama               | 1        | 2.78%   |
| Gigabyte Technology  | 1        | 2.78%   |
| DMG                  | 1        | 2.78%   |
| Dell                 | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch                  | 2        | 5.56%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                  | 2        | 5.56%   |
| Samsung Electronics SyncMaster SAM049B 1920x1080 477x268mm 21.5-inch  | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 2.78%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 2.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 2.78%   |
| Philips PHL 278E1 PHLC217 3840x2160 597x336mm 27.0-inch               | 1        | 2.78%   |
| Philips PHL 276E8V PHLC18F 1920x1080 597x336mm 27.0-inch              | 1        | 2.78%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 2.78%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1        | 2.78%   |
| Medion MD21473 MED461C 2560x1440 597x336mm 27.0-inch                  | 1        | 2.78%   |
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                   | 1        | 2.78%   |
| Iiyama PL3270Q IVM7608 2560x1440 698x393mm 31.5-inch                  | 1        | 2.78%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch            | 1        | 2.78%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 1        | 2.78%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1        | 2.78%   |
| Goldstar ULTRAGEAR GSM773B 2560x1080 798x334mm 34.1-inch              | 1        | 2.78%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1        | 2.78%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                 | 1        | 2.78%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 2.78%   |
| DMG 34CHR DMGFFFF 3440x1440 797x334mm 34.0-inch                       | 1        | 2.78%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 1        | 2.78%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 2.78%   |
| BenQ GL2440H BNQ7889 1920x1080 531x298mm 24.0-inch                    | 1        | 2.78%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                      | 1        | 2.78%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 1        | 2.78%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 1        | 2.78%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 2.78%   |
| AOC 2043 AOC2043 1600x900 443x249mm 20.0-inch                         | 1        | 2.78%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 2.78%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 1        | 2.78%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 1        | 2.78%   |
| Acer XB271HU A ACR052F 2560x1440 598x336mm 27.0-inch                  | 1        | 2.78%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 55.88%  |
| 2560x1440 (QHD)    | 6        | 17.65%  |
| 3840x2160 (4K)     | 3        | 8.82%   |
| 3840x1600          | 1        | 2.94%   |
| 3840x1080          | 1        | 2.94%   |
| 3440x1440          | 1        | 2.94%   |
| 2560x1080          | 1        | 2.94%   |
| 1680x1050 (WSXGA+) | 1        | 2.94%   |
| 1600x900 (HD+)     | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 9        | 25.71%  |
| 24     | 6        | 17.14%  |
| 23     | 6        | 17.14%  |
| 21     | 5        | 14.29%  |
| 100    | 2        | 5.71%   |
| 31     | 2        | 5.71%   |
| 72     | 1        | 2.86%   |
| 48     | 1        | 2.86%   |
| 37     | 1        | 2.86%   |
| 34     | 1        | 2.86%   |
| 20     | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 18       | 54.55%  |
| 401-500        | 7        | 21.21%  |
| More than 2000 | 2        | 6.06%   |
| 601-700        | 2        | 6.06%   |
| 801-900        | 1        | 3.03%   |
| 701-800        | 1        | 3.03%   |
| 1501-2000      | 1        | 3.03%   |
| 1001-1500      | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 25       | 83.33%  |
| 21/9  | 2        | 6.67%   |
| 32/9  | 1        | 3.33%   |
| 3/2   | 1        | 3.33%   |
| 16/10 | 1        | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 36.36%  |
| 301-350        | 9        | 27.27%  |
| 351-500        | 4        | 12.12%  |
| More than 1000 | 3        | 9.09%   |
| 151-200        | 3        | 9.09%   |
| 251-300        | 1        | 3.03%   |
| 501-1000       | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 60.61%  |
| 101-120 | 8        | 24.24%  |
| 1-50    | 2        | 6.06%   |
| 161-240 | 2        | 6.06%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 73.33%  |
| 2     | 6        | 20%     |
| 3     | 1        | 3.33%   |
| 0     | 1        | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 42.86%  |
| Intel                 | 13       | 26.53%  |
| Qualcomm Atheros      | 4        | 8.16%   |
| Ralink Technology     | 2        | 4.08%   |
| Microsoft             | 2        | 4.08%   |
| TP-Link               | 1        | 2.04%   |
| NetGear               | 1        | 2.04%   |
| MicroPython           | 1        | 2.04%   |
| MEDIATEK              | 1        | 2.04%   |
| Broadcom              | 1        | 2.04%   |
| Belkin Components     | 1        | 2.04%   |
| ASUSTek Computer      | 1        | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 17       | 33.33%  |
| Realtek RTL8125 2.5GbE Controller                                  | 3        | 5.88%   |
| Intel Wi-Fi 6 AX200                                                | 3        | 5.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 2        | 3.92%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 3.92%   |
| Intel Ethernet Connection I217-LM                                  | 2        | 3.92%   |
| Intel Ethernet Connection (2) I219-V                               | 2        | 3.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1        | 1.96%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1        | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1        | 1.96%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                  | 1        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                    | 1        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1        | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1        | 1.96%   |
| NetGear A6210                                                      | 1        | 1.96%   |
| MicroPython Board in FS mode                                       | 1        | 1.96%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1        | 1.96%   |
| Intel Wireless 8260                                                | 1        | 1.96%   |
| Intel Wireless 7260                                                | 1        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 1.96%   |
| Intel Ethernet Controller I225-V                                   | 1        | 1.96%   |
| Intel Ethernet Connection (7) I219-V                               | 1        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 1.96%   |
| Intel 82578DM Gigabit Network Connection                           | 1        | 1.96%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 1.96%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 1.96%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 36.84%  |
| Ralink Technology     | 2        | 10.53%  |
| Microsoft             | 2        | 10.53%  |
| TP-Link               | 1        | 5.26%   |
| Realtek Semiconductor | 1        | 5.26%   |
| Qualcomm Atheros      | 1        | 5.26%   |
| NetGear               | 1        | 5.26%   |
| MEDIATEK              | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |
| Belkin Components     | 1        | 5.26%   |
| ASUSTek Computer      | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                | 3        | 15.79%  |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 10.53%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1        | 5.26%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1        | 5.26%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                  | 1        | 5.26%   |
| Ralink MT7601U Wireless Adapter                                    | 1        | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1        | 5.26%   |
| NetGear A6210                                                      | 1        | 5.26%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1        | 5.26%   |
| Intel Wireless 8260                                                | 1        | 5.26%   |
| Intel Wireless 7260                                                | 1        | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 5.26%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 5.26%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 5.26%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 67.74%  |
| Intel                 | 7        | 22.58%  |
| Qualcomm Atheros      | 3        | 9.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 54.84%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 9.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 6.45%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 6.45%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 3.23%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.23%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 62.5%   |
| WiFi     | 17       | 35.42%  |
| Modem    | 1        | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 66.67%  |
| WiFi     | 12       | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 63.33%  |
| 2     | 11       | 36.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 70%     |
| Yes  | 9        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 54.55%  |
| TP-Link                         | 1        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| MediaTek                        | 1        | 9.09%   |
| Cambridge Silicon Radio         | 1        | 9.09%   |
| ASUSTek Computer                | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 27.27%  |
| TP-Link UB500 Adapter                               | 1        | 9.09%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 9.09%   |
| MediaTek Wireless_Device                            | 1        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 9.09%   |
| Intel Bluetooth wireless interface                  | 1        | 9.09%   |
| Intel AX210 Bluetooth                               | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 9.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 18       | 31.58%  |
| AMD                      | 14       | 24.56%  |
| Nvidia                   | 13       | 22.81%  |
| Logitech                 | 2        | 3.51%   |
| Creative Labs            | 2        | 3.51%   |
| XMOS                     | 1        | 1.75%   |
| Turtle Beach             | 1        | 1.75%   |
| Sony                     | 1        | 1.75%   |
| Micro Star International | 1        | 1.75%   |
| KORG                     | 1        | 1.75%   |
| Focusrite-Novation       | 1        | 1.75%   |
| Corsair                  | 1        | 1.75%   |
| C-Media Electronics      | 1        | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 8.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 7.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 5.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 5.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 4.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.99%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 2.99%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2.99%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1        | 1.49%   |
| Turtle Beach Elite SuperAmp PC                                             | 1        | 1.49%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.49%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.49%   |
| Micro Star International USB Audio                                         | 1        | 1.49%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1        | 1.49%   |
| Logitech Blue Snowball                                                     | 1        | 1.49%   |
| KORG microKEY-37                                                           | 1        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.49%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.49%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.49%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.49%   |
| Focusrite-Novation Scarlett 2i4 USB                                        | 1        | 1.49%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.49%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 1        | 1.49%   |
| Corsair VOID PRO Wireless Gaming Headset                                   | 1        | 1.49%   |
| C-Media Electronics USB Audio Device                                       | 1        | 1.49%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.49%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 4        | 16.67%  |
| G.Skill             | 4        | 16.67%  |
| Kingston            | 3        | 12.5%   |
| Unknown             | 2        | 8.33%   |
| SK Hynix            | 2        | 8.33%   |
| Crucial             | 2        | 8.33%   |
| V-GeN               | 1        | 4.17%   |
| Samsung Electronics | 1        | 4.17%   |
| Samsung 1           | 1        | 4.17%   |
| Mushkin             | 1        | 4.17%   |
| GOODRAM             | 1        | 4.17%   |
| Corsair             | 1        | 4.17%   |
| A-TECH              | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s            | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 4.17%   |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s             | 1        | 4.17%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| SK Hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s          | 1        | 4.17%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 1        | 4.17%   |
| Samsung 1 RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s    | 1        | 4.17%   |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s    | 1        | 4.17%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM 2133MT/s           | 1        | 4.17%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s      | 1        | 4.17%   |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s     | 1        | 4.17%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 1        | 4.17%   |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s   | 1        | 4.17%   |
| Kingston RAM 99U5471-034.A 4GB DIMM DDR3 667MT/s         | 1        | 4.17%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 1        | 4.17%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 4.17%   |
| G.Skill RAM F4-2400C15-16GVR 16GB DIMM DDR4 2400MT/s     | 1        | 4.17%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s     | 1        | 4.17%   |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s    | 1        | 4.17%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s | 1        | 4.17%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| A-TECH RAM ATECH-4G1600 4GB DIMM DDR3 1600MT/s           | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 52.63%  |
| DDR3    | 8        | 42.11%  |
| Unknown | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 18       | 94.74%  |
| RIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 8        | 38.1%   |
| 8192  | 7        | 33.33%  |
| 16384 | 4        | 19.05%  |
| 2048  | 2        | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 23.81%  |
| 3200  | 4        | 19.05%  |
| 2133  | 4        | 19.05%  |
| 1333  | 2        | 9.52%   |
| 3866  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 2400  | 1        | 4.76%   |
| 1867  | 1        | 4.76%   |
| 800   | 1        | 4.76%   |
| 667   | 1        | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP Neverstop Laser 100x | 1        | 50%     |
| Brother Printer         | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 50%     |
| Canon CanoScan LiDE 200 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 3        | 50%     |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Microsoft                     | 1        | 16.67%  |
| KYE Systems (Mouse Systems)   | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Sunplus HD 720P webcam                    | 1        | 16.67%  |
| Microsoft LifeCam Cinema                  | 1        | 16.67%  |
| Logitech QuickCam Communicate Deluxe      | 1        | 16.67%  |
| Logitech HD Webcam C615                   | 1        | 16.67%  |
| Logitech B525 HD Webcam                   | 1        | 16.67%  |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 16.67%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

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
| 0     | 25       | 83.33%  |
| 1     | 4        | 13.33%  |
| 2     | 1        | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Unassigned class   | 1        | 25%     |
| Net/wireless       | 1        | 25%     |
| Graphics card      | 1        | 25%     |
| Fingerprint reader | 1        | 25%     |

