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

Total: 53

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
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
| antiX 21       | 19        | 44.19%  |
| antiX 22       | 6         | 13.95%  |
| antiX 19.2     | 6         | 13.95%  |
| antiX 19.3     | 3         | 6.98%   |
| antiX 21-runit | 2         | 4.65%   |
| antiX 19.4     | 2         | 4.65%   |
| antiX 19.1     | 2         | 4.65%   |
| antiX 17.4.1   | 1         | 2.33%   |
| antiX 17.2.1   | 1         | 2.33%   |
| antiX 17       | 1         | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 13        | 30.23%  |
| 5.10.57-antix.1-amd64-smp    | 3         | 6.98%   |
| 4.9.0-326-antix.1-amd64-smp  | 3         | 6.98%   |
| 4.9.0-279-antix.1-amd64-smp  | 3         | 6.98%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 4.65%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 4.65%   |
| 4.9.212-antix.1-486-smp      | 2         | 4.65%   |
| 4.9.200-antix.1-486-smp      | 2         | 4.65%   |
| 4.9.0-326-antix.1-486-smp    | 2         | 4.65%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 2.33%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 2.33%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 2.33%   |
| 5.10.142-antix.2-amd64-smp   | 1         | 2.33%   |
| 4.9.160-antix.2-486-smp      | 1         | 2.33%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 2.33%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 2.33%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 2.33%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 2.33%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 2.33%   |
| 4.10.5-antix.1-486-smp       | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 21        | 50%     |
| 4.9.212  | 4         | 9.52%   |
| 5.10.57  | 3         | 7.14%   |
| 4.9.235  | 2         | 4.76%   |
| 4.9.200  | 2         | 4.76%   |
| 4.9.160  | 2         | 4.76%   |
| 5.14.0   | 1         | 2.38%   |
| 5.10.88  | 1         | 2.38%   |
| 5.10.27  | 1         | 2.38%   |
| 5.10.142 | 1         | 2.38%   |
| 4.19.202 | 1         | 2.38%   |
| 4.19.100 | 1         | 2.38%   |
| 4.19.0   | 1         | 2.38%   |
| 4.10.5   | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 31        | 73.81%  |
| 5.10    | 6         | 14.29%  |
| 4.19    | 3         | 7.14%   |
| 5.14    | 1         | 2.38%   |
| 4.10    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 23        | 54.76%  |
| x86_64 | 18        | 42.86%  |
| i586   | 1         | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 59.52%  |
| icewm   | 15        | 35.71%  |
| XFCE    | 1         | 2.38%   |
| GNOME   | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 42        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 54.76%  |
| SLiM    | 15        | 35.71%  |
| LightDM | 2         | 4.76%   |
| SLIMSKI | 1         | 2.38%   |
| SDDM    | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 50%     |
| ru_RU | 5         | 11.9%   |
| de_DE | 4         | 9.52%   |
| ja_JP | 2         | 4.76%   |
| en_AU | 2         | 4.76%   |
| zh_HK | 1         | 2.38%   |
| uk_UA | 1         | 2.38%   |
| pt_BR | 1         | 2.38%   |
| nl_NL | 1         | 2.38%   |
| it_IT | 1         | 2.38%   |
| es_VE | 1         | 2.38%   |
| es_MX | 1         | 2.38%   |
| en_GB | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 35        | 83.33%  |
| EFI  | 7         | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 35        | 83.33%  |
| Overlay  | 6         | 14.29%  |
| Reiserfs | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 34        | 80.95%  |
| GPT     | 7         | 16.67%  |
| Unknown | 1         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 79.07%  |
| Yes       | 9         | 20.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 59.52%  |
| Yes       | 17        | 40.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 21.43%  |
| Hewlett-Packard     | 6         | 14.29%  |
| Lenovo              | 5         | 11.9%   |
| IBM                 | 5         | 11.9%   |
| Acer                | 3         | 7.14%   |
| KOHJINSHA           | 2         | 4.76%   |
| Fujitsu             | 2         | 4.76%   |
| Dell                | 2         | 4.76%   |
| Toshiba             | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Packard Bell        | 1         | 2.38%   |
| MSI                 | 1         | 2.38%   |
| Medion              | 1         | 2.38%   |
| Google              | 1         | 2.38%   |
| Compaq              | 1         | 2.38%   |
| Apple               | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 4.76%   |
| HP Mini 110-3700                   | 2         | 4.76%   |
| Toshiba Satellite 1905             | 1         | 2.38%   |
| Samsung SQ1S                       | 1         | 2.38%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2.38%   |
| MSI GE62 7RE                       | 1         | 2.38%   |
| Medion WIM2170                     | 1         | 2.38%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 2.38%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2.38%   |
| Lenovo G550 2958                   | 1         | 2.38%   |
| Lenovo 3000 V100 076346G           | 1         | 2.38%   |
| KOHJINSHA SX series                | 1         | 2.38%   |
| KOHJINSHA SC series                | 1         | 2.38%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 2.38%   |
| IBM ThinkPad T41 2374K50           | 1         | 2.38%   |
| IBM ThinkPad T40 237342G           | 1         | 2.38%   |
| HP Pavilion dv2700                 | 1         | 2.38%   |
| HP Mini 5101                       | 1         | 2.38%   |
| HP EliteBook 8770w                 | 1         | 2.38%   |
| HP EliteBook 2570p                 | 1         | 2.38%   |
| Google Candy                       | 1         | 2.38%   |
| Fujitsu FMVS54EB                   | 1         | 2.38%   |
| Fujitsu FMVNU6G1C                  | 1         | 2.38%   |
| Dell Latitude E6400                | 1         | 2.38%   |
| Dell Latitude 5480                 | 1         | 2.38%   |
| Compaq Tablet PC TC1000            | 1         | 2.38%   |
| ASUS X71SL                         | 1         | 2.38%   |
| ASUS X51RL                         | 1         | 2.38%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2.38%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2.38%   |
| ASUS S3N                           | 1         | 2.38%   |
| ASUS A3L                           | 1         | 2.38%   |
| ASUS 900HA                         | 1         | 2.38%   |
| ASUS 900A                          | 1         | 2.38%   |
| ASUS 1011CX                        | 1         | 2.38%   |
| Apple MacBook7,1                   | 1         | 2.38%   |
| Acer Aspire 7520                   | 1         | 2.38%   |
| Acer Aspire 5920G                  | 1         | 2.38%   |
| Acer AOA150                        | 1         | 2.38%   |
| Unknown                            | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 7.14%   |
| HP Mini               | 3         | 7.14%   |
| Lenovo ThinkPad       | 2         | 4.76%   |
| IBM 260921H           | 2         | 4.76%   |
| HP EliteBook          | 2         | 4.76%   |
| Dell Latitude         | 2         | 4.76%   |
| ASUS VivoBook         | 2         | 4.76%   |
| Acer Aspire           | 2         | 4.76%   |
| Toshiba Satellite     | 1         | 2.38%   |
| Samsung SQ1S          | 1         | 2.38%   |
| Packard Bell EasyNote | 1         | 2.38%   |
| MSI GE62              | 1         | 2.38%   |
| Medion WIM2170        | 1         | 2.38%   |
| Lenovo G550           | 1         | 2.38%   |
| Lenovo 3000           | 1         | 2.38%   |
| KOHJINSHA SX          | 1         | 2.38%   |
| KOHJINSHA SC          | 1         | 2.38%   |
| HP Pavilion           | 1         | 2.38%   |
| Google Candy          | 1         | 2.38%   |
| Fujitsu FMVS54EB      | 1         | 2.38%   |
| Fujitsu FMVNU6G1C     | 1         | 2.38%   |
| Compaq Tablet         | 1         | 2.38%   |
| ASUS X71SL            | 1         | 2.38%   |
| ASUS X51RL            | 1         | 2.38%   |
| ASUS S3N              | 1         | 2.38%   |
| ASUS A3L              | 1         | 2.38%   |
| ASUS 900HA            | 1         | 2.38%   |
| ASUS 900A             | 1         | 2.38%   |
| ASUS 1011CX           | 1         | 2.38%   |
| Apple MacBook7        | 1         | 2.38%   |
| Acer AOA150           | 1         | 2.38%   |
| Unknown               | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2007 | 7         | 16.67%  |
| 2009 | 6         | 14.29%  |
| 2008 | 5         | 11.9%   |
| 2012 | 3         | 7.14%   |
| 2003 | 3         | 7.14%   |
| 2013 | 2         | 4.76%   |
| 2011 | 2         | 4.76%   |
| 2010 | 2         | 4.76%   |
| 2005 | 2         | 4.76%   |
| 2004 | 2         | 4.76%   |
| 1999 | 2         | 4.76%   |
| 2022 | 1         | 2.38%   |
| 2020 | 1         | 2.38%   |
| 2019 | 1         | 2.38%   |
| 2017 | 1         | 2.38%   |
| 2016 | 1         | 2.38%   |
| 2006 | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 42        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 97.62%  |
| Yes  | 1         | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 23.81%  |
| 0.51-1.0   | 9         | 21.43%  |
| 1.01-2.0   | 7         | 16.67%  |
| 2.01-3.0   | 6         | 14.29%  |
| 0.01-0.5   | 3         | 7.14%   |
| 4.01-8.0   | 2         | 4.76%   |
| 32.01-64.0 | 2         | 4.76%   |
| 8.01-16.0  | 2         | 4.76%   |
| 16.01-24.0 | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 45.24%  |
| 0.51-1.0 | 14        | 33.33%  |
| 1.01-2.0 | 6         | 14.29%  |
| 2.01-3.0 | 3         | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 80.95%  |
| 2      | 6         | 14.29%  |
| 3      | 1         | 2.38%   |
| 0      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 54.76%  |
| Yes       | 19        | 45.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 83.33%  |
| No        | 7         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 97.62%  |
| No        | 1         | 2.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 61.9%   |
| Yes       | 16        | 38.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 19.05%  |
| Hong Kong   | 8         | 19.05%  |
| Russia      | 6         | 14.29%  |
| Germany     | 5         | 11.9%   |
| Netherlands | 2         | 4.76%   |
| Japan       | 2         | 4.76%   |
| Australia   | 2         | 4.76%   |
| Ukraine     | 1         | 2.38%   |
| Mexico      | 1         | 2.38%   |
| Kenya       | 1         | 2.38%   |
| Kazakhstan  | 1         | 2.38%   |
| Italy       | 1         | 2.38%   |
| Hungary     | 1         | 2.38%   |
| Denmark     | 1         | 2.38%   |
| Chile       | 1         | 2.38%   |
| Brazil      | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 13.95%  |
| Sydney                    | 2         | 4.65%   |
| St Petersburg             | 2         | 4.65%   |
| Moscow                    | 2         | 4.65%   |
| Yuzhno-Sakhalinsk         | 1         | 2.33%   |
| Yokohama                  | 1         | 2.33%   |
| Whitney                   | 1         | 2.33%   |
| Toms River                | 1         | 2.33%   |
| Sheung Shui               | 1         | 2.33%   |
| Schloss Holte-Stukenbrock | 1         | 2.33%   |
| Santiago                  | 1         | 2.33%   |
| Salto                     | 1         | 2.33%   |
| Rotterdam                 | 1         | 2.33%   |
| Reutlingen                | 1         | 2.33%   |
| Portland                  | 1         | 2.33%   |
| Norden                    | 1         | 2.33%   |
| Neyagawa                  | 1         | 2.33%   |
| Nairobi                   | 1         | 2.33%   |
| Mittegrossefehn           | 1         | 2.33%   |
| Mechanicsburg             | 1         | 2.33%   |
| Karaganda                 | 1         | 2.33%   |
| Jonesboro                 | 1         | 2.33%   |
| Inveruno                  | 1         | 2.33%   |
| Hobbs                     | 1         | 2.33%   |
| Hagenbach                 | 1         | 2.33%   |
| Greenville                | 1         | 2.33%   |
| Godley                    | 1         | 2.33%   |
| Elektrostal               | 1         | 2.33%   |
| El Cerrito                | 1         | 2.33%   |
| Dnipro                    | 1         | 2.33%   |
| Copenhagen                | 1         | 2.33%   |
| Central                   | 1         | 2.33%   |
| Celaya                    | 1         | 2.33%   |
| Budapest                  | 1         | 2.33%   |
| Amsterdam                 | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 23.4%   |
| Seagate             | 8         | 8      | 17.02%  |
| WDC                 | 6         | 6      | 12.77%  |
| Toshiba             | 3         | 3      | 6.38%   |
| Samsung Electronics | 3         | 3      | 6.38%   |
| Unknown             | 2         | 2      | 4.26%   |
| Kingston            | 2         | 2      | 4.26%   |
| Zheino              | 1         | 1      | 2.13%   |
| Unknown (CF)        | 1         | 1      | 2.13%   |
| Transcend           | 1         | 1      | 2.13%   |
| RECADATA            | 1         | 1      | 2.13%   |
| OCZ                 | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| IBM/Hitachi         | 1         | 1      | 2.13%   |
| HGST                | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| Fujitsu             | 1         | 1      | 2.13%   |
| BHT                 | 1         | 2      | 2.13%   |
| ASUS-PHISON         | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 4.26%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 4.26%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 2.13%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.13%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 2.13%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.13%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 2.13%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 2.13%   |
| Unknown SR64G  64GB                     | 1         | 2.13%   |
| Unknown HAG2e  16GB                     | 1         | 2.13%   |
| Unknown (CF) Card 16GB SSD              | 1         | 2.13%   |
| Transcend SSD 2GB                       | 1         | 2.13%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 2.13%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 2.13%   |
| Toshiba MK2576GSX 250GB                 | 1         | 2.13%   |
| Seagate ST9320325AS 320GB               | 1         | 2.13%   |
| Seagate ST9250421ASG 250GB              | 1         | 2.13%   |
| Seagate ST9160411AS 160GB               | 1         | 2.13%   |
| Seagate ST9160314AS 160GB               | 1         | 2.13%   |
| Seagate ST9160310AS 160GB               | 1         | 2.13%   |
| Seagate ST9160301AS 160GB               | 1         | 2.13%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 2.13%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 2.13%   |
| Samsung HS06THB 64GB                    | 1         | 2.13%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 2.13%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 2.13%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 2.13%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 2.13%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 2.13%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB       | 1         | 2.13%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 2.13%   |
| Hitachi HTS723232A7A364 320GB           | 1         | 2.13%   |
| Hitachi HTS721060G9AT00 64GB            | 1         | 2.13%   |
| Hitachi HTS545025B9A300 250GB           | 1         | 2.13%   |
| Hitachi HTS543225A7A384 250GB           | 1         | 2.13%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 2.13%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 2.13%   |
| Hitachi HTC426040G8CE00 40GB            | 1         | 2.13%   |
| Hitachi DK23AA-60 6GB                   | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 36.67%  |
| Seagate             | 8         | 8      | 26.67%  |
| WDC                 | 6         | 6      | 20%     |
| Toshiba             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| IBM/Hitachi         | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |

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
| BHT                 | 1         | 2      | 6.67%   |
| ASUS-PHISON         | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 30     | 64.44%  |
| SSD  | 14        | 16     | 31.11%  |
| MMC  | 2         | 2      | 4.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 46     | 95.24%  |
| MMC  | 2         | 2      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 44     | 95.24%  |
| 0.51-1.0   | 2         | 2      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 14        | 32.56%  |
| 101-250    | 12        | 27.91%  |
| 21-50      | 6         | 13.95%  |
| 51-100     | 6         | 13.95%  |
| 251-500    | 3         | 6.98%   |
| 501-1000   | 1         | 2.33%   |
| Unknown    | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 33        | 78.57%  |
| 21-50   | 4         | 9.52%   |
| 101-250 | 2         | 4.76%   |
| 51-100  | 2         | 4.76%   |
| Unknown | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-22ZCT0 250GB   | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB     | 1         | 1      | 7.14%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 7.14%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 7.14%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 7.14%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 7.14%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 7.14%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 7.14%   |
| Hitachi HTS543225A7A384 250GB | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 7.14%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 7.14%   |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 7.14%   |
| Hitachi DK23AA-60 6GB         | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 64.29%  |
| Seagate | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 64.29%  |
| Seagate | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 100%    |

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
| Works    | 25        | 29     | 56.82%  |
| Malfunc  | 14        | 14     | 31.82%  |
| Detected | 5         | 5      | 11.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 34        | 79.07%  |
| Silicon Integrated Systems [SiS] | 2         | 4.65%   |
| Nvidia                           | 2         | 4.65%   |
| AMD                              | 2         | 4.65%   |
| VIA Technologies                 | 1         | 2.33%   |
| Silicon Image                    | 1         | 2.33%   |
| JMicron Technology               | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 7.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 7.55%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 7.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 5.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 5.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 5.66%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 3.77%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 3.77%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 3.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 3.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.77%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 3.77%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.89%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.89%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.89%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.89%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.89%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.89%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.89%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.89%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.89%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.89%   |
| AMD SB600 IDE                                                                  | 1         | 1.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 26        | 54.17%  |
| SATA | 19        | 39.58%  |
| RAID | 3         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 39        | 92.86%  |
| AMD          | 2         | 4.76%   |
| GenuineTMx86 | 1         | 2.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 9.52%   |
| Intel Pentium M processor 1.60GHz              | 2         | 4.76%   |
| Intel Pentium M processor 1.00GHz              | 2         | 4.76%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 4.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 4.76%   |
| Intel Celeron (Mendocino)                      | 2         | 4.76%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 4.76%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 2         | 4.76%   |
| Intel Pentium M processor 1600MHz              | 1         | 2.38%   |
| Intel Pentium M processor 1.86GHz              | 1         | 2.38%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.38%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 2.38%   |
| Intel Genuine processor 800MHz                 | 1         | 2.38%   |
| Intel Genuine CPU T2400 @ 1.83GHz              | 1         | 2.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.38%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 2.38%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.38%   |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 2.38%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 2.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.38%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 2.38%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.38%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 2.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.38%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 2.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 1         | 2.38%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 2.38%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 1         | 2.38%   |
| Intel Atom CPU N2600 @ 1.60GHz                 | 1         | 2.38%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 2.38%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 2.38%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-53     | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 10        | 23.81%  |
| Intel Pentium M         | 6         | 14.29%  |
| Intel Core 2 Duo        | 6         | 14.29%  |
| Intel Celeron           | 5         | 11.9%   |
| Intel Core i7           | 4         | 9.52%   |
| Intel Genuine           | 2         | 4.76%   |
| Intel Core i5           | 2         | 4.76%   |
| Other                   | 1         | 2.38%   |
| Intel Pentium Dual      | 1         | 2.38%   |
| Intel Pentium 4         | 1         | 2.38%   |
| Intel Core i3           | 1         | 2.38%   |
| Intel Celeron Dual-Core | 1         | 2.38%   |
| AMD E2                  | 1         | 2.38%   |
| AMD Athlon 64 X2        | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 50%     |
| 2      | 19        | 45.24%  |
| 4      | 2         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 59.52%  |
| 2      | 17        | 40.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 52.38%  |
| 32-bit         | 20        | 47.62%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 16.67%  |
| 0x6fd      | 4         | 9.52%   |
| 0x6d6      | 4         | 9.52%   |
| 0x1067a    | 4         | 9.52%   |
| 0x6d8      | 2         | 4.76%   |
| 0x66a      | 2         | 4.76%   |
| 0x306a9    | 2         | 4.76%   |
| 0x106ca    | 2         | 4.76%   |
| Unknown    | 2         | 4.76%   |
| 0xf24      | 1         | 2.38%   |
| 0x906e9    | 1         | 2.38%   |
| 0x806e9    | 1         | 2.38%   |
| 0x706a1    | 1         | 2.38%   |
| 0x6e8      | 1         | 2.38%   |
| 0x695      | 1         | 2.38%   |
| 0x306c3    | 1         | 2.38%   |
| 0x30678    | 1         | 2.38%   |
| 0x30661    | 1         | 2.38%   |
| 0x206a7    | 1         | 2.38%   |
| 0x20655    | 1         | 2.38%   |
| 0x10661    | 1         | 2.38%   |
| 0x07030106 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 10        | 23.81%  |
| P6            | 8         | 19.05%  |
| Core          | 5         | 11.9%   |
| Penryn        | 4         | 9.52%   |
| Unknown       | 3         | 7.14%   |
| KabyLake      | 2         | 4.76%   |
| IvyBridge     | 2         | 4.76%   |
| Westmere      | 1         | 2.38%   |
| Silvermont    | 1         | 2.38%   |
| SandyBridge   | 1         | 2.38%   |
| Puma          | 1         | 2.38%   |
| NetBurst      | 1         | 2.38%   |
| K8 Hammer     | 1         | 2.38%   |
| Haswell       | 1         | 2.38%   |
| Goldmont plus | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 60.47%  |
| Nvidia                           | 7         | 16.28%  |
| AMD                              | 7         | 16.28%  |
| Neomagic                         | 2         | 4.65%   |
| Silicon Integrated Systems [SiS] | 1         | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 13.73%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 9.8%    |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 3.92%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 3.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 3.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 3.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 3.92%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 3.92%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 3.92%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.96%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.96%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.96%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.96%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.96%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.96%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.96%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.96%   |
| Intel HD Graphics 630                                                         | 1         | 1.96%   |
| Intel HD Graphics 620                                                         | 1         | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.96%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.96%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.96%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.96%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.96%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.96%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 54.76%  |
| 1 x AMD        | 7         | 16.67%  |
| 1 x Nvidia     | 6         | 14.29%  |
| Other          | 2         | 4.76%   |
| 1 x Neomagic   | 2         | 4.76%   |
| 1 x SiS        | 1         | 2.38%   |
| Intel + Nvidia | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 88.1%   |
| Unknown     | 4         | 9.52%   |
| Proprietary | 1         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 23        | 54.76%  |
| Unknown    | 14        | 33.33%  |
| 1.01-2.0   | 4         | 9.52%   |
| 3.01-4.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 28.57%  |
| LG Display              | 5         | 17.86%  |
| Samsung Electronics     | 3         | 10.71%  |
| HannStar                | 3         | 10.71%  |
| LG Philips              | 2         | 7.14%   |
| Lenovo                  | 1         | 3.57%   |
| HJW                     | 1         | 3.57%   |
| CPT                     | 1         | 3.57%   |
| Chimei Innolux          | 1         | 3.57%   |
| Chi Mei Optoelectronics | 1         | 3.57%   |
| BOE                     | 1         | 3.57%   |
| Apple                   | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 3.57%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 3.57%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 3.57%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 3.57%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 3.57%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 3.57%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 3.57%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 3.57%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 3.57%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 3.57%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 3.57%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 3.57%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 3.57%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 3.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 3.57%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 3.57%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 8         | 29.63%  |
| 1280x800 (WXGA)  | 6         | 22.22%  |
| 1024x600         | 6         | 22.22%  |
| 1920x1080 (FHD)  | 4         | 14.81%  |
| 1440x900 (WXGA+) | 3         | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 21.43%  |
| 10     | 5         | 17.86%  |
| 14     | 4         | 14.29%  |
| 13     | 4         | 14.29%  |
| 17     | 3         | 10.71%  |
| 12     | 2         | 7.14%   |
| 8      | 2         | 7.14%   |
| 32     | 1         | 3.57%   |
| 11     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 39.29%  |
| 201-300     | 11        | 39.29%  |
| 351-400     | 3         | 10.71%  |
| 101-200     | 2         | 7.14%   |
| 701-800     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 62.96%  |
| 16/10 | 9         | 33.33%  |
| 3/2   | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 21.43%  |
| 101-110        | 6         | 21.43%  |
| 41-50          | 5         | 17.86%  |
| 71-80          | 2         | 7.14%   |
| 61-70          | 2         | 7.14%   |
| 1-40           | 2         | 7.14%   |
| 131-140        | 2         | 7.14%   |
| 51-60          | 1         | 3.57%   |
| 351-500        | 1         | 3.57%   |
| 121-130        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 39.29%  |
| 101-120 | 11        | 39.29%  |
| 51-100  | 6         | 21.43%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 88.37%  |
| 0     | 3         | 6.98%   |
| 2     | 2         | 4.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 27.54%  |
| Qualcomm Atheros                 | 17        | 24.64%  |
| Realtek Semiconductor            | 11        | 15.94%  |
| Broadcom                         | 9         | 13.04%  |
| Silicon Integrated Systems [SiS] | 2         | 2.9%    |
| Nvidia                           | 2         | 2.9%    |
| Marvell Technology Group         | 2         | 2.9%    |
| Texas Instruments                | 1         | 1.45%   |
| Ralink                           | 1         | 1.45%   |
| Qualcomm Atheros Communications  | 1         | 1.45%   |
| MediaTek                         | 1         | 1.45%   |
| Hewlett-Packard                  | 1         | 1.45%   |
| Attansic Technology              | 1         | 1.45%   |
| ASIX Electronics                 | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 9.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 5.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 4.65%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 3.49%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 3.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 3.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.33%   |
| Intel Wireless 7260                                                           | 2         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.33%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 2.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 2.33%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.16%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.16%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 1.16%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.16%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.16%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.16%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.16%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 1.16%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.16%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.16%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.16%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.16%   |
| Intel WiFi Link 5100                                                          | 1         | 1.16%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.16%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.16%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.16%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 38.64%  |
| Qualcomm Atheros                | 15        | 34.09%  |
| Broadcom                        | 7         | 15.91%  |
| Texas Instruments               | 1         | 2.27%   |
| Realtek Semiconductor           | 1         | 2.27%   |
| Ralink                          | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| MediaTek                        | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 17.78%  |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 6.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 4.44%   |
| Intel Wireless 7260                                                           | 2         | 4.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 4.44%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 4.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 4.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 4.44%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.22%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.22%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.22%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.22%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.22%   |
| Intel WiFi Link 5100                                                          | 1         | 2.22%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.22%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.22%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.22%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.22%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 10        | 28.57%  |
| Intel                            | 10        | 28.57%  |
| Broadcom                         | 4         | 11.43%  |
| Qualcomm Atheros                 | 3         | 8.57%   |
| Silicon Integrated Systems [SiS] | 2         | 5.71%   |
| Nvidia                           | 2         | 5.71%   |
| Marvell Technology Group         | 2         | 5.71%   |
| Attansic Technology              | 1         | 2.86%   |
| ASIX Electronics                 | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.43%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 5.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.71%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 5.71%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 5.71%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1         | 2.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.86%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.86%   |
| Nvidia MCP67 Ethernet                                             | 1         | 2.86%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.86%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.86%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.86%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.86%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.86%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.86%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.86%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 2.86%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 50%     |
| Ethernet | 35        | 42.68%  |
| Modem    | 6         | 7.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 85.71%  |
| Ethernet | 6         | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 78.57%  |
| 1     | 9         | 21.43%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 86.05%  |
| Yes  | 6         | 13.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 7         | 43.75%  |
| Intel                   | 3         | 18.75%  |
| IMC Networks            | 2         | 12.5%   |
| Ralink Technology       | 1         | 6.25%   |
| Cambridge Silicon Radio | 1         | 6.25%   |
| ASUSTek Computer        | 1         | 6.25%   |
| Apple                   | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 12.5%   |
| IMC Networks Bluetooth Device                       | 2         | 12.5%   |
| Broadcom HP Portable SoftSailing                    | 2         | 12.5%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 12.5%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 6.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 6.25%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 6.25%   |
| Apple Bluetooth Host Controller                     | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 33        | 75%     |
| Nvidia                           | 3         | 6.82%   |
| AMD                              | 3         | 6.82%   |
| Silicon Integrated Systems [SiS] | 2         | 4.55%   |
| ESS Technology                   | 2         | 4.55%   |
| VIA Technologies                 | 1         | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 21.74%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 8.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 6.52%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 4.35%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 4.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.35%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 4.35%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 2.17%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.17%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 2.17%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.17%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.17%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.17%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.17%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 2.17%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.17%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 21        | 46.67%  |
| SK hynix            | 7         | 15.56%  |
| Unknown             | 5         | 11.11%  |
| Samsung Electronics | 3         | 6.67%   |
| Micron Technology   | 3         | 6.67%   |
| Kingston            | 2         | 4.44%   |
| Crucial             | 2         | 4.44%   |
| Unknown (8A02)      | 1         | 2.22%   |
| Avant               | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 10.64%  |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 6.38%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 4.26%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 4.26%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 4.26%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 2.13%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2.13%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2.13%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.13%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 2.13%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 2.13%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.13%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.13%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.13%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.13%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.13%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s        | 1         | 2.13%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.13%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 2.13%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.13%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 2.13%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.13%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.13%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.13%   |
| Kingston RAM 9905428-095.D00LF 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.13%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 10        | 25.64%  |
| SDRAM | 9         | 23.08%  |
| DDR2  | 9         | 23.08%  |
| DDR   | 5         | 12.82%  |
| DRAM  | 3         | 7.69%   |
| DDR4  | 3         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 36        | 92.31%  |
| DIMM   | 3         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 13        | 28.89%  |
| 1024  | 12        | 26.67%  |
| 4096  | 5         | 11.11%  |
| 8192  | 4         | 8.89%   |
| 512   | 4         | 8.89%   |
| 256   | 3         | 6.67%   |
| 64    | 2         | 4.44%   |
| 16384 | 1         | 2.22%   |
| 232   | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 45%     |
| 1600    | 6         | 15%     |
| 1067    | 3         | 7.5%    |
| 667     | 2         | 5%      |
| 533     | 2         | 5%      |
| 3266    | 1         | 2.5%    |
| 3200    | 1         | 2.5%    |
| 2667    | 1         | 2.5%    |
| 2400    | 1         | 2.5%    |
| 1333    | 1         | 2.5%    |
| 975     | 1         | 2.5%    |
| 800     | 1         | 2.5%    |
| 266     | 1         | 2.5%    |
| 200     | 1         | 2.5%    |

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
| Chicony Electronics                    | 5         | 18.52%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 14.81%  |
| Microdia                               | 3         | 11.11%  |
| IMC Networks                           | 3         | 11.11%  |
| Acer                                   | 3         | 11.11%  |
| Suyin                                  | 2         | 7.41%   |
| Pixart Imaging                         | 2         | 7.41%   |
| Sunplus Innovation Technology          | 1         | 3.7%    |
| Silicon Motion                         | 1         | 3.7%    |
| Lenovo                                 | 1         | 3.7%    |
| Importek                               | 1         | 3.7%    |
| Apple                                  | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 7.41%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 7.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 7.41%   |
| Suyin Lenovo EasyCamera                                 | 1         | 3.7%    |
| Suyin Integrated_Webcam_HD                              | 1         | 3.7%    |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.7%    |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.7%    |
| Microdia Integrated Webcam                              | 1         | 3.7%    |
| Lenovo Integrated Webcam                                | 1         | 3.7%    |
| Importek FJ Camera                                      | 1         | 3.7%    |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.7%    |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.7%    |
| Chicony Integrated HP HD Webcam                         | 1         | 3.7%    |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.7%    |
| Chicony CNF8243 Webcam                                  | 1         | 3.7%    |
| Chicony CNF7050                                         | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.7%    |
| Apple Built-in iSight                                   | 1         | 3.7%    |
| Acer Lenovo EasyCamera                                  | 1         | 3.7%    |
| Acer Crystal Eye Webcam                                 | 1         | 3.7%    |
| Acer BisonCam, NB Pro                                   | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 4         | 66.67%  |
| Validity Sensors | 1         | 16.67%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 33.33%  |
| AuthenTec AES1600                                      | 2         | 33.33%  |
| Validity Sensors VFS491                                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |

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
| 0     | 31        | 73.81%  |
| 1     | 10        | 23.81%  |
| 2     | 1         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 50%     |
| Graphics card      | 5         | 41.67%  |
| Chipcard           | 1         | 8.33%   |

