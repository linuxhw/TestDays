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

Total: 64

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0M5DCD A00                  | Desktop     | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | Notebook    | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
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
| Lilidog 22 | 40        | 78.43%  |
| Lilidog 23 | 11        | 21.57%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-16-amd64           | 6         | 10.34%  |
| 6.1.0-9-amd64             | 5         | 8.62%   |
| 5.10.0-18-amd64           | 5         | 8.62%   |
| 5.10.0-15-amd64           | 5         | 8.62%   |
| 6.1.0-10-amd64            | 4         | 6.9%    |
| 5.10.0-13-amd64           | 4         | 6.9%    |
| 5.10.0-21-amd64           | 3         | 5.17%   |
| 5.10.0-20-amd64           | 3         | 5.17%   |
| 6.1.0-7-amd64             | 2         | 3.45%   |
| 6.0.8-x64v1-xanmod1       | 2         | 3.45%   |
| 5.10.0-14-amd64           | 2         | 3.45%   |
| 6.4.5-1-liquorix-amd64    | 1         | 1.72%   |
| 6.2.12-x64v1-xanmod1      | 1         | 1.72%   |
| 6.2.11-x64v1-xanmod1      | 1         | 1.72%   |
| 6.1.0-7.2-liquorix-amd64  | 1         | 1.72%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 1.72%   |
| 6.0.10-x64v1-xanmod1      | 1         | 1.72%   |
| 6.0.0-5-amd64             | 1         | 1.72%   |
| 6.0.0-2-amd64             | 1         | 1.72%   |
| 6.0.0-0.deb11.6-amd64     | 1         | 1.72%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 1.72%   |
| 5.19.0-7.1-liquorix-amd64 | 1         | 1.72%   |
| 5.19.0-0.deb11.2-amd64    | 1         | 1.72%   |
| 5.18.0-1-amd64            | 1         | 1.72%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 1.72%   |
| 5.10.0-22-amd64           | 1         | 1.72%   |
| 5.10.0-19-amd64           | 1         | 1.72%   |
| 5.10.0-17-amd64           | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 52.73%  |
| 6.1.0   | 12        | 21.82%  |
| 6.0.0   | 4         | 7.27%   |
| 6.0.8   | 2         | 3.64%   |
| 5.19.0  | 2         | 3.64%   |
| 6.4.5   | 1         | 1.82%   |
| 6.2.12  | 1         | 1.82%   |
| 6.2.11  | 1         | 1.82%   |
| 6.0.10  | 1         | 1.82%   |
| 5.18.0  | 1         | 1.82%   |
| 5.17.0  | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 29        | 52.73%  |
| 6.1     | 12        | 21.82%  |
| 6.0     | 7         | 12.73%  |
| 6.2     | 2         | 3.64%   |
| 5.19    | 2         | 3.64%   |
| 6.4     | 1         | 1.82%   |
| 5.18    | 1         | 1.82%   |
| 5.17    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 46        | 88.46%  |
| openbox          | 6         | 11.54%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 50        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 50        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 39        | 76.47%  |
| de_DE | 4         | 7.84%   |
| es_ES | 2         | 3.92%   |
| en_GB | 2         | 3.92%   |
| ru_RU | 1         | 1.96%   |
| es_MX | 1         | 1.96%   |
| en_IE | 1         | 1.96%   |
| cs_CZ | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 28        | 56%     |
| BIOS | 22        | 44%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 64.71%  |
| Overlay | 15        | 29.41%  |
| Btrfs   | 3         | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 33        | 66%     |
| MBR  | 17        | 34%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 61.54%  |
| Yes       | 20        | 38.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 82%     |
| Yes       | 9         | 18%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 20%     |
| Lenovo              | 6         | 12%     |
| Hewlett-Packard     | 5         | 10%     |
| Apple               | 5         | 10%     |
| Acer                | 5         | 10%     |
| Gigabyte Technology | 3         | 6%      |
| ASUSTek Computer    | 3         | 6%      |
| Panasonic           | 2         | 4%      |
| Google              | 2         | 4%      |
| TUXEDO              | 1         | 2%      |
| Inventec            | 1         | 2%      |
| Intel               | 1         | 2%      |
| GPU Company         | 1         | 2%      |
| Foxconn             | 1         | 2%      |
| Fanless Mini PC     | 1         | 2%      |
| eMachines           | 1         | 2%      |
| Biostar             | 1         | 2%      |
| Unknown             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 4%      |
| TUXEDO N8xEJEK                             | 1         | 2%      |
| Panasonic CFMX4-1                          | 1         | 2%      |
| Panasonic CF-31ATXAX1M                     | 1         | 2%      |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 2%      |
| Lenovo ThinkPad T400 6474WPU               | 1         | 2%      |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1         | 2%      |
| Lenovo G500 20236                          | 1         | 2%      |
| Inventec Dell Thin Client Desktop 5060     | 1         | 2%      |
| Intel NUC11BTMi7                           | 1         | 2%      |
| HP t520 Flexible Series TC                 | 1         | 2%      |
| HP Laptop 15s-fq1xxx                       | 1         | 2%      |
| HP G62                                     | 1         | 2%      |
| HP EliteDesk 705 G2 MINI                   | 1         | 2%      |
| HP All-in-One Desktop 27-cb1xxx            | 1         | 2%      |
| GPU Company GWNR71517                      | 1         | 2%      |
| Google Sand                                | 1         | 2%      |
| Google Auron_Yuna                          | 1         | 2%      |
| Gigabyte PERSONAL COMPUTER                 | 1         | 2%      |
| Gigabyte B450 AORUS PRO                    | 1         | 2%      |
| Gigabyte B365M DS3H                        | 1         | 2%      |
| Foxconn NETBOX NT-425/525                  | 1         | 2%      |
| Fanless Mini PC Quieter 3                  | 1         | 2%      |
| eMachines EL1352                           | 1         | 2%      |
| Dell XPS 8930                              | 1         | 2%      |
| Dell OptiPlex 780                          | 1         | 2%      |
| Dell OptiPlex 755                          | 1         | 2%      |
| Dell OptiPlex 390                          | 1         | 2%      |
| Dell OptiPlex 3020                         | 1         | 2%      |
| Dell Latitude E5440                        | 1         | 2%      |
| Dell Latitude 7414                         | 1         | 2%      |
| Dell Latitude 7390                         | 1         | 2%      |
| Dell Inspiron 3793                         | 1         | 2%      |
| Dell DM051                                 | 1         | 2%      |
| Biostar A320MH                             | 1         | 2%      |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 2%      |
| ASUS PRIME H510M-K                         | 1         | 2%      |
| ASUS H110M-A/DP                            | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell OptiPlex           | 4         | 8%      |
| Lenovo ThinkPad         | 3         | 6%      |
| Dell Latitude           | 3         | 6%      |
| Acer Aspire             | 2         | 4%      |
| Acer AOD255E            | 2         | 4%      |
| TUXEDO N8xEJEK          | 1         | 2%      |
| Panasonic CFMX4-1       | 1         | 2%      |
| Panasonic CF-31ATXAX1M  | 1         | 2%      |
| Lenovo Yoga             | 1         | 2%      |
| Lenovo Legion           | 1         | 2%      |
| Lenovo G500             | 1         | 2%      |
| Inventec Dell           | 1         | 2%      |
| Intel NUC11BTMi7        | 1         | 2%      |
| HP t520                 | 1         | 2%      |
| HP Laptop               | 1         | 2%      |
| HP G62                  | 1         | 2%      |
| HP EliteDesk            | 1         | 2%      |
| HP All-in-One           | 1         | 2%      |
| GPU Company GWNR71517   | 1         | 2%      |
| Google Sand             | 1         | 2%      |
| Google Auron            | 1         | 2%      |
| Gigabyte PERSONAL       | 1         | 2%      |
| Gigabyte B450           | 1         | 2%      |
| Gigabyte B365M          | 1         | 2%      |
| Foxconn NETBOX          | 1         | 2%      |
| Fanless Mini PC Quieter | 1         | 2%      |
| eMachines EL1352        | 1         | 2%      |
| Dell XPS                | 1         | 2%      |
| Dell Inspiron           | 1         | 2%      |
| Dell DM051              | 1         | 2%      |
| Biostar A320MH          | 1         | 2%      |
| ASUS VivoBook           | 1         | 2%      |
| ASUS PRIME              | 1         | 2%      |
| ASUS H110M-A            | 1         | 2%      |
| Apple Macmini6          | 1         | 2%      |
| Apple Macmini4          | 1         | 2%      |
| Apple MacBookPro3       | 1         | 2%      |
| Apple iMac12            | 1         | 2%      |
| Apple iMac11            | 1         | 2%      |
| Acer V5-131             | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 9         | 18%     |
| 2018 | 7         | 14%     |
| 2019 | 5         | 10%     |
| 2021 | 4         | 8%      |
| 2022 | 3         | 6%      |
| 2017 | 3         | 6%      |
| 2014 | 3         | 6%      |
| 2020 | 2         | 4%      |
| 2015 | 2         | 4%      |
| 2013 | 2         | 4%      |
| 2012 | 2         | 4%      |
| 2011 | 2         | 4%      |
| 2007 | 2         | 4%      |
| 2016 | 1         | 2%      |
| 2009 | 1         | 2%      |
| 2008 | 1         | 2%      |
| 2006 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 24        | 48%     |
| Desktop    | 18        | 36%     |
| Mini pc    | 5         | 10%     |
| All in one | 3         | 6%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 48        | 96%     |
| Enabled  | 2         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 94%     |
| Yes  | 3         | 6%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 34%     |
| 3.01-4.0   | 11        | 22%     |
| 16.01-24.0 | 9         | 18%     |
| 8.01-16.0  | 4         | 8%      |
| 32.01-64.0 | 3         | 6%      |
| 2.01-3.0   | 2         | 4%      |
| 1.01-2.0   | 2         | 4%      |
| 0.51-1.0   | 2         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 31        | 59.62%  |
| 1.01-2.0  | 14        | 26.92%  |
| 2.01-3.0  | 4         | 7.69%   |
| 0.01-0.5  | 2         | 3.85%   |
| 8.01-16.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 68.63%  |
| 2      | 13        | 25.49%  |
| 3      | 2         | 3.92%   |
| 4      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 64.71%  |
| Yes       | 18        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 86%     |
| No        | 7         | 14%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 78%     |
| No        | 11        | 22%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 52%     |
| No        | 24        | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 40%     |
| Germany     | 7         | 14%     |
| UK          | 4         | 8%      |
| Spain       | 3         | 6%      |
| Italy       | 2         | 4%      |
| Vietnam     | 1         | 2%      |
| Thailand    | 1         | 2%      |
| Taiwan      | 1         | 2%      |
| Russia      | 1         | 2%      |
| Romania     | 1         | 2%      |
| Portugal    | 1         | 2%      |
| Netherlands | 1         | 2%      |
| Mexico      | 1         | 2%      |
| Kenya       | 1         | 2%      |
| Indonesia   | 1         | 2%      |
| Czechia     | 1         | 2%      |
| Belgium     | 1         | 2%      |
| Austria     | 1         | 2%      |
| Argentina   | 1         | 2%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 9.62%   |
| Fayetteville                | 5         | 9.62%   |
| Charlotte                   | 3         | 5.77%   |
| Egan                        | 2         | 3.85%   |
| Denver                      | 2         | 3.85%   |
| Zapopan                     | 1         | 1.92%   |
| Workum                      | 1         | 1.92%   |
| Vienna                      | 1         | 1.92%   |
| Uelzen                      | 1         | 1.92%   |
| Stockport                   | 1         | 1.92%   |
| St Petersburg               | 1         | 1.92%   |
| San Nicolás de los Arroyos | 1         | 1.92%   |
| Rome                        | 1         | 1.92%   |
| Rinteln                     | 1         | 1.92%   |
| Ratchathewi                 | 1         | 1.92%   |
| Poricany                    | 1         | 1.92%   |
| Palembang                   | 1         | 1.92%   |
| Nairobi                     | 1         | 1.92%   |
| Morgantown                  | 1         | 1.92%   |
| Milan                       | 1         | 1.92%   |
| Memphis                     | 1         | 1.92%   |
| Madrid                      | 1         | 1.92%   |
| Lisbon                      | 1         | 1.92%   |
| Leicester                   | 1         | 1.92%   |
| Langelsheim                 | 1         | 1.92%   |
| Idsegahuizum                | 1         | 1.92%   |
| Ho Chi Minh City            | 1         | 1.92%   |
| Golden Valley               | 1         | 1.92%   |
| Ghent                       | 1         | 1.92%   |
| Fongshan District           | 1         | 1.92%   |
| Filderstadt                 | 1         | 1.92%   |
| Eppelborn                   | 1         | 1.92%   |
| Düsseldorf                 | 1         | 1.92%   |
| Darmstadt                   | 1         | 1.92%   |
| Conway                      | 1         | 1.92%   |
| Cervera del Rio Alhama      | 1         | 1.92%   |
| Bradford                    | 1         | 1.92%   |
| Beiuș                      | 1         | 1.92%   |
| Barnsley                    | 1         | 1.92%   |
| Barcelona                   | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 20%     |
| Samsung Electronics | 10        | 13     | 15.38%  |
| WDC                 | 7         | 11     | 10.77%  |
| Kingston            | 6         | 7      | 9.23%   |
| SanDisk             | 5         | 6      | 7.69%   |
| Toshiba             | 3         | 4      | 4.62%   |
| Hitachi             | 2         | 2      | 3.08%   |
| Crucial             | 2         | 2      | 3.08%   |
| Apacer              | 2         | 2      | 3.08%   |
| Wibtek              | 1         | 1      | 1.54%   |
| Unknown             | 1         | 1      | 1.54%   |
| SSK                 | 1         | 2      | 1.54%   |
| SK hynix            | 1         | 1      | 1.54%   |
| Silicon Motion      | 1         | 1      | 1.54%   |
| OWC                 | 1         | 2      | 1.54%   |
| Mushkin             | 1         | 1      | 1.54%   |
| Micron Technology   | 1         | 2      | 1.54%   |
| Lexar               | 1         | 1      | 1.54%   |
| KIOXIA              | 1         | 1      | 1.54%   |
| Intel               | 1         | 1      | 1.54%   |
| ASMedia             | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |
| Unknown             | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST31000528AS 1TB             | 2         | 2.99%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2.99%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 2.99%   |
| Wibtek W800S 512GB                   | 1         | 1.49%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 1.49%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1.49%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.49%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 1.49%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 1.49%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.49%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.49%   |
| Unknown NCard  32GB                  | 1         | 1.49%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.49%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.49%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.49%   |
| SSK Disk 120GB                       | 1         | 1.49%   |
| SK hynix C2S3T/480G 480GB SSD        | 1         | 1.49%   |
| Silicon Motion NE-128 128GB          | 1         | 1.49%   |
| Seagate ST9320325ASG 320GB           | 1         | 1.49%   |
| Seagate ST9250315AS 250GB            | 1         | 1.49%   |
| Seagate ST500VM000-1SD101 500GB      | 1         | 1.49%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.49%   |
| Seagate ST3160023AS 160GB            | 1         | 1.49%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1.49%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.49%   |
| Seagate Expansion 1TB                | 1         | 1.49%   |
| Seagate BUP Slim BK 2TB              | 1         | 1.49%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1         | 1.49%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.49%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 1.49%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1         | 1.49%   |
| SanDisk DF4032  32GB                 | 1         | 1.49%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 1.49%   |
| Samsung SSD 980 1TB                  | 1         | 1.49%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.49%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.49%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.49%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.49%   |
| Samsung PM991a NVMe 512GB            | 1         | 1.49%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 16     | 52%     |
| WDC     | 4         | 4      | 16%     |
| Toshiba | 3         | 4      | 12%     |
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
| Samsung Electronics | 6         | 6      | 23.08%  |
| Kingston            | 5         | 6      | 19.23%  |
| SanDisk             | 4         | 4      | 15.38%  |
| Crucial             | 2         | 2      | 7.69%   |
| Apacer              | 2         | 2      | 7.69%   |
| Wibtek              | 1         | 1      | 3.85%   |
| WDC                 | 1         | 2      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| OWC                 | 1         | 2      | 3.85%   |
| Mushkin             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 2      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 30     | 41.67%  |
| HDD  | 21        | 30     | 35%     |
| NVMe | 12        | 17     | 20%     |
| MMC  | 2         | 4      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 54     | 68.85%  |
| NVMe | 12        | 17     | 19.67%  |
| SAS  | 5         | 6      | 8.2%    |
| MMC  | 2         | 4      | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 41     | 69.39%  |
| 0.51-1.0   | 11        | 14     | 22.45%  |
| 1.01-2.0   | 3         | 4      | 6.12%   |
| 4.01-10.0  | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 14        | 26.92%  |
| 251-500    | 13        | 25%     |
| 101-250    | 13        | 25%     |
| 1001-2000  | 4         | 7.69%   |
| 501-1000   | 3         | 5.77%   |
| 51-100     | 3         | 5.77%   |
| 21-50      | 2         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 86.27%  |
| 21-50     | 3         | 5.88%   |
| 101-250   | 2         | 3.92%   |
| 251-500   | 1         | 1.96%   |
| 1001-2000 | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 10%     |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 10%     |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 10%     |
| Seagate ST9250315AS 250GB          | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB    | 1         | 2      | 10%     |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 10%     |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 10%     |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 10%     |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 10%     |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 4      | 30%     |
| WDC      | 2         | 3      | 20%     |
| Toshiba  | 1         | 1      | 10%     |
| SanDisk  | 1         | 1      | 10%     |
| OWC      | 1         | 2      | 10%     |
| Mushkin  | 1         | 1      | 10%     |
| Kingston | 1         | 1      | 10%     |

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
| SSD  | 5         | 7      | 50%     |
| HDD  | 5         | 6      | 50%     |

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
| Works    | 39        | 57     | 69.64%  |
| Malfunc  | 10        | 13     | 17.86%  |
| Detected | 6         | 9      | 10.71%  |
| Failed   | 1         | 2      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 65.52%  |
| AMD                          | 7         | 12.07%  |
| Samsung Electronics          | 5         | 8.62%   |
| SanDisk                      | 2         | 3.45%   |
| Nvidia                       | 2         | 3.45%   |
| Silicon Motion               | 1         | 1.72%   |
| Shenzhen Longsys Electronics | 1         | 1.72%   |
| KIOXIA                       | 1         | 1.72%   |
| Kingston Technology Company  | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 8.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 4.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 4.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 4.29%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 2.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 2         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 1.43%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                             | 1         | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 1.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.43%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 1.43%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 1.43%   |
| Nvidia MCP61 IDE                                                              | 1         | 1.43%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 1.43%   |
| Kingston Company KC3000/Renegade NVMe SSD                                     | 1         | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.43%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 1         | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.43%   |
| Intel NVMe Optane Memory Series                                               | 1         | 1.43%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 1.43%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.43%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 1         | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 1.43%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 1.43%   |
| Intel 82Q35 Express PT IDER Controller                                        | 1         | 1.43%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                    | 1         | 1.43%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                    | 1         | 1.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 61.29%  |
| NVMe | 12        | 19.35%  |
| IDE  | 8         | 12.9%   |
| RAID | 4         | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 82%     |
| AMD    | 9         | 18%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 4%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 4%      |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 4%      |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz            | 1         | 2%      |
| Intel Pentium Gold G6405 CPU @ 4.10GHz        | 1         | 2%      |
| Intel Pentium D CPU 2.80GHz                   | 1         | 2%      |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2%      |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2%      |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2%      |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 2%      |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-2500S CPU @ 2.70GHz             | 1         | 2%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2%      |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 2%      |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1         | 2%      |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 2%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 2%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 2%      |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 2%      |
| Intel Celeron N5105 @ 2.00GHz                 | 1         | 2%      |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 2%      |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2%      |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 2%      |
| Intel Atom CPU D525 @ 1.80GHz                 | 1         | 2%      |
| Intel 12th Gen Core i5-1235U                  | 1         | 2%      |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz      | 1         | 2%      |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2%      |
| Intel 11th Gen Core i7-11700B @ 3.20GHz       | 1         | 2%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 22%     |
| Intel Core i7           | 6         | 12%     |
| Intel Core 2 Duo        | 5         | 10%     |
| Other                   | 4         | 8%      |
| Intel Celeron           | 4         | 8%      |
| Intel Core i3           | 3         | 6%      |
| Intel Atom              | 3         | 6%      |
| Intel Pentium           | 2         | 4%      |
| AMD Ryzen 5             | 2         | 4%      |
| AMD GX                  | 2         | 4%      |
| Intel Xeon              | 1         | 2%      |
| Intel Pentium Gold      | 1         | 2%      |
| Intel Pentium D         | 1         | 2%      |
| AMD Ryzen 7             | 1         | 2%      |
| AMD PRO A10             | 1         | 2%      |
| AMD Athlon II Dual-Core | 1         | 2%      |
| AMD Athlon II           | 1         | 2%      |
| AMD A12                 | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 54%     |
| 4      | 13        | 26%     |
| 6      | 4         | 8%      |
| 1      | 3         | 6%      |
| 8      | 2         | 4%      |
| 10     | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 58%     |
| 1      | 21        | 42%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 50        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 9.62%   |
| 0x306a9    | 3         | 5.77%   |
| 0x106ca    | 3         | 5.77%   |
| 0x1067a    | 3         | 5.77%   |
| 0x906ea    | 2         | 3.85%   |
| 0x806ea    | 2         | 3.85%   |
| 0x406e3    | 2         | 3.85%   |
| 0x40651    | 2         | 3.85%   |
| 0x306d4    | 2         | 3.85%   |
| 0x206a7    | 2         | 3.85%   |
| 0x20655    | 2         | 3.85%   |
| 0x0600611a | 2         | 3.85%   |
| 0xf44      | 1         | 1.92%   |
| 0xa0671    | 1         | 1.92%   |
| 0xa0653    | 1         | 1.92%   |
| 0x906ed    | 1         | 1.92%   |
| 0x906e9    | 1         | 1.92%   |
| 0x906c0    | 1         | 1.92%   |
| 0x906a4    | 1         | 1.92%   |
| 0x806d1    | 1         | 1.92%   |
| 0x806c1    | 1         | 1.92%   |
| 0x706e5    | 1         | 1.92%   |
| 0x6fa      | 1         | 1.92%   |
| 0x506c9    | 1         | 1.92%   |
| 0x306c3    | 1         | 1.92%   |
| 0x30678    | 1         | 1.92%   |
| 0x206d7    | 1         | 1.92%   |
| 0x10676    | 1         | 1.92%   |
| 0x08600106 | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |
| 0x0810100b | 1         | 1.92%   |
| 0x07030105 | 1         | 1.92%   |
| 0x07030104 | 1         | 1.92%   |
| 0x010000c8 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 11.76%  |
| Penryn      | 4         | 7.84%   |
| IceLake     | 4         | 7.84%   |
| Westmere    | 3         | 5.88%   |
| SandyBridge | 3         | 5.88%   |
| IvyBridge   | 3         | 5.88%   |
| Haswell     | 3         | 5.88%   |
| Bonnell     | 3         | 5.88%   |
| Skylake     | 2         | 3.92%   |
| Puma        | 2         | 3.92%   |
| K10         | 2         | 3.92%   |
| Excavator   | 2         | 3.92%   |
| Broadwell   | 2         | 3.92%   |
| Unknown     | 2         | 3.92%   |
| Zen+        | 1         | 1.96%   |
| Zen 2       | 1         | 1.96%   |
| Zen         | 1         | 1.96%   |
| Tremont     | 1         | 1.96%   |
| TigerLake   | 1         | 1.96%   |
| Silvermont  | 1         | 1.96%   |
| NetBurst    | 1         | 1.96%   |
| Goldmont    | 1         | 1.96%   |
| Core        | 1         | 1.96%   |
| CometLake   | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 58.62%  |
| AMD    | 15        | 25.86%  |
| Nvidia | 9         | 15.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 5.08%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 5.08%   |
| Intel UHD Graphics 620                                                    | 2         | 3.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 3.39%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 3.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.69%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 1.69%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                         | 1         | 1.69%   |
| Nvidia GA102 [GeForce RTX 3080]                                           | 1         | 1.69%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 1.69%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                    | 1         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.69%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.69%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.69%   |
| Intel HD Graphics 630                                                     | 1         | 1.69%   |
| Intel HD Graphics 5500                                                    | 1         | 1.69%   |
| Intel HD Graphics                                                         | 1         | 1.69%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                  | 1         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.69%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1         | 1.69%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                   | 1         | 1.69%   |
| Intel 82Q35 Express Integrated Graphics Controller                        | 1         | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1         | 1.69%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                             | 1         | 1.69%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                | 1         | 1.69%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]          | 1         | 1.69%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.69%   |
| AMD RV370 [Radeon X600/X600 SE]                                           | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 52.94%  |
| 1 x AMD        | 11        | 21.57%  |
| 1 x Nvidia     | 6         | 11.76%  |
| Intel + Nvidia | 3         | 5.88%   |
| Intel + AMD    | 3         | 5.88%   |
| 2 x AMD        | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 92.16%  |
| Unknown     | 3         | 5.88%   |
| Proprietary | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 59.62%  |
| 0.01-0.5   | 12        | 23.08%  |
| 3.01-4.0   | 3         | 5.77%   |
| 1.01-2.0   | 2         | 3.85%   |
| 0.51-1.0   | 2         | 3.85%   |
| 7.01-8.0   | 1         | 1.92%   |
| 8.01-16.0  | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 19.57%  |
| Chimei Innolux          | 4         | 8.7%    |
| Samsung Electronics     | 3         | 6.52%   |
| LG Display              | 3         | 6.52%   |
| Lenovo                  | 3         | 6.52%   |
| Dell                    | 3         | 6.52%   |
| Zoran                   | 2         | 4.35%   |
| Sceptre Tech            | 2         | 4.35%   |
| Goldstar                | 2         | 4.35%   |
| BOE                     | 2         | 4.35%   |
| Sony                    | 1         | 2.17%   |
| Sharp                   | 1         | 2.17%   |
| SAC                     | 1         | 2.17%   |
| Philips                 | 1         | 2.17%   |
| JDI                     | 1         | 2.17%   |
| Insignia                | 1         | 2.17%   |
| HUAWEI                  | 1         | 2.17%   |
| Hewlett-Packard         | 1         | 2.17%   |
| eMachines               | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| ASUSTek Computer        | 1         | 2.17%   |
| Apple                   | 1         | 2.17%   |
| AOC                     | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                       | 2         | 4.35%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch            | 2         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 4.35%   |
| Sony TV SNY0101 1360x768                                                 | 1         | 2.17%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                   | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch    | 1         | 2.17%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch        | 1         | 2.17%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch        | 1         | 2.17%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                    | 1         | 2.17%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                       | 1         | 2.17%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch            | 1         | 2.17%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.17%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 1         | 2.17%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                  | 1         | 2.17%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                     | 1         | 2.17%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                    | 1         | 2.17%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch                   | 1         | 2.17%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                     | 1         | 2.17%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch             | 1         | 2.17%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch                 | 1         | 2.17%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                   | 1         | 2.17%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                    | 1         | 2.17%   |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                        | 1         | 2.17%   |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                        | 1         | 2.17%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch         | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 2.17%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                     | 1         | 2.17%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 44.44%  |
| 1366x768 (WXGA)    | 7         | 15.56%  |
| 1360x768           | 4         | 8.89%   |
| 2560x1440 (QHD)    | 3         | 6.67%   |
| 3840x2160 (4K)     | 2         | 4.44%   |
| 1280x800 (WXGA)    | 2         | 4.44%   |
| 1024x600           | 2         | 4.44%   |
| 3440x1440          | 1         | 2.22%   |
| 1920x1200 (WUXGA)  | 1         | 2.22%   |
| 1680x1050 (WSXGA+) | 1         | 2.22%   |
| 1600x900 (HD+)     | 1         | 2.22%   |
| 1024x768 (XGA)     | 1         | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 21.74%  |
| 24      | 6         | 13.04%  |
| 14      | 5         | 10.87%  |
| 21      | 4         | 8.7%    |
| 22      | 3         | 6.52%   |
| 17      | 3         | 6.52%   |
| 31      | 2         | 4.35%   |
| 23      | 2         | 4.35%   |
| 13      | 2         | 4.35%   |
| 10      | 2         | 4.35%   |
| 84      | 1         | 2.17%   |
| 34      | 1         | 2.17%   |
| 32      | 1         | 2.17%   |
| 27      | 1         | 2.17%   |
| 12      | 1         | 2.17%   |
| 11      | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 34.78%  |
| 501-600     | 9         | 19.57%  |
| 401-500     | 7         | 15.22%  |
| 201-300     | 5         | 10.87%  |
| 351-400     | 3         | 6.52%   |
| 701-800     | 2         | 4.35%   |
| 601-700     | 2         | 4.35%   |
| 1501-2000   | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 86.36%  |
| 16/10 | 4         | 9.09%   |
| 4/3   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 30.43%  |
| 101-110        | 10        | 21.74%  |
| 81-90          | 6         | 13.04%  |
| 351-500        | 4         | 8.7%    |
| 121-130        | 3         | 6.52%   |
| 41-50          | 2         | 4.35%   |
| More than 1000 | 1         | 2.17%   |
| 71-80          | 1         | 2.17%   |
| 61-70          | 1         | 2.17%   |
| 51-60          | 1         | 2.17%   |
| 301-350        | 1         | 2.17%   |
| 151-200        | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 32.61%  |
| 51-100  | 15        | 32.61%  |
| 121-160 | 10        | 21.74%  |
| 161-240 | 4         | 8.7%    |
| 1-50    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 86.27%  |
| 0     | 4         | 7.84%   |
| 2     | 3         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 29.73%  |
| Intel                           | 21        | 28.38%  |
| Qualcomm Atheros                | 13        | 17.57%  |
| Broadcom                        | 10        | 13.51%  |
| Qualcomm Atheros Communications | 3         | 4.05%   |
| Ralink Technology               | 1         | 1.35%   |
| Prolific Technology             | 1         | 1.35%   |
| Nvidia                          | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| Marvell Technology Group        | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 14        | 15.73%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 4.49%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.25%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 2         | 2.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.25%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 2.25%   |
| Intel Wireless 8260                                                                   | 2         | 2.25%   |
| Intel Wireless 7260                                                                   | 2         | 2.25%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 2.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.12%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.12%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.12%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 1.12%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.12%   |
| Prolific USB-Serial Controller                                                        | 1         | 1.12%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 1.12%   |
| MediaTek 100026191                                                                    | 1         | 1.12%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 1.12%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.12%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 1.12%   |
| Intel Wireless 7265                                                                   | 1         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.12%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.12%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1         | 1.12%   |
| Intel I211 Gigabit Network Connection                                                 | 1         | 1.12%   |
| Intel Ethernet Controller I225-LM                                                     | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 35.71%  |
| Qualcomm Atheros                | 10        | 23.81%  |
| Realtek Semiconductor           | 8         | 19.05%  |
| Broadcom                        | 5         | 11.9%   |
| Qualcomm Atheros Communications | 3         | 7.14%   |
| Ralink Technology               | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 9.52%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 4.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 4.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 4.76%   |
| Intel Wireless 8260                                                                   | 2         | 4.76%   |
| Intel Wireless 7260                                                                   | 2         | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.38%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.38%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.38%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.38%   |
| Intel Wireless-AC 9260                                                                | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.38%   |
| Intel Wireless 7265                                                                   | 1         | 2.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 2.38%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.38%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 39.13%  |
| Intel                    | 13        | 28.26%  |
| Broadcom                 | 7         | 15.22%  |
| Qualcomm Atheros         | 5         | 10.87%  |
| Nvidia                   | 1         | 2.17%   |
| MediaTek                 | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 30.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 4.35%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.17%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.17%   |
| MediaTek 100026191                                                | 1         | 2.17%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.17%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.17%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.17%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.17%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.17%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.17%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 51.81%  |
| WiFi     | 39        | 46.99%  |
| Modem    | 1         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 53.85%  |
| WiFi     | 24        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 56.86%  |
| 1     | 20        | 39.22%  |
| 3     | 1         | 1.96%   |
| 0     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 60.78%  |
| Yes  | 20        | 39.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 42.31%  |
| Apple                           | 5         | 19.23%  |
| Qualcomm Atheros Communications | 3         | 11.54%  |
| Realtek Semiconductor           | 2         | 7.69%   |
| Lite-On Technology              | 2         | 7.69%   |
| IMC Networks                    | 2         | 7.69%   |
| Broadcom                        | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 23.08%  |
| Intel AX201 Bluetooth                              | 3         | 11.54%  |
| Realtek Bluetooth Radio                            | 2         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 7.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 2         | 7.69%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 3.85%   |
| IMC Networks Bluetooth Radio                       | 1         | 3.85%   |
| IMC Networks Bluetooth Device                      | 1         | 3.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.85%   |
| Apple Bluetooth USB Host Controller                | 1         | 3.85%   |
| Apple Bluetooth Host Controller                    | 1         | 3.85%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 60%     |
| AMD                   | 13        | 20%     |
| Nvidia                | 7         | 10.77%  |
| SAVITECH              | 1         | 1.54%   |
| Roland                | 1         | 1.54%   |
| Realtek Semiconductor | 1         | 1.54%   |
| JMTek                 | 1         | 1.54%   |
| Huawei Technologies   | 1         | 1.54%   |
| Anlya.cn              | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.56%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.56%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.56%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.56%   |
| SAVITECH USB HIFI Audio                                                    | 1         | 1.28%   |
| Roland QUAD-CAPTURE                                                        | 1         | 1.28%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.28%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.28%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.28%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.28%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.28%   |
| JMTek USB Audio Device                                                     | 1         | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.28%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.28%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.28%   |
| Intel HD Graphics SGPC                                                     | 1         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.28%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 10        | 16.67%  |
| Unknown             | 7         | 11.67%  |
| Crucial             | 7         | 11.67%  |
| Samsung Electronics | 6         | 10%     |
| Micron Technology   | 6         | 10%     |
| Kingston            | 4         | 6.67%   |
| A-DATA Technology   | 4         | 6.67%   |
| Elpida              | 3         | 5%      |
| Corsair             | 3         | 5%      |
| Timetec             | 2         | 3.33%   |
| Unknown (08C8)      | 1         | 1.67%   |
| Team                | 1         | 1.67%   |
| SK_Hynix            | 1         | 1.67%   |
| Patriot             | 1         | 1.67%   |
| Nanya Technology    | 1         | 1.67%   |
| Infineon            | 1         | 1.67%   |
| G.Skill             | 1         | 1.67%   |
| Unknown             | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.17%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.59%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.59%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s     | 1         | 1.59%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 1.59%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.59%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 1.59%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.59%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.59%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.59%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.59%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s                  | 1         | 1.59%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.59%   |
| Patriot RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.59%   |
| Nanya RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 1.59%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.59%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 1.59%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.59%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Micron RAM 16HTF12864AY-53EB1 1GB DIMM DDR 533MT/s               | 1         | 1.59%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                        | 1         | 1.59%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                        | 1         | 1.59%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.59%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 22        | 45.83%  |
| DDR4   | 15        | 31.25%  |
| DDR2   | 5         | 10.42%  |
| LPDDR4 | 4         | 8.33%   |
| LPDDR3 | 1         | 2.08%   |
| DDR    | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 56.25%  |
| DIMM         | 15        | 31.25%  |
| Row Of Chips | 3         | 6.25%   |
| Unknown      | 2         | 4.17%   |
| Chip         | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 32%     |
| 4096  | 15        | 30%     |
| 2048  | 9         | 18%     |
| 1024  | 5         | 10%     |
| 16384 | 3         | 6%      |
| 32768 | 1         | 2%      |
| 512   | 1         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 13        | 25%     |
| 2667  | 6         | 11.54%  |
| 667   | 6         | 11.54%  |
| 1067  | 5         | 9.62%   |
| 3200  | 4         | 7.69%   |
| 2400  | 3         | 5.77%   |
| 8400  | 1         | 1.92%   |
| 4267  | 1         | 1.92%   |
| 4266  | 1         | 1.92%   |
| 3733  | 1         | 1.92%   |
| 3600  | 1         | 1.92%   |
| 2800  | 1         | 1.92%   |
| 2733  | 1         | 1.92%   |
| 2666  | 1         | 1.92%   |
| 1867  | 1         | 1.92%   |
| 1866  | 1         | 1.92%   |
| 1800  | 1         | 1.92%   |
| 1333  | 1         | 1.92%   |
| 1066  | 1         | 1.92%   |
| 800   | 1         | 1.92%   |
| 533   | 1         | 1.92%   |

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
| Chicony Electronics           | 4         | 16.67%  |
| Apple                         | 4         | 16.67%  |
| Sunplus Innovation Technology | 2         | 8.33%   |
| Realtek Semiconductor         | 2         | 8.33%   |
| Microdia                      | 2         | 8.33%   |
| Logitech                      | 2         | 8.33%   |
| IMC Networks                  | 2         | 8.33%   |
| ALi                           | 2         | 8.33%   |
| Suyin                         | 1         | 4.17%   |
| Quanta                        | 1         | 4.17%   |
| Luxvisions Innotech Limited   | 1         | 4.17%   |
| Bison Electronics             | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 2         | 8.33%   |
| Apple Built-in iSight                               | 2         | 8.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 4.17%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 4.17%   |
| Sunplus HD WebCam                                   | 1         | 4.17%   |
| Realtek Lenovo EasyCamera                           | 1         | 4.17%   |
| Realtek 2SF022                                      | 1         | 4.17%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.17%   |
| Microdia Integrated Webcam                          | 1         | 4.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.17%   |
| Logitech Logitech Webcam C160                       | 1         | 4.17%   |
| Logitech HD Pro Webcam C920                         | 1         | 4.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4.17%   |
| IMC Networks Integrated Camera                      | 1         | 4.17%   |
| Chicony Integrated Camera                           | 1         | 4.17%   |
| Chicony HD WebCam (Acer)                            | 1         | 4.17%   |
| Bison BisonCam, NB Pro                              | 1         | 4.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 4.17%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 4.17%   |
| ALi WebCam                                          | 1         | 4.17%   |
| ALi Gateway Webcam                                  | 1         | 4.17%   |

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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 74.51%  |
| 1     | 13        | 25.49%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 38.46%  |
| Multimedia controller    | 2         | 15.38%  |
| Fingerprint reader       | 2         | 15.38%  |
| Net/wireless             | 1         | 7.69%   |
| Communication controller | 1         | 7.69%   |
| Chipcard                 | 1         | 7.69%   |
| Camera                   | 1         | 7.69%   |

