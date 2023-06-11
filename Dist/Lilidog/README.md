Lilidog - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lilidog.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lilidog/Desktop/README.md) and [notebooks](/Dist/Lilidog/Notebook/README.md).

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

Total: 56

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | Notebook    | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | Notebook    | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | Notebook    | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [bd50784a0b](https://linux-hardware.org/?probe=bd50784a0b) | May 05, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4d91f9900d](https://linux-hardware.org/?probe=4d91f9900d) | Apr 25, 2023 |
| Dell          | 0GM819                      | Desktop     | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Google        | Sand                        | Notebook    | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| HP            | 805B                        | Desktop     | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [b74e119c7e](https://linux-hardware.org/?probe=b74e119c7e) | Nov 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar       | A320MH                      | Desktop     | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | Notebook    | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [209e0387a9](https://linux-hardware.org/?probe=209e0387a9) | Aug 27, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [5bfd5ddd59](https://linux-hardware.org/?probe=5bfd5ddd59) | Aug 26, 2022 |
| HP            | 805B                        | Desktop     | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b7173a46ac](https://linux-hardware.org/?probe=b7173a46ac) | Aug 21, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c9be76cad8](https://linux-hardware.org/?probe=c9be76cad8) | Aug 21, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [de75a91d9f](https://linux-hardware.org/?probe=de75a91d9f) | Jul 09, 2022 |
| Acer          | V5-131                      | Notebook    | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | Notebook    | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | Notebook    | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Acer          | AOD255E                     | Notebook    | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| eMachines     | EL1352                      | Desktop     | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP            | 212B                        | Desktop     | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| HP            | 21EF                        | Desktop     | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0HJ054                      | Desktop     | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Lilidog 22 | 40        | 93.02%  |
| Lilidog 23 | 3         | 6.98%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 43        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-16-amd64           | 6         | 12%     |
| 5.10.0-18-amd64           | 5         | 10%     |
| 5.10.0-15-amd64           | 5         | 10%     |
| 5.10.0-13-amd64           | 4         | 8%      |
| 5.10.0-21-amd64           | 3         | 6%      |
| 5.10.0-20-amd64           | 3         | 6%      |
| 6.1.0-9-amd64             | 2         | 4%      |
| 6.1.0-7-amd64             | 2         | 4%      |
| 6.0.8-x64v1-xanmod1       | 2         | 4%      |
| 5.10.0-14-amd64           | 2         | 4%      |
| 6.2.12-x64v1-xanmod1      | 1         | 2%      |
| 6.2.11-x64v1-xanmod1      | 1         | 2%      |
| 6.1.0-7.2-liquorix-amd64  | 1         | 2%      |
| 6.1.0-0.deb11.6-amd64     | 1         | 2%      |
| 6.0.10-x64v1-xanmod1      | 1         | 2%      |
| 6.0.0-5-amd64             | 1         | 2%      |
| 6.0.0-2-amd64             | 1         | 2%      |
| 6.0.0-0.deb11.6-amd64     | 1         | 2%      |
| 6.0.0-0.deb11.2-amd64     | 1         | 2%      |
| 5.19.0-7.1-liquorix-amd64 | 1         | 2%      |
| 5.19.0-0.deb11.2-amd64    | 1         | 2%      |
| 5.18.0-1-amd64            | 1         | 2%      |
| 5.17.0-5.1-liquorix-amd64 | 1         | 2%      |
| 5.10.0-22-amd64           | 1         | 2%      |
| 5.10.0-19-amd64           | 1         | 2%      |
| 5.10.0-17-amd64           | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 61.7%   |
| 6.1.0   | 5         | 10.64%  |
| 6.0.0   | 4         | 8.51%   |
| 6.0.8   | 2         | 4.26%   |
| 5.19.0  | 2         | 4.26%   |
| 6.2.12  | 1         | 2.13%   |
| 6.2.11  | 1         | 2.13%   |
| 6.0.10  | 1         | 2.13%   |
| 5.18.0  | 1         | 2.13%   |
| 5.17.0  | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 29        | 61.7%   |
| 6.0     | 7         | 14.89%  |
| 6.1     | 5         | 10.64%  |
| 6.2     | 2         | 4.26%   |
| 5.19    | 2         | 4.26%   |
| 5.18    | 1         | 2.13%   |
| 5.17    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 40        | 88.89%  |
| openbox          | 5         | 11.11%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 43        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 43        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 34        | 79.07%  |
| de_DE | 4         | 9.3%    |
| en_GB | 2         | 4.65%   |
| ru_RU | 1         | 2.33%   |
| es_MX | 1         | 2.33%   |
| cs_CZ | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 24        | 55.81%  |
| BIOS | 19        | 44.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 27        | 61.36%  |
| Overlay | 14        | 31.82%  |
| Btrfs   | 3         | 6.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 28        | 65.12%  |
| MBR  | 15        | 34.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 60%     |
| Yes       | 18        | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 81.4%   |
| Yes       | 8         | 18.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 7         | 16.28%  |
| Lenovo              | 5         | 11.63%  |
| Apple               | 5         | 11.63%  |
| Acer                | 5         | 11.63%  |
| Hewlett-Packard     | 4         | 9.3%    |
| Gigabyte Technology | 3         | 6.98%   |
| ASUSTek Computer    | 3         | 6.98%   |
| TUXEDO              | 1         | 2.33%   |
| Panasonic           | 1         | 2.33%   |
| Inventec            | 1         | 2.33%   |
| Intel               | 1         | 2.33%   |
| GPU Company         | 1         | 2.33%   |
| Google              | 1         | 2.33%   |
| Foxconn             | 1         | 2.33%   |
| Fanless Mini PC     | 1         | 2.33%   |
| eMachines           | 1         | 2.33%   |
| Biostar             | 1         | 2.33%   |
| Unknown             | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 4.65%   |
| TUXEDO N8xEJEK                             | 1         | 2.33%   |
| Panasonic CF-31ATXAX1M                     | 1         | 2.33%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 2.33%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2.33%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 2.33%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1         | 2.33%   |
| Lenovo G500 20236                          | 1         | 2.33%   |
| Inventec Dell Thin Client Desktop 5060     | 1         | 2.33%   |
| Intel NUC11BTMi7                           | 1         | 2.33%   |
| HP t520 Flexible Series TC                 | 1         | 2.33%   |
| HP G62                                     | 1         | 2.33%   |
| HP EliteDesk 705 G2 MINI                   | 1         | 2.33%   |
| HP All-in-One Desktop 27-cb1xxx            | 1         | 2.33%   |
| GPU Company GWNR71517                      | 1         | 2.33%   |
| Google Sand                                | 1         | 2.33%   |
| Gigabyte PERSONAL COMPUTER                 | 1         | 2.33%   |
| Gigabyte B450 AORUS PRO                    | 1         | 2.33%   |
| Gigabyte B365M DS3H                        | 1         | 2.33%   |
| Foxconn NETBOX NT-425/525                  | 1         | 2.33%   |
| Fanless Mini PC Quieter 3                  | 1         | 2.33%   |
| eMachines EL1352                           | 1         | 2.33%   |
| Dell XPS 8930                              | 1         | 2.33%   |
| Dell OptiPlex 780                          | 1         | 2.33%   |
| Dell OptiPlex 755                          | 1         | 2.33%   |
| Dell OptiPlex 3020                         | 1         | 2.33%   |
| Dell Latitude 7390                         | 1         | 2.33%   |
| Dell Inspiron 3793                         | 1         | 2.33%   |
| Dell DM051                                 | 1         | 2.33%   |
| Biostar A320MH                             | 1         | 2.33%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 2.33%   |
| ASUS PRIME H510M-K                         | 1         | 2.33%   |
| ASUS H110M-A/DP                            | 1         | 2.33%   |
| Apple Macmini6,1                           | 1         | 2.33%   |
| Apple Macmini4,1                           | 1         | 2.33%   |
| Apple MacBookPro3,1                        | 1         | 2.33%   |
| Apple iMac12,2                             | 1         | 2.33%   |
| Apple iMac11,2                             | 1         | 2.33%   |
| Acer V5-131                                | 1         | 2.33%   |
| Acer Aspire E5-573                         | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell OptiPlex           | 3         | 6.98%   |
| Lenovo ThinkPad         | 2         | 4.65%   |
| Acer Aspire             | 2         | 4.65%   |
| Acer AOD255E            | 2         | 4.65%   |
| TUXEDO N8xEJEK          | 1         | 2.33%   |
| Panasonic CF-31ATXAX1M  | 1         | 2.33%   |
| Lenovo Yoga             | 1         | 2.33%   |
| Lenovo Legion           | 1         | 2.33%   |
| Lenovo G500             | 1         | 2.33%   |
| Inventec Dell           | 1         | 2.33%   |
| Intel NUC11BTMi7        | 1         | 2.33%   |
| HP t520                 | 1         | 2.33%   |
| HP G62                  | 1         | 2.33%   |
| HP EliteDesk            | 1         | 2.33%   |
| HP All-in-One           | 1         | 2.33%   |
| GPU Company GWNR71517   | 1         | 2.33%   |
| Google Sand             | 1         | 2.33%   |
| Gigabyte PERSONAL       | 1         | 2.33%   |
| Gigabyte B450           | 1         | 2.33%   |
| Gigabyte B365M          | 1         | 2.33%   |
| Foxconn NETBOX          | 1         | 2.33%   |
| Fanless Mini PC Quieter | 1         | 2.33%   |
| eMachines EL1352        | 1         | 2.33%   |
| Dell XPS                | 1         | 2.33%   |
| Dell Latitude           | 1         | 2.33%   |
| Dell Inspiron           | 1         | 2.33%   |
| Dell DM051              | 1         | 2.33%   |
| Biostar A320MH          | 1         | 2.33%   |
| ASUS VivoBook           | 1         | 2.33%   |
| ASUS PRIME              | 1         | 2.33%   |
| ASUS H110M-A            | 1         | 2.33%   |
| Apple Macmini6          | 1         | 2.33%   |
| Apple Macmini4          | 1         | 2.33%   |
| Apple MacBookPro3       | 1         | 2.33%   |
| Apple iMac12            | 1         | 2.33%   |
| Apple iMac11            | 1         | 2.33%   |
| Acer V5-131             | 1         | 2.33%   |
| Unknown                 | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 9         | 20.93%  |
| 2018 | 7         | 16.28%  |
| 2019 | 4         | 9.3%    |
| 2022 | 3         | 6.98%   |
| 2021 | 3         | 6.98%   |
| 2017 | 2         | 4.65%   |
| 2015 | 2         | 4.65%   |
| 2014 | 2         | 4.65%   |
| 2012 | 2         | 4.65%   |
| 2007 | 2         | 4.65%   |
| 2023 | 1         | 2.33%   |
| 2020 | 1         | 2.33%   |
| 2013 | 1         | 2.33%   |
| 2011 | 1         | 2.33%   |
| 2009 | 1         | 2.33%   |
| 2008 | 1         | 2.33%   |
| 2006 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 18        | 41.86%  |
| Desktop    | 17        | 39.53%  |
| Mini pc    | 5         | 11.63%  |
| All in one | 3         | 6.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 95.35%  |
| Enabled  | 2         | 4.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 95.35%  |
| Yes  | 2         | 4.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 30.23%  |
| 3.01-4.0   | 9         | 20.93%  |
| 16.01-24.0 | 9         | 20.93%  |
| 32.01-64.0 | 3         | 6.98%   |
| 8.01-16.0  | 3         | 6.98%   |
| 2.01-3.0   | 2         | 4.65%   |
| 1.01-2.0   | 2         | 4.65%   |
| 0.51-1.0   | 2         | 4.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 27        | 60%     |
| 1.01-2.0  | 12        | 26.67%  |
| 2.01-3.0  | 3         | 6.67%   |
| 0.01-0.5  | 2         | 4.44%   |
| 8.01-16.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 63.64%  |
| 2      | 13        | 29.55%  |
| 3      | 2         | 4.55%   |
| 4      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 61.36%  |
| Yes       | 17        | 38.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 88.37%  |
| No        | 5         | 11.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 79.07%  |
| No        | 9         | 20.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 51.16%  |
| Yes       | 21        | 48.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 37.21%  |
| Germany     | 7         | 16.28%  |
| UK          | 4         | 9.3%    |
| Italy       | 2         | 4.65%   |
| Vietnam     | 1         | 2.33%   |
| Thailand    | 1         | 2.33%   |
| Taiwan      | 1         | 2.33%   |
| Spain       | 1         | 2.33%   |
| Russia      | 1         | 2.33%   |
| Romania     | 1         | 2.33%   |
| Portugal    | 1         | 2.33%   |
| Netherlands | 1         | 2.33%   |
| Mexico      | 1         | 2.33%   |
| Indonesia   | 1         | 2.33%   |
| Czechia     | 1         | 2.33%   |
| Belgium     | 1         | 2.33%   |
| Austria     | 1         | 2.33%   |
| Argentina   | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 11.11%  |
| Fayetteville                | 5         | 11.11%  |
| Egan                        | 2         | 4.44%   |
| Charlotte                   | 2         | 4.44%   |
| Zapopan                     | 1         | 2.22%   |
| Workum                      | 1         | 2.22%   |
| Vienna                      | 1         | 2.22%   |
| Uelzen                      | 1         | 2.22%   |
| Stockport                   | 1         | 2.22%   |
| St Petersburg               | 1         | 2.22%   |
| San Nicolás de los Arroyos | 1         | 2.22%   |
| Rome                        | 1         | 2.22%   |
| Rinteln                     | 1         | 2.22%   |
| Ratchathewi                 | 1         | 2.22%   |
| Poricany                    | 1         | 2.22%   |
| Palembang                   | 1         | 2.22%   |
| Milan                       | 1         | 2.22%   |
| Memphis                     | 1         | 2.22%   |
| Madrid                      | 1         | 2.22%   |
| Lisbon                      | 1         | 2.22%   |
| Leicester                   | 1         | 2.22%   |
| Langelsheim                 | 1         | 2.22%   |
| Idsegahuizum                | 1         | 2.22%   |
| Ho Chi Minh City            | 1         | 2.22%   |
| Golden Valley               | 1         | 2.22%   |
| Ghent                       | 1         | 2.22%   |
| Fongshan District           | 1         | 2.22%   |
| Filderstadt                 | 1         | 2.22%   |
| Eppelborn                   | 1         | 2.22%   |
| Düsseldorf                 | 1         | 2.22%   |
| Darmstadt                   | 1         | 2.22%   |
| Conway                      | 1         | 2.22%   |
| Bradford                    | 1         | 2.22%   |
| Beiuș                      | 1         | 2.22%   |
| Barnsley                    | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 22.41%  |
| WDC                 | 7         | 11     | 12.07%  |
| Samsung Electronics | 7         | 10     | 12.07%  |
| SanDisk             | 5         | 6      | 8.62%   |
| Kingston            | 5         | 6      | 8.62%   |
| Toshiba             | 3         | 3      | 5.17%   |
| Hitachi             | 2         | 2      | 3.45%   |
| Crucial             | 2         | 2      | 3.45%   |
| Apacer              | 2         | 2      | 3.45%   |
| Wibtek              | 1         | 1      | 1.72%   |
| Unknown             | 1         | 1      | 1.72%   |
| SSK                 | 1         | 2      | 1.72%   |
| Silicon Motion      | 1         | 1      | 1.72%   |
| OWC                 | 1         | 2      | 1.72%   |
| Mushkin             | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| ASMedia             | 1         | 1      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |
| Unknown             | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST31000528AS 1TB             | 2         | 3.33%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 3.33%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 3.33%   |
| Wibtek W800S 512GB SSD               | 1         | 1.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 1.67%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1.67%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.67%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 1.67%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 1.67%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.67%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.67%   |
| Unknown NCard  32GB                  | 1         | 1.67%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.67%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.67%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.67%   |
| SSK Disk 256GB                       | 1         | 1.67%   |
| Silicon Motion NE-128 128GB          | 1         | 1.67%   |
| Seagate ST9320325ASG 320GB           | 1         | 1.67%   |
| Seagate ST9250315AS 250GB            | 1         | 1.67%   |
| Seagate ST500VM000-1SD101 500GB      | 1         | 1.67%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.67%   |
| Seagate ST3160023AS 160GB            | 1         | 1.67%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1.67%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.67%   |
| Seagate Expansion 1TB                | 1         | 1.67%   |
| Seagate BUP Slim BK 2TB              | 1         | 1.67%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1         | 1.67%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.67%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 1.67%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1         | 1.67%   |
| SanDisk DF4032  32GB                 | 1         | 1.67%   |
| Samsung SSD 980 1TB                  | 1         | 1.67%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.67%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.67%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.67%   |
| Samsung PM991a NVMe 512GB            | 1         | 1.67%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.67%   |
| Samsung MZ7TE128HMGR-000L1 128GB SSD | 1         | 1.67%   |
| OWC Mercury EXTREME Pro 6G SSD       | 1         | 1.67%   |
| Mushkin MKNSSDCR120GB                | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 16     | 52%     |
| WDC     | 4         | 4      | 16%     |
| Toshiba | 3         | 3      | 12%     |
| Hitachi | 2         | 2      | 8%      |
| SSK     | 1         | 2      | 4%      |
| ASMedia | 1         | 1      | 4%      |
| Apple   | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 19.05%  |
| Kingston            | 4         | 5      | 19.05%  |
| Samsung Electronics | 3         | 3      | 14.29%  |
| Crucial             | 2         | 2      | 9.52%   |
| Apacer              | 2         | 2      | 9.52%   |
| Wibtek              | 1         | 1      | 4.76%   |
| WDC                 | 1         | 2      | 4.76%   |
| OWC                 | 1         | 2      | 4.76%   |
| Mushkin             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 29     | 39.62%  |
| SSD  | 20        | 24     | 37.74%  |
| NVMe | 10        | 15     | 18.87%  |
| MMC  | 2         | 4      | 3.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 47     | 68.52%  |
| NVMe | 10        | 15     | 18.52%  |
| SAS  | 5         | 6      | 9.26%   |
| MMC  | 2         | 4      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 35     | 65.91%  |
| 0.51-1.0   | 11        | 13     | 25%     |
| 1.01-2.0   | 3         | 4      | 6.82%   |
| 4.01-10.0  | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 13        | 28.89%  |
| 251-500    | 11        | 24.44%  |
| 101-250    | 10        | 22.22%  |
| 1001-2000  | 4         | 8.89%   |
| 501-1000   | 3         | 6.67%   |
| 51-100     | 3         | 6.67%   |
| 21-50      | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 84.09%  |
| 21-50     | 3         | 6.82%   |
| 101-250   | 2         | 4.55%   |
| 251-500   | 1         | 2.27%   |
| 1001-2000 | 1         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 11.11%  |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 11.11%  |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 11.11%  |
| Seagate ST9250315AS 250GB          | 1         | 1      | 11.11%  |
| Seagate ST500LT012-9WS142 500GB    | 1         | 2      | 11.11%  |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 11.11%  |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 11.11%  |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 11.11%  |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 33.33%  |
| WDC     | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| SanDisk | 1         | 1      | 11.11%  |
| OWC     | 1         | 2      | 11.11%  |
| Mushkin | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 55.56%  |
| SSD  | 4         | 6      | 44.44%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 33        | 49     | 67.35%  |
| Malfunc  | 9         | 12     | 18.37%  |
| Detected | 6         | 9      | 12.24%  |
| Failed   | 1         | 2      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 32        | 64%     |
| AMD                         | 7         | 14%     |
| Samsung Electronics         | 5         | 10%     |
| SanDisk                     | 2         | 4%      |
| Nvidia                      | 2         | 4%      |
| Silicon Motion              | 1         | 2%      |
| Kingston Technology Company | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 9.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.92%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 3.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 3.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 3.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 3.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.64%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.64%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 1.64%   |
| Nvidia MCP61 IDE                                                               | 1         | 1.64%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.64%   |
| Intel NVMe Optane Memory Series                                                | 1         | 1.64%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.64%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.64%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 1.64%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1         | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 1         | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 1         | 1.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.64%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.64%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 64.81%  |
| NVMe | 10        | 18.52%  |
| IDE  | 7         | 12.96%  |
| RAID | 2         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 79.07%  |
| AMD    | 9         | 20.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz              | 2         | 4.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2         | 4.65%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 2         | 4.65%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz             | 1         | 2.33%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz         | 1         | 2.33%   |
| Intel Pentium D CPU 2.80GHz                    | 1         | 2.33%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 2.33%   |
| Intel Pentium 3556U @ 1.70GHz                  | 1         | 2.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 2.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 2.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz              | 1         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 2.33%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 2.33%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1         | 2.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 2.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 1         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 2.33%   |
| Intel Core i5-2500S CPU @ 2.70GHz              | 1         | 2.33%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1         | 2.33%   |
| Intel Core i3 CPU 540 @ 3.07GHz                | 1         | 2.33%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz           | 1         | 2.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 1         | 2.33%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz           | 1         | 2.33%   |
| Intel Celeron N5105 @ 2.00GHz                  | 1         | 2.33%   |
| Intel Celeron CPU N2807 @ 1.58GHz              | 1         | 2.33%   |
| Intel Celeron CPU 1007U @ 1.50GHz              | 1         | 2.33%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1         | 2.33%   |
| Intel 12th Gen Core i5-1235U                   | 1         | 2.33%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz       | 1         | 2.33%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 1         | 2.33%   |
| Intel 11th Gen Core i7-11700B @ 3.20GHz        | 1         | 2.33%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx  | 1         | 2.33%   |
| AMD Ryzen 5 4500U with Radeon Graphics         | 1         | 2.33%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1         | 2.33%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G   | 1         | 2.33%   |
| AMD GX-424CC SOC with Radeon R5E Graphics      | 1         | 2.33%   |
| AMD GX-212JC SOC with Radeon R2E Graphics      | 1         | 2.33%   |
| AMD Athlon II Dual-Core M300                   | 1         | 2.33%   |
| AMD Athlon II 170u Processor                   | 1         | 2.33%   |
| AMD A12-9800 RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 16.28%  |
| Intel Core i7           | 5         | 11.63%  |
| Intel Core 2 Duo        | 5         | 11.63%  |
| Other                   | 4         | 9.3%    |
| Intel Celeron           | 3         | 6.98%   |
| Intel Atom              | 3         | 6.98%   |
| Intel Pentium           | 2         | 4.65%   |
| Intel Core i3           | 2         | 4.65%   |
| AMD Ryzen 5             | 2         | 4.65%   |
| AMD GX                  | 2         | 4.65%   |
| Intel Xeon              | 1         | 2.33%   |
| Intel Pentium Gold      | 1         | 2.33%   |
| Intel Pentium D         | 1         | 2.33%   |
| AMD Ryzen 7             | 1         | 2.33%   |
| AMD PRO A10             | 1         | 2.33%   |
| AMD Athlon II Dual-Core | 1         | 2.33%   |
| AMD Athlon II           | 1         | 2.33%   |
| AMD A12                 | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 48.84%  |
| 4      | 12        | 27.91%  |
| 6      | 4         | 9.3%    |
| 1      | 3         | 6.98%   |
| 8      | 2         | 4.65%   |
| 10     | 1         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 53.49%  |
| 1      | 20        | 46.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 8.89%   |
| 0x306a9    | 3         | 6.67%   |
| 0x106ca    | 3         | 6.67%   |
| 0x1067a    | 3         | 6.67%   |
| 0x906ea    | 2         | 4.44%   |
| 0x806ea    | 2         | 4.44%   |
| 0x20655    | 2         | 4.44%   |
| 0x0600611a | 2         | 4.44%   |
| 0xf44      | 1         | 2.22%   |
| 0xa0671    | 1         | 2.22%   |
| 0xa0653    | 1         | 2.22%   |
| 0x906ed    | 1         | 2.22%   |
| 0x906e9    | 1         | 2.22%   |
| 0x906c0    | 1         | 2.22%   |
| 0x906a4    | 1         | 2.22%   |
| 0x806d1    | 1         | 2.22%   |
| 0x806c1    | 1         | 2.22%   |
| 0x706e5    | 1         | 2.22%   |
| 0x6fa      | 1         | 2.22%   |
| 0x506c9    | 1         | 2.22%   |
| 0x40651    | 1         | 2.22%   |
| 0x306c3    | 1         | 2.22%   |
| 0x30678    | 1         | 2.22%   |
| 0x206d7    | 1         | 2.22%   |
| 0x206a7    | 1         | 2.22%   |
| 0x10676    | 1         | 2.22%   |
| 0x08600106 | 1         | 2.22%   |
| 0x08108109 | 1         | 2.22%   |
| 0x0810100b | 1         | 2.22%   |
| 0x07030105 | 1         | 2.22%   |
| 0x07030104 | 1         | 2.22%   |
| 0x010000c8 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 13.64%  |
| Penryn      | 4         | 9.09%   |
| Westmere    | 3         | 6.82%   |
| IvyBridge   | 3         | 6.82%   |
| Icelake     | 3         | 6.82%   |
| Bonnell     | 3         | 6.82%   |
| SandyBridge | 2         | 4.55%   |
| Puma        | 2         | 4.55%   |
| K10         | 2         | 4.55%   |
| Haswell     | 2         | 4.55%   |
| Excavator   | 2         | 4.55%   |
| Unknown     | 2         | 4.55%   |
| Zen+        | 1         | 2.27%   |
| Zen 2       | 1         | 2.27%   |
| Zen         | 1         | 2.27%   |
| Tremont     | 1         | 2.27%   |
| TigerLake   | 1         | 2.27%   |
| Silvermont  | 1         | 2.27%   |
| NetBurst    | 1         | 2.27%   |
| Goldmont    | 1         | 2.27%   |
| Core        | 1         | 2.27%   |
| CometLake   | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 52.94%  |
| AMD    | 15        | 29.41%  |
| Nvidia | 9         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 5.77%   |
| Intel UHD Graphics 620                                                    | 2         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 3.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 3.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.92%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.92%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                         | 1         | 1.92%   |
| Nvidia GA102 [GeForce RTX 3080]                                           | 1         | 1.92%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 1.92%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                    | 1         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.92%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.92%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.92%   |
| Intel HD Graphics 630                                                     | 1         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 1.92%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                  | 1         | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.92%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1         | 1.92%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                   | 1         | 1.92%   |
| Intel 82Q35 Express Integrated Graphics Controller                        | 1         | 1.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 1.92%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                             | 1         | 1.92%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                | 1         | 1.92%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]          | 1         | 1.92%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.92%   |
| AMD RV370 [Radeon X600/X600 SE]                                           | 1         | 1.92%   |
| AMD Renoir                                                                | 1         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.92%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 45.45%  |
| 1 x AMD        | 11        | 25%     |
| 1 x Nvidia     | 6         | 13.64%  |
| Intel + Nvidia | 3         | 6.82%   |
| Intel + AMD    | 3         | 6.82%   |
| 2 x AMD        | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 40        | 90.91%  |
| Unknown     | 3         | 6.82%   |
| Proprietary | 1         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 53.33%  |
| 0.01-0.5   | 12        | 26.67%  |
| 3.01-4.0   | 3         | 6.67%   |
| 1.01-2.0   | 2         | 4.44%   |
| 0.51-1.0   | 2         | 4.44%   |
| 7.01-8.0   | 1         | 2.22%   |
| 8.01-16.0  | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 23.08%  |
| Samsung Electronics     | 3         | 7.69%   |
| Lenovo                  | 3         | 7.69%   |
| Dell                    | 3         | 7.69%   |
| Sceptre Tech            | 2         | 5.13%   |
| LG Display              | 2         | 5.13%   |
| Goldstar                | 2         | 5.13%   |
| Chimei Innolux          | 2         | 5.13%   |
| Zoran                   | 1         | 2.56%   |
| Sony                    | 1         | 2.56%   |
| SAC                     | 1         | 2.56%   |
| Philips                 | 1         | 2.56%   |
| Insignia                | 1         | 2.56%   |
| HUAWEI                  | 1         | 2.56%   |
| Hewlett-Packard         | 1         | 2.56%   |
| eMachines               | 1         | 2.56%   |
| Chi Mei Optoelectronics | 1         | 2.56%   |
| BOE                     | 1         | 2.56%   |
| ASUSTek Computer        | 1         | 2.56%   |
| Apple                   | 1         | 2.56%   |
| AOC                     | 1         | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                   | 2         | 5.13%   |
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                       | 1         | 2.56%   |
| Sony TV SNY0101 1360x768                                                 | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch  | 1         | 2.56%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch        | 1         | 2.56%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch        | 1         | 2.56%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                    | 1         | 2.56%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                       | 1         | 2.56%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch            | 1         | 2.56%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.56%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 1         | 2.56%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                  | 1         | 2.56%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                     | 1         | 2.56%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch                   | 1         | 2.56%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                     | 1         | 2.56%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch             | 1         | 2.56%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch                 | 1         | 2.56%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                   | 1         | 2.56%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                    | 1         | 2.56%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                        | 1         | 2.56%   |
| Dell P2319H DELD0D5 1920x1080 509x286mm 23.0-inch                        | 1         | 2.56%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                         | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch         | 1         | 2.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 2.56%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 1         | 2.56%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch             | 1         | 2.56%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 1         | 2.56%   |
| AOC E2219 AOC2219 1680x1050 470x300mm 22.0-inch                          | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 44.74%  |
| 1366x768 (WXGA)    | 4         | 10.53%  |
| 2560x1440 (QHD)    | 3         | 7.89%   |
| 1360x768           | 3         | 7.89%   |
| 3840x2160 (4K)     | 2         | 5.26%   |
| 1280x800 (WXGA)    | 2         | 5.26%   |
| 1024x600           | 2         | 5.26%   |
| 3440x1440          | 1         | 2.63%   |
| 1920x1200 (WUXGA)  | 1         | 2.63%   |
| 1680x1050 (WSXGA+) | 1         | 2.63%   |
| 1600x900 (HD+)     | 1         | 2.63%   |
| 1024x768 (XGA)     | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 20.51%  |
| 24      | 6         | 15.38%  |
| 21      | 4         | 10.26%  |
| 17      | 3         | 7.69%   |
| 14      | 3         | 7.69%   |
| 31      | 2         | 5.13%   |
| 23      | 2         | 5.13%   |
| 22      | 2         | 5.13%   |
| 10      | 2         | 5.13%   |
| 84      | 1         | 2.56%   |
| 34      | 1         | 2.56%   |
| 32      | 1         | 2.56%   |
| 27      | 1         | 2.56%   |
| 13      | 1         | 2.56%   |
| 11      | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 28.21%  |
| 501-600     | 9         | 23.08%  |
| 401-500     | 6         | 15.38%  |
| 201-300     | 4         | 10.26%  |
| 351-400     | 3         | 7.69%   |
| 701-800     | 2         | 5.13%   |
| 601-700     | 2         | 5.13%   |
| 1501-2000   | 1         | 2.56%   |
| Unknown     | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 83.78%  |
| 16/10 | 4         | 10.81%  |
| 4/3   | 1         | 2.7%    |
| 21/9  | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 13        | 33.33%  |
| 101-110        | 8         | 20.51%  |
| 351-500        | 4         | 10.26%  |
| 81-90          | 3         | 7.69%   |
| 121-130        | 3         | 7.69%   |
| 41-50          | 2         | 5.13%   |
| More than 1000 | 1         | 2.56%   |
| 71-80          | 1         | 2.56%   |
| 51-60          | 1         | 2.56%   |
| 301-350        | 1         | 2.56%   |
| 151-200        | 1         | 2.56%   |
| Unknown        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 14        | 35.9%   |
| 101-120 | 12        | 30.77%  |
| 121-160 | 8         | 20.51%  |
| 161-240 | 3         | 7.69%   |
| 1-50    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 84.09%  |
| 0     | 4         | 9.09%   |
| 2     | 3         | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 19        | 28.79%  |
| Intel                           | 16        | 24.24%  |
| Qualcomm Atheros                | 13        | 19.7%   |
| Broadcom                        | 10        | 15.15%  |
| Qualcomm Atheros Communications | 3         | 4.55%   |
| Ralink Technology               | 1         | 1.52%   |
| Prolific Technology             | 1         | 1.52%   |
| Nvidia                          | 1         | 1.52%   |
| MediaTek                        | 1         | 1.52%   |
| Marvell Technology Group        | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 13        | 16.67%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 5.13%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 2         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 2.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 2.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.28%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 1.28%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 1.28%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.28%   |
| Prolific USB-Serial Controller                                                        | 1         | 1.28%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 1.28%   |
| MediaTek CPH2211                                                                      | 1         | 1.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 1.28%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.28%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 1.28%   |
| Intel Wireless 7265                                                                   | 1         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.28%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1         | 1.28%   |
| Intel I211 Gigabit Network Connection                                                 | 1         | 1.28%   |
| Intel Ethernet Controller I225-LM                                                     | 1         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 1.28%   |
| Intel Ethernet Connection (14) I219-V                                                 | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 29.73%  |
| Qualcomm Atheros                | 10        | 27.03%  |
| Realtek Semiconductor           | 7         | 18.92%  |
| Broadcom                        | 5         | 13.51%  |
| Qualcomm Atheros Communications | 3         | 8.11%   |
| Ralink Technology               | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 10.81%  |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 8.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 5.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 5.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 5.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.7%    |
| Realtek 802.11ac NIC                                                                  | 1         | 2.7%    |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.7%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.7%    |
| Intel Wireless-AC 9260                                                                | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.7%    |
| Intel Wireless 7265                                                                   | 1         | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 2.7%    |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.7%    |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 2.7%    |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.7%    |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 40%     |
| Intel                    | 9         | 22.5%   |
| Broadcom                 | 7         | 17.5%   |
| Qualcomm Atheros         | 5         | 12.5%   |
| Nvidia                   | 1         | 2.5%    |
| MediaTek                 | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 32.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5%      |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 5%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.5%    |
| Nvidia MCP61 Ethernet                                             | 1         | 2.5%    |
| MediaTek CPH2211                                                  | 1         | 2.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.5%    |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 1         | 2.5%    |
| Intel Ethernet Controller I225-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.5%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 52.05%  |
| WiFi     | 34        | 46.58%  |
| Modem    | 1         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 57.78%  |
| WiFi     | 19        | 42.22%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 59.09%  |
| 1     | 16        | 36.36%  |
| 3     | 1         | 2.27%   |
| 0     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 54.55%  |
| Yes  | 20        | 45.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 33.33%  |
| Apple                           | 5         | 23.81%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| Lite-On Technology              | 2         | 9.52%   |
| IMC Networks                    | 2         | 9.52%   |
| Realtek Semiconductor           | 1         | 4.76%   |
| Broadcom                        | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                              | 3         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 9.52%   |
| Intel Bluetooth wireless interface                 | 2         | 9.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 2         | 9.52%   |
| Realtek Bluetooth Radio                            | 1         | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 1         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 4.76%   |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 4.76%   |
| IMC Networks Bluetooth Radio                       | 1         | 4.76%   |
| IMC Networks Bluetooth Device                      | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 4.76%   |
| Apple Bluetooth USB Host Controller                | 1         | 4.76%   |
| Apple Bluetooth Host Controller                    | 1         | 4.76%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 55.17%  |
| AMD                   | 13        | 22.41%  |
| Nvidia                | 7         | 12.07%  |
| SAVITECH              | 1         | 1.72%   |
| Roland                | 1         | 1.72%   |
| Realtek Semiconductor | 1         | 1.72%   |
| JMTek                 | 1         | 1.72%   |
| Huawei Technologies   | 1         | 1.72%   |
| Anlya.cn              | 1         | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 5.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.41%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 4.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.94%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.94%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.94%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.94%   |
| SAVITECH USB HIFI Audio                                                    | 1         | 1.47%   |
| Roland QUAD-CAPTURE                                                        | 1         | 1.47%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.47%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.47%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.47%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.47%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.47%   |
| JMTek USB Audio Device                                                     | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.47%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.47%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.47%   |
| Intel HD Graphics SGPC                                                     | 1         | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.47%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 15.09%  |
| Unknown             | 7         | 13.21%  |
| Crucial             | 7         | 13.21%  |
| Micron Technology   | 6         | 11.32%  |
| Samsung Electronics | 5         | 9.43%   |
| Kingston            | 3         | 5.66%   |
| Corsair             | 3         | 5.66%   |
| A-DATA Technology   | 3         | 5.66%   |
| Timetec             | 2         | 3.77%   |
| Unknown (08C8)      | 1         | 1.89%   |
| Team                | 1         | 1.89%   |
| SK_Hynix            | 1         | 1.89%   |
| Patriot             | 1         | 1.89%   |
| Nanya Technology    | 1         | 1.89%   |
| Infineon            | 1         | 1.89%   |
| G.Skill             | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.64%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.82%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s     | 1         | 1.82%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 1.82%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.82%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 1.82%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.82%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.82%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.82%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s                  | 1         | 1.82%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Patriot RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.82%   |
| Nanya RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 1.82%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.82%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Micron RAM 16HTF12864AY-53EB1 1GB DIMM DDR 533MT/s               | 1         | 1.82%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                        | 1         | 1.82%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                        | 1         | 1.82%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.82%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 1         | 1.82%   |
| Infineon RAM 64T64000HU3.7A 512MB DIMM DDR2 533MT/s              | 1         | 1.82%   |
| G.Skill RAM F2-6400CL5-2GBPQ 2GB DIMM DDR2 800MT/s               | 1         | 1.82%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 19        | 44.19%  |
| DDR4   | 14        | 32.56%  |
| DDR2   | 5         | 11.63%  |
| LPDDR4 | 4         | 9.3%    |
| DDR    | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 57.14%  |
| DIMM         | 14        | 33.33%  |
| Row Of Chips | 3         | 7.14%   |
| Unknown      | 1         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 33.33%  |
| 4096  | 12        | 26.67%  |
| 2048  | 8         | 17.78%  |
| 1024  | 5         | 11.11%  |
| 16384 | 3         | 6.67%   |
| 32768 | 1         | 2.22%   |
| 512   | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 10        | 21.74%  |
| 667   | 6         | 13.04%  |
| 2667  | 5         | 10.87%  |
| 1067  | 5         | 10.87%  |
| 3200  | 4         | 8.7%    |
| 2400  | 3         | 6.52%   |
| 8400  | 1         | 2.17%   |
| 4267  | 1         | 2.17%   |
| 4266  | 1         | 2.17%   |
| 3733  | 1         | 2.17%   |
| 3600  | 1         | 2.17%   |
| 2800  | 1         | 2.17%   |
| 2733  | 1         | 2.17%   |
| 2666  | 1         | 2.17%   |
| 1866  | 1         | 2.17%   |
| 1333  | 1         | 2.17%   |
| 1066  | 1         | 2.17%   |
| 800   | 1         | 2.17%   |
| 533   | 1         | 2.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 50%     |
| HP DeskJet F4200 series               | 1         | 25%     |
| HP DeskJet 2130 series                | 1         | 25%     |

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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Apple                         | 4         | 20%     |
| Chicony Electronics           | 3         | 15%     |
| Sunplus Innovation Technology | 2         | 10%     |
| Realtek Semiconductor         | 2         | 10%     |
| Logitech                      | 2         | 10%     |
| ALi                           | 2         | 10%     |
| Suyin                         | 1         | 5%      |
| Quanta                        | 1         | 5%      |
| Microdia                      | 1         | 5%      |
| IMC Networks                  | 1         | 5%      |
| Acer                          | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Apple Built-in iSight                    | 2         | 10%     |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 5%      |
| Sunplus Integrated_Webcam_HD             | 1         | 5%      |
| Sunplus HD WebCam                        | 1         | 5%      |
| Realtek Lenovo EasyCamera                | 1         | 5%      |
| Realtek 2SF022                           | 1         | 5%      |
| Quanta HP 2.0MP High Definition Webcam   | 1         | 5%      |
| Microdia Integrated_Webcam_HD            | 1         | 5%      |
| Logitech Logitech Webcam C160            | 1         | 5%      |
| Logitech HD Pro Webcam C920              | 1         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam       | 1         | 5%      |
| Chicony Integrated Camera                | 1         | 5%      |
| Chicony HD WebCam (Acer)                 | 1         | 5%      |
| Chicony HD WebCam                        | 1         | 5%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 1         | 5%      |
| Apple FaceTime HD Camera (Built-in)      | 1         | 5%      |
| ALi WebCam                               | 1         | 5%      |
| ALi Gateway Webcam                       | 1         | 5%      |
| Acer BisonCam, NB Pro                    | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 50%     |
| Focal-systems.Corp    | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.     | 1         | 50%     |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 74.42%  |
| 1     | 11        | 25.58%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 36.36%  |
| Multimedia controller    | 2         | 18.18%  |
| Fingerprint reader       | 2         | 18.18%  |
| Net/wireless             | 1         | 9.09%   |
| Communication controller | 1         | 9.09%   |
| Camera                   | 1         | 9.09%   |

