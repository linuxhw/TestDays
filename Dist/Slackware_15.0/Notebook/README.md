Slackware 15.0 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 32

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad T470 20JNS01R01    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo    | ThinkPad T410 2518C3U       | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| Fujitsu   | LIFEBOOK A544               | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI       | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Sony      | SVE1713A1EW                 | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| MSI       | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI       | GE76 Raider 11UE            | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook  | X170KM-G                    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Dell      | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP        | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo    | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell      | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.15.19     | 8         | 27.59%  |
| 5.17.1      | 2         | 6.9%    |
| 5.13.8      | 2         | 6.9%    |
| 5.17.5      | 1         | 3.45%   |
| 5.17.2      | 1         | 3.45%   |
| 5.16.9-joe1 | 1         | 3.45%   |
| 5.16.12     | 1         | 3.45%   |
| 5.15.63     | 1         | 3.45%   |
| 5.15.38     | 1         | 3.45%   |
| 5.15.37.a   | 1         | 3.45%   |
| 5.15.33.kjh | 1         | 3.45%   |
| 5.15.27     | 1         | 3.45%   |
| 5.15.1      | 1         | 3.45%   |
| 5.14.9      | 1         | 3.45%   |
| 5.14.8      | 1         | 3.45%   |
| 5.14.10     | 1         | 3.45%   |
| 5.14.0      | 1         | 3.45%   |
| 5.13.5      | 1         | 3.45%   |
| 5.13.11     | 1         | 3.45%   |
| 5.10.91     | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 8         | 27.59%  |
| 5.17.1  | 2         | 6.9%    |
| 5.13.8  | 2         | 6.9%    |
| 5.17.5  | 1         | 3.45%   |
| 5.17.2  | 1         | 3.45%   |
| 5.16.9  | 1         | 3.45%   |
| 5.16.12 | 1         | 3.45%   |
| 5.15.63 | 1         | 3.45%   |
| 5.15.38 | 1         | 3.45%   |
| 5.15.37 | 1         | 3.45%   |
| 5.15.33 | 1         | 3.45%   |
| 5.15.27 | 1         | 3.45%   |
| 5.15.1  | 1         | 3.45%   |
| 5.14.9  | 1         | 3.45%   |
| 5.14.8  | 1         | 3.45%   |
| 5.14.10 | 1         | 3.45%   |
| 5.14.0  | 1         | 3.45%   |
| 5.13.5  | 1         | 3.45%   |
| 5.13.11 | 1         | 3.45%   |
| 5.10.91 | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 14        | 50%     |
| 5.17    | 4         | 14.29%  |
| 5.13    | 4         | 14.29%  |
| 5.14    | 3         | 10.71%  |
| 5.16    | 2         | 7.14%   |
| 5.10    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 14        | 50%     |
| XFCE      | 6         | 21.43%  |
| Unknown   | 4         | 14.29%  |
| xwmconfig | 1         | 3.57%   |
| MATE      | 1         | 3.57%   |
| KDE       | 1         | 3.57%   |
| awesome   | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 18        | 62.07%  |
| Tty     | 9         | 31.03%  |
| Wayland | 2         | 6.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 17        | 60.71%  |
| Unknown | 8         | 28.57%  |
| XDM     | 3         | 10.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 75%     |
| fr_FR | 2         | 7.14%   |
| de_DE | 2         | 7.14%   |
| ru_RU | 1         | 3.57%   |
| pt_BR | 1         | 3.57%   |
| it_IT | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 57.14%  |
| BIOS | 12        | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 23        | 82.14%  |
| Btrfs   | 3         | 10.71%  |
| Overlay | 2         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 18        | 64.29%  |
| MBR     | 5         | 17.86%  |
| Unknown | 5         | 17.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 82.76%  |
| Yes       | 5         | 17.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 53.57%  |
| Yes       | 13        | 46.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 25%     |
| Hewlett-Packard  | 6         | 21.43%  |
| MSI              | 4         | 14.29%  |
| Dell             | 4         | 14.29%  |
| System76         | 1         | 3.57%   |
| Sony             | 1         | 3.57%   |
| Notebook         | 1         | 3.57%   |
| Fujitsu          | 1         | 3.57%   |
| Framework        | 1         | 3.57%   |
| Dynabook         | 1         | 3.57%   |
| ASUSTek Computer | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| System76 Oryx Pro                        | 1         | 3.57%   |
| Sony SVE1713A1EW                         | 1         | 3.57%   |
| Notebook X170KM-G                        | 1         | 3.57%   |
| MSI Modern 14 B11MO                      | 1         | 3.57%   |
| MSI Modern 14 B10MW                      | 1         | 3.57%   |
| MSI GP76 Leopard 11UG                    | 1         | 3.57%   |
| MSI GE76 Raider 11UE                     | 1         | 3.57%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 3.57%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 3.57%   |
| Lenovo ThinkPad T61 765912G              | 1         | 3.57%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 3.57%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 3.57%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 3.57%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 3.57%   |
| HP ProBook 6570b                         | 1         | 3.57%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 3.57%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 3.57%   |
| HP Laptop 15-bs1xx                       | 1         | 3.57%   |
| HP EliteBook 840 G5                      | 1         | 3.57%   |
| HP 245 G7 Notebook PC                    | 1         | 3.57%   |
| Fujitsu LIFEBOOK A544                    | 1         | 3.57%   |
| Framework Laptop                         | 1         | 3.57%   |
| Dynabook P1-C7MP-BL                      | 1         | 3.57%   |
| Dell Vostro 3500                         | 1         | 3.57%   |
| Dell Precision M4700                     | 1         | 3.57%   |
| Dell Latitude 3520                       | 1         | 3.57%   |
| Dell Inspiron 15-3552                    | 1         | 3.57%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 6         | 21.43%  |
| MSI Modern          | 2         | 7.14%   |
| HP Pavilion         | 2         | 7.14%   |
| System76 Oryx       | 1         | 3.57%   |
| Sony SVE1713A1EW    | 1         | 3.57%   |
| Notebook X170KM-G   | 1         | 3.57%   |
| MSI GP76            | 1         | 3.57%   |
| MSI GE76            | 1         | 3.57%   |
| Lenovo IdeaPad      | 1         | 3.57%   |
| HP ProBook          | 1         | 3.57%   |
| HP Laptop           | 1         | 3.57%   |
| HP EliteBook        | 1         | 3.57%   |
| HP 245              | 1         | 3.57%   |
| Fujitsu LIFEBOOK    | 1         | 3.57%   |
| Framework Laptop    | 1         | 3.57%   |
| Dynabook P1-C7MP-BL | 1         | 3.57%   |
| Dell Vostro         | 1         | 3.57%   |
| Dell Precision      | 1         | 3.57%   |
| Dell Latitude       | 1         | 3.57%   |
| Dell Inspiron       | 1         | 3.57%   |
| ASUS ROG            | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 21.43%  |
| 2020 | 6         | 21.43%  |
| 2012 | 5         | 17.86%  |
| 2017 | 3         | 10.71%  |
| 2019 | 1         | 3.57%   |
| 2018 | 1         | 3.57%   |
| 2016 | 1         | 3.57%   |
| 2015 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |
| 2010 | 1         | 3.57%   |
| 2009 | 1         | 3.57%   |
| 2007 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 28        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 28        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 92.86%  |
| Yes  | 2         | 7.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 6         | 21.43%  |
| 3.01-4.0    | 6         | 21.43%  |
| 16.01-24.0  | 6         | 21.43%  |
| 8.01-16.0   | 6         | 21.43%  |
| 32.01-64.0  | 2         | 7.14%   |
| 24.01-32.0  | 1         | 3.57%   |
| 64.01-256.0 | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 10        | 33.33%  |
| 1.01-2.0   | 9         | 30%     |
| 4.01-8.0   | 6         | 20%     |
| 0.51-1.0   | 3         | 10%     |
| 16.01-24.0 | 1         | 3.33%   |
| 0.01-0.5   | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 71.43%  |
| 2      | 7         | 25%     |
| 4      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 75%     |
| Yes       | 7         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 82.14%  |
| No        | 5         | 17.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 92.86%  |
| No        | 2         | 7.14%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 8         | 28.57%  |
| Kazakhstan   | 3         | 10.71%  |
| South Africa | 2         | 7.14%   |
| Japan        | 2         | 7.14%   |
| Germany      | 2         | 7.14%   |
| France       | 2         | 7.14%   |
| Sweden       | 1         | 3.57%   |
| Spain        | 1         | 3.57%   |
| Serbia       | 1         | 3.57%   |
| Portugal     | 1         | 3.57%   |
| Mexico       | 1         | 3.57%   |
| Italy        | 1         | 3.57%   |
| Chile        | 1         | 3.57%   |
| Canada       | 1         | 3.57%   |
| Brazil       | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 6.9%    |
| Worpswede         | 1         | 3.45%   |
| Tsukuba           | 1         | 3.45%   |
| Sun Prairie       | 1         | 3.45%   |
| Skövde           | 1         | 3.45%   |
| Santiago          | 1         | 3.45%   |
| Round Rock        | 1         | 3.45%   |
| Reno              | 1         | 3.45%   |
| Renazzo           | 1         | 3.45%   |
| Plainwell         | 1         | 3.45%   |
| Ōtsu             | 1         | 3.45%   |
| Oberstreit        | 1         | 3.45%   |
| Montreal          | 1         | 3.45%   |
| Mexico City       | 1         | 3.45%   |
| McKinney          | 1         | 3.45%   |
| Luxeuil-les-Bains | 1         | 3.45%   |
| Lisbon            | 1         | 3.45%   |
| League City       | 1         | 3.45%   |
| Karaganda         | 1         | 3.45%   |
| Johannesburg      | 1         | 3.45%   |
| Hayward           | 1         | 3.45%   |
| Fortaleza         | 1         | 3.45%   |
| Chessy            | 1         | 3.45%   |
| Cape Town         | 1         | 3.45%   |
| Bremervoerde      | 1         | 3.45%   |
| Belgrade          | 1         | 3.45%   |
| Algeciras         | 1         | 3.45%   |
| Abingdon          | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 29.41%  |
| WDC                 | 5         | 5      | 14.71%  |
| Toshiba             | 3         | 3      | 8.82%   |
| SK hynix            | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| Seagate             | 1         | 1      | 2.94%   |
| Plextor             | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| KIOXIA              | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 2      | 2.94%   |
| Gigabyte Technology | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 5.41%   |
| WDC WD10JPVT-08A1YT2 1TB                            | 1         | 2.7%    |
| WDC WD Green 2.5 240GB                              | 1         | 2.7%    |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 1         | 2.7%    |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.7%    |
| Toshiba MQ01ACF032 320GB                            | 1         | 2.7%    |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.7%    |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 2.7%    |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB             | 1         | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2.7%    |
| SanDisk Ultra II 960GB SSD                          | 1         | 2.7%    |
| SanDisk SDSSDA240G 240GB                            | 1         | 2.7%    |
| Samsung SSD PM830 2.5 7mm 128GB                     | 1         | 2.7%    |
| Samsung SSD 980 PRO 500GB                           | 1         | 2.7%    |
| Samsung SSD 980 PRO 2TB                             | 1         | 2.7%    |
| Samsung SSD 970 EVO Plus 2TB                        | 1         | 2.7%    |
| Samsung SSD 970 EVO 2TB                             | 1         | 2.7%    |
| Samsung SSD 870 EVO 1TB                             | 1         | 2.7%    |
| Samsung SSD 860 EVO mSATA 500GB                     | 1         | 2.7%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 2.7%    |
| Samsung MZVLQ512HALU-000H1 512GB                    | 1         | 2.7%    |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 1         | 2.7%    |
| Samsung MZVKW512HMJP-000H1 512GB                    | 1         | 2.7%    |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 1         | 2.7%    |
| Plextor PX-128M6S 128GB SSD                         | 1         | 2.7%    |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 2.7%    |
| KIOXIA KBG40ZNS256G NVMe 256GB                      | 1         | 2.7%    |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 2.7%    |
| Kingston SHSS37A480G 480GB SSD                      | 1         | 2.7%    |
| Intel SSDPEKKF256G7L 256GB                          | 1         | 2.7%    |
| HGST HTS725050A7E630 500GB                          | 1         | 2.7%    |
| HGST HTS545050A7E380 500GB                          | 1         | 2.7%    |
| HP SSD EX950 2TB                                    | 1         | 2.7%    |
| Gigabyte GP-GSTFS31240GNTD 240GB                    | 1         | 2.7%    |
| Crucial CT500P2SSD8 500GB                           | 1         | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 33.33%  |
| Toshiba | 3         | 3      | 33.33%  |
| HGST    | 2         | 2      | 22.22%  |
| Seagate | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 5      | 30%     |
| SanDisk             | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Plextor             | 1         | 1      | 10%     |
| Gigabyte Technology | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 19     | 44.12%  |
| SSD  | 10        | 12     | 29.41%  |
| HDD  | 9         | 9      | 26.47%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 21     | 51.61%  |
| NVMe | 15        | 19     | 48.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 14     | 61.11%  |
| 0.51-1.0   | 7         | 7      | 38.89%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 8         | 28.57%  |
| 251-500        | 7         | 25%     |
| 101-250        | 7         | 25%     |
| 1001-2000      | 3         | 10.71%  |
| 1-20           | 2         | 7.14%   |
| More than 3000 | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 8         | 28.57%  |
| 21-50     | 6         | 21.43%  |
| 251-500   | 5         | 17.86%  |
| 1-20      | 5         | 17.86%  |
| 501-1000  | 2         | 7.14%   |
| 1001-2000 | 1         | 3.57%   |
| 51-100    | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 25%     |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 25%     |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 25%     |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Plextor             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| HDD  | 2         | 2      | 50%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 22        | 28     | 70.97%  |
| Detected | 5         | 8      | 16.13%  |
| Malfunc  | 4         | 4      | 12.9%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 17        | 50%     |
| Samsung Electronics       | 7         | 20.59%  |
| AMD                       | 3         | 8.82%   |
| SK hynix                  | 2         | 5.88%   |
| SanDisk                   | 1         | 2.94%   |
| Micron/Crucial Technology | 1         | 2.94%   |
| Micron Technology         | 1         | 2.94%   |
| KIOXIA                    | 1         | 2.94%   |
| Biwin Storage Technology  | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 11.11%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 8.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 8.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 5.56%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 5.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 5.56%   |
| SK hynix Gold P31 SSD                                                            | 1         | 2.78%   |
| SK hynix BC511                                                                   | 1         | 2.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.78%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.78%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.78%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.78%   |
| Intel SSD 600P Series                                                            | 1         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 2.78%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 16        | 45.71%  |
| NVMe | 15        | 42.86%  |
| RAID | 3         | 8.57%   |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 89.29%  |
| AMD    | 3         | 10.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 10.71%  |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 7.14%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 3.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.57%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.57%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 3.57%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.57%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 3.57%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.57%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 3.57%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.57%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 3.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.57%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.57%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 3.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 28.57%  |
| Other            | 7         | 25%     |
| Intel Core i7    | 6         | 21.43%  |
| AMD Ryzen 5      | 2         | 7.14%   |
| Intel Pentium    | 1         | 3.57%   |
| Intel Core i3    | 1         | 3.57%   |
| Intel Core 2 Duo | 1         | 3.57%   |
| Intel Celeron    | 1         | 3.57%   |
| AMD Ryzen 9      | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 46.43%  |
| 4      | 8         | 28.57%  |
| 8      | 6         | 21.43%  |
| 6      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 89.29%  |
| 1      | 3         | 10.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 25%     |
| 0x306a9    | 5         | 17.86%  |
| 0x806d1    | 3         | 10.71%  |
| 0x806c1    | 3         | 10.71%  |
| 0xa0671    | 1         | 3.57%   |
| 0xa0652    | 1         | 3.57%   |
| 0x806ec    | 1         | 3.57%   |
| 0x806ea    | 1         | 3.57%   |
| 0x406e3    | 1         | 3.57%   |
| 0x406c4    | 1         | 3.57%   |
| 0x306d4    | 1         | 3.57%   |
| 0x306c3    | 1         | 3.57%   |
| 0x08600106 | 1         | 3.57%   |
| 0x08108109 | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| IvyBridge  | 5         | 17.86%  |
| KabyLake   | 4         | 14.29%  |
| Icelake    | 4         | 14.29%  |
| TigerLake  | 3         | 10.71%  |
| Zen 2      | 2         | 7.14%   |
| Westmere   | 2         | 7.14%   |
| Skylake    | 2         | 7.14%   |
| Zen+       | 1         | 3.57%   |
| Silvermont | 1         | 3.57%   |
| Haswell    | 1         | 3.57%   |
| Core       | 1         | 3.57%   |
| CometLake  | 1         | 3.57%   |
| Broadwell  | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 58.82%  |
| Nvidia | 8         | 23.53%  |
| AMD    | 6         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 8.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 8.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 5.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 5.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 5.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.71%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 5.71%   |
| AMD Renoir                                                                               | 2         | 5.71%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 2.86%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 2.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.86%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.86%   |
| Intel HD Graphics 620                                                                    | 1         | 2.86%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.86%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 57.14%  |
| 1 x AMD        | 5         | 17.86%  |
| Intel + Nvidia | 4         | 14.29%  |
| 1 x Nvidia     | 2         | 7.14%   |
| AMD + Nvidia   | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 25        | 89.29%  |
| Proprietary | 3         | 10.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 67.86%  |
| 0.51-1.0   | 3         | 10.71%  |
| 7.01-8.0   | 2         | 7.14%   |
| 0.01-0.5   | 2         | 7.14%   |
| 5.01-6.0   | 1         | 3.57%   |
| 1.01-2.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 8         | 25.81%  |
| LG Display          | 7         | 22.58%  |
| AU Optronics        | 4         | 12.9%   |
| Sharp               | 2         | 6.45%   |
| Lenovo              | 2         | 6.45%   |
| Hewlett-Packard     | 2         | 6.45%   |
| Chimei Innolux      | 2         | 6.45%   |
| Sony                | 1         | 3.23%   |
| Samsung Electronics | 1         | 3.23%   |
| PANDA               | 1         | 3.23%   |
| Dell                | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY8102 1360x768                                             | 1         | 3.23%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 3.23%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 3.23%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 3.23%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch              | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4031 1280x800 286x179mm 13.3-inch              | 1         | 3.23%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 3.23%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 3.23%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch     | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 3.23%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                | 1         | 3.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch       | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 380x210mm 17.1-inch       | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 15        | 51.72%  |
| 1366x768 (WXGA) | 8         | 27.59%  |
| 1280x800 (WXGA) | 2         | 6.9%    |
| 3840x2160 (4K)  | 1         | 3.45%   |
| 2256x1504       | 1         | 3.45%   |
| 1600x900 (HD+)  | 1         | 3.45%   |
| 1360x768        | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 38.71%  |
| 14     | 6         | 19.35%  |
| 13     | 4         | 12.9%   |
| 17     | 3         | 9.68%   |
| 72     | 1         | 3.23%   |
| 27     | 1         | 3.23%   |
| 24     | 1         | 3.23%   |
| 21     | 1         | 3.23%   |
| 16     | 1         | 3.23%   |
| 12     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 67.74%  |
| 351-400     | 4         | 12.9%   |
| 501-600     | 2         | 6.45%   |
| 201-300     | 2         | 6.45%   |
| 401-500     | 1         | 3.23%   |
| 1501-2000   | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 85.71%  |
| 16/10 | 3         | 10.71%  |
| 3/2   | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 41.94%  |
| 81-90          | 10        | 32.26%  |
| 121-130        | 3         | 9.68%   |
| More than 1000 | 1         | 3.23%   |
| 61-70          | 1         | 3.23%   |
| 301-350        | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| 151-200        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 50%     |
| 101-120       | 9         | 30%     |
| 51-100        | 3         | 10%     |
| More than 240 | 1         | 3.33%   |
| 1-50          | 1         | 3.33%   |
| 161-240       | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 85.71%  |
| 2     | 4         | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 52.38%  |
| Realtek Semiconductor | 16        | 38.1%   |
| Ralink Technology     | 1         | 2.38%   |
| Qualcomm Atheros      | 1         | 2.38%   |
| Hewlett-Packard       | 1         | 2.38%   |
| Broadcom Limited      | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 22.22%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.56%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                        | 2         | 3.7%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.7%    |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.85%   |
| Intel Wireless 8260                                               | 1         | 1.85%   |
| Intel Wireless 7260                                               | 1         | 1.85%   |
| Intel Wireless 3165                                               | 1         | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.85%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.85%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 75%     |
| Realtek Semiconductor | 4         | 14.29%  |
| Ralink Technology     | 1         | 3.57%   |
| Qualcomm Atheros      | 1         | 3.57%   |
| Broadcom Limited      | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 10.34%  |
| Intel Wireless 8265 / 8275                                    | 2         | 6.9%    |
| Intel Wi-Fi 6 AX201                                           | 2         | 6.9%    |
| Intel Wi-Fi 6 AX200                                           | 2         | 6.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 6.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 3.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 3.45%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 3.45%   |
| Intel Wireless 8260                                           | 1         | 3.45%   |
| Intel Wireless 7260                                           | 1         | 3.45%   |
| Intel Wireless 3165                                           | 1         | 3.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 3.45%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 65.22%  |
| Intel                 | 8         | 34.78%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 50%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 12.5%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 8.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.17%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.17%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 53.85%  |
| Ethernet | 23        | 44.23%  |
| Modem    | 1         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 80.65%  |
| Ethernet | 6         | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 78.57%  |
| 1     | 6         | 21.43%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 89.29%  |
| Yes  | 3         | 10.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 65.38%  |
| Broadcom              | 5         | 19.23%  |
| Realtek Semiconductor | 3         | 11.54%  |
| Foxconn / Hon Hai     | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 6         | 23.08%  |
| Intel AX201 Bluetooth                            | 5         | 19.23%  |
| Intel AX210 Bluetooth                            | 3         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 7.69%   |
| Intel AX200 Bluetooth                            | 2         | 7.69%   |
| Realtek Bluetooth Radio                          | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 3.85%   |
| Broadcom HP Portable SoftSailing                 | 1         | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 3.85%   |
| Broadcom BCM20702A0                              | 1         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 3.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 25        | 62.5%   |
| Nvidia              | 8         | 20%     |
| AMD                 | 6         | 15%     |
| C-Media Electronics | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 11.36%  |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 9.09%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 6.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 6.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.55%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 4.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.27%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.27%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 22.22%  |
| Kingston            | 6         | 22.22%  |
| Samsung Electronics | 4         | 14.81%  |
| Micron Technology   | 3         | 11.11%  |
| Crucial             | 3         | 11.11%  |
| Neo Forza           | 1         | 3.7%    |
| Nanya Technology    | 1         | 3.7%    |
| Essencore Limited   | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |
| A-DATA Technology   | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 3.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 3.45%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 3.45%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 3.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 3.45%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 3.45%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 3.45%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 3.45%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 3.45%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 3.45%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 3.45%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.45%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 3.45%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 3.45%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 3.45%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 3.45%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 3.45%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 3.45%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 3.45%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 3.45%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 3200MT/s                | 1         | 3.45%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 3.45%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4GB SODIMM DDR3 1600MT/s                 | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 60.87%  |
| DDR3   | 8         | 34.78%  |
| LPDDR3 | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 95.65%  |
| Row Of Chips | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 48.15%  |
| 4096  | 10        | 37.04%  |
| 16384 | 3         | 11.11%  |
| 32768 | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 34.62%  |
| 1600  | 8         | 30.77%  |
| 2667  | 3         | 11.54%  |
| 2400  | 2         | 7.69%   |
| 2133  | 1         | 3.85%   |
| 1867  | 1         | 3.85%   |
| 1333  | 1         | 3.85%   |
| 701   | 1         | 3.85%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 28.57%  |
| Acer                                   | 7         | 25%     |
| Microdia                               | 4         | 14.29%  |
| Realtek Semiconductor                  | 2         | 7.14%   |
| Syntek                                 | 1         | 3.57%   |
| Samsung Electronics                    | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Luxvisions Innotech Limited            | 1         | 3.57%   |
| Logitech                               | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 10.71%  |
| Chicony Integrated Camera                                      | 2         | 7.14%   |
| Acer BisonCam,NB Pro                                           | 2         | 7.14%   |
| Syntek USB2.0 Camera                                           | 1         | 3.57%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 3.57%   |
| Realtek Laptop Camera                                          | 1         | 3.57%   |
| Realtek EasyCamera                                             | 1         | 3.57%   |
| Quanta HP Webcam                                               | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.57%   |
| Microdia Integrated Webcam                                     | 1         | 3.57%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 3.57%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 3.57%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 3.57%   |
| Chicony Web Camera - FHD                                       | 1         | 3.57%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 3.57%   |
| Chicony HP TrueVision HD Camera                                | 1         | 3.57%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.57%   |
| Chicony HP HD Camera                                           | 1         | 3.57%   |
| Chicony FJ Camera                                              | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.57%   |
| Acer ThinkPad Integrated Camera                                | 1         | 3.57%   |
| Acer Integrated Camera                                         | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 50%     |
| Synaptics          | 2         | 33.33%  |
| STMicroelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI            | 2         | 33.33%  |
| Unknown                                    | 2         | 33.33%  |
| Validity Sensors VFS300 Fingerprint Reader | 1         | 16.67%  |
| STMicroelectronics Fingerprint Reader      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 64.29%  |
| 1     | 8         | 28.57%  |
| 2     | 2         | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 50%     |
| Multimedia controller | 2         | 16.67%  |
| Net/wireless          | 1         | 8.33%   |
| Graphics card         | 1         | 8.33%   |
| Chipcard              | 1         | 8.33%   |
| Bluetooth             | 1         | 8.33%   |

