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

Total: 45

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
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
| antiX 21       | 17        | 48.57%  |
| antiX 19.2     | 6         | 17.14%  |
| antiX 19.3     | 3         | 8.57%   |
| antiX 21-runit | 2         | 5.71%   |
| antiX 19.4     | 2         | 5.71%   |
| antiX 19.1     | 2         | 5.71%   |
| antiX 17.4.1   | 1         | 2.86%   |
| antiX 17.2.1   | 1         | 2.86%   |
| antiX 17       | 1         | 2.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 35        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 11        | 31.43%  |
| 5.10.57-antix.1-amd64-smp    | 3         | 8.57%   |
| 4.9.0-279-antix.1-amd64-smp  | 3         | 8.57%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 5.71%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 5.71%   |
| 4.9.212-antix.1-486-smp      | 2         | 5.71%   |
| 4.9.200-antix.1-486-smp      | 2         | 5.71%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 2.86%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 2.86%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 2.86%   |
| 4.9.160-antix.2-486-smp      | 1         | 2.86%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 2.86%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 2.86%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 2.86%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 2.86%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 2.86%   |
| 4.10.5-antix.1-486-smp       | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 15        | 42.86%  |
| 4.9.212  | 4         | 11.43%  |
| 5.10.57  | 3         | 8.57%   |
| 4.9.235  | 2         | 5.71%   |
| 4.9.200  | 2         | 5.71%   |
| 4.9.160  | 2         | 5.71%   |
| 5.14.0   | 1         | 2.86%   |
| 5.10.88  | 1         | 2.86%   |
| 5.10.27  | 1         | 2.86%   |
| 4.19.202 | 1         | 2.86%   |
| 4.19.100 | 1         | 2.86%   |
| 4.19.0   | 1         | 2.86%   |
| 4.10.5   | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 25        | 71.43%  |
| 5.10    | 5         | 14.29%  |
| 4.19    | 3         | 8.57%   |
| 5.14    | 1         | 2.86%   |
| 4.10    | 1         | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 19        | 54.29%  |
| x86_64 | 15        | 42.86%  |
| i586   | 1         | 2.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 60%     |
| icewm   | 12        | 34.29%  |
| XFCE    | 1         | 2.86%   |
| GNOME   | 1         | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 35        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 45.71%  |
| SLiM    | 15        | 42.86%  |
| LightDM | 2         | 5.71%   |
| SLIMSKI | 1         | 2.86%   |
| SDDM    | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 18        | 51.43%  |
| de_DE | 3         | 8.57%   |
| ru_RU | 2         | 5.71%   |
| ja_JP | 2         | 5.71%   |
| en_AU | 2         | 5.71%   |
| zh_HK | 1         | 2.86%   |
| uk_UA | 1         | 2.86%   |
| pt_BR | 1         | 2.86%   |
| nl_NL | 1         | 2.86%   |
| it_IT | 1         | 2.86%   |
| es_VE | 1         | 2.86%   |
| es_MX | 1         | 2.86%   |
| en_GB | 1         | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 29        | 82.86%  |
| EFI  | 6         | 17.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 29        | 82.86%  |
| Overlay  | 5         | 14.29%  |
| Reiserfs | 1         | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 28        | 80%     |
| GPT     | 6         | 17.14%  |
| Unknown | 1         | 2.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 82.86%  |
| Yes       | 6         | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 57.14%  |
| Yes       | 15        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 7         | 20%     |
| IBM                 | 5         | 14.29%  |
| Hewlett-Packard     | 5         | 14.29%  |
| Lenovo              | 4         | 11.43%  |
| KOHJINSHA           | 2         | 5.71%   |
| Dell                | 2         | 5.71%   |
| Acer                | 2         | 5.71%   |
| Toshiba             | 1         | 2.86%   |
| Samsung Electronics | 1         | 2.86%   |
| Packard Bell        | 1         | 2.86%   |
| MSI                 | 1         | 2.86%   |
| Medion              | 1         | 2.86%   |
| Fujitsu             | 1         | 2.86%   |
| Compaq              | 1         | 2.86%   |
| Apple               | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 5.71%   |
| Toshiba Satellite 1905             | 1         | 2.86%   |
| Samsung SQ1S                       | 1         | 2.86%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2.86%   |
| MSI GE62 7RE                       | 1         | 2.86%   |
| Medion WIM2170                     | 1         | 2.86%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 2.86%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2.86%   |
| Lenovo G550 2958                   | 1         | 2.86%   |
| KOHJINSHA SX series                | 1         | 2.86%   |
| KOHJINSHA SC series                | 1         | 2.86%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 2.86%   |
| IBM ThinkPad T41 2374K50           | 1         | 2.86%   |
| IBM ThinkPad T40 237342G           | 1         | 2.86%   |
| HP Pavilion dv2700                 | 1         | 2.86%   |
| HP Mini 5101                       | 1         | 2.86%   |
| HP Mini 110-3700                   | 1         | 2.86%   |
| HP EliteBook 8770w                 | 1         | 2.86%   |
| HP EliteBook 2570p                 | 1         | 2.86%   |
| Fujitsu FMVS54EB                   | 1         | 2.86%   |
| Dell Latitude E6400                | 1         | 2.86%   |
| Dell Latitude 5480                 | 1         | 2.86%   |
| Compaq Tablet PC TC1000            | 1         | 2.86%   |
| ASUS X71SL                         | 1         | 2.86%   |
| ASUS X51RL                         | 1         | 2.86%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2.86%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2.86%   |
| ASUS A3L                           | 1         | 2.86%   |
| ASUS 900HA                         | 1         | 2.86%   |
| ASUS 900A                          | 1         | 2.86%   |
| Apple MacBook7,1                   | 1         | 2.86%   |
| Acer Aspire 5920G                  | 1         | 2.86%   |
| Acer AOA150                        | 1         | 2.86%   |
| Unknown                            | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 8.57%   |
| Lenovo ThinkPad       | 2         | 5.71%   |
| IBM 260921H           | 2         | 5.71%   |
| HP Mini               | 2         | 5.71%   |
| HP EliteBook          | 2         | 5.71%   |
| Dell Latitude         | 2         | 5.71%   |
| ASUS VivoBook         | 2         | 5.71%   |
| Toshiba Satellite     | 1         | 2.86%   |
| Samsung SQ1S          | 1         | 2.86%   |
| Packard Bell EasyNote | 1         | 2.86%   |
| MSI GE62              | 1         | 2.86%   |
| Medion WIM2170        | 1         | 2.86%   |
| Lenovo G550           | 1         | 2.86%   |
| KOHJINSHA SX          | 1         | 2.86%   |
| KOHJINSHA SC          | 1         | 2.86%   |
| HP Pavilion           | 1         | 2.86%   |
| Fujitsu FMVS54EB      | 1         | 2.86%   |
| Compaq Tablet         | 1         | 2.86%   |
| ASUS X71SL            | 1         | 2.86%   |
| ASUS X51RL            | 1         | 2.86%   |
| ASUS A3L              | 1         | 2.86%   |
| ASUS 900HA            | 1         | 2.86%   |
| ASUS 900A             | 1         | 2.86%   |
| Apple MacBook7        | 1         | 2.86%   |
| Acer Aspire           | 1         | 2.86%   |
| Acer AOA150           | 1         | 2.86%   |
| Unknown               | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 6         | 17.14%  |
| 2008 | 5         | 14.29%  |
| 2007 | 5         | 14.29%  |
| 2003 | 3         | 8.57%   |
| 2013 | 2         | 5.71%   |
| 2012 | 2         | 5.71%   |
| 2010 | 2         | 5.71%   |
| 2005 | 2         | 5.71%   |
| 1999 | 2         | 5.71%   |
| 2020 | 1         | 2.86%   |
| 2019 | 1         | 2.86%   |
| 2017 | 1         | 2.86%   |
| 2016 | 1         | 2.86%   |
| 2011 | 1         | 2.86%   |
| 2004 | 1         | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 35        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 35        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 22.86%  |
| 0.51-1.0   | 8         | 22.86%  |
| 2.01-3.0   | 5         | 14.29%  |
| 1.01-2.0   | 5         | 14.29%  |
| 4.01-8.0   | 2         | 5.71%   |
| 32.01-64.0 | 2         | 5.71%   |
| 8.01-16.0  | 2         | 5.71%   |
| 0.01-0.5   | 2         | 5.71%   |
| 16.01-24.0 | 1         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 16        | 45.71%  |
| 0.51-1.0 | 11        | 31.43%  |
| 1.01-2.0 | 5         | 14.29%  |
| 2.01-3.0 | 3         | 8.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 82.86%  |
| 2      | 5         | 14.29%  |
| 3      | 1         | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 54.29%  |
| Yes       | 16        | 45.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 82.86%  |
| No        | 6         | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 97.14%  |
| No        | 1         | 2.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 62.86%  |
| Yes       | 13        | 37.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 20%     |
| Hong Kong   | 7         | 20%     |
| Germany     | 4         | 11.43%  |
| Russia      | 3         | 8.57%   |
| Japan       | 2         | 5.71%   |
| Australia   | 2         | 5.71%   |
| Ukraine     | 1         | 2.86%   |
| Netherlands | 1         | 2.86%   |
| Mexico      | 1         | 2.86%   |
| Kenya       | 1         | 2.86%   |
| Kazakhstan  | 1         | 2.86%   |
| Italy       | 1         | 2.86%   |
| Hungary     | 1         | 2.86%   |
| Denmark     | 1         | 2.86%   |
| Chile       | 1         | 2.86%   |
| Brazil      | 1         | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 17.14%  |
| Sydney                    | 2         | 5.71%   |
| Moscow                    | 2         | 5.71%   |
| Yuzhno-Sakhalinsk         | 1         | 2.86%   |
| Yokohama                  | 1         | 2.86%   |
| Toms River                | 1         | 2.86%   |
| Sheung Shui               | 1         | 2.86%   |
| Schloss Holte-Stukenbrock | 1         | 2.86%   |
| Santiago                  | 1         | 2.86%   |
| Salto                     | 1         | 2.86%   |
| Rotterdam                 | 1         | 2.86%   |
| Reutlingen                | 1         | 2.86%   |
| Portland                  | 1         | 2.86%   |
| Norden                    | 1         | 2.86%   |
| Neyagawa                  | 1         | 2.86%   |
| Nairobi                   | 1         | 2.86%   |
| Mittegrossefehn           | 1         | 2.86%   |
| Mechanicsburg             | 1         | 2.86%   |
| Karaganda                 | 1         | 2.86%   |
| Jonesboro                 | 1         | 2.86%   |
| Inveruno                  | 1         | 2.86%   |
| Greenville                | 1         | 2.86%   |
| Godley                    | 1         | 2.86%   |
| El Cerrito                | 1         | 2.86%   |
| Dnipro                    | 1         | 2.86%   |
| Copenhagen                | 1         | 2.86%   |
| Celaya                    | 1         | 2.86%   |
| Budapest                  | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 10     | 25%     |
| Seagate             | 6         | 6      | 15%     |
| WDC                 | 4         | 4      | 10%     |
| Toshiba             | 3         | 3      | 7.5%    |
| Samsung Electronics | 3         | 3      | 7.5%    |
| Kingston            | 2         | 2      | 5%      |
| Zheino              | 1         | 1      | 2.5%    |
| Unknown (CF)        | 1         | 1      | 2.5%    |
| Unknown             | 1         | 1      | 2.5%    |
| Transcend           | 1         | 1      | 2.5%    |
| RECADATA            | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| BHT                 | 1         | 1      | 2.5%    |
| ASUS-PHISON         | 1         | 1      | 2.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 5%      |
| Hitachi HTS548040M9AT00 40GB            | 2         | 5%      |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 2.5%    |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.5%    |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 2.5%    |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.5%    |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 2.5%    |
| Unknown SR64G  64GB                     | 1         | 2.5%    |
| Unknown (CF) Card 16GB SSD              | 1         | 2.5%    |
| Transcend SSD 2GB                       | 1         | 2.5%    |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 2.5%    |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 2.5%    |
| Toshiba MK2576GSX 250GB                 | 1         | 2.5%    |
| Seagate ST9160411AS 160GB               | 1         | 2.5%    |
| Seagate ST9160314AS 160GB               | 1         | 2.5%    |
| Seagate ST9160310AS 160GB               | 1         | 2.5%    |
| Seagate ST9160301AS 160GB               | 1         | 2.5%    |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 2.5%    |
| Samsung HS06THB 64GB                    | 1         | 2.5%    |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 2.5%    |
| OCZ AGILITY3 120GB SSD                  | 1         | 2.5%    |
| Kingston SUV500MS120G 120GB SSD         | 1         | 2.5%    |
| Kingston SUV400S37120G 120GB SSD        | 1         | 2.5%    |
| Intel SSDSC2BW180A3H 180GB              | 1         | 2.5%    |
| Hitachi HTS725050A7E630 500GB           | 1         | 2.5%    |
| Hitachi HTS723232A7A364 320GB           | 1         | 2.5%    |
| Hitachi HTS721060G9AT00 64GB            | 1         | 2.5%    |
| Hitachi HTS545025B9A300 250GB           | 1         | 2.5%    |
| Hitachi HTS542525K9SA00 250GB           | 1         | 2.5%    |
| Hitachi HTS541612J9SA00 120GB           | 1         | 2.5%    |
| Hitachi HTC426040G8CE00 40GB            | 1         | 2.5%    |
| Hitachi DK23AA-60 6GB                   | 1         | 2.5%    |
| HGST HTS721010A9E630 1TB                | 1         | 2.5%    |
| HP SSD S750 512GB                       | 1         | 2.5%    |
| Fujitsu MHW2120BH 120GB                 | 1         | 2.5%    |
| BHT WR202I0064G E70245F5 64GB           | 1         | 2.5%    |
| ASUS-PHISON SSD 8GB                     | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 10     | 41.67%  |
| Seagate             | 6         | 6      | 25%     |
| WDC                 | 4         | 4      | 16.67%  |
| Toshiba             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 2         | 2      | 13.33%  |
| Zheino              | 1         | 1      | 6.67%   |
| Unknown (CF)        | 1         | 1      | 6.67%   |
| Transcend           | 1         | 1      | 6.67%   |
| RECADATA            | 1         | 1      | 6.67%   |
| OCZ                 | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hewlett-Packard     | 1         | 1      | 6.67%   |
| BHT                 | 1         | 1      | 6.67%   |
| ASUS-PHISON         | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 24     | 61.54%  |
| SSD  | 14        | 15     | 35.9%   |
| MMC  | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 39     | 97.22%  |
| MMC  | 1         | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 37     | 94.59%  |
| 0.51-1.0   | 2         | 2      | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 31.43%  |
| 1-20       | 11        | 31.43%  |
| 51-100     | 5         | 14.29%  |
| 21-50      | 4         | 11.43%  |
| 251-500    | 2         | 5.71%   |
| 501-1000   | 1         | 2.86%   |
| Unknown    | 1         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 27        | 77.14%  |
| 21-50   | 3         | 8.57%   |
| 101-250 | 2         | 5.71%   |
| 51-100  | 2         | 5.71%   |
| Unknown | 1         | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 9.09%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 9.09%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 9.09%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 9.09%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 9.09%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 9.09%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 9.09%   |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 9.09%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 9.09%   |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 9.09%   |
| Hitachi DK23AA-60 6GB         | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 72.73%  |
| Seagate | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 72.73%  |
| Seagate | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 100%    |

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
| Works    | 23        | 25     | 60.53%  |
| Malfunc  | 11        | 11     | 28.95%  |
| Detected | 4         | 4      | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 78.38%  |
| Silicon Integrated Systems [SiS] | 2         | 5.41%   |
| AMD                              | 2         | 5.41%   |
| VIA Technologies                 | 1         | 2.7%    |
| Silicon Image                    | 1         | 2.7%    |
| Nvidia                           | 1         | 2.7%    |
| JMicron Technology               | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 8.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 6.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 6.67%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 6.67%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 4.44%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 4.44%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 4.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 4.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 4.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.44%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 4.44%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 2.22%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 2.22%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 2.22%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.22%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 2.22%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 2.22%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.22%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.22%   |
| AMD SB600 IDE                                                                  | 1         | 2.22%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 22        | 53.66%  |
| SATA | 16        | 39.02%  |
| RAID | 3         | 7.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 33        | 94.29%  |
| GenuineTMx86 | 1         | 2.86%   |
| AMD          | 1         | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 11.43%  |
| Intel Pentium M processor 1.60GHz              | 2         | 5.71%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 5.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 5.71%   |
| Intel Celeron (Mendocino)                      | 2         | 5.71%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 5.71%   |
| Intel Pentium M processor 1600MHz              | 1         | 2.86%   |
| Intel Pentium M processor 1.86GHz              | 1         | 2.86%   |
| Intel Pentium M processor 1.00GHz              | 1         | 2.86%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.86%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 2.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.86%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 2.86%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.86%   |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 2.86%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 2.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.86%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 2.86%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.86%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 2.86%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.86%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 2.86%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 2.86%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 2.86%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 1         | 2.86%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 2.86%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 8         | 22.86%  |
| Intel Core 2 Duo        | 6         | 17.14%  |
| Intel Pentium M         | 5         | 14.29%  |
| Intel Core i7           | 4         | 11.43%  |
| Intel Celeron           | 4         | 11.43%  |
| Intel Core i5           | 2         | 5.71%   |
| Other                   | 1         | 2.86%   |
| Intel Pentium Dual      | 1         | 2.86%   |
| Intel Pentium 4         | 1         | 2.86%   |
| Intel Core i3           | 1         | 2.86%   |
| Intel Celeron Dual-Core | 1         | 2.86%   |
| AMD E2                  | 1         | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 51.43%  |
| 2      | 15        | 42.86%  |
| 4      | 2         | 5.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 57.14%  |
| 2      | 15        | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 54.29%  |
| 32-bit         | 16        | 45.71%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 20%     |
| 0x6fd      | 4         | 11.43%  |
| 0x1067a    | 4         | 11.43%  |
| 0x6d6      | 3         | 8.57%   |
| 0x66a      | 2         | 5.71%   |
| 0x306a9    | 2         | 5.71%   |
| 0xf24      | 1         | 2.86%   |
| 0x906e9    | 1         | 2.86%   |
| 0x806e9    | 1         | 2.86%   |
| 0x706a1    | 1         | 2.86%   |
| 0x6d8      | 1         | 2.86%   |
| 0x695      | 1         | 2.86%   |
| 0x306c3    | 1         | 2.86%   |
| 0x206a7    | 1         | 2.86%   |
| 0x20655    | 1         | 2.86%   |
| 0x106ca    | 1         | 2.86%   |
| 0x10661    | 1         | 2.86%   |
| 0x07030106 | 1         | 2.86%   |
| Unknown    | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 8         | 22.86%  |
| P6            | 5         | 14.29%  |
| Core          | 5         | 14.29%  |
| Penryn        | 4         | 11.43%  |
| Unknown       | 3         | 8.57%   |
| KabyLake      | 2         | 5.71%   |
| IvyBridge     | 2         | 5.71%   |
| Westmere      | 1         | 2.86%   |
| SandyBridge   | 1         | 2.86%   |
| Puma          | 1         | 2.86%   |
| NetBurst      | 1         | 2.86%   |
| Haswell       | 1         | 2.86%   |
| Goldmont plus | 1         | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 20        | 55.56%  |
| AMD                              | 7         | 19.44%  |
| Nvidia                           | 6         | 16.67%  |
| Neomagic                         | 2         | 5.56%   |
| Silicon Integrated Systems [SiS] | 1         | 2.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 11.9%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 5         | 11.9%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 4.76%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 4.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 4.76%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 4.76%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 2.38%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 2.38%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 2.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.38%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 2.38%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 2.38%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.38%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 2.38%   |
| Intel HD Graphics 630                                                         | 1         | 2.38%   |
| Intel HD Graphics 620                                                         | 1         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 2.38%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2.38%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.38%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 2.38%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 2.38%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 2.38%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 2.38%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 51.43%  |
| 1 x AMD        | 7         | 20%     |
| 1 x Nvidia     | 5         | 14.29%  |
| 1 x Neomagic   | 2         | 5.71%   |
| Other          | 1         | 2.86%   |
| 1 x SiS        | 1         | 2.86%   |
| Intel + Nvidia | 1         | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 30        | 85.71%  |
| Unknown     | 4         | 11.43%  |
| Proprietary | 1         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 19        | 54.29%  |
| Unknown    | 12        | 34.29%  |
| 1.01-2.0   | 3         | 8.57%   |
| 3.01-4.0   | 1         | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 26.09%  |
| LG Display          | 5         | 21.74%  |
| Samsung Electronics | 3         | 13.04%  |
| HannStar            | 2         | 8.7%    |
| LG Philips          | 1         | 4.35%   |
| Lenovo              | 1         | 4.35%   |
| HJW                 | 1         | 4.35%   |
| CPT                 | 1         | 4.35%   |
| Chimei Innolux      | 1         | 4.35%   |
| BOE                 | 1         | 4.35%   |
| Apple               | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 1         | 4.35%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 4.35%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 4.35%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 4.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 4.35%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 4.35%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 4.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 4.35%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 4.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 4.35%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 4.35%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 4.35%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 4.35%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 31.82%  |
| 1280x800 (WXGA)  | 5         | 22.73%  |
| 1920x1080 (FHD)  | 4         | 18.18%  |
| 1024x600         | 4         | 18.18%  |
| 1440x900 (WXGA+) | 2         | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 26.09%  |
| 14     | 4         | 17.39%  |
| 13     | 4         | 17.39%  |
| 10     | 3         | 13.04%  |
| 17     | 2         | 8.7%    |
| 8      | 2         | 8.7%    |
| 32     | 1         | 4.35%   |
| 12     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 47.83%  |
| 201-300     | 7         | 30.43%  |
| 351-400     | 2         | 8.7%    |
| 101-200     | 2         | 8.7%    |
| 701-800     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 63.64%  |
| 16/10 | 7         | 31.82%  |
| 3/2   | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 26.09%  |
| 101-110        | 6         | 26.09%  |
| 41-50          | 3         | 13.04%  |
| 71-80          | 2         | 8.7%    |
| 1-40           | 2         | 8.7%    |
| 61-70          | 1         | 4.35%   |
| 351-500        | 1         | 4.35%   |
| 131-140        | 1         | 4.35%   |
| 121-130        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 9         | 39.13%  |
| 101-120 | 9         | 39.13%  |
| 51-100  | 5         | 21.74%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 85.71%  |
| 0     | 3         | 8.57%   |
| 2     | 2         | 5.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 16        | 28.57%  |
| Qualcomm Atheros                 | 15        | 26.79%  |
| Realtek Semiconductor            | 7         | 12.5%   |
| Broadcom                         | 7         | 12.5%   |
| Silicon Integrated Systems [SiS] | 2         | 3.57%   |
| Marvell Technology Group         | 2         | 3.57%   |
| Texas Instruments                | 1         | 1.79%   |
| Ralink                           | 1         | 1.79%   |
| Qualcomm Atheros Communications  | 1         | 1.79%   |
| Nvidia                           | 1         | 1.79%   |
| MediaTek                         | 1         | 1.79%   |
| Hewlett-Packard                  | 1         | 1.79%   |
| ASIX Electronics                 | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 9.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 4.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 4.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 2.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.78%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.78%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 2.78%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 2.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 2.78%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.39%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 1.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.39%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.39%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.39%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.39%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.39%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.39%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.39%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.39%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.39%   |
| Intel Wireless 7260                                                           | 1         | 1.39%   |
| Intel WiFi Link 5100                                                          | 1         | 1.39%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.39%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.39%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.39%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.39%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.39%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.39%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.39%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.39%   |
| Intel 82551QM Ethernet Controller                                             | 1         | 1.39%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.39%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 1.39%   |
| ASIX AX88772A Fast Ethernet                                                   | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 37.84%  |
| Qualcomm Atheros                | 13        | 35.14%  |
| Broadcom                        | 5         | 13.51%  |
| Texas Instruments               | 1         | 2.7%    |
| Realtek Semiconductor           | 1         | 2.7%    |
| Ralink                          | 1         | 2.7%    |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| MediaTek                        | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 18.42%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 7.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 5.26%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 5.26%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 5.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 5.26%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.63%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.63%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.63%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.63%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.63%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.63%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.63%   |
| Intel Wireless 7260                                                           | 1         | 2.63%   |
| Intel WiFi Link 5100                                                          | 1         | 2.63%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.63%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 2.63%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.63%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.63%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10        | 34.48%  |
| Realtek Semiconductor            | 6         | 20.69%  |
| Broadcom                         | 4         | 13.79%  |
| Qualcomm Atheros                 | 3         | 10.34%  |
| Silicon Integrated Systems [SiS] | 2         | 6.9%    |
| Marvell Technology Group         | 2         | 6.9%    |
| Nvidia                           | 1         | 3.45%   |
| ASIX Electronics                 | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 10.34%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 6.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 6.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.9%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 6.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 6.9%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.45%   |
| Nvidia MCP89 Ethernet                                             | 1         | 3.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 3.45%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.45%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 3.45%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.45%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 3.45%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 3.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.45%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 50%     |
| Ethernet | 29        | 42.65%  |
| Modem    | 5         | 7.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 85.29%  |
| Ethernet | 5         | 14.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 77.14%  |
| 1     | 8         | 22.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 82.86%  |
| Yes  | 6         | 17.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 5         | 38.46%  |
| Intel                   | 2         | 15.38%  |
| IMC Networks            | 2         | 15.38%  |
| Ralink Technology       | 1         | 7.69%   |
| Cambridge Silicon Radio | 1         | 7.69%   |
| ASUSTek Computer        | 1         | 7.69%   |
| Apple                   | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Device                       | 2         | 15.38%  |
| Broadcom HP Portable SoftSailing                    | 2         | 15.38%  |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 7.69%   |
| Intel Bluetooth wireless interface                  | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 7.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 7.69%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 7.69%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 7.69%   |
| Apple Bluetooth Host Controller                     | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 27        | 72.97%  |
| AMD                              | 3         | 8.11%   |
| Silicon Integrated Systems [SiS] | 2         | 5.41%   |
| Nvidia                           | 2         | 5.41%   |
| ESS Technology                   | 2         | 5.41%   |
| VIA Technologies                 | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 15.38%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 7.69%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 7.69%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 5.13%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5.13%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 5.13%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 2.56%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.56%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.56%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.56%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.56%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 2.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 46.15%  |
| SK hynix            | 6         | 15.38%  |
| Unknown             | 4         | 10.26%  |
| Micron Technology   | 3         | 7.69%   |
| Samsung Electronics | 2         | 5.13%   |
| Kingston            | 2         | 5.13%   |
| Crucial             | 2         | 5.13%   |
| Unknown (8A02)      | 1         | 2.56%   |
| Avant               | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 4         | 9.76%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 7.32%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 4.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 4.88%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 4.88%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2.44%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2.44%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.44%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.44%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.44%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.44%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.44%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 2.44%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.44%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.44%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.44%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s       | 1         | 2.44%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 1         | 2.44%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.44%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.44%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.44%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 8         | 24.24%  |
| DDR3  | 8         | 24.24%  |
| DDR2  | 6         | 18.18%  |
| DDR   | 5         | 15.15%  |
| DRAM  | 3         | 9.09%   |
| DDR4  | 3         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 30        | 90.91%  |
| DIMM   | 3         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 11        | 28.21%  |
| 1024  | 10        | 25.64%  |
| 8192  | 4         | 10.26%  |
| 4096  | 4         | 10.26%  |
| 512   | 3         | 7.69%   |
| 256   | 3         | 7.69%   |
| 64    | 2         | 5.13%   |
| 16384 | 1         | 2.56%   |
| 232   | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 44.12%  |
| 1600    | 5         | 14.71%  |
| 1067    | 3         | 8.82%   |
| 667     | 2         | 5.88%   |
| 533     | 2         | 5.88%   |
| 3266    | 1         | 2.94%   |
| 2667    | 1         | 2.94%   |
| 2400    | 1         | 2.94%   |
| 1333    | 1         | 2.94%   |
| 975     | 1         | 2.94%   |
| 800     | 1         | 2.94%   |
| 266     | 1         | 2.94%   |

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
| Chicony Electronics                    | 5         | 21.74%  |
| Microdia                               | 3         | 13.04%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 13.04%  |
| Pixart Imaging                         | 2         | 8.7%    |
| IMC Networks                           | 2         | 8.7%    |
| Acer                                   | 2         | 8.7%    |
| Suyin                                  | 1         | 4.35%   |
| Sunplus Innovation Technology          | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Lenovo                                 | 1         | 4.35%   |
| Importek                               | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 8.7%    |
| Microdia Sonix USB 2.0 Camera                           | 2         | 8.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 8.7%    |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 4.35%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 4.35%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 4.35%   |
| Microdia Integrated Webcam                              | 1         | 4.35%   |
| Lenovo Integrated Webcam                                | 1         | 4.35%   |
| Importek FJ Camera                                      | 1         | 4.35%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 4.35%   |
| Chicony Integrated HP HD Webcam                         | 1         | 4.35%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 4.35%   |
| Chicony CNF8243 Webcam                                  | 1         | 4.35%   |
| Chicony CNF7050                                         | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 4.35%   |
| Apple Built-in iSight                                   | 1         | 4.35%   |
| Acer Lenovo EasyCamera                                  | 1         | 4.35%   |
| Acer BisonCam, NB Pro                                   | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 50%     |
| Validity Sensors | 1         | 25%     |
| Upek             | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 25%     |
| AuthenTec AES1600                                      | 1         | 25%     |

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
| 0     | 26        | 74.29%  |
| 1     | 8         | 22.86%  |
| 2     | 1         | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 5         | 50%     |
| Fingerprint reader | 4         | 40%     |
| Chipcard           | 1         | 10%     |

