antiX - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for antiX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/antiX/Desktop/README.md) and [notebooks](/Dist/antiX/Notebook/README.md).

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

Total: 55

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Unknown       | K8NF3-VSTA                  | Desktop     | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| AZW           | GK mini                     | Mini pc     | [9d00f58b53](https://linux-hardware.org/?probe=9d00f58b53) | May 04, 2022 |
| AZW           | GK mini                     | Mini pc     | [d474b9b330](https://linux-hardware.org/?probe=d474b9b330) | May 04, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | Notebook    | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | Notebook    | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Unknown       | NF-CK804                    | Desktop     | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | Notebook    | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | Notebook    | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | Notebook    | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | Notebook    | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | Notebook    | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [4a3e3cd4ee](https://linux-hardware.org/?probe=4a3e3cd4ee) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [e751bd8090](https://linux-hardware.org/?probe=e751bd8090) | Jan 14, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [cac53c0d21](https://linux-hardware.org/?probe=cac53c0d21) | Jan 14, 2021 |
| HP            | Mini 110-3700               | Notebook    | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| HP            | 8430 1000                   | All in one  | [db9e0da88a](https://linux-hardware.org/?probe=db9e0da88a) | Dec 06, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | Notebook    | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | Notebook    | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | 3641h                       | Desktop     | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| HP            | Mini 5101                   | Notebook    | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | Notebook    | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | Notebook    | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | Notebook    | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | Notebook    | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | Notebook    | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo        | ThinkCentre M91p 4480B9U    | Desktop     | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 17        | 39.53%  |
| antiX 19.2     | 8         | 18.6%   |
| antiX 19.3     | 4         | 9.3%    |
| antiX 17.4.1   | 4         | 9.3%    |
| antiX 21-runit | 2         | 4.65%   |
| antiX 19.4     | 2         | 4.65%   |
| antiX 19.1     | 2         | 4.65%   |
| antiX 17.2.1   | 1         | 2.33%   |
| antiX 17.1     | 1         | 2.33%   |
| antiX 17       | 1         | 2.33%   |
| antiX 15       | 1         | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 43        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 8         | 18.6%   |
| 4.9.0-279-antix.1-amd64-smp  | 6         | 13.95%  |
| 5.10.57-antix.1-amd64-smp    | 4         | 9.3%    |
| 4.9.160-antix.2-486-smp      | 4         | 9.3%    |
| 4.9.235-antix.1-amd64-smp    | 3         | 6.98%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 6.98%   |
| 4.9.212-antix.1-486-smp      | 3         | 6.98%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 4.65%   |
| 4.9.200-antix.1-486-smp      | 2         | 4.65%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 2.33%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 2.33%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 2.33%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 2.33%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 2.33%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 2.33%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 2.33%   |
| 4.10.5-antix.1-486-smp       | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 15        | 34.88%  |
| 4.9.212  | 6         | 13.95%  |
| 4.9.160  | 5         | 11.63%  |
| 5.10.57  | 4         | 9.3%    |
| 4.9.235  | 3         | 6.98%   |
| 5.10.88  | 2         | 4.65%   |
| 4.9.200  | 2         | 4.65%   |
| 5.14.0   | 1         | 2.33%   |
| 5.10.27  | 1         | 2.33%   |
| 4.9.87   | 1         | 2.33%   |
| 4.19.202 | 1         | 2.33%   |
| 4.19.100 | 1         | 2.33%   |
| 4.10.5   | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 74.42%  |
| 5.10    | 7         | 16.28%  |
| 4.19    | 2         | 4.65%   |
| 5.14    | 1         | 2.33%   |
| 4.10    | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 51.16%  |
| i686   | 20        | 46.51%  |
| i586   | 1         | 2.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 23        | 53.49%  |
| icewm        | 13        | 30.23%  |
| XFCE         | 4         | 9.3%    |
| jwm          | 1         | 2.33%   |
| herbstluftwm | 1         | 2.33%   |
| GNOME        | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 42        | 97.67%  |
| Tty  | 1         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 21        | 48.84%  |
| Unknown | 14        | 32.56%  |
| LightDM | 5         | 11.63%  |
| SLIMSKI | 2         | 4.65%   |
| SDDM    | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 17        | 39.53%  |
| ru_RU   | 3         | 6.98%   |
| ja_JP   | 3         | 6.98%   |
| de_DE   | 3         | 6.98%   |
| Unknown | 3         | 6.98%   |
| sk_SK   | 2         | 4.65%   |
| pl_PL   | 2         | 4.65%   |
| en_AU   | 2         | 4.65%   |
| zh_HK   | 1         | 2.33%   |
| uk_UA   | 1         | 2.33%   |
| pt_BR   | 1         | 2.33%   |
| nl_NL   | 1         | 2.33%   |
| it_IT   | 1         | 2.33%   |
| es_VE   | 1         | 2.33%   |
| es_MX   | 1         | 2.33%   |
| en_GB   | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 34        | 79.07%  |
| EFI  | 9         | 20.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 36        | 83.72%  |
| Overlay  | 6         | 13.95%  |
| Reiserfs | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 33        | 76.74%  |
| GPT     | 8         | 18.6%   |
| Unknown | 2         | 4.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 81.4%   |
| Yes       | 8         | 18.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 62.79%  |
| Yes       | 16        | 37.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 20.93%  |
| Hewlett-Packard     | 7         | 16.28%  |
| Lenovo              | 3         | 6.98%   |
| IBM                 | 3         | 6.98%   |
| Unknown             | 3         | 6.98%   |
| MSI                 | 2         | 4.65%   |
| Gigabyte Technology | 2         | 4.65%   |
| Dell                | 2         | 4.65%   |
| Acer                | 2         | 4.65%   |
| Toshiba             | 1         | 2.33%   |
| Samsung Electronics | 1         | 2.33%   |
| Radiant Systems     | 1         | 2.33%   |
| Packard Bell        | 1         | 2.33%   |
| Medion              | 1         | 2.33%   |
| KOHJINSHA           | 1         | 2.33%   |
| Fujitsu             | 1         | 2.33%   |
| Compaq              | 1         | 2.33%   |
| AZW                 | 1         | 2.33%   |
| Apple               | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 3         | 6.98%   |
| Toshiba Satellite 1905             | 1         | 2.33%   |
| Samsung SQ1S                       | 1         | 2.33%   |
| Radiant Systems P845               | 1         | 2.33%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2.33%   |
| MSI US Desktop                     | 1         | 2.33%   |
| MSI GE62 7RE                       | 1         | 2.33%   |
| Medion WIM2170                     | 1         | 2.33%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2.33%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 2.33%   |
| Lenovo G550 2958                   | 1         | 2.33%   |
| KOHJINSHA SX series                | 1         | 2.33%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 2.33%   |
| IBM ThinkPad T41 2374K50           | 1         | 2.33%   |
| IBM ThinkPad T40 237342G           | 1         | 2.33%   |
| HP t5740                           | 1         | 2.33%   |
| HP Pavilion dv2700                 | 1         | 2.33%   |
| HP Mini 5101                       | 1         | 2.33%   |
| HP Mini 110-3700                   | 1         | 2.33%   |
| HP EliteBook 8770w                 | 1         | 2.33%   |
| HP EliteBook 2570p                 | 1         | 2.33%   |
| HP All-in-One 24-f0xx              | 1         | 2.33%   |
| Gigabyte F2A85XM-D3H               | 1         | 2.33%   |
| Gigabyte 945GCMX-S2                | 1         | 2.33%   |
| Fujitsu FMVS54EB                   | 1         | 2.33%   |
| Dell Latitude E6400                | 1         | 2.33%   |
| Dell Latitude 5480                 | 1         | 2.33%   |
| Compaq Tablet PC TC1000            | 1         | 2.33%   |
| AZW GK mini                        | 1         | 2.33%   |
| ASUS X71SL                         | 1         | 2.33%   |
| ASUS X51RL                         | 1         | 2.33%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2.33%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2.33%   |
| ASUS P5KPL/1600                    | 1         | 2.33%   |
| ASUS A8R-MVP                       | 1         | 2.33%   |
| ASUS A3L                           | 1         | 2.33%   |
| ASUS 900HA                         | 1         | 2.33%   |
| ASUS 900A                          | 1         | 2.33%   |
| Apple MacBook7,1                   | 1         | 2.33%   |
| Acer Aspire 5920G                  | 1         | 2.33%   |
| Acer AOA150                        | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 6.98%   |
| Unknown               | 3         | 6.98%   |
| HP Mini               | 2         | 4.65%   |
| HP EliteBook          | 2         | 4.65%   |
| Dell Latitude         | 2         | 4.65%   |
| ASUS VivoBook         | 2         | 4.65%   |
| Toshiba Satellite     | 1         | 2.33%   |
| Samsung SQ1S          | 1         | 2.33%   |
| Radiant Systems P845  | 1         | 2.33%   |
| Packard Bell EasyNote | 1         | 2.33%   |
| MSI US                | 1         | 2.33%   |
| MSI GE62              | 1         | 2.33%   |
| Medion WIM2170        | 1         | 2.33%   |
| Lenovo ThinkPad       | 1         | 2.33%   |
| Lenovo ThinkCentre    | 1         | 2.33%   |
| Lenovo G550           | 1         | 2.33%   |
| KOHJINSHA SX          | 1         | 2.33%   |
| HP t5740              | 1         | 2.33%   |
| HP Pavilion           | 1         | 2.33%   |
| HP All-in-One         | 1         | 2.33%   |
| Gigabyte F2A85XM-D3H  | 1         | 2.33%   |
| Gigabyte 945GCMX-S2   | 1         | 2.33%   |
| Fujitsu FMVS54EB      | 1         | 2.33%   |
| Compaq Tablet         | 1         | 2.33%   |
| AZW GK                | 1         | 2.33%   |
| ASUS X71SL            | 1         | 2.33%   |
| ASUS X51RL            | 1         | 2.33%   |
| ASUS P5KPL            | 1         | 2.33%   |
| ASUS A8R-MVP          | 1         | 2.33%   |
| ASUS A3L              | 1         | 2.33%   |
| ASUS 900HA            | 1         | 2.33%   |
| ASUS 900A             | 1         | 2.33%   |
| Apple MacBook7        | 1         | 2.33%   |
| Acer Aspire           | 1         | 2.33%   |
| Acer AOA150           | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 8         | 18.6%   |
| 2007    | 7         | 16.28%  |
| 2009    | 5         | 11.63%  |
| 2012    | 3         | 6.98%   |
| 2005    | 3         | 6.98%   |
| 2003    | 3         | 6.98%   |
| 2021    | 2         | 4.65%   |
| 2013    | 2         | 4.65%   |
| 2011    | 2         | 4.65%   |
| 2020    | 1         | 2.33%   |
| 2019    | 1         | 2.33%   |
| 2018    | 1         | 2.33%   |
| 2017    | 1         | 2.33%   |
| 2016    | 1         | 2.33%   |
| 2010    | 1         | 2.33%   |
| 2004    | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 30        | 69.77%  |
| Desktop    | 10        | 23.26%  |
| Mini pc    | 2         | 4.65%   |
| All in one | 1         | 2.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 23.26%  |
| 0.51-1.0   | 8         | 18.6%   |
| 1.01-2.0   | 7         | 16.28%  |
| 2.01-3.0   | 6         | 13.95%  |
| 32.01-64.0 | 3         | 6.98%   |
| 8.01-16.0  | 3         | 6.98%   |
| 4.01-8.0   | 2         | 4.65%   |
| 16.01-24.0 | 2         | 4.65%   |
| 0.01-0.5   | 2         | 4.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 18        | 41.86%  |
| 0.51-1.0 | 13        | 30.23%  |
| 1.01-2.0 | 6         | 13.95%  |
| 2.01-3.0 | 5         | 11.63%  |
| 4.01-8.0 | 1         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 76.74%  |
| 2      | 5         | 11.63%  |
| 3      | 3         | 6.98%   |
| 0      | 2         | 4.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 51.16%  |
| No        | 21        | 48.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 90.7%   |
| No        | 4         | 9.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 76.74%  |
| No        | 10        | 23.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 65.12%  |
| Yes       | 15        | 34.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 20.93%  |
| Russia      | 5         | 11.63%  |
| Germany     | 5         | 11.63%  |
| Japan       | 3         | 6.98%   |
| Hong Kong   | 3         | 6.98%   |
| Slovakia    | 2         | 4.65%   |
| Poland      | 2         | 4.65%   |
| Australia   | 2         | 4.65%   |
| Ukraine     | 1         | 2.33%   |
| Netherlands | 1         | 2.33%   |
| Mexico      | 1         | 2.33%   |
| Kenya       | 1         | 2.33%   |
| Kazakhstan  | 1         | 2.33%   |
| Italy       | 1         | 2.33%   |
| Hungary     | 1         | 2.33%   |
| Greece      | 1         | 2.33%   |
| France      | 1         | 2.33%   |
| Denmark     | 1         | 2.33%   |
| Chile       | 1         | 2.33%   |
| Brazil      | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 3         | 6.98%   |
| Sydney                    | 2         | 4.65%   |
| Moscow                    | 2         | 4.65%   |
| Bratislava                | 2         | 4.65%   |
| Zagnansk                  | 1         | 2.33%   |
| Yuzhno-Sakhalinsk         | 1         | 2.33%   |
| Yokohama                  | 1         | 2.33%   |
| Violes                    | 1         | 2.33%   |
| Toms River                | 1         | 2.33%   |
| Schloss Holte-Stukenbrock | 1         | 2.33%   |
| Santiago                  | 1         | 2.33%   |
| Salto                     | 1         | 2.33%   |
| Rotterdam                 | 1         | 2.33%   |
| Reutlingen                | 1         | 2.33%   |
| Portland                  | 1         | 2.33%   |
| Otwock                    | 1         | 2.33%   |
| Norden                    | 1         | 2.33%   |
| Neyagawa                  | 1         | 2.33%   |
| Nairobi                   | 1         | 2.33%   |
| Mittegrossefehn           | 1         | 2.33%   |
| Mechanicsburg             | 1         | 2.33%   |
| Mason                     | 1         | 2.33%   |
| Kazan’                  | 1         | 2.33%   |
| Karaganda                 | 1         | 2.33%   |
| Kagoshima                 | 1         | 2.33%   |
| Jonesboro                 | 1         | 2.33%   |
| Inveruno                  | 1         | 2.33%   |
| Houston                   | 1         | 2.33%   |
| Heraklion                 | 1         | 2.33%   |
| Godley                    | 1         | 2.33%   |
| Frankfurt am Main         | 1         | 2.33%   |
| El Cerrito                | 1         | 2.33%   |
| Domodedovo                | 1         | 2.33%   |
| Dnipro                    | 1         | 2.33%   |
| Copenhagen                | 1         | 2.33%   |
| Celaya                    | 1         | 2.33%   |
| Budapest                  | 1         | 2.33%   |
| Boulder                   | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 11     | 20.41%  |
| Seagate             | 9         | 9      | 18.37%  |
| WDC                 | 7         | 7      | 14.29%  |
| Samsung Electronics | 5         | 6      | 10.2%   |
| Unknown             | 3         | 3      | 6.12%   |
| Toshiba             | 3         | 3      | 6.12%   |
| Kingston            | 2         | 2      | 4.08%   |
| Zheino              | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| RECADATA            | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |
| ASUS-PHISON         | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB          | 2         | 4%      |
| Hitachi HTS723232A7A364 320GB      | 2         | 4%      |
| Hitachi HTS548040M9AT00 40GB       | 2         | 4%      |
| Zheino CHN mSATAM3 128 128GB SSD   | 1         | 2%      |
| WDC WD800JB-00ETA0 80GB            | 1         | 2%      |
| WDC WD5000LPLX-08ZNTT0 500GB       | 1         | 2%      |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 2%      |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 2%      |
| WDC WD205BA 21GB                   | 1         | 2%      |
| WDC WD1600AAJS-00PSA0 160GB        | 1         | 2%      |
| WDC WD1200BEVE-00A0HT0 120GB       | 1         | 2%      |
| Unknown SR64G  64GB                | 1         | 2%      |
| Unknown SD/MMC/MS PRO 128GB        | 1         | 2%      |
| Unknown 2GB ATA Flash Disk         | 1         | 2%      |
| Toshiba THNSNJ256G8NY 256GB SSD    | 1         | 2%      |
| Toshiba MK2576GSX 250GB            | 1         | 2%      |
| Toshiba DT01ACA100 1TB             | 1         | 2%      |
| Seagate ST9160411AS 160GB          | 1         | 2%      |
| Seagate ST9160314AS 160GB          | 1         | 2%      |
| Seagate ST9160310AS 160GB          | 1         | 2%      |
| Seagate ST9160301AS 160GB          | 1         | 2%      |
| Seagate ST500LM030-1RK17D 500GB    | 1         | 2%      |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 2%      |
| Seagate ST500DM002-1BD142 500GB    | 1         | 2%      |
| Seagate ST3320620AS 320GB          | 1         | 2%      |
| Seagate ST3320413CS 320GB          | 1         | 2%      |
| SanDisk sandisk120 120GB SSD       | 1         | 2%      |
| Samsung SSD 850 EVO 120GB          | 1         | 2%      |
| Samsung HD250HJ 250GB              | 1         | 2%      |
| Samsung HD160JJ 160GB              | 1         | 2%      |
| Samsung HD080HJ/ 80GB              | 1         | 2%      |
| RECADATA RD-S350MCN-N0642 64GB SSD | 1         | 2%      |
| OCZ AGILITY3 120GB SSD             | 1         | 2%      |
| Kingston SUV500MS120G 120GB SSD    | 1         | 2%      |
| Kingston SUV400S37120G 120GB SSD   | 1         | 2%      |
| Intel SSDSC2BW180A3H 180GB         | 1         | 2%      |
| Hitachi HTS725050A7E630 500GB      | 1         | 2%      |
| Hitachi HTS721060G9AT00 64GB       | 1         | 2%      |
| Hitachi HTS545025B9A300 250GB      | 1         | 2%      |
| Hitachi HTS542525K9SA00 250GB      | 1         | 2%      |
| Hitachi HTS541612J9SA00 120GB      | 1         | 2%      |
| Hitachi HTC426040G8CE00 40GB       | 1         | 2%      |
| HGST HTS721010A9E630 1TB           | 1         | 2%      |
| HP SSD S750 512GB                  | 1         | 2%      |
| China M.2 SSD 128GB                | 1         | 2%      |
| BHT WR202I0064G E70245F5 64GB      | 1         | 2%      |
| ASUS-PHISON SSD 8GB                | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 10        | 11     | 30.3%   |
| Seagate             | 9         | 9      | 27.27%  |
| WDC                 | 7         | 7      | 21.21%  |
| Unknown             | 2         | 2      | 6.06%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 3      | 6.06%   |
| HGST                | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 20%     |
| Kingston            | 2         | 2      | 13.33%  |
| Zheino              | 1         | 1      | 6.67%   |
| Toshiba             | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| RECADATA            | 1         | 1      | 6.67%   |
| OCZ                 | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hewlett-Packard     | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| BHT                 | 1         | 1      | 6.67%   |
| ASUS-PHISON         | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 35     | 65.22%  |
| SSD  | 15        | 15     | 32.61%  |
| MMC  | 1         | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 49     | 95.35%  |
| SAS  | 1         | 1      | 2.33%   |
| MMC  | 1         | 1      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 47     | 93.18%  |
| 0.51-1.0   | 3         | 3      | 6.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 32.56%  |
| 1-20       | 10        | 23.26%  |
| 51-100     | 8         | 18.6%   |
| 21-50      | 6         | 13.95%  |
| 251-500    | 2         | 4.65%   |
| 501-1000   | 2         | 4.65%   |
| Unknown    | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 33        | 76.74%  |
| 21-50   | 4         | 9.3%    |
| 101-250 | 3         | 6.98%   |
| 51-100  | 2         | 4.65%   |
| Unknown | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800JB-00ETA0 80GB         | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 5.88%   |
| WDC WD205BA 21GB                | 1         | 1      | 5.88%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 5.88%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 5.88%   |
| Seagate ST3320620AS 320GB       | 1         | 1      | 5.88%   |
| Seagate ST3320413CS 320GB       | 1         | 1      | 5.88%   |
| SanDisk sandisk120 120GB SSD    | 1         | 1      | 5.88%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 5.88%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 5.88%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 5.88%   |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 5.88%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 5.88%   |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 5.88%   |
| China M.2 SSD 128GB             | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 7         | 7      | 41.18%  |
| Seagate | 5         | 5      | 29.41%  |
| WDC     | 3         | 3      | 17.65%  |
| SanDisk | 1         | 1      | 5.88%   |
| China   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 7         | 7      | 46.67%  |
| Seagate | 5         | 5      | 33.33%  |
| WDC     | 3         | 3      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 23        | 28     | 51.11%  |
| Malfunc  | 17        | 17     | 37.78%  |
| Detected | 5         | 6      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 32        | 68.09%  |
| AMD                              | 4         | 8.51%   |
| Nvidia                           | 3         | 6.38%   |
| Silicon Integrated Systems [SiS] | 2         | 4.26%   |
| ASMedia Technology               | 2         | 4.26%   |
| VIA Technologies                 | 1         | 2.13%   |
| ULi Electronics                  | 1         | 2.13%   |
| Silicon Image                    | 1         | 2.13%   |
| JMicron Technology               | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 5.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 5.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 5.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 5.08%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 5.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.08%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 3.39%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 3.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.39%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 3.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.69%   |
| ULi ULi M5288 SATA                                                             | 1         | 1.69%   |
| ULi M5229 IDE                                                                  | 1         | 1.69%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.69%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 1.69%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.69%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 1.69%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 1.69%   |
| Nvidia CK804 IDE                                                               | 1         | 1.69%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.69%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.69%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.69%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 1.69%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.69%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.69%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.69%   |
| AMD SB600 IDE                                                                  | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 26        | 50.98%  |
| SATA | 22        | 43.14%  |
| RAID | 3         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 36        | 83.72%  |
| AMD          | 6         | 13.95%  |
| GenuineTMx86 | 1         | 2.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 3         | 6.98%   |
| Intel Pentium M processor 1.60GHz              | 2         | 4.65%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 4.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 4.65%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 2         | 4.65%   |
| Intel Xeon CPU L5410 @ 2.33GHz                 | 1         | 2.33%   |
| Intel Pentium M processor 1600MHz              | 1         | 2.33%   |
| Intel Pentium M processor 1.86GHz              | 1         | 2.33%   |
| Intel Pentium M processor 1.00GHz              | 1         | 2.33%   |
| Intel Pentium II (Deschutes)                   | 1         | 2.33%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.33%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 1         | 2.33%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 2.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.33%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 2.33%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.33%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 2.33%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 2.33%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.33%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 2.33%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.33%   |
| Intel Celeron M processor 900MHz               | 1         | 2.33%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 2.33%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 2.33%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 2.33%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 1         | 2.33%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 2.33%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 1         | 2.33%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 2.33%   |
| AMD Sempron Processor 3000+                    | 1         | 2.33%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 2.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+     | 1         | 2.33%   |
| AMD Athlon 64 Processor 3200+                  | 1         | 2.33%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.33%   |
| AMD A6-5400K APU with Radeon HD Graphics       | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 7         | 16.28%  |
| Intel Core 2 Duo        | 6         | 13.95%  |
| Intel Pentium M         | 5         | 11.63%  |
| Other                   | 3         | 6.98%   |
| Intel Core i7           | 3         | 6.98%   |
| Intel Core i5           | 3         | 6.98%   |
| Intel Celeron           | 3         | 6.98%   |
| Intel Pentium Dual      | 2         | 4.65%   |
| Intel Xeon              | 1         | 2.33%   |
| Intel Pentium 4         | 1         | 2.33%   |
| Intel Pentium           | 1         | 2.33%   |
| Intel Core i3           | 1         | 2.33%   |
| Intel Celeron M         | 1         | 2.33%   |
| Intel Celeron Dual-Core | 1         | 2.33%   |
| AMD Sempron             | 1         | 2.33%   |
| AMD E2                  | 1         | 2.33%   |
| AMD Athlon 64 X2        | 1         | 2.33%   |
| AMD Athlon 64           | 1         | 2.33%   |
| AMD A6                  | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 46.51%  |
| 2      | 17        | 39.53%  |
| 4      | 5         | 11.63%  |
| 6      | 1         | 2.33%   |

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
| 1      | 28        | 65.12%  |
| 2      | 15        | 34.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 65.12%  |
| 32-bit         | 15        | 34.88%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 6         | 13.95%  |
| 0x6fd      | 5         | 11.63%  |
| 0x1067a    | 4         | 9.3%    |
| Unknown    | 4         | 9.3%    |
| 0x6d6      | 3         | 6.98%   |
| 0x6d8      | 2         | 4.65%   |
| 0x306a9    | 2         | 4.65%   |
| 0x206a7    | 2         | 4.65%   |
| 0xf24      | 1         | 2.33%   |
| 0xa0671    | 1         | 2.33%   |
| 0x906e9    | 1         | 2.33%   |
| 0x806e9    | 1         | 2.33%   |
| 0x706a8    | 1         | 2.33%   |
| 0x706a1    | 1         | 2.33%   |
| 0x695      | 1         | 2.33%   |
| 0x652      | 1         | 2.33%   |
| 0x306c3    | 1         | 2.33%   |
| 0x106ca    | 1         | 2.33%   |
| 0x10676    | 1         | 2.33%   |
| 0x10661    | 1         | 2.33%   |
| 0x07030106 | 1         | 2.33%   |
| 0x06006705 | 1         | 2.33%   |
| 0x06001116 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 7         | 16.28%  |
| P6            | 6         | 13.95%  |
| Core          | 6         | 13.95%  |
| Penryn        | 5         | 11.63%  |
| K8 Hammer     | 3         | 6.98%   |
| Unknown       | 3         | 6.98%   |
| SandyBridge   | 2         | 4.65%   |
| KabyLake      | 2         | 4.65%   |
| IvyBridge     | 2         | 4.65%   |
| Goldmont plus | 2         | 4.65%   |
| Puma          | 1         | 2.33%   |
| Piledriver    | 1         | 2.33%   |
| NetBurst      | 1         | 2.33%   |
| Haswell       | 1         | 2.33%   |
| Excavator     | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 50%     |
| AMD                              | 12        | 27.27%  |
| Nvidia                           | 9         | 20.45%  |
| Silicon Integrated Systems [SiS] | 1         | 2.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 7.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 7.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 5.66%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.77%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 3.77%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 3.77%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.89%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 1.89%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.89%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.89%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.89%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.89%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.89%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.89%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.89%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.89%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.89%   |
| Intel HD Graphics 630                                                         | 1         | 1.89%   |
| Intel HD Graphics 620                                                         | 1         | 1.89%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 1.89%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.89%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.89%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.89%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 1.89%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 1.89%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.89%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.89%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                       | 1         | 1.89%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                            | 1         | 1.89%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.89%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.89%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                               | 1         | 1.89%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.89%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 46.51%  |
| 1 x Nvidia     | 8         | 18.6%   |
| 1 x AMD        | 8         | 18.6%   |
| 2 x AMD        | 4         | 9.3%    |
| Other          | 1         | 2.33%   |
| 1 x SiS        | 1         | 2.33%   |
| Intel + Nvidia | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 35        | 81.4%   |
| Unknown     | 6         | 13.95%  |
| Proprietary | 2         | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 23        | 53.49%  |
| Unknown    | 13        | 30.23%  |
| 1.01-2.0   | 6         | 13.95%  |
| 3.01-4.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 20.69%  |
| Samsung Electronics | 5         | 17.24%  |
| LG Display          | 5         | 17.24%  |
| Acer                | 3         | 10.34%  |
| HannStar            | 2         | 6.9%    |
| Vizio               | 1         | 3.45%   |
| LG Philips          | 1         | 3.45%   |
| HJW                 | 1         | 3.45%   |
| Hewlett-Packard     | 1         | 3.45%   |
| Chimei Innolux      | 1         | 3.45%   |
| BOE                 | 1         | 3.45%   |
| Arnos Instruments   | 1         | 3.45%   |
| Apple               | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 6.9%    |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                   | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 3.45%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 3.45%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 3.45%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 3.45%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 3.45%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch     | 1         | 3.45%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 3.45%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 3.45%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 3.45%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch        | 1         | 3.45%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 3.45%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1         | 3.45%   |
| Acer V243H ACR00A3 1920x1080 530x290mm 23.8-inch                     | 1         | 3.45%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 8         | 28.57%  |
| 1366x768 (WXGA)  | 8         | 28.57%  |
| 1280x800 (WXGA)  | 4         | 14.29%  |
| 1024x600         | 3         | 10.71%  |
| 1600x1200        | 2         | 7.14%   |
| 1440x900 (WXGA+) | 2         | 7.14%   |
| 1280x1024 (SXGA) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 20.69%  |
| 14     | 4         | 13.79%  |
| 13     | 4         | 13.79%  |
| 21     | 3         | 10.34%  |
| 17     | 3         | 10.34%  |
| 10     | 2         | 6.9%    |
| 8      | 2         | 6.9%    |
| 38     | 1         | 3.45%   |
| 32     | 1         | 3.45%   |
| 27     | 1         | 3.45%   |
| 24     | 1         | 3.45%   |
| 23     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 41.38%  |
| 201-300     | 5         | 17.24%  |
| 501-600     | 3         | 10.34%  |
| 401-500     | 3         | 10.34%  |
| 351-400     | 2         | 6.9%    |
| 101-200     | 2         | 6.9%    |
| 801-900     | 1         | 3.45%   |
| 701-800     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 64.29%  |
| 16/10 | 7         | 25%     |
| 4/3   | 2         | 7.14%   |
| 5/4   | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 20.69%  |
| 101-110        | 6         | 20.69%  |
| 201-250        | 5         | 17.24%  |
| 71-80          | 2         | 6.9%    |
| 41-50          | 2         | 6.9%    |
| 1-40           | 2         | 6.9%    |
| 351-500        | 1         | 3.45%   |
| 301-350        | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| 131-140        | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |
| 501-1000       | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 10        | 35.71%  |
| 101-120 | 9         | 32.14%  |
| 121-160 | 8         | 28.57%  |
| 1-50    | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 81.4%   |
| 0     | 6         | 13.95%  |
| 2     | 2         | 4.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 18        | 26.47%  |
| Realtek Semiconductor            | 16        | 23.53%  |
| Qualcomm Atheros                 | 14        | 20.59%  |
| Broadcom                         | 7         | 10.29%  |
| Nvidia                           | 3         | 4.41%   |
| Marvell Technology Group         | 3         | 4.41%   |
| Silicon Integrated Systems [SiS] | 2         | 2.94%   |
| Qualcomm Atheros Communications  | 2         | 2.94%   |
| Ralink                           | 1         | 1.47%   |
| LSI                              | 1         | 1.47%   |
| Hewlett-Packard                  | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 6         | 7.14%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4         | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 3.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 2.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.38%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 2.38%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 2.38%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 1.19%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.19%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.19%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.19%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.19%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.19%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.19%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.19%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.19%   |
| Nvidia CK8S Ethernet Controller                                               | 1         | 1.19%   |
| Nvidia CK804 Ethernet Controller                                              | 1         | 1.19%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.19%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.19%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 1.19%   |
| LSI 56k WinModem                                                              | 1         | 1.19%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.19%   |
| Intel Wireless 7260                                                           | 1         | 1.19%   |
| Intel Wireless 3165                                                           | 1         | 1.19%   |
| Intel WiFi Link 5100                                                          | 1         | 1.19%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.19%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.19%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.19%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 1.19%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.19%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.19%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.19%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.19%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1         | 1.19%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.19%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.19%   |
| Intel 82551QM Ethernet Controller                                             | 1         | 1.19%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.19%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.19%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.19%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 38.89%  |
| Qualcomm Atheros                | 12        | 33.33%  |
| Broadcom                        | 4         | 11.11%  |
| Realtek Semiconductor           | 3         | 8.33%   |
| Qualcomm Atheros Communications | 2         | 5.56%   |
| Ralink                          | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 6         | 16.22%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 5.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 5.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 2.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.7%    |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 2.7%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.7%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.7%    |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.7%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.7%    |
| Intel Wireless 7260                                                           | 1         | 2.7%    |
| Intel Wireless 3165                                                           | 1         | 2.7%    |
| Intel WiFi Link 5100                                                          | 1         | 2.7%    |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 2.7%    |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 2.7%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.7%    |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.7%    |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.7%    |
| Intel Centrino Ultimate-N 6300                                                | 1         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 15        | 36.59%  |
| Intel                            | 11        | 26.83%  |
| Broadcom                         | 4         | 9.76%   |
| Qualcomm Atheros                 | 3         | 7.32%   |
| Nvidia                           | 3         | 7.32%   |
| Marvell Technology Group         | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] | 2         | 4.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 9.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 9.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 4.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 4.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.88%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 4.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.44%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.44%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 2.44%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 2.44%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.44%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 2.44%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.44%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.44%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 50%     |
| WiFi     | 33        | 42.31%  |
| Modem    | 6         | 7.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 63.41%  |
| Ethernet | 15        | 36.59%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 69.77%  |
| 1     | 13        | 30.23%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 83.72%  |
| Yes  | 7         | 16.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 4         | 26.67%  |
| Broadcom                | 4         | 26.67%  |
| IMC Networks            | 2         | 13.33%  |
| Realtek Semiconductor   | 1         | 6.67%   |
| Ralink Technology       | 1         | 6.67%   |
| Cambridge Silicon Radio | 1         | 6.67%   |
| ASUSTek Computer        | 1         | 6.67%   |
| Apple                   | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 13.33%  |
| IMC Networks Bluetooth Device                       | 2         | 13.33%  |
| Broadcom HP Portable SoftSailing                    | 2         | 13.33%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 6.67%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 6.67%   |
| Intel Bluetooth Device                              | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 6.67%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 6.67%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 6.67%   |
| Apple Bluetooth Host Controller                     | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 60.42%  |
| Nvidia                           | 5         | 10.42%  |
| AMD                              | 5         | 10.42%  |
| Silicon Integrated Systems [SiS] | 2         | 4.17%   |
| Creative Labs                    | 2         | 4.17%   |
| C-Media Electronics              | 2         | 4.17%   |
| VIA Technologies                 | 1         | 2.08%   |
| ULi Electronics                  | 1         | 2.08%   |
| Ensoniq                          | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 11.76%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 5.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 5.88%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 5.88%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.92%   |
| AMD FCH Azalia Controller                                                  | 2         | 3.92%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.96%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.96%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.96%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.96%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.96%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.96%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.96%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.96%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.96%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.96%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.96%   |
| C-Media Electronics CM6501                                                 | 1         | 1.96%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.96%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.96%   |
| AMD High Definition Audio Controller                                       | 1         | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 44.44%  |
| SK hynix            | 6         | 13.33%  |
| Samsung Electronics | 4         | 8.89%   |
| Kingston            | 4         | 8.89%   |
| Micron Technology   | 3         | 6.67%   |
| Unknown             | 2         | 4.44%   |
| Unknown (ABCD)      | 1         | 2.22%   |
| Unknown (8A02)      | 1         | 2.22%   |
| Patriot             | 1         | 2.22%   |
| Crucial             | 1         | 2.22%   |
| Corsair             | 1         | 2.22%   |
| Avant               | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 6.25%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 4.17%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 4.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 4.17%   |
| Unknown                                                        | 2         | 4.17%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2.08%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 2.08%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 2.08%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 2.08%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.08%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2.08%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 2.08%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.08%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.08%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 2.08%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 2.08%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.08%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.08%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 2.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 2.08%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.08%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.08%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s       | 1         | 2.08%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.08%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.08%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.08%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 2.08%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s                 | 1         | 2.08%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1         | 2.08%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.08%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.08%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.08%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 2.08%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s              | 1         | 2.08%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.08%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.08%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 1         | 2.08%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 10        | 25%     |
| DDR     | 8         | 20%     |
| SDRAM   | 7         | 17.5%   |
| DDR2    | 6         | 15%     |
| DDR4    | 5         | 12.5%   |
| Unknown | 2         | 5%      |
| LPDDR4  | 1         | 2.5%    |
| DRAM    | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 29        | 72.5%   |
| DIMM   | 11        | 27.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 1024  | 12        | 26.67%  |
| 2048  | 11        | 24.44%  |
| 512   | 7         | 15.56%  |
| 4096  | 6         | 13.33%  |
| 8192  | 4         | 8.89%   |
| 16384 | 3         | 6.67%   |
| 256   | 1         | 2.22%   |
| 232   | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 14        | 33.33%  |
| 1600    | 6         | 14.29%  |
| 667     | 5         | 11.9%   |
| 1067    | 3         | 7.14%   |
| 3266    | 2         | 4.76%   |
| 2400    | 2         | 4.76%   |
| 1333    | 2         | 4.76%   |
| 3200    | 1         | 2.38%   |
| 2667    | 1         | 2.38%   |
| 975     | 1         | 2.38%   |
| 800     | 1         | 2.38%   |
| 533     | 1         | 2.38%   |
| 400     | 1         | 2.38%   |
| 333     | 1         | 2.38%   |
| 266     | 1         | 2.38%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 23.81%  |
| Microdia                               | 3         | 14.29%  |
| Pixart Imaging                         | 2         | 9.52%   |
| IMC Networks                           | 2         | 9.52%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 9.52%   |
| Acer                                   | 2         | 9.52%   |
| Suyin                                  | 1         | 4.76%   |
| Sunplus Innovation Technology          | 1         | 4.76%   |
| Lite-On Technology                     | 1         | 4.76%   |
| Importek                               | 1         | 4.76%   |
| Apple                                  | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 9.52%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 9.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 9.52%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 4.76%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 4.76%   |
| Microdia Integrated Webcam                              | 1         | 4.76%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 4.76%   |
| Importek FJ Camera                                      | 1         | 4.76%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 4.76%   |
| Chicony Integrated HP HD Webcam                         | 1         | 4.76%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 4.76%   |
| Chicony CNF8243 Webcam                                  | 1         | 4.76%   |
| Chicony CNF7050                                         | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 4.76%   |
| Apple Built-in iSight                                   | 1         | 4.76%   |
| Acer Lenovo EasyCamera                                  | 1         | 4.76%   |
| Acer HP Webcam                                          | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors VFS491              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor | 1         | 33.33%  |
| AuthenTec AES1600                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 76.74%  |
| 1     | 5         | 11.63%  |
| 2     | 3         | 6.98%   |
| 3     | 2         | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 7         | 41.18%  |
| Fingerprint reader       | 3         | 17.65%  |
| Communication controller | 3         | 17.65%  |
| Sound                    | 1         | 5.88%   |
| Net/ethernet             | 1         | 5.88%   |
| Modem                    | 1         | 5.88%   |
| Chipcard                 | 1         | 5.88%   |

