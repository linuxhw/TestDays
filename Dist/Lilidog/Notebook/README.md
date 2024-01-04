Lilidog - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lilidog.

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

Total: 37

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X280 20KES63G00    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Toshiba       | Satellite Pro L450          | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Acer          | AOD270                      | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Acer          | Aspire one                  | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Sony          | VPCF23P1E                   | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| Google        | Sand                        | [97e4755fe5](https://linux-hardware.org/?probe=97e4755fe5) | Nov 07, 2023 |
| Dell          | Inspiron 1318               | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| HP            | 435                         | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Google        | Sand                        | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Lenovo        | G500 20236                  | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Acer          | V5-131                      | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| Acer          | AOD255E                     | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| GPU Compan... | GWNR71517                   | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| Dell          | Inspiron 3793               | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Lilidog 23 | 17        | 51.52%  |
| Lilidog 22 | 16        | 48.48%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lilidog | 31        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-9-amd64             | 5         | 13.89%  |
| 5.10.0-15-amd64           | 4         | 11.11%  |
| 6.1.0-10-amd64            | 3         | 8.33%   |
| 5.10.0-16-amd64           | 3         | 8.33%   |
| 6.5.0-0.deb12.4-amd64     | 2         | 5.56%   |
| 6.5.0-0.deb12.1-amd64     | 2         | 5.56%   |
| 5.10.0-21-amd64           | 2         | 5.56%   |
| 5.10.0-18-amd64           | 2         | 5.56%   |
| 6.4.5-1-liquorix-amd64    | 1         | 2.78%   |
| 6.4.0-0.deb12.2-amd64     | 1         | 2.78%   |
| 6.1.0-7-amd64             | 1         | 2.78%   |
| 6.1.0-13-amd64            | 1         | 2.78%   |
| 6.1.0-13-686-pae          | 1         | 2.78%   |
| 6.1.0-11-amd64            | 1         | 2.78%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 2.78%   |
| 6.0.10-x64v1-xanmod1      | 1         | 2.78%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 2.78%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 2.78%   |
| 5.10.0-22-amd64           | 1         | 2.78%   |
| 5.10.0-14-amd64           | 1         | 2.78%   |
| 5.10.0-13-amd64           | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 12        | 36.36%  |
| 5.10.0  | 12        | 36.36%  |
| 6.5.0   | 4         | 12.12%  |
| 6.4.5   | 1         | 3.03%   |
| 6.4.0   | 1         | 3.03%   |
| 6.0.10  | 1         | 3.03%   |
| 6.0.0   | 1         | 3.03%   |
| 5.17.0  | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 12        | 36.36%  |
| 5.10    | 12        | 36.36%  |
| 6.5     | 4         | 12.12%  |
| 6.4     | 2         | 6.06%   |
| 6.0     | 2         | 6.06%   |
| 5.17    | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 96.77%  |
| i686   | 1         | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 27        | 81.82%  |
| openbox          | 6         | 18.18%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 31        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 31        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 20        | 62.5%   |
| de_DE | 4         | 12.5%   |
| es_ES | 2         | 6.25%   |
| it_IT | 1         | 3.13%   |
| es_CO | 1         | 3.13%   |
| es_CL | 1         | 3.13%   |
| en_IE | 1         | 3.13%   |
| en_GB | 1         | 3.13%   |
| cs_CZ | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 58.06%  |
| EFI  | 13        | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 21        | 65.63%  |
| Overlay | 9         | 28.13%  |
| Btrfs   | 2         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 18        | 56.25%  |
| GPT  | 14        | 43.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 63.64%  |
| Yes       | 12        | 36.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 83.87%  |
| Yes       | 5         | 16.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Acer             | 7         | 22.58%  |
| Lenovo           | 6         | 19.35%  |
| Dell             | 5         | 16.13%  |
| Hewlett-Packard  | 3         | 9.68%   |
| Panasonic        | 2         | 6.45%   |
| Google           | 2         | 6.45%   |
| TUXEDO           | 1         | 3.23%   |
| Toshiba          | 1         | 3.23%   |
| Sony             | 1         | 3.23%   |
| GPU Company      | 1         | 3.23%   |
| ASUSTek Computer | 1         | 3.23%   |
| Apple            | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 6.45%   |
| TUXEDO N8xEJEK                             | 1         | 3.23%   |
| Toshiba Satellite Pro L450                 | 1         | 3.23%   |
| Sony VPCF23P1E                             | 1         | 3.23%   |
| Panasonic CFMX4-1                          | 1         | 3.23%   |
| Panasonic CF-31ATXAX1M                     | 1         | 3.23%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 3.23%   |
| Lenovo ThinkPad X280 20KES63G00            | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 3.23%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 3.23%   |
| Lenovo G500 20236                          | 1         | 3.23%   |
| HP Laptop 15s-fq1xxx                       | 1         | 3.23%   |
| HP G62                                     | 1         | 3.23%   |
| HP 435                                     | 1         | 3.23%   |
| GPU Company GWNR71517                      | 1         | 3.23%   |
| Google Sand                                | 1         | 3.23%   |
| Google Auron_Yuna                          | 1         | 3.23%   |
| Dell Latitude E5440                        | 1         | 3.23%   |
| Dell Latitude 7414                         | 1         | 3.23%   |
| Dell Latitude 7390                         | 1         | 3.23%   |
| Dell Inspiron 3793                         | 1         | 3.23%   |
| Dell Inspiron 1318                         | 1         | 3.23%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 3.23%   |
| Apple MacBookPro3,1                        | 1         | 3.23%   |
| Acer V5-131                                | 1         | 3.23%   |
| Acer Aspire one                            | 1         | 3.23%   |
| Acer Aspire E5-573                         | 1         | 3.23%   |
| Acer Aspire 7540                           | 1         | 3.23%   |
| Acer AOD270                                | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 4         | 12.9%   |
| Dell Latitude          | 3         | 9.68%   |
| Acer Aspire            | 3         | 9.68%   |
| Dell Inspiron          | 2         | 6.45%   |
| Acer AOD255E           | 2         | 6.45%   |
| TUXEDO N8xEJEK         | 1         | 3.23%   |
| Toshiba Satellite      | 1         | 3.23%   |
| Sony VPCF23P1E         | 1         | 3.23%   |
| Panasonic CFMX4-1      | 1         | 3.23%   |
| Panasonic CF-31ATXAX1M | 1         | 3.23%   |
| Lenovo Yoga            | 1         | 3.23%   |
| Lenovo G500            | 1         | 3.23%   |
| HP Laptop              | 1         | 3.23%   |
| HP G62                 | 1         | 3.23%   |
| HP 435                 | 1         | 3.23%   |
| GPU Company GWNR71517  | 1         | 3.23%   |
| Google Sand            | 1         | 3.23%   |
| Google Auron           | 1         | 3.23%   |
| ASUS VivoBook          | 1         | 3.23%   |
| Apple MacBookPro3      | 1         | 3.23%   |
| Acer V5-131            | 1         | 3.23%   |
| Acer AOD270            | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 5         | 16.13%  |
| 2010 | 5         | 16.13%  |
| 2021 | 2         | 6.45%   |
| 2020 | 2         | 6.45%   |
| 2019 | 2         | 6.45%   |
| 2013 | 2         | 6.45%   |
| 2012 | 2         | 6.45%   |
| 2011 | 2         | 6.45%   |
| 2009 | 2         | 6.45%   |
| 2008 | 2         | 6.45%   |
| 2017 | 1         | 3.23%   |
| 2016 | 1         | 3.23%   |
| 2015 | 1         | 3.23%   |
| 2014 | 1         | 3.23%   |
| 2007 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 96.77%  |
| Enabled  | 1         | 3.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 90.32%  |
| Yes  | 3         | 9.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 32.26%  |
| 3.01-4.0   | 9         | 29.03%  |
| 1.01-2.0   | 4         | 12.9%   |
| 16.01-24.0 | 3         | 9.68%   |
| 8.01-16.0  | 2         | 6.45%   |
| 32.01-64.0 | 1         | 3.23%   |
| 2.01-3.0   | 1         | 3.23%   |
| 0.51-1.0   | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 21        | 65.63%  |
| 1.01-2.0 | 8         | 25%     |
| 2.01-3.0 | 3         | 9.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 87.5%   |
| 2      | 4         | 12.5%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 64.52%  |
| Yes       | 11        | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 78.13%  |
| No        | 7         | 21.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 62.5%   |
| No        | 12        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 29.03%  |
| Germany     | 7         | 22.58%  |
| Spain       | 3         | 9.68%   |
| Italy       | 2         | 6.45%   |
| Vietnam     | 1         | 3.23%   |
| Thailand    | 1         | 3.23%   |
| Portugal    | 1         | 3.23%   |
| Netherlands | 1         | 3.23%   |
| Mexico      | 1         | 3.23%   |
| Kenya       | 1         | 3.23%   |
| Finland     | 1         | 3.23%   |
| Czechia     | 1         | 3.23%   |
| Colombia    | 1         | 3.23%   |
| Chile       | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Fayetteville           | 3         | 9.68%   |
| Milan                  | 2         | 6.45%   |
| Egan                   | 2         | 6.45%   |
| Denver                 | 2         | 6.45%   |
| Viña del Mar          | 1         | 3.23%   |
| Uelzen                 | 1         | 3.23%   |
| Schiedam               | 1         | 3.23%   |
| Rinteln                | 1         | 3.23%   |
| Ratchathewi            | 1         | 3.23%   |
| Poricany               | 1         | 3.23%   |
| Norderstedt            | 1         | 3.23%   |
| Nairobi                | 1         | 3.23%   |
| Morgantown             | 1         | 3.23%   |
| Monclova               | 1         | 3.23%   |
| Medellín              | 1         | 3.23%   |
| Madrid                 | 1         | 3.23%   |
| Lisbon                 | 1         | 3.23%   |
| Ho Chi Minh City       | 1         | 3.23%   |
| Helsinki               | 1         | 3.23%   |
| Filderstadt            | 1         | 3.23%   |
| Eppelborn              | 1         | 3.23%   |
| Düsseldorf            | 1         | 3.23%   |
| Darmstadt              | 1         | 3.23%   |
| Charlotte              | 1         | 3.23%   |
| Cervera del Rio Alhama | 1         | 3.23%   |
| Barcelona              | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 20.59%  |
| Seagate             | 5         | 6      | 14.71%  |
| Toshiba             | 3         | 4      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 4      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| Wibtek              | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |
| Mushkin             | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 2      | 2.94%   |
| Lexar               | 1         | 1      | 2.94%   |
| KIOXIA              | 1         | 1      | 2.94%   |
| KingFast            | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| Blackpcs            | 1         | 1      | 2.94%   |
| Apacer              | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB             | 2         | 5.71%   |
| Wibtek W800S 512GB SSD                      | 1         | 2.86%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 2.86%   |
| WDC WD1600BEVT-22ZCT0 160GB                 | 1         | 2.86%   |
| Unknown NCard  32GB                         | 1         | 2.86%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 2.86%   |
| Toshiba MK6034GSX 64GB                      | 1         | 2.86%   |
| Toshiba MK1665GSX 160GB                     | 1         | 2.86%   |
| Seagate ST9320325AS 320GB                   | 1         | 2.86%   |
| Seagate ST9250315AS 250GB                   | 1         | 2.86%   |
| Seagate ST320LT020-9YG142 320GB             | 1         | 2.86%   |
| SanDisk SD8TN8U256G1001 256GB SSD           | 1         | 2.86%   |
| SanDisk DF4032  32GB                        | 1         | 2.86%   |
| Samsung SSD PM841 2.5 7mm 256GB             | 1         | 2.86%   |
| Samsung SSD 970 EVO Plus 250GB              | 1         | 2.86%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.86%   |
| Samsung SSD 860 EVO 1TB                     | 1         | 2.86%   |
| Samsung SSD 850 EVO 250GB                   | 1         | 2.86%   |
| Samsung PM991a NVMe 512GB                   | 1         | 2.86%   |
| Samsung MZVL21T0HCLR-00BL7 1TB              | 1         | 2.86%   |
| Samsung MZNTE128HMGR-00000 128GB SSD        | 1         | 2.86%   |
| Mushkin MKNSSDCR120GB                       | 1         | 2.86%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD         | 1         | 2.86%   |
| Lexar SSD NM620 256GB                       | 1         | 2.86%   |
| KIOXIA KBG40ZNV1T02 1024GB                  | 1         | 2.86%   |
| Kingston SNS4151S332GD 32GB SSD             | 1         | 2.86%   |
| Kingston SKC3000D2048G 2TB                  | 1         | 2.86%   |
| KingFast SSD 240GB                          | 1         | 2.86%   |
| Intel SSDPEKKF256G8L BTHH831605D3256B 256GB | 1         | 2.86%   |
| Hitachi HTS545016B9SA00 160GB               | 1         | 2.86%   |
| Crucial CT480BX500SSD1 480GB                | 1         | 2.86%   |
| China SSD 120GB                             | 1         | 2.86%   |
| Blackpcs SSDPro 120GB                       | 1         | 2.86%   |
| Apacer AS350 512GB SSD                      | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 45.45%  |
| Toshiba | 3         | 4      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 33.33%  |
| Wibtek              | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| Mushkin             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 2      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| KingFast            | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| Blackpcs            | 1         | 1      | 6.67%   |
| Apacer              | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 16     | 44.12%  |
| HDD  | 11        | 13     | 32.35%  |
| NVMe | 7         | 8      | 20.59%  |
| MMC  | 1         | 4      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 29     | 75%     |
| NVMe | 7         | 8      | 21.88%  |
| MMC  | 1         | 4      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 24     | 84%     |
| 0.51-1.0   | 4         | 5      | 16%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 9         | 27.27%  |
| 1-20       | 9         | 27.27%  |
| 101-250    | 8         | 24.24%  |
| 51-100     | 3         | 9.09%   |
| 21-50      | 2         | 6.06%   |
| 1001-2000  | 1         | 3.03%   |
| 501-1000   | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 27        | 81.82%  |
| 21-50   | 5         | 15.15%  |
| 51-100  | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 2         | 3      | 33.33%  |
| Toshiba MK1665GSX 160GB         | 1         | 1      | 16.67%  |
| Seagate ST9250315AS 250GB       | 1         | 1      | 16.67%  |
| Mushkin MKNSSDCR120GB           | 1         | 1      | 16.67%  |
| Kingston SNS4151S332GD 32GB SSD | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 4      | 50%     |
| Toshiba  | 1         | 1      | 16.67%  |
| Mushkin  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 75%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 24        | 29     | 75%     |
| Malfunc  | 6         | 7      | 18.75%  |
| Detected | 1         | 4      | 3.13%   |
| Failed   | 1         | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 24        | 72.73%  |
| Samsung Electronics          | 3         | 9.09%   |
| AMD                          | 3         | 9.09%   |
| Shenzhen Longsys Electronics | 1         | 3.03%   |
| KIOXIA                       | 1         | 3.03%   |
| Kingston Technology Company  | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 8.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 3         | 8.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 5.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 5.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 5.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 5.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 5.41%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                            | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 2.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 2.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 2.7%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                           | 1         | 2.7%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 1         | 2.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 1         | 2.7%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 1         | 2.7%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 2.7%    |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 23        | 63.89%  |
| NVMe | 7         | 19.44%  |
| IDE  | 4         | 11.11%  |
| RAID | 2         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 87.1%   |
| AMD    | 4         | 12.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 6.45%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 6.45%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 3.23%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 3.23%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.23%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.23%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 3.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.23%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 3.23%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 1         | 3.23%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 3.23%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 3.23%   |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 3.23%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 3.23%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 1         | 3.23%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.23%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.23%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.23%   |
| AMD Phenom II N830 Triple-Core Processor      | 1         | 3.23%   |
| AMD Athlon II Dual-Core M300                  | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 25.81%  |
| Intel Core i7           | 6         | 19.35%  |
| Intel Atom              | 4         | 12.9%   |
| Intel Core 2 Duo        | 3         | 9.68%   |
| Intel Pentium           | 2         | 6.45%   |
| Intel Celeron           | 2         | 6.45%   |
| Other                   | 1         | 3.23%   |
| Intel Pentium Dual-Core | 1         | 3.23%   |
| AMD Ryzen 7             | 1         | 3.23%   |
| AMD Ryzen 5             | 1         | 3.23%   |
| AMD Phenom II           | 1         | 3.23%   |
| AMD Athlon II Dual-Core | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 51.61%  |
| 4      | 9         | 29.03%  |
| 1      | 3         | 9.68%   |
| 6      | 2         | 6.45%   |
| 3      | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 64.52%  |
| 1      | 11        | 35.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 96.77%  |
| 32-bit         | 1         | 3.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 25%     |
| 0x806ea    | 2         | 6.25%   |
| 0x406e3    | 2         | 6.25%   |
| 0x40651    | 2         | 6.25%   |
| 0x306d4    | 2         | 6.25%   |
| 0x306a9    | 2         | 6.25%   |
| 0x106ca    | 2         | 6.25%   |
| 0x906ea    | 1         | 3.13%   |
| 0x806c1    | 1         | 3.13%   |
| 0x706e5    | 1         | 3.13%   |
| 0x6fa      | 1         | 3.13%   |
| 0x506c9    | 1         | 3.13%   |
| 0x20655    | 1         | 3.13%   |
| 0x106c2    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x10676    | 1         | 3.13%   |
| 0x08600106 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x010000c8 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 12.9%   |
| Bonnell     | 4         | 12.9%   |
| Westmere    | 2         | 6.45%   |
| Skylake     | 2         | 6.45%   |
| Penryn      | 2         | 6.45%   |
| K10         | 2         | 6.45%   |
| IvyBridge   | 2         | 6.45%   |
| IceLake     | 2         | 6.45%   |
| Haswell     | 2         | 6.45%   |
| Core        | 2         | 6.45%   |
| Broadwell   | 2         | 6.45%   |
| Zen+        | 1         | 3.23%   |
| Zen 2       | 1         | 3.23%   |
| TigerLake   | 1         | 3.23%   |
| SandyBridge | 1         | 3.23%   |
| Goldmont    | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 71.43%  |
| AMD    | 6         | 17.14%  |
| Nvidia | 4         | 11.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                        | 3         | 8.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 5.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 5.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 5.41%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 5.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 5.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 2.7%    |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 2.7%    |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 2.7%    |
| Intel Iris Plus Graphics G7                                                   | 1         | 2.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 2.7%    |
| Intel HD Graphics 5500                                                        | 1         | 2.7%    |
| Intel HD Graphics                                                             | 1         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 2.7%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.7%    |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 2.7%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]              | 1         | 2.7%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 2.7%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 1         | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.7%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 2.7%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 58.06%  |
| 1 x AMD        | 4         | 12.9%   |
| 2 x Intel      | 3         | 9.68%   |
| 1 x Nvidia     | 2         | 6.45%   |
| Intel + Nvidia | 2         | 6.45%   |
| Intel + AMD    | 2         | 6.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 30        | 96.77%  |
| Unknown | 1         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 70.97%  |
| 0.01-0.5   | 5         | 16.13%  |
| 3.01-4.0   | 2         | 6.45%   |
| 1.01-2.0   | 2         | 6.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 38.71%  |
| LG Display              | 5         | 16.13%  |
| Chimei Innolux          | 4         | 12.9%   |
| Chi Mei Optoelectronics | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| Sharp                   | 1         | 3.23%   |
| Samsung Electronics     | 1         | 3.23%   |
| Lenovo                  | 1         | 3.23%   |
| JDI                     | 1         | 3.23%   |
| EQV                     | 1         | 3.23%   |
| AOC                     | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 6.45%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                    | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 3.23%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                   | 1         | 3.23%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                     | 1         | 3.23%   |
| EQV LCD Monitor EQV1080 1920x1080 477x268mm 21.5-inch                     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch          | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 3.23%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                      | 1         | 3.23%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch             | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 1         | 3.23%   |
| AOC 2219 AOC2219 1680x1050 474x296mm 22.0-inch                            | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 36.67%  |
| 1366x768 (WXGA)    | 11        | 36.67%  |
| 1024x600           | 4         | 13.33%  |
| 1920x1200 (WUXGA)  | 1         | 3.33%   |
| 1680x1050 (WSXGA+) | 1         | 3.33%   |
| 1600x900 (HD+)     | 1         | 3.33%   |
| 1280x800 (WXGA)    | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 32.26%  |
| 14     | 6         | 19.35%  |
| 10     | 4         | 12.9%   |
| 17     | 3         | 9.68%   |
| 13     | 2         | 6.45%   |
| 12     | 2         | 6.45%   |
| 22     | 1         | 3.23%   |
| 21     | 1         | 3.23%   |
| 16     | 1         | 3.23%   |
| 11     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 51.61%  |
| 201-300     | 8         | 25.81%  |
| 351-400     | 5         | 16.13%  |
| 401-500     | 2         | 6.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 90%     |
| 16/10 | 3         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 32.26%  |
| 81-90          | 7         | 22.58%  |
| 41-50          | 4         | 12.9%   |
| 121-130        | 3         | 9.68%   |
| 61-70          | 2         | 6.45%   |
| 71-80          | 1         | 3.23%   |
| 51-60          | 1         | 3.23%   |
| 201-250        | 1         | 3.23%   |
| 151-200        | 1         | 3.23%   |
| 111-120        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 14        | 45.16%  |
| 121-160 | 11        | 35.48%  |
| 161-240 | 3         | 9.68%   |
| 51-100  | 3         | 9.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 90.63%  |
| 2     | 2         | 6.25%   |
| 0     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 28.57%  |
| Qualcomm Atheros                | 13        | 26.53%  |
| Realtek Semiconductor           | 12        | 24.49%  |
| Broadcom                        | 6         | 12.24%  |
| Research In Motion              | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| Marvell Technology Group        | 1         | 2.04%   |
| ICS Advent                      | 1         | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 5         | 8.47%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 3         | 5.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 3.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 3.39%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 3.39%   |
| Intel Wireless 8260                                                                   | 2         | 3.39%   |
| Intel Wireless 7260                                                                   | 2         | 3.39%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 3.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 3.39%   |
| Research In Motion BlackBerry                                                         | 1         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.69%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 1.69%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 1.69%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 1.69%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.69%   |
| Intel Wireless 7265                                                                   | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.69%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 1.69%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.69%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 1.69%   |
| ICS Advent 10/100M LAN                                                                | 1         | 1.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                   | 1         | 1.69%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                       | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 37.5%   |
| Qualcomm Atheros                | 11        | 34.38%  |
| Realtek Semiconductor           | 4         | 12.5%   |
| Broadcom                        | 4         | 12.5%   |
| Qualcomm Atheros Communications | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 9.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 6.25%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 6.25%   |
| Intel Wireless 8260                                                                   | 2         | 6.25%   |
| Intel Wireless 7260                                                                   | 2         | 6.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 3.13%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 3.13%   |
| Realtek 802.11ac NIC                                                                  | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.13%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 3.13%   |
| Intel Wireless-AC 9260                                                                | 1         | 3.13%   |
| Intel Wireless 7265                                                                   | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 3.13%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.13%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 3.13%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 3.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 9         | 33.33%  |
| Intel                    | 8         | 29.63%  |
| Qualcomm Atheros         | 4         | 14.81%  |
| Broadcom                 | 3         | 11.11%  |
| Research In Motion       | 1         | 3.7%    |
| Marvell Technology Group | 1         | 3.7%    |
| ICS Advent               | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 18.52%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 11.11%  |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 7.41%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 7.41%   |
| Research In Motion BlackBerry                                     | 1         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.7%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.7%    |
| ICS Advent 10/100M LAN                                            | 1         | 3.7%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 3.7%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 54.55%  |
| Ethernet | 25        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 62.5%   |
| Ethernet | 12        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 70.97%  |
| 1     | 8         | 25.81%  |
| 0     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 58.06%  |
| Yes  | 13        | 41.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 50%     |
| Qualcomm Atheros Communications | 3         | 15%     |
| Lite-On Technology              | 3         | 15%     |
| Realtek Semiconductor           | 1         | 5%      |
| IMC Networks                    | 1         | 5%      |
| Broadcom                        | 1         | 5%      |
| Apple                           | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 7         | 35%     |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 10%     |
| Realtek Bluetooth Radio                            | 1         | 5%      |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 5%      |
| Lite-On Bluetooth USB Host Controller              | 1         | 5%      |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 5%      |
| Intel Bluetooth Device                             | 1         | 5%      |
| IMC Networks Bluetooth Device                      | 1         | 5%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5%      |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 77.14%  |
| AMD    | 5         | 14.29%  |
| Nvidia | 2         | 5.71%   |
| JMTek  | 1         | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 11.63%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 9.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 4.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 4.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4.65%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 4.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 4.65%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 4.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 4.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 4.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.33%   |
| JMTek USB PnP Audio Device                                                 | 1         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2.33%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 21.88%  |
| Unknown             | 6         | 18.75%  |
| Micron Technology   | 5         | 15.63%  |
| A-DATA Technology   | 4         | 12.5%   |
| Samsung Electronics | 3         | 9.38%   |
| Elpida              | 3         | 9.38%   |
| Kingston            | 2         | 6.25%   |
| Toshiba             | 1         | 3.13%   |
| Nanya Technology    | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.86%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 2.86%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 2.86%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 2.86%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 2.86%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 2.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.86%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 2.86%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.86%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.86%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 2.86%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 2.86%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8192MB SODIMM DDR4 2400MT/s          | 1         | 2.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.86%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 1         | 2.86%   |
| Kingston RAM 9905295-045.A01LF 2GB SODIMM DDR 667MT/s            | 1         | 2.86%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB SODIMM LPDDR3 1867MT/s           | 1         | 2.86%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB Chip LPDDR3 1867MT/s             | 1         | 2.86%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2048MB SODIMM DDR3 1067MT/s         | 1         | 2.86%   |
| A-DATA RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 2.86%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s             | 1         | 2.86%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| A-DATA RAM ADOVE1B163BE 2GB SODIMM DDR 975MT/s                   | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 42.86%  |
| DDR4   | 7         | 25%     |
| DDR2   | 5         | 17.86%  |
| LPDDR4 | 3         | 10.71%  |
| LPDDR3 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 82.76%  |
| Row Of Chips | 2         | 6.9%    |
| Unknown      | 2         | 6.9%    |
| Chip         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 11        | 37.93%  |
| 4096  | 10        | 34.48%  |
| 8192  | 5         | 17.24%  |
| 1024  | 2         | 6.9%    |
| 16384 | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 20.69%  |
| 667     | 5         | 17.24%  |
| 2667    | 4         | 13.79%  |
| 2400    | 3         | 10.34%  |
| 1067    | 2         | 6.9%    |
| 8400    | 1         | 3.45%   |
| 4267    | 1         | 3.45%   |
| 4266    | 1         | 3.45%   |
| 1867    | 1         | 3.45%   |
| 1334    | 1         | 3.45%   |
| 1066    | 1         | 3.45%   |
| 975     | 1         | 3.45%   |
| 533     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 32%     |
| Microdia                      | 3         | 12%     |
| Sunplus Innovation Technology | 2         | 8%      |
| Realtek Semiconductor         | 2         | 8%      |
| IMC Networks                  | 2         | 8%      |
| Apple                         | 2         | 8%      |
| ALi                           | 2         | 8%      |
| Suyin                         | 1         | 4%      |
| Ricoh                         | 1         | 4%      |
| Luxvisions Innotech Limited   | 1         | 4%      |
| Bison Electronics             | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 2         | 8%      |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 4%      |
| Sunplus Integrated_Webcam_HD                        | 1         | 4%      |
| Sunplus HD WebCam                                   | 1         | 4%      |
| Ricoh USB2.0 Camera                                 | 1         | 4%      |
| Realtek USB Camera                                  | 1         | 4%      |
| Realtek Lenovo EasyCamera                           | 1         | 4%      |
| Microdia Sonix USB 2.0 Camera                       | 1         | 4%      |
| Microdia Integrated_Webcam_HD                       | 1         | 4%      |
| Microdia Integrated Webcam                          | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4%      |
| IMC Networks Integrated Camera                      | 1         | 4%      |
| Chicony WebCam                                      | 1         | 4%      |
| Chicony Integrated Camera (1280x720@30)             | 1         | 4%      |
| Chicony Integrated Camera                           | 1         | 4%      |
| Chicony HP Webcam-101                               | 1         | 4%      |
| Chicony HD WebCam (Acer)                            | 1         | 4%      |
| Chicony Camera                                      | 1         | 4%      |
| Bison BisonCam, NB Pro                              | 1         | 4%      |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 4%      |
| Apple Built-in iSight                               | 1         | 4%      |
| ALi WebCam                                          | 1         | 4%      |
| ALi Gateway Webcam                                  | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 50%     |
| Focal-systems.Corp    | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 70.97%  |
| 1     | 8         | 25.81%  |
| 2     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 40%     |
| Fingerprint reader    | 2         | 20%     |
| Net/wireless          | 1         | 10%     |
| Multimedia controller | 1         | 10%     |
| Chipcard              | 1         | 10%     |
| Camera                | 1         | 10%     |

