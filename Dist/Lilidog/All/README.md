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

Total: 66

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| BANGHO        | Suma 1025                   | Tablet      | [5dab721f9a](https://linux-hardware.org/?probe=5dab721f9a) | Aug 21, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Lilidog 22 | 40        | 75.47%  |
| Lilidog 23 | 13        | 24.53%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 52        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-16-amd64           | 6         | 10%     |
| 6.1.0-9-amd64             | 5         | 8.33%   |
| 5.10.0-18-amd64           | 5         | 8.33%   |
| 5.10.0-15-amd64           | 5         | 8.33%   |
| 6.1.0-10-amd64            | 4         | 6.67%   |
| 5.10.0-13-amd64           | 4         | 6.67%   |
| 5.10.0-21-amd64           | 3         | 5%      |
| 5.10.0-20-amd64           | 3         | 5%      |
| 6.1.0-7-amd64             | 2         | 3.33%   |
| 6.1.0-11-amd64            | 2         | 3.33%   |
| 6.0.8-x64v1-xanmod1       | 2         | 3.33%   |
| 5.10.0-14-amd64           | 2         | 3.33%   |
| 6.4.5-1-liquorix-amd64    | 1         | 1.67%   |
| 6.2.12-x64v1-xanmod1      | 1         | 1.67%   |
| 6.2.11-x64v1-xanmod1      | 1         | 1.67%   |
| 6.1.0-7.2-liquorix-amd64  | 1         | 1.67%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 1.67%   |
| 6.0.10-x64v1-xanmod1      | 1         | 1.67%   |
| 6.0.0-5-amd64             | 1         | 1.67%   |
| 6.0.0-2-amd64             | 1         | 1.67%   |
| 6.0.0-0.deb11.6-amd64     | 1         | 1.67%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 1.67%   |
| 5.19.0-7.1-liquorix-amd64 | 1         | 1.67%   |
| 5.19.0-0.deb11.2-amd64    | 1         | 1.67%   |
| 5.18.0-1-amd64            | 1         | 1.67%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 1.67%   |
| 5.10.0-22-amd64           | 1         | 1.67%   |
| 5.10.0-19-amd64           | 1         | 1.67%   |
| 5.10.0-17-amd64           | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 29        | 50.88%  |
| 6.1.0   | 14        | 24.56%  |
| 6.0.0   | 4         | 7.02%   |
| 6.0.8   | 2         | 3.51%   |
| 5.19.0  | 2         | 3.51%   |
| 6.4.5   | 1         | 1.75%   |
| 6.2.12  | 1         | 1.75%   |
| 6.2.11  | 1         | 1.75%   |
| 6.0.10  | 1         | 1.75%   |
| 5.18.0  | 1         | 1.75%   |
| 5.17.0  | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 29        | 50.88%  |
| 6.1     | 14        | 24.56%  |
| 6.0     | 7         | 12.28%  |
| 6.2     | 2         | 3.51%   |
| 5.19    | 2         | 3.51%   |
| 6.4     | 1         | 1.75%   |
| 5.18    | 1         | 1.75%   |
| 5.17    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 47        | 87.04%  |
| openbox          | 7         | 12.96%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 52        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 52        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 39        | 73.58%  |
| de_DE | 4         | 7.55%   |
| es_MX | 2         | 3.77%   |
| es_ES | 2         | 3.77%   |
| en_GB | 2         | 3.77%   |
| ru_RU | 1         | 1.89%   |
| es_CL | 1         | 1.89%   |
| en_IE | 1         | 1.89%   |
| cs_CZ | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 29        | 55.77%  |
| BIOS | 23        | 44.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 66.04%  |
| Overlay | 15        | 28.3%   |
| Btrfs   | 3         | 5.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 34        | 65.38%  |
| MBR  | 18        | 34.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 62.96%  |
| Yes       | 20        | 37.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 82.69%  |
| Yes       | 9         | 17.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 19.23%  |
| Lenovo              | 6         | 11.54%  |
| Hewlett-Packard     | 6         | 11.54%  |
| Apple               | 5         | 9.62%   |
| Acer                | 5         | 9.62%   |
| Gigabyte Technology | 3         | 5.77%   |
| ASUSTek Computer    | 3         | 5.77%   |
| Panasonic           | 2         | 3.85%   |
| Google              | 2         | 3.85%   |
| TUXEDO              | 1         | 1.92%   |
| Inventec            | 1         | 1.92%   |
| Intel               | 1         | 1.92%   |
| GPU Company         | 1         | 1.92%   |
| Foxconn             | 1         | 1.92%   |
| Fanless Mini PC     | 1         | 1.92%   |
| eMachines           | 1         | 1.92%   |
| Biostar             | 1         | 1.92%   |
| BANGHO              | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 3.85%   |
| TUXEDO N8xEJEK                             | 1         | 1.92%   |
| Panasonic CFMX4-1                          | 1         | 1.92%   |
| Panasonic CF-31ATXAX1M                     | 1         | 1.92%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 1.92%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 1.92%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 1.92%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 1.92%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH         | 1         | 1.92%   |
| Lenovo G500 20236                          | 1         | 1.92%   |
| Inventec Dell Thin Client Desktop 5060     | 1         | 1.92%   |
| Intel NUC11BTMi7                           | 1         | 1.92%   |
| HP t520 Flexible Series TC                 | 1         | 1.92%   |
| HP Laptop 15s-fq1xxx                       | 1         | 1.92%   |
| HP G62                                     | 1         | 1.92%   |
| HP EliteDesk 705 G2 MINI                   | 1         | 1.92%   |
| HP All-in-One Desktop 27-cb1xxx            | 1         | 1.92%   |
| HP 435                                     | 1         | 1.92%   |
| GPU Company GWNR71517                      | 1         | 1.92%   |
| Google Sand                                | 1         | 1.92%   |
| Google Auron_Yuna                          | 1         | 1.92%   |
| Gigabyte PERSONAL COMPUTER                 | 1         | 1.92%   |
| Gigabyte B450 AORUS PRO                    | 1         | 1.92%   |
| Gigabyte B365M DS3H                        | 1         | 1.92%   |
| Foxconn NETBOX NT-425/525                  | 1         | 1.92%   |
| Fanless Mini PC Quieter 3                  | 1         | 1.92%   |
| eMachines EL1352                           | 1         | 1.92%   |
| Dell XPS 8930                              | 1         | 1.92%   |
| Dell OptiPlex 780                          | 1         | 1.92%   |
| Dell OptiPlex 755                          | 1         | 1.92%   |
| Dell OptiPlex 390                          | 1         | 1.92%   |
| Dell OptiPlex 3020                         | 1         | 1.92%   |
| Dell Latitude E5440                        | 1         | 1.92%   |
| Dell Latitude 7414                         | 1         | 1.92%   |
| Dell Latitude 7390                         | 1         | 1.92%   |
| Dell Inspiron 3793                         | 1         | 1.92%   |
| Dell DM051                                 | 1         | 1.92%   |
| Biostar A320MH                             | 1         | 1.92%   |
| BANGHO Suma 1025                           | 1         | 1.92%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell OptiPlex           | 4         | 7.69%   |
| Lenovo ThinkPad         | 3         | 5.77%   |
| Dell Latitude           | 3         | 5.77%   |
| Acer Aspire             | 2         | 3.85%   |
| Acer AOD255E            | 2         | 3.85%   |
| TUXEDO N8xEJEK          | 1         | 1.92%   |
| Panasonic CFMX4-1       | 1         | 1.92%   |
| Panasonic CF-31ATXAX1M  | 1         | 1.92%   |
| Lenovo Yoga             | 1         | 1.92%   |
| Lenovo Legion           | 1         | 1.92%   |
| Lenovo G500             | 1         | 1.92%   |
| Inventec Dell           | 1         | 1.92%   |
| Intel NUC11BTMi7        | 1         | 1.92%   |
| HP t520                 | 1         | 1.92%   |
| HP Laptop               | 1         | 1.92%   |
| HP G62                  | 1         | 1.92%   |
| HP EliteDesk            | 1         | 1.92%   |
| HP All-in-One           | 1         | 1.92%   |
| HP 435                  | 1         | 1.92%   |
| GPU Company GWNR71517   | 1         | 1.92%   |
| Google Sand             | 1         | 1.92%   |
| Google Auron            | 1         | 1.92%   |
| Gigabyte PERSONAL       | 1         | 1.92%   |
| Gigabyte B450           | 1         | 1.92%   |
| Gigabyte B365M          | 1         | 1.92%   |
| Foxconn NETBOX          | 1         | 1.92%   |
| Fanless Mini PC Quieter | 1         | 1.92%   |
| eMachines EL1352        | 1         | 1.92%   |
| Dell XPS                | 1         | 1.92%   |
| Dell Inspiron           | 1         | 1.92%   |
| Dell DM051              | 1         | 1.92%   |
| Biostar A320MH          | 1         | 1.92%   |
| BANGHO Suma             | 1         | 1.92%   |
| ASUS VivoBook           | 1         | 1.92%   |
| ASUS PRIME              | 1         | 1.92%   |
| ASUS H110M-A            | 1         | 1.92%   |
| Apple Macmini6          | 1         | 1.92%   |
| Apple Macmini4          | 1         | 1.92%   |
| Apple MacBookPro3       | 1         | 1.92%   |
| Apple iMac12            | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 9         | 17.31%  |
| 2018 | 7         | 13.46%  |
| 2019 | 5         | 9.62%   |
| 2021 | 4         | 7.69%   |
| 2014 | 4         | 7.69%   |
| 2022 | 3         | 5.77%   |
| 2017 | 3         | 5.77%   |
| 2011 | 3         | 5.77%   |
| 2020 | 2         | 3.85%   |
| 2015 | 2         | 3.85%   |
| 2013 | 2         | 3.85%   |
| 2012 | 2         | 3.85%   |
| 2007 | 2         | 3.85%   |
| 2016 | 1         | 1.92%   |
| 2009 | 1         | 1.92%   |
| 2008 | 1         | 1.92%   |
| 2006 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 25        | 48.08%  |
| Desktop    | 18        | 34.62%  |
| Mini pc    | 5         | 9.62%   |
| All in one | 3         | 5.77%   |
| Tablet     | 1         | 1.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 50        | 96.15%  |
| Enabled  | 2         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 94.23%  |
| Yes  | 3         | 5.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 34.62%  |
| 3.01-4.0   | 12        | 23.08%  |
| 16.01-24.0 | 9         | 17.31%  |
| 8.01-16.0  | 4         | 7.69%   |
| 32.01-64.0 | 3         | 5.77%   |
| 2.01-3.0   | 2         | 3.85%   |
| 1.01-2.0   | 2         | 3.85%   |
| 0.51-1.0   | 2         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 32        | 59.26%  |
| 1.01-2.0  | 15        | 27.78%  |
| 2.01-3.0  | 4         | 7.41%   |
| 0.01-0.5  | 2         | 3.7%    |
| 8.01-16.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 67.92%  |
| 2      | 14        | 26.42%  |
| 3      | 2         | 3.77%   |
| 4      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 66.04%  |
| Yes       | 18        | 33.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 86.54%  |
| No        | 7         | 13.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 78.85%  |
| No        | 11        | 21.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 53.85%  |
| No        | 24        | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 38.46%  |
| Germany     | 7         | 13.46%  |
| UK          | 4         | 7.69%   |
| Spain       | 3         | 5.77%   |
| Italy       | 2         | 3.85%   |
| Argentina   | 2         | 3.85%   |
| Vietnam     | 1         | 1.92%   |
| Thailand    | 1         | 1.92%   |
| Taiwan      | 1         | 1.92%   |
| Russia      | 1         | 1.92%   |
| Romania     | 1         | 1.92%   |
| Portugal    | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Mexico      | 1         | 1.92%   |
| Kenya       | 1         | 1.92%   |
| Indonesia   | 1         | 1.92%   |
| Czechia     | 1         | 1.92%   |
| Chile       | 1         | 1.92%   |
| Belgium     | 1         | 1.92%   |
| Austria     | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 9.26%   |
| Fayetteville                | 5         | 9.26%   |
| Charlotte                   | 3         | 5.56%   |
| Egan                        | 2         | 3.7%    |
| Denver                      | 2         | 3.7%    |
| Zapopan                     | 1         | 1.85%   |
| Workum                      | 1         | 1.85%   |
| Viña del Mar               | 1         | 1.85%   |
| Vienna                      | 1         | 1.85%   |
| Uelzen                      | 1         | 1.85%   |
| Stockport                   | 1         | 1.85%   |
| St Petersburg               | 1         | 1.85%   |
| San Nicolás de los Arroyos | 1         | 1.85%   |
| Rome                        | 1         | 1.85%   |
| Rio Ceballos                | 1         | 1.85%   |
| Rinteln                     | 1         | 1.85%   |
| Ratchathewi                 | 1         | 1.85%   |
| Poricany                    | 1         | 1.85%   |
| Palembang                   | 1         | 1.85%   |
| Nairobi                     | 1         | 1.85%   |
| Morgantown                  | 1         | 1.85%   |
| Milan                       | 1         | 1.85%   |
| Memphis                     | 1         | 1.85%   |
| Madrid                      | 1         | 1.85%   |
| Lisbon                      | 1         | 1.85%   |
| Leicester                   | 1         | 1.85%   |
| Langelsheim                 | 1         | 1.85%   |
| Idsegahuizum                | 1         | 1.85%   |
| Ho Chi Minh City            | 1         | 1.85%   |
| Golden Valley               | 1         | 1.85%   |
| Ghent                       | 1         | 1.85%   |
| Fongshan District           | 1         | 1.85%   |
| Filderstadt                 | 1         | 1.85%   |
| Eppelborn                   | 1         | 1.85%   |
| Düsseldorf                 | 1         | 1.85%   |
| Darmstadt                   | 1         | 1.85%   |
| Conway                      | 1         | 1.85%   |
| Cervera del Rio Alhama      | 1         | 1.85%   |
| Bradford                    | 1         | 1.85%   |
| Beiuș                      | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 22.06%  |
| Samsung Electronics | 10        | 13     | 14.71%  |
| WDC                 | 7         | 11     | 10.29%  |
| Kingston            | 6         | 7      | 8.82%   |
| SanDisk             | 5         | 6      | 7.35%   |
| Toshiba             | 3         | 4      | 4.41%   |
| Hitachi             | 2         | 2      | 2.94%   |
| Crucial             | 2         | 2      | 2.94%   |
| Apacer              | 2         | 2      | 2.94%   |
| Wibtek              | 1         | 1      | 1.47%   |
| Unknown             | 1         | 1      | 1.47%   |
| SSK                 | 1         | 2      | 1.47%   |
| SK hynix            | 1         | 1      | 1.47%   |
| Silicon Motion      | 1         | 1      | 1.47%   |
| OWC                 | 1         | 2      | 1.47%   |
| Mushkin             | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 2      | 1.47%   |
| Lexar               | 1         | 1      | 1.47%   |
| KIOXIA              | 1         | 1      | 1.47%   |
| Intel               | 1         | 1      | 1.47%   |
| China               | 1         | 1      | 1.47%   |
| ASMedia             | 1         | 1      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |
| A-DATA Technology   | 1         | 1      | 1.47%   |
| Unknown             | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST31000528AS 1TB             | 2         | 2.86%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2.86%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 2.86%   |
| Wibtek W800S 512GB SSD               | 1         | 1.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 1.43%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1.43%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.43%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 1.43%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 1.43%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 1.43%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.43%   |
| Unknown NCard  32GB                  | 1         | 1.43%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.43%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.43%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.43%   |
| SSK Disk 1TB                         | 1         | 1.43%   |
| SK hynix C2S3T/480G 480GB SSD        | 1         | 1.43%   |
| Silicon Motion NE-128 128GB          | 1         | 1.43%   |
| Seagate ST9320325ASG 320GB           | 1         | 1.43%   |
| Seagate ST9320325AS 320GB            | 1         | 1.43%   |
| Seagate ST9250315AS 250GB            | 1         | 1.43%   |
| Seagate ST500VM000-1SD101 500GB      | 1         | 1.43%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.43%   |
| Seagate ST3160023AS 160GB            | 1         | 1.43%   |
| Seagate ST2000DX002-2DV164 2TB       | 1         | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.43%   |
| Seagate Expansion 2TB                | 1         | 1.43%   |
| Seagate BUP Slim BK 1TB              | 1         | 1.43%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD   | 1         | 1.43%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.43%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 1.43%   |
| SanDisk SD7SB6S128G1122 128GB SSD    | 1         | 1.43%   |
| SanDisk DF4032  32GB                 | 1         | 1.43%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 1.43%   |
| Samsung SSD 980 1TB                  | 1         | 1.43%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.43%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.43%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.43%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 18     | 55.56%  |
| WDC     | 4         | 4      | 14.81%  |
| Toshiba | 3         | 4      | 11.11%  |
| Hitachi | 2         | 2      | 7.41%   |
| SSK     | 1         | 2      | 3.7%    |
| ASMedia | 1         | 1      | 3.7%    |
| Apple   | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 22.22%  |
| Kingston            | 5         | 6      | 18.52%  |
| SanDisk             | 4         | 4      | 14.81%  |
| Crucial             | 2         | 2      | 7.41%   |
| Apacer              | 2         | 2      | 7.41%   |
| Wibtek              | 1         | 1      | 3.7%    |
| WDC                 | 1         | 2      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| OWC                 | 1         | 2      | 3.7%    |
| Mushkin             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 2      | 3.7%    |
| China               | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 26        | 31     | 41.27%  |
| HDD  | 23        | 32     | 36.51%  |
| NVMe | 12        | 17     | 19.05%  |
| MMC  | 2         | 4      | 3.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 57     | 69.84%  |
| NVMe | 12        | 17     | 19.05%  |
| SAS  | 5         | 6      | 7.94%   |
| MMC  | 2         | 4      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 42     | 70%     |
| 0.51-1.0   | 11        | 16     | 22%     |
| 1.01-2.0   | 3         | 4      | 6%      |
| 4.01-10.0  | 1         | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 15        | 27.78%  |
| 1-20       | 14        | 25.93%  |
| 101-250    | 13        | 24.07%  |
| 1001-2000  | 4         | 7.41%   |
| 501-1000   | 3         | 5.56%   |
| 51-100     | 3         | 5.56%   |
| 21-50      | 2         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 86.79%  |
| 21-50     | 3         | 5.66%   |
| 101-250   | 2         | 3.77%   |
| 251-500   | 1         | 1.89%   |
| 1001-2000 | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 7      | 50%     |
| HDD  | 5         | 6      | 50%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 41        | 59     | 69.49%  |
| Malfunc  | 10        | 13     | 16.95%  |
| Detected | 6         | 9      | 10.17%  |
| Failed   | 2         | 3      | 3.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 65%     |
| AMD                          | 8         | 13.33%  |
| Samsung Electronics          | 5         | 8.33%   |
| SanDisk                      | 2         | 3.33%   |
| Nvidia                       | 2         | 3.33%   |
| Silicon Motion               | 1         | 1.67%   |
| Shenzhen Longsys Electronics | 1         | 1.67%   |
| KIOXIA                       | 1         | 1.67%   |
| Kingston Technology Company  | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 8.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 4.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 4.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 4.11%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2         | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 2         | 2.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 2.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1         | 1.37%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                             | 1         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.37%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 1.37%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 1.37%   |
| Nvidia MCP61 IDE                                                              | 1         | 1.37%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 1.37%   |
| Kingston Company KC3000/Renegade NVMe SSD                                     | 1         | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.37%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 1         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.37%   |
| Intel NVMe Optane Memory Series                                               | 1         | 1.37%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 1.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.37%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 1         | 1.37%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 1.37%   |
| Intel 82Q35 Express PT IDER Controller                                        | 1         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                    | 1         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                    | 1         | 1.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 61.54%  |
| NVMe | 12        | 18.46%  |
| IDE  | 9         | 13.85%  |
| RAID | 4         | 6.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 42        | 80.77%  |
| AMD    | 10        | 19.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 3.85%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 2         | 3.85%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 3.85%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz            | 1         | 1.92%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz        | 1         | 1.92%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 1.92%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.92%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.92%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.92%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 1.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.92%   |
| Intel Core i5-2500S CPU @ 2.70GHz             | 1         | 1.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.92%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1         | 1.92%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.92%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.92%   |
| Intel Celeron N5105 @ 2.00GHz                 | 1         | 1.92%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 1.92%   |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 1.92%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 1         | 1.92%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 1.92%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz      | 1         | 1.92%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.92%   |
| Intel 11th Gen Core i7-11700B @ 3.20GHz       | 1         | 1.92%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.92%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 21.15%  |
| Intel Core i7           | 6         | 11.54%  |
| Intel Core 2 Duo        | 5         | 9.62%   |
| Intel Celeron           | 5         | 9.62%   |
| Other                   | 4         | 7.69%   |
| Intel Core i3           | 3         | 5.77%   |
| Intel Atom              | 3         | 5.77%   |
| Intel Pentium           | 2         | 3.85%   |
| AMD Ryzen 5             | 2         | 3.85%   |
| AMD GX                  | 2         | 3.85%   |
| Intel Xeon              | 1         | 1.92%   |
| Intel Pentium Gold      | 1         | 1.92%   |
| Intel Pentium D         | 1         | 1.92%   |
| AMD Ryzen 7             | 1         | 1.92%   |
| AMD PRO A10             | 1         | 1.92%   |
| AMD Phenom II           | 1         | 1.92%   |
| AMD Athlon II Dual-Core | 1         | 1.92%   |
| AMD Athlon II           | 1         | 1.92%   |
| AMD A12                 | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 53.85%  |
| 4      | 13        | 25%     |
| 6      | 4         | 7.69%   |
| 1      | 3         | 5.77%   |
| 8      | 2         | 3.85%   |
| 10     | 1         | 1.92%   |
| 3      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 55.77%  |
| 1      | 23        | 44.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 9.26%   |
| 0x306a9    | 3         | 5.56%   |
| 0x106ca    | 3         | 5.56%   |
| 0x1067a    | 3         | 5.56%   |
| 0x906ea    | 2         | 3.7%    |
| 0x806ea    | 2         | 3.7%    |
| 0x406e3    | 2         | 3.7%    |
| 0x40651    | 2         | 3.7%    |
| 0x306d4    | 2         | 3.7%    |
| 0x30678    | 2         | 3.7%    |
| 0x206a7    | 2         | 3.7%    |
| 0x20655    | 2         | 3.7%    |
| 0x0600611a | 2         | 3.7%    |
| 0x010000c8 | 2         | 3.7%    |
| 0xf44      | 1         | 1.85%   |
| 0xa0671    | 1         | 1.85%   |
| 0xa0653    | 1         | 1.85%   |
| 0x906ed    | 1         | 1.85%   |
| 0x906e9    | 1         | 1.85%   |
| 0x906c0    | 1         | 1.85%   |
| 0x906a4    | 1         | 1.85%   |
| 0x806d1    | 1         | 1.85%   |
| 0x806c1    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x6fa      | 1         | 1.85%   |
| 0x506c9    | 1         | 1.85%   |
| 0x306c3    | 1         | 1.85%   |
| 0x206d7    | 1         | 1.85%   |
| 0x10676    | 1         | 1.85%   |
| 0x08600106 | 1         | 1.85%   |
| 0x08108109 | 1         | 1.85%   |
| 0x0810100b | 1         | 1.85%   |
| 0x07030105 | 1         | 1.85%   |
| 0x07030104 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 11.32%  |
| Penryn      | 4         | 7.55%   |
| Icelake     | 4         | 7.55%   |
| Westmere    | 3         | 5.66%   |
| SandyBridge | 3         | 5.66%   |
| K10         | 3         | 5.66%   |
| IvyBridge   | 3         | 5.66%   |
| Haswell     | 3         | 5.66%   |
| Bonnell     | 3         | 5.66%   |
| Skylake     | 2         | 3.77%   |
| Silvermont  | 2         | 3.77%   |
| Puma        | 2         | 3.77%   |
| Excavator   | 2         | 3.77%   |
| Broadwell   | 2         | 3.77%   |
| Unknown     | 2         | 3.77%   |
| Zen+        | 1         | 1.89%   |
| Zen 2       | 1         | 1.89%   |
| Zen         | 1         | 1.89%   |
| Tremont     | 1         | 1.89%   |
| TigerLake   | 1         | 1.89%   |
| NetBurst    | 1         | 1.89%   |
| Goldmont    | 1         | 1.89%   |
| Core        | 1         | 1.89%   |
| CometLake   | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 58.33%  |
| AMD    | 16        | 26.67%  |
| Nvidia | 9         | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 3         | 4.92%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 4.92%   |
| Intel UHD Graphics 620                                                    | 2         | 3.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 3.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 3.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 3.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.64%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 1.64%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.64%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                         | 1         | 1.64%   |
| Nvidia GA102 [GeForce RTX 3080]                                           | 1         | 1.64%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 1.64%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                    | 1         | 1.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.64%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.64%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.64%   |
| Intel HD Graphics 630                                                     | 1         | 1.64%   |
| Intel HD Graphics 5500                                                    | 1         | 1.64%   |
| Intel HD Graphics                                                         | 1         | 1.64%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                  | 1         | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.64%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1         | 1.64%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                   | 1         | 1.64%   |
| Intel 82Q35 Express Integrated Graphics Controller                        | 1         | 1.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1         | 1.64%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                             | 1         | 1.64%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                | 1         | 1.64%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]          | 1         | 1.64%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.64%   |
| AMD RV370 [Radeon X600/X600 SE]                                           | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 52.83%  |
| 1 x AMD        | 12        | 22.64%  |
| 1 x Nvidia     | 6         | 11.32%  |
| Intel + Nvidia | 3         | 5.66%   |
| Intel + AMD    | 3         | 5.66%   |
| 2 x AMD        | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 49        | 92.45%  |
| Unknown     | 3         | 5.66%   |
| Proprietary | 1         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 59.26%  |
| 0.01-0.5   | 13        | 24.07%  |
| 3.01-4.0   | 3         | 5.56%   |
| 1.01-2.0   | 2         | 3.7%    |
| 0.51-1.0   | 2         | 3.7%    |
| 7.01-8.0   | 1         | 1.85%   |
| 8.01-16.0  | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 18.75%  |
| LG Display              | 4         | 8.33%   |
| Chimei Innolux          | 4         | 8.33%   |
| Samsung Electronics     | 3         | 6.25%   |
| Lenovo                  | 3         | 6.25%   |
| Dell                    | 3         | 6.25%   |
| Zoran                   | 2         | 4.17%   |
| Sceptre Tech            | 2         | 4.17%   |
| Goldstar                | 2         | 4.17%   |
| BOE                     | 2         | 4.17%   |
| Sony                    | 1         | 2.08%   |
| Sharp                   | 1         | 2.08%   |
| SAC                     | 1         | 2.08%   |
| Philips                 | 1         | 2.08%   |
| JDI                     | 1         | 2.08%   |
| Insignia                | 1         | 2.08%   |
| InfoVision              | 1         | 2.08%   |
| HUAWEI                  | 1         | 2.08%   |
| Hewlett-Packard         | 1         | 2.08%   |
| eMachines               | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| ASUSTek Computer        | 1         | 2.08%   |
| Apple                   | 1         | 2.08%   |
| AOC                     | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                       | 2         | 4.17%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                   | 2         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 4.17%   |
| Sony TV SNY0101 1360x768                                                 | 1         | 2.08%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                   | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch    | 1         | 2.08%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch        | 1         | 2.08%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch        | 1         | 2.08%   |
| SAC LED MONITOR SAC952D 1920x1080 480x260mm 21.5-inch                    | 1         | 2.08%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                       | 1         | 2.08%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch            | 1         | 2.08%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 2.08%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                  | 1         | 2.08%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                     | 1         | 2.08%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                    | 1         | 2.08%   |
| Insignia DX-LCD32 BBYCD32 1360x768 709x399mm 32.0-inch                   | 1         | 2.08%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch              | 1         | 2.08%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                     | 1         | 2.08%   |
| Hewlett-Packard W2271d HWP3102 1920x1080 477x268mm 21.5-inch             | 1         | 2.08%   |
| Goldstar ULTRAGEAR GSM776E 2560x1440 697x392mm 31.5-inch                 | 1         | 2.08%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                   | 1         | 2.08%   |
| eMachines E15T4W EMA05E1 1280x800 332x207mm 15.4-inch                    | 1         | 2.08%   |
| Dell P2415Q DELA0C0 3840x2160 527x296mm 23.8-inch                        | 1         | 2.08%   |
| Dell P2319H DELD0D5 1920x1080 510x290mm 23.1-inch                        | 1         | 2.08%   |
| Dell E152FP DELA009 1024x768 304x228mm 15.0-inch                         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch         | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                     | 1         | 2.08%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 340x190mm 15.3-inch           | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 42.55%  |
| 1366x768 (WXGA)    | 9         | 19.15%  |
| 1360x768           | 4         | 8.51%   |
| 2560x1440 (QHD)    | 3         | 6.38%   |
| 3840x2160 (4K)     | 2         | 4.26%   |
| 1280x800 (WXGA)    | 2         | 4.26%   |
| 1024x600           | 2         | 4.26%   |
| 3440x1440          | 1         | 2.13%   |
| 1920x1200 (WUXGA)  | 1         | 2.13%   |
| 1680x1050 (WSXGA+) | 1         | 2.13%   |
| 1600x900 (HD+)     | 1         | 2.13%   |
| 1024x768 (XGA)     | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 20.83%  |
| 24      | 6         | 12.5%   |
| 14      | 6         | 12.5%   |
| 21      | 4         | 8.33%   |
| 22      | 3         | 6.25%   |
| 17      | 3         | 6.25%   |
| 10      | 3         | 6.25%   |
| 31      | 2         | 4.17%   |
| 23      | 2         | 4.17%   |
| 13      | 2         | 4.17%   |
| 84      | 1         | 2.08%   |
| 34      | 1         | 2.08%   |
| 32      | 1         | 2.08%   |
| 27      | 1         | 2.08%   |
| 12      | 1         | 2.08%   |
| 11      | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 35.42%  |
| 501-600     | 9         | 18.75%  |
| 401-500     | 7         | 14.58%  |
| 201-300     | 6         | 12.5%   |
| 351-400     | 3         | 6.25%   |
| 701-800     | 2         | 4.17%   |
| 601-700     | 2         | 4.17%   |
| 1501-2000   | 1         | 2.08%   |
| Unknown     | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 86.96%  |
| 16/10 | 4         | 8.7%    |
| 4/3   | 1         | 2.17%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 29.17%  |
| 101-110        | 10        | 20.83%  |
| 81-90          | 7         | 14.58%  |
| 351-500        | 4         | 8.33%   |
| 41-50          | 3         | 6.25%   |
| 121-130        | 3         | 6.25%   |
| More than 1000 | 1         | 2.08%   |
| 71-80          | 1         | 2.08%   |
| 61-70          | 1         | 2.08%   |
| 51-60          | 1         | 2.08%   |
| 301-350        | 1         | 2.08%   |
| 151-200        | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 33.33%  |
| 51-100  | 15        | 31.25%  |
| 121-160 | 11        | 22.92%  |
| 161-240 | 4         | 8.33%   |
| 1-50    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 46        | 86.79%  |
| 0     | 4         | 7.55%   |
| 2     | 3         | 5.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 24        | 31.17%  |
| Intel                           | 21        | 27.27%  |
| Qualcomm Atheros                | 14        | 18.18%  |
| Broadcom                        | 10        | 12.99%  |
| Qualcomm Atheros Communications | 3         | 3.9%    |
| Ralink Technology               | 1         | 1.3%    |
| Prolific Technology             | 1         | 1.3%    |
| Nvidia                          | 1         | 1.3%    |
| MediaTek                        | 1         | 1.3%    |
| Marvell Technology Group        | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 14        | 15.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 4         | 4.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 4.3%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 2.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 2         | 2.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.15%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 2.15%   |
| Intel Wireless 8260                                                                   | 2         | 2.15%   |
| Intel Wireless 7260                                                                   | 2         | 2.15%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 2.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.15%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.08%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 1.08%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.08%   |
| Prolific USB-Serial Controller                                                        | 1         | 1.08%   |
| Nvidia MCP61 Ethernet                                                                 | 1         | 1.08%   |
| MediaTek Infinix HOT 11S NFC                                                          | 1         | 1.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 1.08%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 1.08%   |
| Intel Wireless 7265                                                                   | 1         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.08%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1         | 1.08%   |
| Intel I211 Gigabit Network Connection                                                 | 1         | 1.08%   |
| Intel Ethernet Controller I225-LM                                                     | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 34.09%  |
| Qualcomm Atheros                | 11        | 25%     |
| Realtek Semiconductor           | 9         | 20.45%  |
| Broadcom                        | 5         | 11.36%  |
| Qualcomm Atheros Communications | 3         | 6.82%   |
| Ralink Technology               | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 4         | 9.09%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 6.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 4.55%   |
| Intel Wireless 8260                                                                   | 2         | 4.55%   |
| Intel Wireless 7260                                                                   | 2         | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.55%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.27%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.27%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 2.27%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.27%   |
| Intel Wireless-AC 9260                                                                | 1         | 2.27%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.27%   |
| Intel Wireless 7265                                                                   | 1         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.27%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 2.27%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.27%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 41.67%  |
| Intel                    | 13        | 27.08%  |
| Broadcom                 | 7         | 14.58%  |
| Qualcomm Atheros         | 5         | 10.42%  |
| Nvidia                   | 1         | 2.08%   |
| MediaTek                 | 1         | 2.08%   |
| Marvell Technology Group | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 29.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.17%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 4.17%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.08%   |
| Nvidia MCP61 Ethernet                                             | 1         | 2.08%   |
| MediaTek Infinix HOT 11S NFC                                      | 1         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 2.08%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.08%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.08%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.08%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 51.72%  |
| WiFi     | 41        | 47.13%  |
| Modem    | 1         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 51.85%  |
| WiFi     | 26        | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 58.49%  |
| 1     | 20        | 37.74%  |
| 3     | 1         | 1.89%   |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 60.38%  |
| Yes  | 21        | 39.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 39.29%  |
| Apple                           | 5         | 17.86%  |
| Qualcomm Atheros Communications | 4         | 14.29%  |
| Realtek Semiconductor           | 3         | 10.71%  |
| Lite-On Technology              | 2         | 7.14%   |
| IMC Networks                    | 2         | 7.14%   |
| Broadcom                        | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 21.43%  |
| Intel AX201 Bluetooth                              | 3         | 10.71%  |
| Realtek Bluetooth Radio                            | 2         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 7.14%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 7.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI               | 2         | 7.14%   |
| Realtek RTL8723B Bluetooth                         | 1         | 3.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 3.57%   |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 3.57%   |
| IMC Networks Bluetooth Radio                       | 1         | 3.57%   |
| IMC Networks Bluetooth Device                      | 1         | 3.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.57%   |
| Apple Bluetooth USB Host Controller                | 1         | 3.57%   |
| Apple Bluetooth Host Controller                    | 1         | 3.57%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 59.7%   |
| AMD                   | 14        | 20.9%   |
| Nvidia                | 7         | 10.45%  |
| SAVITECH              | 1         | 1.49%   |
| Roland                | 1         | 1.49%   |
| Realtek Semiconductor | 1         | 1.49%   |
| JMTek                 | 1         | 1.49%   |
| Huawei Technologies   | 1         | 1.49%   |
| Anlya.cn              | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 4.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 4.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.47%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.47%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.47%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.47%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.47%   |
| SAVITECH SA9123 USB Audio                                                  | 1         | 1.23%   |
| Roland QUAD-CAPTURE                                                        | 1         | 1.23%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.23%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.23%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.23%   |
| JMTek USB Audio Device                                                     | 1         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.23%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.23%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.23%   |
| Intel HD Graphics SGPC                                                     | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 17.46%  |
| Unknown             | 8         | 12.7%   |
| Crucial             | 7         | 11.11%  |
| Samsung Electronics | 6         | 9.52%   |
| Micron Technology   | 6         | 9.52%   |
| Kingston            | 5         | 7.94%   |
| A-DATA Technology   | 4         | 6.35%   |
| Elpida              | 3         | 4.76%   |
| Corsair             | 3         | 4.76%   |
| Timetec             | 2         | 3.17%   |
| Unknown (08C8)      | 1         | 1.59%   |
| Team                | 1         | 1.59%   |
| SK_Hynix            | 1         | 1.59%   |
| Patriot             | 1         | 1.59%   |
| Nanya Technology    | 1         | 1.59%   |
| Infineon            | 1         | 1.59%   |
| G.Skill             | 1         | 1.59%   |
| Unknown             | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.03%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 3.03%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.52%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.52%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s     | 1         | 1.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 1.52%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.52%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.52%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.52%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.52%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.52%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.52%   |
| Samsung RAM M393B1K70CH0 8GB DIMM DDR3 1866MT/s                  | 1         | 1.52%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Patriot RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.52%   |
| Nanya RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 1.52%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.52%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Micron RAM 16HTF12864AY-53EB1 1GB DIMM DDR 533MT/s               | 1         | 1.52%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                        | 1         | 1.52%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                        | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 24        | 48%     |
| DDR4   | 15        | 30%     |
| DDR2   | 5         | 10%     |
| LPDDR4 | 4         | 8%      |
| LPDDR3 | 1         | 2%      |
| DDR    | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 58%     |
| DIMM         | 15        | 30%     |
| Row Of Chips | 3         | 6%      |
| Unknown      | 2         | 4%      |
| Chip         | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 17        | 32.69%  |
| 8192  | 16        | 30.77%  |
| 2048  | 9         | 17.31%  |
| 1024  | 5         | 9.62%   |
| 16384 | 3         | 5.77%   |
| 32768 | 1         | 1.92%   |
| 512   | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 13        | 24.07%  |
| 2667  | 6         | 11.11%  |
| 667   | 6         | 11.11%  |
| 1067  | 5         | 9.26%   |
| 3200  | 4         | 7.41%   |
| 2400  | 3         | 5.56%   |
| 1333  | 2         | 3.7%    |
| 8400  | 1         | 1.85%   |
| 4267  | 1         | 1.85%   |
| 4266  | 1         | 1.85%   |
| 3733  | 1         | 1.85%   |
| 3600  | 1         | 1.85%   |
| 2800  | 1         | 1.85%   |
| 2733  | 1         | 1.85%   |
| 2666  | 1         | 1.85%   |
| 1867  | 1         | 1.85%   |
| 1866  | 1         | 1.85%   |
| 1800  | 1         | 1.85%   |
| 1334  | 1         | 1.85%   |
| 1066  | 1         | 1.85%   |
| 800   | 1         | 1.85%   |
| 533   | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 50%     |
| HP DeskJet F4200 series               | 1         | 25%     |
| HP DeskJet 2130 series                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 6         | 23.08%  |
| Apple                         | 4         | 15.38%  |
| Sunplus Innovation Technology | 2         | 7.69%   |
| Realtek Semiconductor         | 2         | 7.69%   |
| Microdia                      | 2         | 7.69%   |
| Logitech                      | 2         | 7.69%   |
| IMC Networks                  | 2         | 7.69%   |
| ALi                           | 2         | 7.69%   |
| Suyin                         | 1         | 3.85%   |
| Quanta                        | 1         | 3.85%   |
| Luxvisions Innotech Limited   | 1         | 3.85%   |
| Bison Electronics             | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 2         | 7.69%   |
| Apple Built-in iSight                               | 2         | 7.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 3.85%   |
| Sunplus HD WebCam                                   | 1         | 3.85%   |
| Realtek USB2.0-Camera                               | 1         | 3.85%   |
| Realtek Lenovo EasyCamera                           | 1         | 3.85%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.85%   |
| Microdia Integrated Webcam                          | 1         | 3.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.85%   |
| Logitech Logitech Webcam C160                       | 1         | 3.85%   |
| Logitech HD Pro Webcam C920                         | 1         | 3.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.85%   |
| IMC Networks Integrated Camera                      | 1         | 3.85%   |
| Chicony USB 2.0 Camera                              | 1         | 3.85%   |
| Chicony Integrated Camera                           | 1         | 3.85%   |
| Chicony HP Integrated Webcam                        | 1         | 3.85%   |
| Chicony HD WebCam (Acer)                            | 1         | 3.85%   |
| Bison BisonCam, NB Pro                              | 1         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 3.85%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 3.85%   |
| ALi WebCam                                          | 1         | 3.85%   |
| ALi Gateway Webcam                                  | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 50%     |
| Focal-systems.Corp    | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 40        | 75.47%  |
| 1     | 12        | 22.64%  |
| 2     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 42.86%  |
| Multimedia controller    | 2         | 14.29%  |
| Fingerprint reader       | 2         | 14.29%  |
| Net/wireless             | 1         | 7.14%   |
| Communication controller | 1         | 7.14%   |
| Chipcard                 | 1         | 7.14%   |
| Camera                   | 1         | 7.14%   |

