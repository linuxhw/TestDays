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

Total: 37

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Acer      | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
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
| 5.15.19     | 9         | 28.13%  |
| 5.17.1      | 2         | 6.25%   |
| 5.13.8      | 2         | 6.25%   |
| 6.1.1       | 1         | 3.13%   |
| 5.19.17     | 1         | 3.13%   |
| 5.17.5      | 1         | 3.13%   |
| 5.17.2      | 1         | 3.13%   |
| 5.16.9-joe1 | 1         | 3.13%   |
| 5.16.12     | 1         | 3.13%   |
| 5.15.63     | 1         | 3.13%   |
| 5.15.38     | 1         | 3.13%   |
| 5.15.37.a   | 1         | 3.13%   |
| 5.15.33.kjh | 1         | 3.13%   |
| 5.15.27     | 1         | 3.13%   |
| 5.15.1      | 1         | 3.13%   |
| 5.14.9      | 1         | 3.13%   |
| 5.14.8      | 1         | 3.13%   |
| 5.14.10     | 1         | 3.13%   |
| 5.14.0      | 1         | 3.13%   |
| 5.13.5      | 1         | 3.13%   |
| 5.13.11     | 1         | 3.13%   |
| 5.10.91     | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 9         | 28.13%  |
| 5.17.1  | 2         | 6.25%   |
| 5.13.8  | 2         | 6.25%   |
| 6.1.1   | 1         | 3.13%   |
| 5.19.17 | 1         | 3.13%   |
| 5.17.5  | 1         | 3.13%   |
| 5.17.2  | 1         | 3.13%   |
| 5.16.9  | 1         | 3.13%   |
| 5.16.12 | 1         | 3.13%   |
| 5.15.63 | 1         | 3.13%   |
| 5.15.38 | 1         | 3.13%   |
| 5.15.37 | 1         | 3.13%   |
| 5.15.33 | 1         | 3.13%   |
| 5.15.27 | 1         | 3.13%   |
| 5.15.1  | 1         | 3.13%   |
| 5.14.9  | 1         | 3.13%   |
| 5.14.8  | 1         | 3.13%   |
| 5.14.10 | 1         | 3.13%   |
| 5.14.0  | 1         | 3.13%   |
| 5.13.5  | 1         | 3.13%   |
| 5.13.11 | 1         | 3.13%   |
| 5.10.91 | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 15        | 48.39%  |
| 5.17    | 4         | 12.9%   |
| 5.13    | 4         | 12.9%   |
| 5.14    | 3         | 9.68%   |
| 5.16    | 2         | 6.45%   |
| 6.1     | 1         | 3.23%   |
| 5.19    | 1         | 3.23%   |
| 5.10    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 17        | 53.13%  |
| XFCE      | 6         | 18.75%  |
| Unknown   | 4         | 12.5%   |
| xwmconfig | 1         | 3.13%   |
| MATE      | 1         | 3.13%   |
| KDE       | 1         | 3.13%   |
| GNOME     | 1         | 3.13%   |
| awesome   | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 19        | 57.58%  |
| Tty     | 11        | 33.33%  |
| Wayland | 3         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 19        | 59.38%  |
| Unknown | 9         | 28.13%  |
| XDM     | 3         | 9.38%   |
| GDM     | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 23        | 74.19%  |
| pt_BR | 2         | 6.45%   |
| fr_FR | 2         | 6.45%   |
| de_DE | 2         | 6.45%   |
| ru_RU | 1         | 3.23%   |
| it_IT | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 18        | 58.06%  |
| BIOS | 13        | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 80.65%  |
| Btrfs   | 3         | 9.68%   |
| Overlay | 2         | 6.45%   |
| Xfs     | 1         | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 20        | 64.52%  |
| Unknown | 6         | 19.35%  |
| MBR     | 5         | 16.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 84.38%  |
| Yes       | 5         | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 51.61%  |
| Yes       | 15        | 48.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 22.58%  |
| Hewlett-Packard  | 7         | 22.58%  |
| MSI              | 4         | 12.9%   |
| Dell             | 4         | 12.9%   |
| ASUSTek Computer | 2         | 6.45%   |
| System76         | 1         | 3.23%   |
| Sony             | 1         | 3.23%   |
| Notebook         | 1         | 3.23%   |
| Fujitsu          | 1         | 3.23%   |
| Framework        | 1         | 3.23%   |
| Dynabook         | 1         | 3.23%   |
| Acer             | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| System76 Oryx Pro                        | 1         | 3.23%   |
| Sony SVE1713A1EW                         | 1         | 3.23%   |
| Notebook X170KM-G                        | 1         | 3.23%   |
| MSI Modern 14 B11MO                      | 1         | 3.23%   |
| MSI Modern 14 B10MW                      | 1         | 3.23%   |
| MSI GP76 Leopard 11UG                    | 1         | 3.23%   |
| MSI GE76 Raider 11UE                     | 1         | 3.23%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 3.23%   |
| Lenovo ThinkPad T61 765912G              | 1         | 3.23%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 3.23%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 3.23%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 3.23%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 3.23%   |
| HP ProBook 6570b                         | 1         | 3.23%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 3.23%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 3.23%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 3.23%   |
| HP Laptop 15-bs1xx                       | 1         | 3.23%   |
| HP EliteBook 840 G5                      | 1         | 3.23%   |
| HP 245 G7 Notebook PC                    | 1         | 3.23%   |
| Fujitsu LIFEBOOK A544                    | 1         | 3.23%   |
| Framework Laptop                         | 1         | 3.23%   |
| Dynabook P1-C7MP-BL                      | 1         | 3.23%   |
| Dell Vostro 3500                         | 1         | 3.23%   |
| Dell Precision M4700                     | 1         | 3.23%   |
| Dell Latitude 3520                       | 1         | 3.23%   |
| Dell Inspiron 15-3552                    | 1         | 3.23%   |
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 1         | 3.23%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 3.23%   |
| Acer Nitro AN515-54                      | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 6         | 19.35%  |
| MSI Modern          | 2         | 6.45%   |
| HP Pavilion         | 2         | 6.45%   |
| System76 Oryx       | 1         | 3.23%   |
| Sony SVE1713A1EW    | 1         | 3.23%   |
| Notebook X170KM-G   | 1         | 3.23%   |
| MSI GP76            | 1         | 3.23%   |
| MSI GE76            | 1         | 3.23%   |
| Lenovo IdeaPad      | 1         | 3.23%   |
| HP ProBook          | 1         | 3.23%   |
| HP OMEN             | 1         | 3.23%   |
| HP Laptop           | 1         | 3.23%   |
| HP EliteBook        | 1         | 3.23%   |
| HP 245              | 1         | 3.23%   |
| Fujitsu LIFEBOOK    | 1         | 3.23%   |
| Framework Laptop    | 1         | 3.23%   |
| Dynabook P1-C7MP-BL | 1         | 3.23%   |
| Dell Vostro         | 1         | 3.23%   |
| Dell Precision      | 1         | 3.23%   |
| Dell Latitude       | 1         | 3.23%   |
| Dell Inspiron       | 1         | 3.23%   |
| ASUS VivoBook       | 1         | 3.23%   |
| ASUS ROG            | 1         | 3.23%   |
| Acer Nitro          | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 19.35%  |
| 2020 | 6         | 19.35%  |
| 2012 | 5         | 16.13%  |
| 2017 | 3         | 9.68%   |
| 2022 | 2         | 6.45%   |
| 2019 | 2         | 6.45%   |
| 2018 | 1         | 3.23%   |
| 2016 | 1         | 3.23%   |
| 2015 | 1         | 3.23%   |
| 2013 | 1         | 3.23%   |
| 2010 | 1         | 3.23%   |
| 2009 | 1         | 3.23%   |
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
| Disabled | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 93.55%  |
| Yes  | 2         | 6.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 7         | 22.58%  |
| 8.01-16.0   | 7         | 22.58%  |
| 4.01-8.0    | 6         | 19.35%  |
| 3.01-4.0    | 6         | 19.35%  |
| 32.01-64.0  | 3         | 9.68%   |
| 24.01-32.0  | 1         | 3.23%   |
| 64.01-256.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 12        | 35.29%  |
| 1.01-2.0   | 9         | 26.47%  |
| 4.01-8.0   | 7         | 20.59%  |
| 0.51-1.0   | 3         | 8.82%   |
| 3.01-4.0   | 1         | 2.94%   |
| 16.01-24.0 | 1         | 2.94%   |
| 0.01-0.5   | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 70.97%  |
| 2      | 8         | 25.81%  |
| 4      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 80.65%  |
| No        | 6         | 19.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 93.55%  |
| No        | 2         | 6.45%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 8         | 25.81%  |
| Kazakhstan   | 3         | 9.68%   |
| South Africa | 2         | 6.45%   |
| Japan        | 2         | 6.45%   |
| Italy        | 2         | 6.45%   |
| Germany      | 2         | 6.45%   |
| France       | 2         | 6.45%   |
| Brazil       | 2         | 6.45%   |
| Sweden       | 1         | 3.23%   |
| Spain        | 1         | 3.23%   |
| Serbia       | 1         | 3.23%   |
| Portugal     | 1         | 3.23%   |
| Mexico       | 1         | 3.23%   |
| Greece       | 1         | 3.23%   |
| Chile        | 1         | 3.23%   |
| Canada       | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 6.25%   |
| Worpswede         | 1         | 3.13%   |
| Tsukuba           | 1         | 3.13%   |
| Sun Prairie       | 1         | 3.13%   |
| Skövde           | 1         | 3.13%   |
| Sao Paulo         | 1         | 3.13%   |
| Santiago          | 1         | 3.13%   |
| Round Rock        | 1         | 3.13%   |
| Reno              | 1         | 3.13%   |
| Renazzo           | 1         | 3.13%   |
| Plainwell         | 1         | 3.13%   |
| Ōtsu             | 1         | 3.13%   |
| Oberstreit        | 1         | 3.13%   |
| Montreal          | 1         | 3.13%   |
| Mexico City       | 1         | 3.13%   |
| McKinney          | 1         | 3.13%   |
| Luxeuil-les-Bains | 1         | 3.13%   |
| Lisbon            | 1         | 3.13%   |
| League City       | 1         | 3.13%   |
| Karaganda         | 1         | 3.13%   |
| Johannesburg      | 1         | 3.13%   |
| Hayward           | 1         | 3.13%   |
| Frignano          | 1         | 3.13%   |
| Fortaleza         | 1         | 3.13%   |
| Chessy            | 1         | 3.13%   |
| Chania            | 1         | 3.13%   |
| Cape Town         | 1         | 3.13%   |
| Bremervoerde      | 1         | 3.13%   |
| Belgrade          | 1         | 3.13%   |
| Algeciras         | 1         | 3.13%   |
| Abingdon          | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 27.03%  |
| WDC                 | 6         | 7      | 16.22%  |
| Toshiba             | 3         | 3      | 8.11%   |
| SanDisk             | 3         | 4      | 8.11%   |
| SK hynix            | 2         | 2      | 5.41%   |
| Kingston            | 2         | 2      | 5.41%   |
| Intel               | 2         | 2      | 5.41%   |
| HGST                | 2         | 2      | 5.41%   |
| Seagate             | 1         | 1      | 2.7%    |
| Plextor             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| KIOXIA              | 1         | 1      | 2.7%    |
| Hewlett-Packard     | 1         | 2      | 2.7%    |
| Gigabyte Technology | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 4.88%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 2.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 2.44%   |
| WDC WD10JPVT-08A1YT2 1TB                            | 1         | 2.44%   |
| WDC WD Green 2.5 240GB                              | 1         | 2.44%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 1         | 2.44%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.44%   |
| Toshiba MQ01ACF032 320GB                            | 1         | 2.44%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.44%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 2.44%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB             | 1         | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2.44%   |
| SanDisk Ultra II 960GB SSD                          | 1         | 2.44%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 2.44%   |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2.44%   |
| Samsung SSD PM830 2.5 7mm 128GB                     | 1         | 2.44%   |
| Samsung SSD 980 PRO 500GB                           | 1         | 2.44%   |
| Samsung SSD 980 PRO 2TB                             | 1         | 2.44%   |
| Samsung SSD 970 EVO Plus 2TB                        | 1         | 2.44%   |
| Samsung SSD 970 EVO 2TB                             | 1         | 2.44%   |
| Samsung SSD 870 EVO 1TB                             | 1         | 2.44%   |
| Samsung SSD 860 EVO mSATA 500GB                     | 1         | 2.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 2.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2.44%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 1         | 2.44%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 1         | 2.44%   |
| Samsung MZVKW512HMJP-000H1 512GB                    | 1         | 2.44%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 1         | 2.44%   |
| Plextor PX-128M6S 128GB SSD                         | 1         | 2.44%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 2.44%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                      | 1         | 2.44%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 2.44%   |
| Kingston SHSS37A480G 480GB SSD                      | 1         | 2.44%   |
| Intel SSDPEKKF256G7L 256GB                          | 1         | 2.44%   |
| Intel SSD 660P Series 1024GB                        | 1         | 2.44%   |
| HGST HTS725050A7E630 500GB                          | 1         | 2.44%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2.44%   |
| HP SSD EX950 2TB                                    | 1         | 2.44%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                | 1         | 2.44%   |
| Crucial CT500P2SSD8 500GB                           | 1         | 2.44%   |

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
| Samsung Electronics | 3         | 5      | 27.27%  |
| WDC                 | 2         | 3      | 18.18%  |
| SanDisk             | 2         | 2      | 18.18%  |
| Kingston            | 2         | 2      | 18.18%  |
| Plextor             | 1         | 1      | 9.09%   |
| Gigabyte Technology | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 22     | 45.95%  |
| SSD  | 11        | 14     | 29.73%  |
| HDD  | 9         | 9      | 24.32%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 22     | 50%     |
| SATA | 17        | 23     | 50%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 14     | 57.89%  |
| 0.51-1.0   | 8         | 9      | 42.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 10        | 32.26%  |
| 251-500        | 7         | 22.58%  |
| 101-250        | 7         | 22.58%  |
| 1001-2000      | 4         | 12.9%   |
| 1-20           | 2         | 6.45%   |
| More than 3000 | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 8         | 25%     |
| 251-500   | 6         | 18.75%  |
| 21-50     | 6         | 18.75%  |
| 1-20      | 6         | 18.75%  |
| 1001-2000 | 2         | 6.25%   |
| 501-1000  | 2         | 6.25%   |
| 51-100    | 2         | 6.25%   |

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
| Works    | 23        | 29     | 67.65%  |
| Detected | 7         | 12     | 20.59%  |
| Malfunc  | 4         | 4      | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 19        | 51.35%  |
| Samsung Electronics       | 7         | 18.92%  |
| AMD                       | 3         | 8.11%   |
| SK hynix                  | 2         | 5.41%   |
| SanDisk                   | 2         | 5.41%   |
| Micron/Crucial Technology | 1         | 2.7%    |
| Micron Technology         | 1         | 2.7%    |
| KIOXIA                    | 1         | 2.7%    |
| Biwin Storage Technology  | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 10%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 10%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 7.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 7.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 5%      |
| Samsung NVMe SSD Controller 980                                                  | 2         | 5%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 5%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 2.5%    |
| SK hynix BC511                                                                   | 1         | 2.5%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.5%    |
| Micron Non-Volatile memory controller                                            | 1         | 2.5%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.5%    |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.5%    |
| Intel SSD 660P Series                                                            | 1         | 2.5%    |
| Intel SSD 600P Series                                                            | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 2.5%    |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 17        | 43.59%  |
| SATA | 16        | 41.03%  |
| RAID | 5         | 12.82%  |
| IDE  | 1         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 90.32%  |
| AMD    | 3         | 9.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 9.68%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 6.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 6.45%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 3.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.23%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.23%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 3.23%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.23%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 3.23%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.23%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 3.23%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.23%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 3.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.23%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.23%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 3.23%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 9         | 29.03%  |
| Intel Core i5    | 8         | 25.81%  |
| Intel Core i7    | 7         | 22.58%  |
| AMD Ryzen 5      | 2         | 6.45%   |
| Intel Pentium    | 1         | 3.23%   |
| Intel Core i3    | 1         | 3.23%   |
| Intel Core 2 Duo | 1         | 3.23%   |
| Intel Celeron    | 1         | 3.23%   |
| AMD Ryzen 9      | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 41.94%  |
| 4      | 8         | 25.81%  |
| 8      | 6         | 19.35%  |
| 14     | 2         | 6.45%   |
| 6      | 2         | 6.45%   |

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
| 2      | 28        | 90.32%  |
| 1      | 3         | 9.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 25.81%  |
| 0x306a9    | 5         | 16.13%  |
| 0x806d1    | 3         | 9.68%   |
| 0x806c1    | 3         | 9.68%   |
| 0x906a3    | 2         | 6.45%   |
| 0xa0671    | 1         | 3.23%   |
| 0xa0652    | 1         | 3.23%   |
| 0x806ec    | 1         | 3.23%   |
| 0x806ea    | 1         | 3.23%   |
| 0x406e3    | 1         | 3.23%   |
| 0x406c4    | 1         | 3.23%   |
| 0x306d4    | 1         | 3.23%   |
| 0x306c3    | 1         | 3.23%   |
| 0x08600106 | 1         | 3.23%   |
| 0x08108109 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 5         | 16.13%  |
| IvyBridge        | 5         | 16.13%  |
| Icelake          | 4         | 12.9%   |
| TigerLake        | 3         | 9.68%   |
| Zen 2            | 2         | 6.45%   |
| Westmere         | 2         | 6.45%   |
| Skylake          | 2         | 6.45%   |
| Alderlake Hybrid | 2         | 6.45%   |
| Zen+             | 1         | 3.23%   |
| Silvermont       | 1         | 3.23%   |
| Haswell          | 1         | 3.23%   |
| Core             | 1         | 3.23%   |
| CometLake        | 1         | 3.23%   |
| Broadwell        | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 57.5%   |
| Nvidia | 11        | 27.5%   |
| AMD    | 6         | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 7.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 7.32%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 4.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 4.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 4.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 4.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 4.88%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 4.88%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 4.88%   |
| AMD Renoir                                                                               | 2         | 4.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.44%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 2.44%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 2.44%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.44%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.44%   |
| Intel HD Graphics 620                                                                    | 1         | 2.44%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.44%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 51.61%  |
| Intel + Nvidia | 7         | 22.58%  |
| 1 x AMD        | 5         | 16.13%  |
| 1 x Nvidia     | 2         | 6.45%   |
| AMD + Nvidia   | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 83.87%  |
| Proprietary | 5         | 16.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 67.74%  |
| 0.51-1.0   | 3         | 9.68%   |
| 7.01-8.0   | 2         | 6.45%   |
| 0.01-0.5   | 2         | 6.45%   |
| 5.01-6.0   | 1         | 3.23%   |
| 3.01-4.0   | 1         | 3.23%   |
| 1.01-2.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 9         | 26.47%  |
| LG Display          | 7         | 20.59%  |
| AU Optronics        | 5         | 14.71%  |
| Sharp               | 2         | 5.88%   |
| Samsung Electronics | 2         | 5.88%   |
| Lenovo              | 2         | 5.88%   |
| Hewlett-Packard     | 2         | 5.88%   |
| Chimei Innolux      | 2         | 5.88%   |
| Sony                | 1         | 2.94%   |
| PANDA               | 1         | 2.94%   |
| Dell                | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY8102 1360x768                                              | 1         | 2.94%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 2.94%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 2.94%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 2.94%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 1         | 2.94%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 2.94%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 2.94%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.94%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 2.94%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.94%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 2.94%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 380x210mm 17.1-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 17        | 53.13%  |
| 1366x768 (WXGA) | 8         | 25%     |
| 1280x800 (WXGA) | 2         | 6.25%   |
| 3840x2160 (4K)  | 1         | 3.13%   |
| 2880x1620       | 1         | 3.13%   |
| 2256x1504       | 1         | 3.13%   |
| 1600x900 (HD+)  | 1         | 3.13%   |
| 1360x768        | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 41.18%  |
| 14     | 6         | 17.65%  |
| 13     | 4         | 11.76%  |
| 17     | 3         | 8.82%   |
| 16     | 2         | 5.88%   |
| 72     | 1         | 2.94%   |
| 27     | 1         | 2.94%   |
| 24     | 1         | 2.94%   |
| 21     | 1         | 2.94%   |
| 12     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 67.65%  |
| 351-400     | 5         | 14.71%  |
| 501-600     | 2         | 5.88%   |
| 201-300     | 2         | 5.88%   |
| 401-500     | 1         | 2.94%   |
| 1501-2000   | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 87.1%   |
| 16/10 | 3         | 9.68%   |
| 3/2   | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 47.06%  |
| 81-90          | 10        | 29.41%  |
| 121-130        | 3         | 8.82%   |
| More than 1000 | 1         | 2.94%   |
| 61-70          | 1         | 2.94%   |
| 301-350        | 1         | 2.94%   |
| 251-300        | 1         | 2.94%   |
| 151-200        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 51.52%  |
| 101-120       | 9         | 27.27%  |
| 51-100        | 3         | 9.09%   |
| 161-240       | 2         | 6.06%   |
| More than 240 | 1         | 3.03%   |
| 1-50          | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 87.1%   |
| 2     | 4         | 12.9%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 47.92%  |
| Realtek Semiconductor | 18        | 37.5%   |
| MediaTek              | 2         | 4.17%   |
| Sitecom Europe        | 1         | 2.08%   |
| Ralink Technology     | 1         | 2.08%   |
| Qualcomm Atheros      | 1         | 2.08%   |
| Hewlett-Packard       | 1         | 2.08%   |
| Broadcom Limited      | 1         | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 23.33%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 5%      |
| Intel Wi-Fi 6 AX200                                               | 3         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5%      |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.33%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.33%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.33%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.67%   |
| MediaTek WLAN controller                                          | 1         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.67%   |
| Intel Wireless 8260                                               | 1         | 1.67%   |
| Intel Wireless 7260                                               | 1         | 1.67%   |
| Intel Wireless 3165                                               | 1         | 1.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.67%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.67%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 68.75%  |
| Realtek Semiconductor | 4         | 12.5%   |
| MediaTek              | 2         | 6.25%   |
| Sitecom Europe        | 1         | 3.13%   |
| Ralink Technology     | 1         | 3.13%   |
| Qualcomm Atheros      | 1         | 3.13%   |
| Broadcom Limited      | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 9.09%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 9.09%   |
| Intel Wireless 8265 / 8275                                    | 2         | 6.06%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 6.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 6.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 6.06%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 3.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 3.03%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 3.03%   |
| MediaTek WLAN controller                                      | 1         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 3.03%   |
| Intel Wireless 8260                                           | 1         | 3.03%   |
| Intel Wireless 7260                                           | 1         | 3.03%   |
| Intel Wireless 3165                                           | 1         | 3.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 3.03%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 68%     |
| Intel                 | 8         | 32%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 53.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 11.54%  |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 7.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 54.39%  |
| Ethernet | 25        | 43.86%  |
| Modem    | 1         | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 82.35%  |
| Ethernet | 6         | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 77.42%  |
| 1     | 7         | 22.58%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 87.1%   |
| Yes  | 4         | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 62.07%  |
| Broadcom              | 5         | 17.24%  |
| Realtek Semiconductor | 3         | 10.34%  |
| IMC Networks          | 2         | 6.9%    |
| Foxconn / Hon Hai     | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 6         | 20.69%  |
| Intel AX201 Bluetooth                            | 5         | 17.24%  |
| Intel AX210 Bluetooth                            | 3         | 10.34%  |
| Intel AX200 Bluetooth                            | 3         | 10.34%  |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 6.9%    |
| IMC Networks Wireless_Device                     | 2         | 6.9%    |
| Realtek Bluetooth Radio                          | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 3.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 3.45%   |
| Broadcom HP Portable SoftSailing                 | 1         | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 3.45%   |
| Broadcom BCM20702A0                              | 1         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 28        | 60.87%  |
| Nvidia              | 11        | 23.91%  |
| AMD                 | 6         | 13.04%  |
| C-Media Electronics | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 10%     |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 8%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 8%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 6%      |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 6%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 6%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 6%      |
| Nvidia Audio device                                                                               | 2         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 4%      |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2%      |
| Nvidia High Definition Audio Controller                                                           | 1         | 2%      |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2%      |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2%      |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 24.14%  |
| Kingston            | 6         | 20.69%  |
| Samsung Electronics | 5         | 17.24%  |
| Micron Technology   | 3         | 10.34%  |
| Crucial             | 3         | 10.34%  |
| Neo Forza           | 1         | 3.45%   |
| Nanya Technology    | 1         | 3.45%   |
| Essencore Limited   | 1         | 3.45%   |
| Corsair             | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 3.23%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 3.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 3.23%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s            | 1         | 3.23%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s            | 1         | 3.23%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 3.23%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 3.23%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 3.23%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s              | 1         | 3.23%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 3.23%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.23%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.23%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 3.23%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.23%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 3.23%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 3.23%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 3.23%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 3.23%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 3.23%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 3.23%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 3200MT/s                | 1         | 3.23%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4GB SODIMM DDR3 1600MT/s                 | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 56%     |
| DDR3   | 8         | 32%     |
| LPDDR5 | 1         | 4%      |
| LPDDR3 | 1         | 4%      |
| DDR5   | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 92%     |
| Row Of Chips | 2         | 8%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 48.28%  |
| 4096  | 10        | 34.48%  |
| 16384 | 3         | 10.34%  |
| 32768 | 1         | 3.45%   |
| 2048  | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 32.14%  |
| 1600  | 8         | 28.57%  |
| 2667  | 3         | 10.71%  |
| 2400  | 2         | 7.14%   |
| 6400  | 1         | 3.57%   |
| 4800  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1867  | 1         | 3.57%   |
| 1333  | 1         | 3.57%   |
| 701   | 1         | 3.57%   |

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
| Chicony Electronics                    | 9         | 29.03%  |
| Acer                                   | 7         | 22.58%  |
| Microdia                               | 4         | 12.9%   |
| Realtek Semiconductor                  | 2         | 6.45%   |
| Luxvisions Innotech Limited            | 2         | 6.45%   |
| Syntek                                 | 1         | 3.23%   |
| Sonix Technology                       | 1         | 3.23%   |
| Samsung Electronics                    | 1         | 3.23%   |
| Quanta                                 | 1         | 3.23%   |
| Logitech                               | 1         | 3.23%   |
| Lenovo                                 | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 9.68%   |
| Chicony Integrated Camera                                      | 2         | 6.45%   |
| Acer Integrated Camera                                         | 2         | 6.45%   |
| Acer BisonCam,NB Pro                                           | 2         | 6.45%   |
| Syntek USB2.0 Camera                                           | 1         | 3.23%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 1         | 3.23%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 3.23%   |
| Realtek Laptop Camera                                          | 1         | 3.23%   |
| Realtek EasyCamera                                             | 1         | 3.23%   |
| Quanta HP Webcam                                               | 1         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.23%   |
| Microdia Integrated Webcam                                     | 1         | 3.23%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 3.23%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 3.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 3.23%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 3.23%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 3.23%   |
| Chicony Web Camera - FHD                                       | 1         | 3.23%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 3.23%   |
| Chicony HP TrueVision HD Camera                                | 1         | 3.23%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.23%   |
| Chicony HP HD Camera                                           | 1         | 3.23%   |
| Chicony HD User Facing                                         | 1         | 3.23%   |
| Chicony FJ Camera                                              | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 3         | 42.86%  |
| Synaptics                          | 2         | 28.57%  |
| STMicroelectronics                 | 1         | 14.29%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 2         | 28.57%  |
| Unknown                                                         | 2         | 28.57%  |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                           | 1         | 14.29%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 14.29%  |

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
| 0     | 20        | 62.5%   |
| 1     | 9         | 28.13%  |
| 2     | 3         | 9.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 46.67%  |
| Net/wireless          | 2         | 13.33%  |
| Multimedia controller | 2         | 13.33%  |
| Graphics card         | 2         | 13.33%  |
| Chipcard              | 1         | 6.67%   |
| Bluetooth             | 1         | 6.67%   |

