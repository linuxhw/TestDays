antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 13        | 43.33%  |
| antiX 19.2     | 6         | 20%     |
| antiX 19.3     | 3         | 10%     |
| antiX 19.4     | 2         | 6.67%   |
| antiX 19.1     | 2         | 6.67%   |
| antiX 21-runit | 1         | 3.33%   |
| antiX 17.4.1   | 1         | 3.33%   |
| antiX 17.2.1   | 1         | 3.33%   |
| antiX 17       | 1         | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 7         | 23.33%  |
| 5.10.57-antix.1-amd64-smp    | 3         | 10%     |
| 4.9.0-279-antix.1-amd64-smp  | 3         | 10%     |
| 4.9.235-antix.1-amd64-smp    | 2         | 6.67%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 6.67%   |
| 4.9.212-antix.1-486-smp      | 2         | 6.67%   |
| 4.9.200-antix.1-486-smp      | 2         | 6.67%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 3.33%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 3.33%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 3.33%   |
| 4.9.160-antix.2-486-smp      | 1         | 3.33%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 3.33%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 3.33%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 3.33%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 3.33%   |
| 4.10.5-antix.1-486-smp       | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 11        | 36.67%  |
| 4.9.212  | 4         | 13.33%  |
| 5.10.57  | 3         | 10%     |
| 4.9.235  | 2         | 6.67%   |
| 4.9.200  | 2         | 6.67%   |
| 4.9.160  | 2         | 6.67%   |
| 5.14.0   | 1         | 3.33%   |
| 5.10.88  | 1         | 3.33%   |
| 5.10.27  | 1         | 3.33%   |
| 4.19.202 | 1         | 3.33%   |
| 4.19.100 | 1         | 3.33%   |
| 4.10.5   | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 21        | 70%     |
| 5.10    | 5         | 16.67%  |
| 4.19    | 2         | 6.67%   |
| 5.14    | 1         | 3.33%   |
| 4.10    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 15        | 50%     |
| x86_64 | 14        | 46.67%  |
| i586   | 1         | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 56.67%  |
| icewm   | 11        | 36.67%  |
| XFCE    | 1         | 3.33%   |
| GNOME   | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 30        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 15        | 50%     |
| Unknown | 11        | 36.67%  |
| LightDM | 2         | 6.67%   |
| SLIMSKI | 1         | 3.33%   |
| SDDM    | 1         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 43.33%  |
| de_DE | 3         | 10%     |
| ru_RU | 2         | 6.67%   |
| ja_JP | 2         | 6.67%   |
| en_AU | 2         | 6.67%   |
| zh_HK | 1         | 3.33%   |
| uk_UA | 1         | 3.33%   |
| pt_BR | 1         | 3.33%   |
| nl_NL | 1         | 3.33%   |
| it_IT | 1         | 3.33%   |
| es_VE | 1         | 3.33%   |
| es_MX | 1         | 3.33%   |
| en_GB | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 80%     |
| EFI  | 6         | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 25        | 83.33%  |
| Overlay  | 4         | 13.33%  |
| Reiserfs | 1         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 23        | 76.67%  |
| GPT     | 6         | 20%     |
| Unknown | 1         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 83.33%  |
| Yes       | 5         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 56.67%  |
| Yes       | 13        | 43.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 7         | 23.33%  |
| Hewlett-Packard     | 5         | 16.67%  |
| IBM                 | 3         | 10%     |
| Lenovo              | 2         | 6.67%   |
| Dell                | 2         | 6.67%   |
| Acer                | 2         | 6.67%   |
| Toshiba             | 1         | 3.33%   |
| Samsung Electronics | 1         | 3.33%   |
| Packard Bell        | 1         | 3.33%   |
| MSI                 | 1         | 3.33%   |
| Medion              | 1         | 3.33%   |
| KOHJINSHA           | 1         | 3.33%   |
| Fujitsu             | 1         | 3.33%   |
| Compaq              | 1         | 3.33%   |
| Apple               | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba Satellite 1905             | 1         | 3.33%   |
| Samsung SQ1S                       | 1         | 3.33%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 3.33%   |
| MSI GE62 7RE                       | 1         | 3.33%   |
| Medion WIM2170                     | 1         | 3.33%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 3.33%   |
| Lenovo G550 2958                   | 1         | 3.33%   |
| KOHJINSHA SX series                | 1         | 3.33%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 3.33%   |
| IBM ThinkPad T41 2374K50           | 1         | 3.33%   |
| IBM ThinkPad T40 237342G           | 1         | 3.33%   |
| HP Pavilion dv2700                 | 1         | 3.33%   |
| HP Mini 5101                       | 1         | 3.33%   |
| HP Mini 110-3700                   | 1         | 3.33%   |
| HP EliteBook 8770w                 | 1         | 3.33%   |
| HP EliteBook 2570p                 | 1         | 3.33%   |
| Fujitsu FMVS54EB                   | 1         | 3.33%   |
| Dell Latitude E6400                | 1         | 3.33%   |
| Dell Latitude 5480                 | 1         | 3.33%   |
| Compaq Tablet PC TC1000            | 1         | 3.33%   |
| ASUS X71SL                         | 1         | 3.33%   |
| ASUS X51RL                         | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 3.33%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 3.33%   |
| ASUS A3L                           | 1         | 3.33%   |
| ASUS 900HA                         | 1         | 3.33%   |
| ASUS 900A                          | 1         | 3.33%   |
| Apple MacBook7,1                   | 1         | 3.33%   |
| Acer Aspire 5920G                  | 1         | 3.33%   |
| Acer AOA150                        | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 10%     |
| HP Mini               | 2         | 6.67%   |
| HP EliteBook          | 2         | 6.67%   |
| Dell Latitude         | 2         | 6.67%   |
| ASUS VivoBook         | 2         | 6.67%   |
| Toshiba Satellite     | 1         | 3.33%   |
| Samsung SQ1S          | 1         | 3.33%   |
| Packard Bell EasyNote | 1         | 3.33%   |
| MSI GE62              | 1         | 3.33%   |
| Medion WIM2170        | 1         | 3.33%   |
| Lenovo ThinkPad       | 1         | 3.33%   |
| Lenovo G550           | 1         | 3.33%   |
| KOHJINSHA SX          | 1         | 3.33%   |
| HP Pavilion           | 1         | 3.33%   |
| Fujitsu FMVS54EB      | 1         | 3.33%   |
| Compaq Tablet         | 1         | 3.33%   |
| ASUS X71SL            | 1         | 3.33%   |
| ASUS X51RL            | 1         | 3.33%   |
| ASUS A3L              | 1         | 3.33%   |
| ASUS 900HA            | 1         | 3.33%   |
| ASUS 900A             | 1         | 3.33%   |
| Apple MacBook7        | 1         | 3.33%   |
| Acer Aspire           | 1         | 3.33%   |
| Acer AOA150           | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 16.67%  |
| 2007 | 5         | 16.67%  |
| 2009 | 4         | 13.33%  |
| 2003 | 3         | 10%     |
| 2013 | 2         | 6.67%   |
| 2012 | 2         | 6.67%   |
| 2005 | 2         | 6.67%   |
| 2020 | 1         | 3.33%   |
| 2019 | 1         | 3.33%   |
| 2017 | 1         | 3.33%   |
| 2016 | 1         | 3.33%   |
| 2011 | 1         | 3.33%   |
| 2010 | 1         | 3.33%   |
| 2004 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 26.67%  |
| 0.51-1.0   | 7         | 23.33%  |
| 1.01-2.0   | 5         | 16.67%  |
| 2.01-3.0   | 4         | 13.33%  |
| 32.01-64.0 | 2         | 6.67%   |
| 8.01-16.0  | 2         | 6.67%   |
| 4.01-8.0   | 1         | 3.33%   |
| 16.01-24.0 | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 12        | 40%     |
| 0.51-1.0 | 11        | 36.67%  |
| 1.01-2.0 | 4         | 13.33%  |
| 2.01-3.0 | 3         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 86.67%  |
| 2      | 3         | 10%     |
| 3      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 53.33%  |
| No        | 14        | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 86.67%  |
| No        | 4         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 96.67%  |
| No        | 1         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 60%     |
| Yes       | 12        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 20%     |
| Germany     | 4         | 13.33%  |
| Russia      | 3         | 10%     |
| Hong Kong   | 3         | 10%     |
| Japan       | 2         | 6.67%   |
| Australia   | 2         | 6.67%   |
| Ukraine     | 1         | 3.33%   |
| Netherlands | 1         | 3.33%   |
| Mexico      | 1         | 3.33%   |
| Kenya       | 1         | 3.33%   |
| Kazakhstan  | 1         | 3.33%   |
| Italy       | 1         | 3.33%   |
| Hungary     | 1         | 3.33%   |
| Denmark     | 1         | 3.33%   |
| Chile       | 1         | 3.33%   |
| Brazil      | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 3         | 10%     |
| Sydney                    | 2         | 6.67%   |
| Moscow                    | 2         | 6.67%   |
| Yuzhno-Sakhalinsk         | 1         | 3.33%   |
| Yokohama                  | 1         | 3.33%   |
| Toms River                | 1         | 3.33%   |
| Schloss Holte-Stukenbrock | 1         | 3.33%   |
| Santiago                  | 1         | 3.33%   |
| Salto                     | 1         | 3.33%   |
| Rotterdam                 | 1         | 3.33%   |
| Reutlingen                | 1         | 3.33%   |
| Portland                  | 1         | 3.33%   |
| Norden                    | 1         | 3.33%   |
| Neyagawa                  | 1         | 3.33%   |
| Nairobi                   | 1         | 3.33%   |
| Mittegrossefehn           | 1         | 3.33%   |
| Mechanicsburg             | 1         | 3.33%   |
| Karaganda                 | 1         | 3.33%   |
| Jonesboro                 | 1         | 3.33%   |
| Inveruno                  | 1         | 3.33%   |
| Godley                    | 1         | 3.33%   |
| El Cerrito                | 1         | 3.33%   |
| Dnipro                    | 1         | 3.33%   |
| Copenhagen                | 1         | 3.33%   |
| Celaya                    | 1         | 3.33%   |
| Budapest                  | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 9         | 9      | 26.47%  |
| Seagate             | 6         | 6      | 17.65%  |
| WDC                 | 4         | 4      | 11.76%  |
| Toshiba             | 2         | 2      | 5.88%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| Zheino              | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |
| RECADATA            | 1         | 1      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| BHT                 | 1         | 1      | 2.94%   |
| ASUS-PHISON         | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB          | 2         | 5.88%   |
| Hitachi HTS548040M9AT00 40GB       | 2         | 5.88%   |
| Zheino CHN mSATAM3 128 128GB SSD   | 1         | 2.94%   |
| WDC WD5000LPLX-08ZNTT0 500GB       | 1         | 2.94%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 2.94%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 2.94%   |
| WDC WD1200BEVE-00A0HT0 120GB       | 1         | 2.94%   |
| Unknown SR64G  64GB                | 1         | 2.94%   |
| Toshiba THNSNJ256G8NY 256GB SSD    | 1         | 2.94%   |
| Toshiba MK2576GSX 250GB            | 1         | 2.94%   |
| Seagate ST9160411AS 160GB          | 1         | 2.94%   |
| Seagate ST9160314AS 160GB          | 1         | 2.94%   |
| Seagate ST9160310AS 160GB          | 1         | 2.94%   |
| Seagate ST9160301AS 160GB          | 1         | 2.94%   |
| Seagate ST500LM030-1RK17D 500GB    | 1         | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 2.94%   |
| RECADATA RD-S350MCN-N0642 64GB SSD | 1         | 2.94%   |
| OCZ AGILITY3 120GB SSD             | 1         | 2.94%   |
| Kingston SUV500MS120G 120GB SSD    | 1         | 2.94%   |
| Kingston SUV400S37120G 120GB SSD   | 1         | 2.94%   |
| Intel SSDSC2BW180A3H 180GB         | 1         | 2.94%   |
| Hitachi HTS725050A7E630 500GB      | 1         | 2.94%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 2.94%   |
| Hitachi HTS721060G9AT00 64GB       | 1         | 2.94%   |
| Hitachi HTS545025B9A300 250GB      | 1         | 2.94%   |
| Hitachi HTS542525K9SA00 250GB      | 1         | 2.94%   |
| Hitachi HTS541612J9SA00 120GB      | 1         | 2.94%   |
| Hitachi HTC426040G8CE00 40GB       | 1         | 2.94%   |
| HGST HTS721010A9E630 1TB           | 1         | 2.94%   |
| HP SSD S750 512GB                  | 1         | 2.94%   |
| BHT WR202I0064G E70245F5 64GB      | 1         | 2.94%   |
| ASUS-PHISON SSD 8GB                | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 42.86%  |
| Seagate | 6         | 6      | 28.57%  |
| WDC     | 4         | 4      | 19.05%  |
| Toshiba | 1         | 1      | 4.76%   |
| HGST    | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| Zheino              | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| RECADATA            | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Hewlett-Packard     | 1         | 1      | 8.33%   |
| BHT                 | 1         | 1      | 8.33%   |
| ASUS-PHISON         | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 21     | 61.76%  |
| SSD  | 12        | 12     | 35.29%  |
| MMC  | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 33     | 96.77%  |
| MMC  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 31     | 93.75%  |
| 0.51-1.0   | 2         | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 33.33%  |
| 1-20       | 7         | 23.33%  |
| 51-100     | 5         | 16.67%  |
| 21-50      | 4         | 13.33%  |
| 251-500    | 2         | 6.67%   |
| 501-1000   | 1         | 3.33%   |
| Unknown    | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 22        | 73.33%  |
| 21-50   | 3         | 10%     |
| 101-250 | 2         | 6.67%   |
| 51-100  | 2         | 6.67%   |
| Unknown | 1         | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 10%     |
| Seagate ST9160314AS 160GB     | 1         | 1      | 10%     |
| Seagate ST9160310AS 160GB     | 1         | 1      | 10%     |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 10%     |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 10%     |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 10%     |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 10%     |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 10%     |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 10%     |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 7         | 7      | 70%     |
| Seagate | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 7         | 7      | 70%     |
| Seagate | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 100%    |

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
| Works    | 19        | 21     | 59.38%  |
| Malfunc  | 10        | 10     | 31.25%  |
| Detected | 3         | 3      | 9.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 75%     |
| Silicon Integrated Systems [SiS] | 2         | 6.25%   |
| AMD                              | 2         | 6.25%   |
| VIA Technologies                 | 1         | 3.13%   |
| Silicon Image                    | 1         | 3.13%   |
| Nvidia                           | 1         | 3.13%   |
| JMicron Technology               | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 7.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 7.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 7.69%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 7.69%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 5.13%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 5.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.13%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 2.56%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 2.56%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 2.56%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 2.56%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.56%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 2.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 2.56%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.56%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.56%   |
| AMD SB600 IDE                                                                  | 1         | 2.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 18        | 50%     |
| SATA | 15        | 41.67%  |
| RAID | 3         | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 28        | 93.33%  |
| GenuineTMx86 | 1         | 3.33%   |
| AMD          | 1         | 3.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 3         | 10%     |
| Intel Pentium M processor 1.60GHz              | 2         | 6.67%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 6.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 6.67%   |
| Intel Pentium M processor 1600MHz              | 1         | 3.33%   |
| Intel Pentium M processor 1.86GHz              | 1         | 3.33%   |
| Intel Pentium M processor 1.00GHz              | 1         | 3.33%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 3.33%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 3.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 3.33%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 3.33%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 3.33%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 3.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 3.33%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 3.33%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 3.33%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 3.33%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 3.33%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 3.33%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 3.33%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 1         | 3.33%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 3.33%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 1         | 3.33%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 3.33%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 6         | 20%     |
| Intel Atom              | 6         | 20%     |
| Intel Pentium M         | 5         | 16.67%  |
| Intel Core i7           | 3         | 10%     |
| Intel Core i5           | 2         | 6.67%   |
| Intel Celeron           | 2         | 6.67%   |
| Other                   | 1         | 3.33%   |
| Intel Pentium Dual      | 1         | 3.33%   |
| Intel Pentium 4         | 1         | 3.33%   |
| Intel Core i3           | 1         | 3.33%   |
| Intel Celeron Dual-Core | 1         | 3.33%   |
| AMD E2                  | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 46.67%  |
| 1      | 14        | 46.67%  |
| 4      | 2         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 60%     |
| 2      | 12        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 60%     |
| 32-bit         | 12        | 40%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 5         | 16.67%  |
| 0x6fd      | 4         | 13.33%  |
| 0x1067a    | 4         | 13.33%  |
| 0x6d6      | 3         | 10%     |
| 0x306a9    | 2         | 6.67%   |
| 0xf24      | 1         | 3.33%   |
| 0x906e9    | 1         | 3.33%   |
| 0x806e9    | 1         | 3.33%   |
| 0x706a1    | 1         | 3.33%   |
| 0x6d8      | 1         | 3.33%   |
| 0x695      | 1         | 3.33%   |
| 0x306c3    | 1         | 3.33%   |
| 0x206a7    | 1         | 3.33%   |
| 0x106ca    | 1         | 3.33%   |
| 0x10661    | 1         | 3.33%   |
| 0x07030106 | 1         | 3.33%   |
| Unknown    | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 6         | 20%     |
| P6            | 5         | 16.67%  |
| Core          | 5         | 16.67%  |
| Penryn        | 4         | 13.33%  |
| KabyLake      | 2         | 6.67%   |
| IvyBridge     | 2         | 6.67%   |
| SandyBridge   | 1         | 3.33%   |
| Puma          | 1         | 3.33%   |
| NetBurst      | 1         | 3.33%   |
| Haswell       | 1         | 3.33%   |
| Goldmont plus | 1         | 3.33%   |
| Unknown       | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17        | 54.84%  |
| AMD                              | 7         | 22.58%  |
| Nvidia                           | 6         | 19.35%  |
| Silicon Integrated Systems [SiS] | 1         | 3.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 11.11%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 11.11%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 5.56%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 5.56%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 2.78%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 2.78%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 2.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.78%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 2.78%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 2.78%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 2.78%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.78%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 2.78%   |
| Intel HD Graphics 630                                                         | 1         | 2.78%   |
| Intel HD Graphics 620                                                         | 1         | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2.78%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.78%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 2.78%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 2.78%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 2.78%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 2.78%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 50%     |
| 1 x AMD        | 7         | 23.33%  |
| 1 x Nvidia     | 5         | 16.67%  |
| Other          | 1         | 3.33%   |
| 1 x SiS        | 1         | 3.33%   |
| Intel + Nvidia | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 90%     |
| Unknown     | 2         | 6.67%   |
| Proprietary | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 18        | 60%     |
| Unknown    | 8         | 26.67%  |
| 1.01-2.0   | 3         | 10%     |
| 3.01-4.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 28.57%  |
| LG Display          | 5         | 23.81%  |
| Samsung Electronics | 3         | 14.29%  |
| HannStar            | 2         | 9.52%   |
| LG Philips          | 1         | 4.76%   |
| HJW                 | 1         | 4.76%   |
| Chimei Innolux      | 1         | 4.76%   |
| BOE                 | 1         | 4.76%   |
| Apple               | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 4.76%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 4.76%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 4.76%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 4.76%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 4.76%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 4.76%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 4.76%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 4.76%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 4.76%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 4.76%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 35%     |
| 1920x1080 (FHD)  | 4         | 20%     |
| 1280x800 (WXGA)  | 4         | 20%     |
| 1024x600         | 3         | 15%     |
| 1440x900 (WXGA+) | 2         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 28.57%  |
| 14     | 4         | 19.05%  |
| 13     | 4         | 19.05%  |
| 17     | 2         | 9.52%   |
| 10     | 2         | 9.52%   |
| 8      | 2         | 9.52%   |
| 32     | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 52.38%  |
| 201-300     | 5         | 23.81%  |
| 351-400     | 2         | 9.52%   |
| 101-200     | 2         | 9.52%   |
| 701-800     | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 13        | 65%     |
| 16/10 | 7         | 35%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 28.57%  |
| 101-110        | 6         | 28.57%  |
| 71-80          | 2         | 9.52%   |
| 41-50          | 2         | 9.52%   |
| 1-40           | 2         | 9.52%   |
| 351-500        | 1         | 4.76%   |
| 131-140        | 1         | 4.76%   |
| 121-130        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 8         | 38.1%   |
| 101-120 | 8         | 38.1%   |
| 51-100  | 5         | 23.81%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 90%     |
| 2     | 2         | 6.67%   |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 14        | 28.57%  |
| Intel                            | 14        | 28.57%  |
| Realtek Semiconductor            | 7         | 14.29%  |
| Broadcom                         | 6         | 12.24%  |
| Silicon Integrated Systems [SiS] | 2         | 4.08%   |
| Marvell Technology Group         | 2         | 4.08%   |
| Ralink                           | 1         | 2.04%   |
| Qualcomm Atheros Communications  | 1         | 2.04%   |
| Nvidia                           | 1         | 2.04%   |
| Hewlett-Packard                  | 1         | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 6         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 4.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 3.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 3.17%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.17%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 3.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 3.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.59%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 1.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.59%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.59%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.59%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.59%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.59%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.59%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.59%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.59%   |
| Intel Wireless 7260                                                           | 1         | 1.59%   |
| Intel WiFi Link 5100                                                          | 1         | 1.59%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.59%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.59%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.59%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.59%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.59%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.59%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.59%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.59%   |
| Intel 82551QM Ethernet Controller                                             | 1         | 1.59%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.59%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 12        | 38.71%  |
| Intel                           | 12        | 38.71%  |
| Broadcom                        | 4         | 12.9%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| Ralink                          | 1         | 3.23%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 6         | 18.75%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 6.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 6.25%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 6.25%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 3.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 3.13%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 3.13%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 3.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 3.13%   |
| Intel Wireless 7260                                                           | 1         | 3.13%   |
| Intel WiFi Link 5100                                                          | 1         | 3.13%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 3.13%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 3.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 3.13%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 3.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 3.13%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 3.13%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 3.13%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9         | 34.62%  |
| Realtek Semiconductor            | 6         | 23.08%  |
| Qualcomm Atheros                 | 3         | 11.54%  |
| Broadcom                         | 3         | 11.54%  |
| Silicon Integrated Systems [SiS] | 2         | 7.69%   |
| Marvell Technology Group         | 2         | 7.69%   |
| Nvidia                           | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 11.54%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 7.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 7.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.69%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 7.69%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1         | 3.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.85%   |
| Nvidia MCP89 Ethernet                                             | 1         | 3.85%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 3.85%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 3.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.85%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 3.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.85%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 3.85%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 3.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 3.85%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 48.33%  |
| Ethernet | 26        | 43.33%  |
| Modem    | 5         | 8.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 85.71%  |
| Ethernet | 4         | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 83.33%  |
| 1     | 5         | 16.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 80%     |
| Yes  | 6         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 4         | 33.33%  |
| Intel                   | 2         | 16.67%  |
| IMC Networks            | 2         | 16.67%  |
| Ralink Technology       | 1         | 8.33%   |
| Cambridge Silicon Radio | 1         | 8.33%   |
| ASUSTek Computer        | 1         | 8.33%   |
| Apple                   | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Device                       | 2         | 16.67%  |
| Broadcom HP Portable SoftSailing                    | 2         | 16.67%  |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 8.33%   |
| Intel Bluetooth wireless interface                  | 1         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 8.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 8.33%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 8.33%   |
| Apple Bluetooth Host Controller                     | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 75%     |
| AMD                              | 3         | 9.38%   |
| Silicon Integrated Systems [SiS] | 2         | 6.25%   |
| Nvidia                           | 2         | 6.25%   |
| VIA Technologies                 | 1         | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 14.71%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 8.82%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 8.82%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 5.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5.88%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 2.94%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.94%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.94%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.94%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.94%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.94%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 2.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.94%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 14        | 43.75%  |
| SK hynix            | 6         | 18.75%  |
| Micron Technology   | 3         | 9.38%   |
| Samsung Electronics | 2         | 6.25%   |
| Kingston            | 2         | 6.25%   |
| Unknown             | 2         | 6.25%   |
| Unknown (8A02)      | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |
| Avant               | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 8.82%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 5.88%   |
| Unknown                                                        | 2         | 5.88%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2.94%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 2.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.94%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 2.94%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.94%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.94%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.94%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.94%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.94%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s       | 1         | 2.94%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 2.94%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.94%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.94%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.94%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.94%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 7         | 25%     |
| DDR3  | 7         | 25%     |
| DDR2  | 5         | 17.86%  |
| DDR   | 5         | 17.86%  |
| DDR4  | 3         | 10.71%  |
| DRAM  | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 26        | 92.86%  |
| DIMM   | 2         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 10        | 31.25%  |
| 1024  | 9         | 28.13%  |
| 8192  | 4         | 12.5%   |
| 4096  | 3         | 9.38%   |
| 512   | 3         | 9.38%   |
| 16384 | 1         | 3.13%   |
| 256   | 1         | 3.13%   |
| 232   | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 41.38%  |
| 1600    | 4         | 13.79%  |
| 1067    | 3         | 10.34%  |
| 667     | 2         | 6.9%    |
| 3266    | 1         | 3.45%   |
| 2667    | 1         | 3.45%   |
| 2400    | 1         | 3.45%   |
| 1333    | 1         | 3.45%   |
| 975     | 1         | 3.45%   |
| 800     | 1         | 3.45%   |
| 533     | 1         | 3.45%   |
| 266     | 1         | 3.45%   |

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
| Chicony Electronics                    | 5         | 25%     |
| Microdia                               | 3         | 15%     |
| Pixart Imaging                         | 2         | 10%     |
| IMC Networks                           | 2         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 2         | 10%     |
| Acer                                   | 2         | 10%     |
| Suyin                                  | 1         | 5%      |
| Sunplus Innovation Technology          | 1         | 5%      |
| Importek                               | 1         | 5%      |
| Apple                                  | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 10%     |
| Microdia Sonix USB 2.0 Camera                           | 2         | 10%     |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 10%     |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 5%      |
| Sunplus Integrated_Webcam_HD                            | 1         | 5%      |
| Microdia Integrated Webcam                              | 1         | 5%      |
| Importek FJ Camera                                      | 1         | 5%      |
| Chicony VGA 30fps UVC Webcam                            | 1         | 5%      |
| Chicony Integrated HP HD Webcam                         | 1         | 5%      |
| Chicony HP HD Webcam [Fixed]                            | 1         | 5%      |
| Chicony CNF8243 Webcam                                  | 1         | 5%      |
| Chicony CNF7050                                         | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 5%      |
| Apple Built-in iSight                                   | 1         | 5%      |
| Acer Lenovo EasyCamera                                  | 1         | 5%      |
| Acer HP Webcam                                          | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors VFS491              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor | 1         | 33.33%  |
| AuthenTec AES1600                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 24        | 80%     |
| 1     | 5         | 16.67%  |
| 2     | 1         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 42.86%  |
| Fingerprint reader | 3         | 42.86%  |
| Chipcard           | 1         | 14.29%  |

