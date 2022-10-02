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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
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
| antiX 21       | 19        | 51.35%  |
| antiX 19.2     | 6         | 16.22%  |
| antiX 19.3     | 3         | 8.11%   |
| antiX 21-runit | 2         | 5.41%   |
| antiX 19.4     | 2         | 5.41%   |
| antiX 19.1     | 2         | 5.41%   |
| antiX 17.4.1   | 1         | 2.7%    |
| antiX 17.2.1   | 1         | 2.7%    |
| antiX 17       | 1         | 2.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 13        | 35.14%  |
| 5.10.57-antix.1-amd64-smp    | 3         | 8.11%   |
| 4.9.0-279-antix.1-amd64-smp  | 3         | 8.11%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 5.41%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 5.41%   |
| 4.9.212-antix.1-486-smp      | 2         | 5.41%   |
| 4.9.200-antix.1-486-smp      | 2         | 5.41%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 2.7%    |
| 5.10.88-antix.1-amd64-smp    | 1         | 2.7%    |
| 5.10.27-antix.1-amd64-smp    | 1         | 2.7%    |
| 4.9.160-antix.2-486-smp      | 1         | 2.7%    |
| 4.9.160-antix.1-amd64-smp    | 1         | 2.7%    |
| 4.9.0-264-antix.1-486-smp    | 1         | 2.7%    |
| 4.19.202-antix.1-686-smp-pae | 1         | 2.7%    |
| 4.19.100-antix.1-686-smp-pae | 1         | 2.7%    |
| 4.19.0-222-antix.1-amd64-smp | 1         | 2.7%    |
| 4.10.5-antix.1-486-smp       | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 17        | 45.95%  |
| 4.9.212  | 4         | 10.81%  |
| 5.10.57  | 3         | 8.11%   |
| 4.9.235  | 2         | 5.41%   |
| 4.9.200  | 2         | 5.41%   |
| 4.9.160  | 2         | 5.41%   |
| 5.14.0   | 1         | 2.7%    |
| 5.10.88  | 1         | 2.7%    |
| 5.10.27  | 1         | 2.7%    |
| 4.19.202 | 1         | 2.7%    |
| 4.19.100 | 1         | 2.7%    |
| 4.19.0   | 1         | 2.7%    |
| 4.10.5   | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 27        | 72.97%  |
| 5.10    | 5         | 13.51%  |
| 4.19    | 3         | 8.11%   |
| 5.14    | 1         | 2.7%    |
| 4.10    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 21        | 56.76%  |
| x86_64 | 15        | 40.54%  |
| i586   | 1         | 2.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 62.16%  |
| icewm   | 12        | 32.43%  |
| XFCE    | 1         | 2.7%    |
| GNOME   | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 37        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 48.65%  |
| SLiM    | 15        | 40.54%  |
| LightDM | 2         | 5.41%   |
| SLIMSKI | 1         | 2.7%    |
| SDDM    | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 51.35%  |
| ru_RU | 3         | 8.11%   |
| de_DE | 3         | 8.11%   |
| ja_JP | 2         | 5.41%   |
| en_AU | 2         | 5.41%   |
| zh_HK | 1         | 2.7%    |
| uk_UA | 1         | 2.7%    |
| pt_BR | 1         | 2.7%    |
| nl_NL | 1         | 2.7%    |
| it_IT | 1         | 2.7%    |
| es_VE | 1         | 2.7%    |
| es_MX | 1         | 2.7%    |
| en_GB | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 83.78%  |
| EFI  | 6         | 16.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 30        | 81.08%  |
| Overlay  | 6         | 16.22%  |
| Reiserfs | 1         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 30        | 81.08%  |
| GPT     | 6         | 16.22%  |
| Unknown | 1         | 2.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 83.78%  |
| Yes       | 6         | 16.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 59.46%  |
| Yes       | 15        | 40.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 8         | 21.62%  |
| IBM                 | 5         | 13.51%  |
| Hewlett-Packard     | 5         | 13.51%  |
| Lenovo              | 4         | 10.81%  |
| KOHJINSHA           | 2         | 5.41%   |
| Fujitsu             | 2         | 5.41%   |
| Dell                | 2         | 5.41%   |
| Acer                | 2         | 5.41%   |
| Toshiba             | 1         | 2.7%    |
| Samsung Electronics | 1         | 2.7%    |
| Packard Bell        | 1         | 2.7%    |
| MSI                 | 1         | 2.7%    |
| Medion              | 1         | 2.7%    |
| Compaq              | 1         | 2.7%    |
| Apple               | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 5.41%   |
| Toshiba Satellite 1905             | 1         | 2.7%    |
| Samsung SQ1S                       | 1         | 2.7%    |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2.7%    |
| MSI GE62 7RE                       | 1         | 2.7%    |
| Medion WIM2170                     | 1         | 2.7%    |
| Lenovo ThinkPad X201 3249CTO       | 1         | 2.7%    |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2.7%    |
| Lenovo G550 2958                   | 1         | 2.7%    |
| KOHJINSHA SX series                | 1         | 2.7%    |
| KOHJINSHA SC series                | 1         | 2.7%    |
| IBM ThinkPad T43 2668WEJ           | 1         | 2.7%    |
| IBM ThinkPad T41 2374K50           | 1         | 2.7%    |
| IBM ThinkPad T40 237342G           | 1         | 2.7%    |
| HP Pavilion dv2700                 | 1         | 2.7%    |
| HP Mini 5101                       | 1         | 2.7%    |
| HP Mini 110-3700                   | 1         | 2.7%    |
| HP EliteBook 8770w                 | 1         | 2.7%    |
| HP EliteBook 2570p                 | 1         | 2.7%    |
| Fujitsu FMVS54EB                   | 1         | 2.7%    |
| Fujitsu FMVNU6G1C                  | 1         | 2.7%    |
| Dell Latitude E6400                | 1         | 2.7%    |
| Dell Latitude 5480                 | 1         | 2.7%    |
| Compaq Tablet PC TC1000            | 1         | 2.7%    |
| ASUS X71SL                         | 1         | 2.7%    |
| ASUS X51RL                         | 1         | 2.7%    |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2.7%    |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2.7%    |
| ASUS A3L                           | 1         | 2.7%    |
| ASUS 900HA                         | 1         | 2.7%    |
| ASUS 900A                          | 1         | 2.7%    |
| ASUS 1011CX                        | 1         | 2.7%    |
| Apple MacBook7,1                   | 1         | 2.7%    |
| Acer Aspire 5920G                  | 1         | 2.7%    |
| Acer AOA150                        | 1         | 2.7%    |
| Unknown                            | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 8.11%   |
| Lenovo ThinkPad       | 2         | 5.41%   |
| IBM 260921H           | 2         | 5.41%   |
| HP Mini               | 2         | 5.41%   |
| HP EliteBook          | 2         | 5.41%   |
| Dell Latitude         | 2         | 5.41%   |
| ASUS VivoBook         | 2         | 5.41%   |
| Toshiba Satellite     | 1         | 2.7%    |
| Samsung SQ1S          | 1         | 2.7%    |
| Packard Bell EasyNote | 1         | 2.7%    |
| MSI GE62              | 1         | 2.7%    |
| Medion WIM2170        | 1         | 2.7%    |
| Lenovo G550           | 1         | 2.7%    |
| KOHJINSHA SX          | 1         | 2.7%    |
| KOHJINSHA SC          | 1         | 2.7%    |
| HP Pavilion           | 1         | 2.7%    |
| Fujitsu FMVS54EB      | 1         | 2.7%    |
| Fujitsu FMVNU6G1C     | 1         | 2.7%    |
| Compaq Tablet         | 1         | 2.7%    |
| ASUS X71SL            | 1         | 2.7%    |
| ASUS X51RL            | 1         | 2.7%    |
| ASUS A3L              | 1         | 2.7%    |
| ASUS 900HA            | 1         | 2.7%    |
| ASUS 900A             | 1         | 2.7%    |
| ASUS 1011CX           | 1         | 2.7%    |
| Apple MacBook7        | 1         | 2.7%    |
| Acer Aspire           | 1         | 2.7%    |
| Acer AOA150           | 1         | 2.7%    |
| Unknown               | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 6         | 16.22%  |
| 2007 | 6         | 16.22%  |
| 2008 | 5         | 13.51%  |
| 2012 | 3         | 8.11%   |
| 2003 | 3         | 8.11%   |
| 2013 | 2         | 5.41%   |
| 2010 | 2         | 5.41%   |
| 2005 | 2         | 5.41%   |
| 1999 | 2         | 5.41%   |
| 2020 | 1         | 2.7%    |
| 2019 | 1         | 2.7%    |
| 2017 | 1         | 2.7%    |
| 2016 | 1         | 2.7%    |
| 2011 | 1         | 2.7%    |
| 2004 | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 37        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 9         | 24.32%  |
| 3.01-4.0   | 8         | 21.62%  |
| 2.01-3.0   | 6         | 16.22%  |
| 1.01-2.0   | 5         | 13.51%  |
| 4.01-8.0   | 2         | 5.41%   |
| 32.01-64.0 | 2         | 5.41%   |
| 8.01-16.0  | 2         | 5.41%   |
| 0.01-0.5   | 2         | 5.41%   |
| 16.01-24.0 | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 17        | 45.95%  |
| 0.51-1.0 | 12        | 32.43%  |
| 1.01-2.0 | 5         | 13.51%  |
| 2.01-3.0 | 3         | 8.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 81.08%  |
| 2      | 5         | 13.51%  |
| 3      | 1         | 2.7%    |
| 0      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 56.76%  |
| Yes       | 16        | 43.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 83.78%  |
| No        | 6         | 16.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 97.3%   |
| No        | 1         | 2.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 64.86%  |
| Yes       | 13        | 35.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Hong Kong   | 8         | 21.62%  |
| USA         | 7         | 18.92%  |
| Russia      | 4         | 10.81%  |
| Germany     | 4         | 10.81%  |
| Japan       | 2         | 5.41%   |
| Australia   | 2         | 5.41%   |
| Ukraine     | 1         | 2.7%    |
| Netherlands | 1         | 2.7%    |
| Mexico      | 1         | 2.7%    |
| Kenya       | 1         | 2.7%    |
| Kazakhstan  | 1         | 2.7%    |
| Italy       | 1         | 2.7%    |
| Hungary     | 1         | 2.7%    |
| Denmark     | 1         | 2.7%    |
| Chile       | 1         | 2.7%    |
| Brazil      | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 16.22%  |
| Sydney                    | 2         | 5.41%   |
| Moscow                    | 2         | 5.41%   |
| Yuzhno-Sakhalinsk         | 1         | 2.7%    |
| Yokohama                  | 1         | 2.7%    |
| Toms River                | 1         | 2.7%    |
| Sheung Shui               | 1         | 2.7%    |
| Schloss Holte-Stukenbrock | 1         | 2.7%    |
| Santiago                  | 1         | 2.7%    |
| Salto                     | 1         | 2.7%    |
| Rotterdam                 | 1         | 2.7%    |
| Reutlingen                | 1         | 2.7%    |
| Portland                  | 1         | 2.7%    |
| Norden                    | 1         | 2.7%    |
| Neyagawa                  | 1         | 2.7%    |
| Nairobi                   | 1         | 2.7%    |
| Mittegrossefehn           | 1         | 2.7%    |
| Mechanicsburg             | 1         | 2.7%    |
| Karaganda                 | 1         | 2.7%    |
| Jonesboro                 | 1         | 2.7%    |
| Inveruno                  | 1         | 2.7%    |
| Greenville                | 1         | 2.7%    |
| Godley                    | 1         | 2.7%    |
| Elektrostal               | 1         | 2.7%    |
| El Cerrito                | 1         | 2.7%    |
| Dnipro                    | 1         | 2.7%    |
| Copenhagen                | 1         | 2.7%    |
| Central                   | 1         | 2.7%    |
| Celaya                    | 1         | 2.7%    |
| Budapest                  | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 10     | 24.39%  |
| Seagate             | 7         | 7      | 17.07%  |
| WDC                 | 4         | 4      | 9.76%   |
| Toshiba             | 3         | 3      | 7.32%   |
| Samsung Electronics | 3         | 3      | 7.32%   |
| Kingston            | 2         | 2      | 4.88%   |
| Zheino              | 1         | 1      | 2.44%   |
| Unknown (CF)        | 1         | 1      | 2.44%   |
| Unknown             | 1         | 1      | 2.44%   |
| Transcend           | 1         | 1      | 2.44%   |
| RECADATA            | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| BHT                 | 1         | 1      | 2.44%   |
| ASUS-PHISON         | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 4.88%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 4.88%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 2.44%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.44%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 2.44%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.44%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 2.44%   |
| Unknown SR64G  64GB                     | 1         | 2.44%   |
| Unknown (CF) Card 16GB SSD              | 1         | 2.44%   |
| Transcend SSD 2GB                       | 1         | 2.44%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 2.44%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 2.44%   |
| Toshiba MK2576GSX 250GB                 | 1         | 2.44%   |
| Seagate ST9320325AS 320GB               | 1         | 2.44%   |
| Seagate ST9160411AS 160GB               | 1         | 2.44%   |
| Seagate ST9160314AS 160GB               | 1         | 2.44%   |
| Seagate ST9160310AS 160GB               | 1         | 2.44%   |
| Seagate ST9160301AS 160GB               | 1         | 2.44%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 2.44%   |
| Samsung HS06THB 64GB                    | 1         | 2.44%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 2.44%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 2.44%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 2.44%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 2.44%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 2.44%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 2.44%   |
| Hitachi HTS723232A7A364 320GB           | 1         | 2.44%   |
| Hitachi HTS721060G9AT00 64GB            | 1         | 2.44%   |
| Hitachi HTS545025B9A300 250GB           | 1         | 2.44%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 2.44%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 2.44%   |
| Hitachi HTC426040G8CE00 40GB            | 1         | 2.44%   |
| Hitachi DK23AA-60 6GB                   | 1         | 2.44%   |
| HGST HTS721010A9E630 1TB                | 1         | 2.44%   |
| HP SSD S750 512GB                       | 1         | 2.44%   |
| Fujitsu MHW2120BH 120GB                 | 1         | 2.44%   |
| BHT WR202I0064G E70245F5 64GB           | 1         | 2.44%   |
| ASUS-PHISON SSD 8GB                     | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 10     | 40%     |
| Seagate             | 7         | 7      | 28%     |
| WDC                 | 4         | 4      | 16%     |
| Toshiba             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

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
| HDD  | 25        | 25     | 62.5%   |
| SSD  | 14        | 15     | 35%     |
| MMC  | 1         | 1      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 40     | 97.3%   |
| MMC  | 1         | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 38     | 94.74%  |
| 0.51-1.0   | 2         | 2      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 12        | 32.43%  |
| 101-250    | 11        | 29.73%  |
| 51-100     | 5         | 13.51%  |
| 21-50      | 4         | 10.81%  |
| 251-500    | 3         | 8.11%   |
| 501-1000   | 1         | 2.7%    |
| Unknown    | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 28        | 75.68%  |
| 21-50   | 4         | 10.81%  |
| 101-250 | 2         | 5.41%   |
| 51-100  | 2         | 5.41%   |
| Unknown | 1         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB     | 1         | 1      | 8.33%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 8.33%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 8.33%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 8.33%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 8.33%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 8.33%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 8.33%   |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 8.33%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 8.33%   |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 8.33%   |
| Hitachi DK23AA-60 6GB         | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 66.67%  |
| Seagate | 3         | 3      | 25%     |
| WDC     | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 66.67%  |
| Seagate | 3         | 3      | 25%     |
| WDC     | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 100%    |

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
| Works    | 23        | 25     | 58.97%  |
| Malfunc  | 12        | 12     | 30.77%  |
| Detected | 4         | 4      | 10.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 79.49%  |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| AMD                              | 2         | 5.13%   |
| VIA Technologies                 | 1         | 2.56%   |
| Silicon Image                    | 1         | 2.56%   |
| Nvidia                           | 1         | 2.56%   |
| JMicron Technology               | 1         | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 8.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 6.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 6.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 6.38%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 4.26%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 4.26%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 4.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 4.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.26%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 4.26%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 2.13%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 2.13%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 2.13%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.13%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 2.13%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.13%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.13%   |
| AMD SB600 IDE                                                                  | 1         | 2.13%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 23        | 53.49%  |
| SATA | 17        | 39.53%  |
| RAID | 3         | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 35        | 94.59%  |
| GenuineTMx86 | 1         | 2.7%    |
| AMD          | 1         | 2.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 10.81%  |
| Intel Pentium M processor 1.60GHz              | 2         | 5.41%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 5.41%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 5.41%   |
| Intel Celeron (Mendocino)                      | 2         | 5.41%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 5.41%   |
| Intel Pentium M processor 1600MHz              | 1         | 2.7%    |
| Intel Pentium M processor 1.86GHz              | 1         | 2.7%    |
| Intel Pentium M processor 1.00GHz              | 1         | 2.7%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.7%    |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 2.7%    |
| Intel Genuine processor 800MHz                 | 1         | 2.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 2.7%    |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.7%    |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 2.7%    |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 2.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.7%    |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 2.7%    |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.7%    |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 2.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.7%    |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 2.7%    |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 2.7%    |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 2.7%    |
| Intel Atom CPU N280 @ 1.66GHz                  | 1         | 2.7%    |
| Intel Atom CPU N2600 @ 1.60GHz                 | 1         | 2.7%    |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 2.7%    |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 9         | 24.32%  |
| Intel Core 2 Duo        | 6         | 16.22%  |
| Intel Pentium M         | 5         | 13.51%  |
| Intel Core i7           | 4         | 10.81%  |
| Intel Celeron           | 4         | 10.81%  |
| Intel Core i5           | 2         | 5.41%   |
| Other                   | 1         | 2.7%    |
| Intel Pentium Dual      | 1         | 2.7%    |
| Intel Pentium 4         | 1         | 2.7%    |
| Intel Genuine           | 1         | 2.7%    |
| Intel Core i3           | 1         | 2.7%    |
| Intel Celeron Dual-Core | 1         | 2.7%    |
| AMD E2                  | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 51.35%  |
| 2      | 16        | 43.24%  |
| 4      | 2         | 5.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 56.76%  |
| 2      | 16        | 43.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 51.35%  |
| 32-bit         | 18        | 48.65%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 18.92%  |
| 0x6fd      | 4         | 10.81%  |
| 0x1067a    | 4         | 10.81%  |
| 0x6d6      | 3         | 8.11%   |
| 0x6d8      | 2         | 5.41%   |
| 0x66a      | 2         | 5.41%   |
| 0x306a9    | 2         | 5.41%   |
| 0xf24      | 1         | 2.7%    |
| 0x906e9    | 1         | 2.7%    |
| 0x806e9    | 1         | 2.7%    |
| 0x706a1    | 1         | 2.7%    |
| 0x695      | 1         | 2.7%    |
| 0x306c3    | 1         | 2.7%    |
| 0x30661    | 1         | 2.7%    |
| 0x206a7    | 1         | 2.7%    |
| 0x20655    | 1         | 2.7%    |
| 0x106ca    | 1         | 2.7%    |
| 0x10661    | 1         | 2.7%    |
| 0x07030106 | 1         | 2.7%    |
| Unknown    | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 9         | 24.32%  |
| P6            | 6         | 16.22%  |
| Core          | 5         | 13.51%  |
| Penryn        | 4         | 10.81%  |
| Unknown       | 3         | 8.11%   |
| KabyLake      | 2         | 5.41%   |
| IvyBridge     | 2         | 5.41%   |
| Westmere      | 1         | 2.7%    |
| SandyBridge   | 1         | 2.7%    |
| Puma          | 1         | 2.7%    |
| NetBurst      | 1         | 2.7%    |
| Haswell       | 1         | 2.7%    |
| Goldmont plus | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 57.89%  |
| AMD                              | 7         | 18.42%  |
| Nvidia                           | 6         | 15.79%  |
| Neomagic                         | 2         | 5.26%   |
| Silicon Integrated Systems [SiS] | 1         | 2.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 6         | 13.33%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 11.11%  |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 4.44%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 4.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 4.44%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 4.44%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 2.22%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 2.22%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.22%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 2.22%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 2.22%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.22%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2.22%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 2.22%   |
| Intel HD Graphics 630                                                         | 1         | 2.22%   |
| Intel HD Graphics 620                                                         | 1         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 2.22%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2.22%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.22%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 2.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.22%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 2.22%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 2.22%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 2.22%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 2.22%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 54.05%  |
| 1 x AMD        | 7         | 18.92%  |
| 1 x Nvidia     | 5         | 13.51%  |
| 1 x Neomagic   | 2         | 5.41%   |
| Other          | 1         | 2.7%    |
| 1 x SiS        | 1         | 2.7%    |
| Intel + Nvidia | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 86.49%  |
| Unknown     | 4         | 10.81%  |
| Proprietary | 1         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 20        | 54.05%  |
| Unknown    | 13        | 35.14%  |
| 1.01-2.0   | 3         | 8.11%   |
| 3.01-4.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 25%     |
| LG Display          | 5         | 20.83%  |
| Samsung Electronics | 3         | 12.5%   |
| HannStar            | 3         | 12.5%   |
| LG Philips          | 1         | 4.17%   |
| Lenovo              | 1         | 4.17%   |
| HJW                 | 1         | 4.17%   |
| CPT                 | 1         | 4.17%   |
| Chimei Innolux      | 1         | 4.17%   |
| BOE                 | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 4.17%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 4.17%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 4.17%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 4.17%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 4.17%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 4.17%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 4.17%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 4.17%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch            | 1         | 4.17%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 4.17%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 380x210mm 17.1-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 4.17%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 30.43%  |
| 1280x800 (WXGA)  | 5         | 21.74%  |
| 1024x600         | 5         | 21.74%  |
| 1920x1080 (FHD)  | 4         | 17.39%  |
| 1440x900 (WXGA+) | 2         | 8.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 25%     |
| 14     | 4         | 16.67%  |
| 13     | 4         | 16.67%  |
| 10     | 4         | 16.67%  |
| 17     | 2         | 8.33%   |
| 8      | 2         | 8.33%   |
| 32     | 1         | 4.17%   |
| 12     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 45.83%  |
| 201-300     | 8         | 33.33%  |
| 351-400     | 2         | 8.33%   |
| 101-200     | 2         | 8.33%   |
| 701-800     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 65.22%  |
| 16/10 | 7         | 30.43%  |
| 3/2   | 1         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 25%     |
| 101-110        | 6         | 25%     |
| 41-50          | 4         | 16.67%  |
| 71-80          | 2         | 8.33%   |
| 1-40           | 2         | 8.33%   |
| 61-70          | 1         | 4.17%   |
| 351-500        | 1         | 4.17%   |
| 131-140        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 41.67%  |
| 121-160 | 9         | 37.5%   |
| 51-100  | 5         | 20.83%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 86.49%  |
| 0     | 3         | 8.11%   |
| 2     | 2         | 5.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 16        | 26.67%  |
| Intel                            | 16        | 26.67%  |
| Realtek Semiconductor            | 8         | 13.33%  |
| Broadcom                         | 8         | 13.33%  |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| Marvell Technology Group         | 2         | 3.33%   |
| Texas Instruments                | 1         | 1.67%   |
| Ralink                           | 1         | 1.67%   |
| Qualcomm Atheros Communications  | 1         | 1.67%   |
| Nvidia                           | 1         | 1.67%   |
| MediaTek                         | 1         | 1.67%   |
| Hewlett-Packard                  | 1         | 1.67%   |
| Attansic Technology              | 1         | 1.67%   |
| ASIX Electronics                 | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 9.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 3.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 3.95%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 3.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.63%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.63%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 2.63%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 2.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 2.63%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.32%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.32%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 1.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.32%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.32%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.32%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.32%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.32%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.32%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.32%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.32%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.32%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.32%   |
| Intel Wireless 7260                                                           | 1         | 1.32%   |
| Intel WiFi Link 5100                                                          | 1         | 1.32%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.32%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.32%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.32%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 14        | 35.9%   |
| Intel                           | 14        | 35.9%   |
| Broadcom                        | 6         | 15.38%  |
| Texas Instruments               | 1         | 2.56%   |
| Realtek Semiconductor           | 1         | 2.56%   |
| Ralink                          | 1         | 2.56%   |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| MediaTek                        | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 17.5%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 7.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 5%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 5%      |
| Intel Centrino Ultimate-N 6300                                                | 2         | 5%      |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 5%      |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.5%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.5%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.5%    |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.5%    |
| Intel Wireless 7260                                                           | 1         | 2.5%    |
| Intel WiFi Link 5100                                                          | 1         | 2.5%    |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.5%    |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 2.5%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.5%    |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.5%    |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10        | 32.26%  |
| Realtek Semiconductor            | 7         | 22.58%  |
| Broadcom                         | 4         | 12.9%   |
| Qualcomm Atheros                 | 3         | 9.68%   |
| Silicon Integrated Systems [SiS] | 2         | 6.45%   |
| Marvell Technology Group         | 2         | 6.45%   |
| Nvidia                           | 1         | 3.23%   |
| Attansic Technology              | 1         | 3.23%   |
| ASIX Electronics                 | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 9.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 6.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.45%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 6.45%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 6.45%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1         | 3.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.23%   |
| Nvidia MCP89 Ethernet                                             | 1         | 3.23%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.23%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 3.23%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 3.23%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.23%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 3.23%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 50%     |
| Ethernet | 31        | 43.06%  |
| Modem    | 5         | 6.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 86.11%  |
| Ethernet | 5         | 13.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 78.38%  |
| 1     | 8         | 21.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 83.78%  |
| Yes  | 6         | 16.22%  |

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
| Intel                            | 29        | 74.36%  |
| AMD                              | 3         | 7.69%   |
| Silicon Integrated Systems [SiS] | 2         | 5.13%   |
| Nvidia                           | 2         | 5.13%   |
| ESS Technology                   | 2         | 5.13%   |
| VIA Technologies                 | 1         | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 19.51%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 7.32%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 4.88%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 4.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.88%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 4.88%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 2.44%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.44%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.44%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.44%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.44%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 2.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 18        | 45%     |
| SK hynix            | 6         | 15%     |
| Unknown             | 5         | 12.5%   |
| Micron Technology   | 3         | 7.5%    |
| Samsung Electronics | 2         | 5%      |
| Kingston            | 2         | 5%      |
| Crucial             | 2         | 5%      |
| Unknown (8A02)      | 1         | 2.5%    |
| Avant               | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 11.9%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 7.14%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 4.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 4.76%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 4.76%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2.38%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.38%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2.38%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.38%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 2.38%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.38%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.38%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.38%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.38%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.38%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 2.38%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.38%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.38%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s      | 1         | 2.38%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s       | 1         | 2.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 2.38%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.38%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.38%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.38%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.38%   |
| Kingston RAM 9905428-095.D00LF 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.38%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.38%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.38%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 8         | 23.53%  |
| DDR3  | 8         | 23.53%  |
| DDR2  | 7         | 20.59%  |
| DDR   | 5         | 14.71%  |
| DRAM  | 3         | 8.82%   |
| DDR4  | 3         | 8.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 31        | 91.18%  |
| DIMM   | 3         | 8.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 11        | 27.5%   |
| 1024  | 11        | 27.5%   |
| 8192  | 4         | 10%     |
| 4096  | 4         | 10%     |
| 512   | 3         | 7.5%    |
| 256   | 3         | 7.5%    |
| 64    | 2         | 5%      |
| 16384 | 1         | 2.5%    |
| 232   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 42.86%  |
| 1600    | 5         | 14.29%  |
| 1067    | 3         | 8.57%   |
| 667     | 2         | 5.71%   |
| 533     | 2         | 5.71%   |
| 3266    | 1         | 2.86%   |
| 2667    | 1         | 2.86%   |
| 2400    | 1         | 2.86%   |
| 1333    | 1         | 2.86%   |
| 975     | 1         | 2.86%   |
| 800     | 1         | 2.86%   |
| 266     | 1         | 2.86%   |
| 200     | 1         | 2.86%   |

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
| Chicony Electronics                    | 5         | 20.83%  |
| Microdia                               | 3         | 12.5%   |
| IMC Networks                           | 3         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 12.5%   |
| Pixart Imaging                         | 2         | 8.33%   |
| Acer                                   | 2         | 8.33%   |
| Suyin                                  | 1         | 4.17%   |
| Sunplus Innovation Technology          | 1         | 4.17%   |
| Silicon Motion                         | 1         | 4.17%   |
| Lenovo                                 | 1         | 4.17%   |
| Importek                               | 1         | 4.17%   |
| Apple                                  | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 8.33%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 8.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 8.33%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 4.17%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 4.17%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 4.17%   |
| Microdia Integrated Webcam                              | 1         | 4.17%   |
| Lenovo Integrated Webcam                                | 1         | 4.17%   |
| Importek FJ Camera                                      | 1         | 4.17%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 4.17%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 4.17%   |
| Chicony Integrated HP HD Webcam                         | 1         | 4.17%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 4.17%   |
| Chicony CNF8243 Webcam                                  | 1         | 4.17%   |
| Chicony CNF7050                                         | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 4.17%   |
| Apple Built-in iSight                                   | 1         | 4.17%   |
| Acer Lenovo EasyCamera                                  | 1         | 4.17%   |
| Acer BisonCam, NB Pro                                   | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 3         | 60%     |
| Validity Sensors | 1         | 20%     |
| Upek             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 40%     |
| Validity Sensors VFS491                                | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| AuthenTec AES1600                                      | 1         | 20%     |

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
| 0     | 25        | 67.57%  |
| 1     | 11        | 29.73%  |
| 3     | 1         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 7         | 53.85%  |
| Fingerprint reader | 5         | 38.46%  |
| Chipcard           | 1         | 7.69%   |

