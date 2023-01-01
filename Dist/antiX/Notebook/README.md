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

Total: 55

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
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
| antiX 21       | 20        | 44.44%  |
| antiX 22       | 7         | 15.56%  |
| antiX 19.2     | 6         | 13.33%  |
| antiX 19.3     | 3         | 6.67%   |
| antiX 21-runit | 2         | 4.44%   |
| antiX 19.4     | 2         | 4.44%   |
| antiX 19.1     | 2         | 4.44%   |
| antiX 17.4.1   | 1         | 2.22%   |
| antiX 17.2.1   | 1         | 2.22%   |
| antiX 17       | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 13        | 28.89%  |
| 5.10.57-antix.1-amd64-smp    | 4         | 8.89%   |
| 4.9.0-326-antix.1-amd64-smp  | 3         | 6.67%   |
| 4.9.0-279-antix.1-amd64-smp  | 3         | 6.67%   |
| 5.10.142-antix.2-amd64-smp   | 2         | 4.44%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 4.44%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 4.44%   |
| 4.9.212-antix.1-486-smp      | 2         | 4.44%   |
| 4.9.200-antix.1-486-smp      | 2         | 4.44%   |
| 4.9.0-326-antix.1-486-smp    | 2         | 4.44%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 2.22%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 2.22%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 2.22%   |
| 4.9.160-antix.2-486-smp      | 1         | 2.22%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 2.22%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 2.22%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 2.22%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 2.22%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 2.22%   |
| 4.10.5-antix.1-486-smp       | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 21        | 47.73%  |
| 5.10.57  | 4         | 9.09%   |
| 4.9.212  | 4         | 9.09%   |
| 5.10.142 | 2         | 4.55%   |
| 4.9.235  | 2         | 4.55%   |
| 4.9.200  | 2         | 4.55%   |
| 4.9.160  | 2         | 4.55%   |
| 5.14.0   | 1         | 2.27%   |
| 5.10.88  | 1         | 2.27%   |
| 5.10.27  | 1         | 2.27%   |
| 4.19.202 | 1         | 2.27%   |
| 4.19.100 | 1         | 2.27%   |
| 4.19.0   | 1         | 2.27%   |
| 4.10.5   | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 31        | 70.45%  |
| 5.10    | 8         | 18.18%  |
| 4.19    | 3         | 6.82%   |
| 5.14    | 1         | 2.27%   |
| 4.10    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 23        | 52.27%  |
| x86_64 | 20        | 45.45%  |
| i586   | 1         | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 56.82%  |
| icewm   | 16        | 36.36%  |
| XFCE    | 1         | 2.27%   |
| GNOME   | 1         | 2.27%   |
| fluxbox | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 44        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 56.82%  |
| SLiM    | 15        | 34.09%  |
| LightDM | 2         | 4.55%   |
| SLIMSKI | 1         | 2.27%   |
| SDDM    | 1         | 2.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 47.73%  |
| ru_RU | 5         | 11.36%  |
| de_DE | 4         | 9.09%   |
| nl_NL | 2         | 4.55%   |
| ja_JP | 2         | 4.55%   |
| en_AU | 2         | 4.55%   |
| zh_HK | 1         | 2.27%   |
| uk_UA | 1         | 2.27%   |
| pt_BR | 1         | 2.27%   |
| it_IT | 1         | 2.27%   |
| es_VE | 1         | 2.27%   |
| es_MX | 1         | 2.27%   |
| en_GB | 1         | 2.27%   |
| de_AT | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 37        | 84.09%  |
| EFI  | 7         | 15.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 37        | 84.09%  |
| Overlay  | 6         | 13.64%  |
| Reiserfs | 1         | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 36        | 81.82%  |
| GPT     | 7         | 15.91%  |
| Unknown | 1         | 2.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 80%     |
| Yes       | 9         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 59.09%  |
| Yes       | 18        | 40.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 20.45%  |
| Hewlett-Packard     | 6         | 13.64%  |
| Lenovo              | 5         | 11.36%  |
| IBM                 | 5         | 11.36%  |
| Dell                | 3         | 6.82%   |
| Acer                | 3         | 6.82%   |
| Toshiba             | 2         | 4.55%   |
| KOHJINSHA           | 2         | 4.55%   |
| Fujitsu             | 2         | 4.55%   |
| Samsung Electronics | 1         | 2.27%   |
| Packard Bell        | 1         | 2.27%   |
| MSI                 | 1         | 2.27%   |
| Medion              | 1         | 2.27%   |
| Google              | 1         | 2.27%   |
| Compaq              | 1         | 2.27%   |
| Apple               | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 4.55%   |
| HP Mini 110-3700                   | 2         | 4.55%   |
| Toshiba Satellite C50-A-1HF        | 1         | 2.27%   |
| Toshiba Satellite 1905             | 1         | 2.27%   |
| Samsung SQ1S                       | 1         | 2.27%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2.27%   |
| MSI GE62 7RE                       | 1         | 2.27%   |
| Medion WIM2170                     | 1         | 2.27%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 2.27%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2.27%   |
| Lenovo G550 2958                   | 1         | 2.27%   |
| Lenovo 3000 V100 076346G           | 1         | 2.27%   |
| KOHJINSHA SX series                | 1         | 2.27%   |
| KOHJINSHA SC series                | 1         | 2.27%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 2.27%   |
| IBM ThinkPad T41 2374K50           | 1         | 2.27%   |
| IBM ThinkPad T40 237342G           | 1         | 2.27%   |
| HP Pavilion dv2700                 | 1         | 2.27%   |
| HP Mini 5101                       | 1         | 2.27%   |
| HP EliteBook 8770w                 | 1         | 2.27%   |
| HP EliteBook 2570p                 | 1         | 2.27%   |
| Google Candy                       | 1         | 2.27%   |
| Fujitsu FMVS54EB                   | 1         | 2.27%   |
| Fujitsu FMVNU6G1C                  | 1         | 2.27%   |
| Dell Latitude E6400                | 1         | 2.27%   |
| Dell Latitude 5480                 | 1         | 2.27%   |
| Dell Latitude 2120                 | 1         | 2.27%   |
| Compaq Tablet PC TC1000            | 1         | 2.27%   |
| ASUS X71SL                         | 1         | 2.27%   |
| ASUS X51RL                         | 1         | 2.27%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2.27%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2.27%   |
| ASUS S3N                           | 1         | 2.27%   |
| ASUS A3L                           | 1         | 2.27%   |
| ASUS 900HA                         | 1         | 2.27%   |
| ASUS 900A                          | 1         | 2.27%   |
| ASUS 1011CX                        | 1         | 2.27%   |
| Apple MacBook7,1                   | 1         | 2.27%   |
| Acer Aspire 7520                   | 1         | 2.27%   |
| Acer Aspire 5920G                  | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 6.82%   |
| HP Mini               | 3         | 6.82%   |
| Dell Latitude         | 3         | 6.82%   |
| Toshiba Satellite     | 2         | 4.55%   |
| Lenovo ThinkPad       | 2         | 4.55%   |
| IBM 260921H           | 2         | 4.55%   |
| HP EliteBook          | 2         | 4.55%   |
| ASUS VivoBook         | 2         | 4.55%   |
| Acer Aspire           | 2         | 4.55%   |
| Samsung SQ1S          | 1         | 2.27%   |
| Packard Bell EasyNote | 1         | 2.27%   |
| MSI GE62              | 1         | 2.27%   |
| Medion WIM2170        | 1         | 2.27%   |
| Lenovo G550           | 1         | 2.27%   |
| Lenovo 3000           | 1         | 2.27%   |
| KOHJINSHA SX          | 1         | 2.27%   |
| KOHJINSHA SC          | 1         | 2.27%   |
| HP Pavilion           | 1         | 2.27%   |
| Google Candy          | 1         | 2.27%   |
| Fujitsu FMVS54EB      | 1         | 2.27%   |
| Fujitsu FMVNU6G1C     | 1         | 2.27%   |
| Compaq Tablet         | 1         | 2.27%   |
| ASUS X71SL            | 1         | 2.27%   |
| ASUS X51RL            | 1         | 2.27%   |
| ASUS S3N              | 1         | 2.27%   |
| ASUS A3L              | 1         | 2.27%   |
| ASUS 900HA            | 1         | 2.27%   |
| ASUS 900A             | 1         | 2.27%   |
| ASUS 1011CX           | 1         | 2.27%   |
| Apple MacBook7        | 1         | 2.27%   |
| Acer AOA150           | 1         | 2.27%   |
| Unknown               | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2007 | 7         | 15.91%  |
| 2009 | 6         | 13.64%  |
| 2008 | 5         | 11.36%  |
| 2013 | 3         | 6.82%   |
| 2012 | 3         | 6.82%   |
| 2010 | 3         | 6.82%   |
| 2003 | 3         | 6.82%   |
| 2011 | 2         | 4.55%   |
| 2005 | 2         | 4.55%   |
| 2004 | 2         | 4.55%   |
| 1999 | 2         | 4.55%   |
| 2022 | 1         | 2.27%   |
| 2020 | 1         | 2.27%   |
| 2019 | 1         | 2.27%   |
| 2017 | 1         | 2.27%   |
| 2016 | 1         | 2.27%   |
| 2006 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 44        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 97.73%  |
| Yes  | 1         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 22.73%  |
| 0.51-1.0   | 9         | 20.45%  |
| 1.01-2.0   | 8         | 18.18%  |
| 2.01-3.0   | 6         | 13.64%  |
| 4.01-8.0   | 3         | 6.82%   |
| 0.01-0.5   | 3         | 6.82%   |
| 32.01-64.0 | 2         | 4.55%   |
| 8.01-16.0  | 2         | 4.55%   |
| 16.01-24.0 | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 43.18%  |
| 0.51-1.0 | 15        | 34.09%  |
| 1.01-2.0 | 7         | 15.91%  |
| 2.01-3.0 | 3         | 6.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 79.55%  |
| 2      | 7         | 15.91%  |
| 3      | 1         | 2.27%   |
| 0      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 54.55%  |
| Yes       | 20        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 84.09%  |
| No        | 7         | 15.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 97.73%  |
| No        | 1         | 2.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 63.64%  |
| Yes       | 16        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 18.18%  |
| Hong Kong   | 8         | 18.18%  |
| Russia      | 6         | 13.64%  |
| Germany     | 5         | 11.36%  |
| Netherlands | 3         | 6.82%   |
| Japan       | 2         | 4.55%   |
| Australia   | 2         | 4.55%   |
| Ukraine     | 1         | 2.27%   |
| Mexico      | 1         | 2.27%   |
| Kenya       | 1         | 2.27%   |
| Kazakhstan  | 1         | 2.27%   |
| Italy       | 1         | 2.27%   |
| Hungary     | 1         | 2.27%   |
| Denmark     | 1         | 2.27%   |
| Chile       | 1         | 2.27%   |
| Brazil      | 1         | 2.27%   |
| Austria     | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 13.33%  |
| Sydney                    | 2         | 4.44%   |
| St Petersburg             | 2         | 4.44%   |
| Moscow                    | 2         | 4.44%   |
| Yuzhno-Sakhalinsk         | 1         | 2.22%   |
| Yokohama                  | 1         | 2.22%   |
| Ybbs an der Donau         | 1         | 2.22%   |
| Whitney                   | 1         | 2.22%   |
| Toms River                | 1         | 2.22%   |
| Sheung Shui               | 1         | 2.22%   |
| Schloss Holte-Stukenbrock | 1         | 2.22%   |
| Santiago                  | 1         | 2.22%   |
| Salto                     | 1         | 2.22%   |
| Rotterdam                 | 1         | 2.22%   |
| Reutlingen                | 1         | 2.22%   |
| Purmerend                 | 1         | 2.22%   |
| Portland                  | 1         | 2.22%   |
| Norden                    | 1         | 2.22%   |
| Neyagawa                  | 1         | 2.22%   |
| Nairobi                   | 1         | 2.22%   |
| Mittegrossefehn           | 1         | 2.22%   |
| Mechanicsburg             | 1         | 2.22%   |
| Karaganda                 | 1         | 2.22%   |
| Jonesboro                 | 1         | 2.22%   |
| Inveruno                  | 1         | 2.22%   |
| Hobbs                     | 1         | 2.22%   |
| Hagenbach                 | 1         | 2.22%   |
| Greenville                | 1         | 2.22%   |
| Godley                    | 1         | 2.22%   |
| Elektrostal               | 1         | 2.22%   |
| El Cerrito                | 1         | 2.22%   |
| Dnipro                    | 1         | 2.22%   |
| Copenhagen                | 1         | 2.22%   |
| Central                   | 1         | 2.22%   |
| Celaya                    | 1         | 2.22%   |
| Budapest                  | 1         | 2.22%   |
| Amsterdam                 | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 22.45%  |
| Seagate             | 8         | 8      | 16.33%  |
| WDC                 | 6         | 6      | 12.24%  |
| Toshiba             | 4         | 4      | 8.16%   |
| Samsung Electronics | 4         | 4      | 8.16%   |
| Unknown             | 2         | 2      | 4.08%   |
| Kingston            | 2         | 2      | 4.08%   |
| Zheino              | 1         | 1      | 2.04%   |
| Unknown (CF)        | 1         | 1      | 2.04%   |
| Transcend           | 1         | 1      | 2.04%   |
| RECADATA            | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| IBM/Hitachi         | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| BHT                 | 1         | 2      | 2.04%   |
| ASUS-PHISON         | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 4.08%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 4.08%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 2.04%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 2.04%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 2.04%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.04%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 2.04%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 2.04%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 2.04%   |
| Unknown SR64G  64GB                     | 1         | 2.04%   |
| Unknown HAG2e  16GB                     | 1         | 2.04%   |
| Unknown (CF) Card 16GB SSD              | 1         | 2.04%   |
| Transcend SSD 2GB                       | 1         | 2.04%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 2.04%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 2.04%   |
| Toshiba MQ01ABF050 500GB                | 1         | 2.04%   |
| Toshiba MK2576GSX 250GB                 | 1         | 2.04%   |
| Seagate ST9320325AS 320GB               | 1         | 2.04%   |
| Seagate ST9250421ASG 250GB              | 1         | 2.04%   |
| Seagate ST9160411AS 160GB               | 1         | 2.04%   |
| Seagate ST9160314AS 160GB               | 1         | 2.04%   |
| Seagate ST9160310AS 160GB               | 1         | 2.04%   |
| Seagate ST9160301AS 160GB               | 1         | 2.04%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 2.04%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 2.04%   |
| Samsung SSD 850 EVO 120GB               | 1         | 2.04%   |
| Samsung HS06THB 64GB                    | 1         | 2.04%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 2.04%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 2.04%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 2.04%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 2.04%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 2.04%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB       | 1         | 2.04%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 2.04%   |
| Hitachi HTS723232A7A364 320GB           | 1         | 2.04%   |
| Hitachi HTS721060G9AT00 64GB            | 1         | 2.04%   |
| Hitachi HTS545025B9A300 250GB           | 1         | 2.04%   |
| Hitachi HTS543225A7A384 250GB           | 1         | 2.04%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 2.04%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 35.48%  |
| Seagate             | 8         | 8      | 25.81%  |
| WDC                 | 6         | 6      | 19.35%  |
| Toshiba             | 2         | 2      | 6.45%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| IBM/Hitachi         | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Kingston            | 2         | 2      | 12.5%   |
| Zheino              | 1         | 1      | 6.25%   |
| Unknown (CF)        | 1         | 1      | 6.25%   |
| Transcend           | 1         | 1      | 6.25%   |
| RECADATA            | 1         | 1      | 6.25%   |
| OCZ                 | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Hewlett-Packard     | 1         | 1      | 6.25%   |
| BHT                 | 1         | 2      | 6.25%   |
| ASUS-PHISON         | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 31     | 63.83%  |
| SSD  | 15        | 17     | 31.91%  |
| MMC  | 2         | 2      | 4.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 48     | 95.45%  |
| MMC  | 2         | 2      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 46     | 95.45%  |
| 0.51-1.0   | 2         | 2      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 31.11%  |
| 1-20       | 14        | 31.11%  |
| 21-50      | 6         | 13.33%  |
| 51-100     | 6         | 13.33%  |
| 251-500    | 3         | 6.67%   |
| 501-1000   | 1         | 2.22%   |
| Unknown    | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 34        | 77.27%  |
| 21-50   | 5         | 11.36%  |
| 101-250 | 2         | 4.55%   |
| 51-100  | 2         | 4.55%   |
| Unknown | 1         | 2.27%   |

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
| Works    | 27        | 31     | 58.7%   |
| Malfunc  | 14        | 14     | 30.43%  |
| Detected | 5         | 5      | 10.87%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 80%     |
| Silicon Integrated Systems [SiS] | 2         | 4.44%   |
| Nvidia                           | 2         | 4.44%   |
| AMD                              | 2         | 4.44%   |
| VIA Technologies                 | 1         | 2.22%   |
| Silicon Image                    | 1         | 2.22%   |
| JMicron Technology               | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 7.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 7.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 7.27%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 7.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 5.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 5.45%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 3.64%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 3.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 3.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 3.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.64%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.82%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.82%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.82%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.82%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.82%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.82%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.82%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.82%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.82%   |
| AMD SB600 IDE                                                                  | 1         | 1.82%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 26        | 52%     |
| SATA | 21        | 42%     |
| RAID | 3         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 41        | 93.18%  |
| AMD          | 2         | 4.55%   |
| GenuineTMx86 | 1         | 2.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 9.09%   |
| Intel Pentium M processor 1.60GHz              | 2         | 4.55%   |
| Intel Pentium M processor 1.00GHz              | 2         | 4.55%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 4.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 4.55%   |
| Intel Celeron (Mendocino)                      | 2         | 4.55%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 4.55%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 2         | 4.55%   |
| Intel Pentium M processor 1600MHz              | 1         | 2.27%   |
| Intel Pentium M processor 1.86GHz              | 1         | 2.27%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 2.27%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 2.27%   |
| Intel Genuine processor 800MHz                 | 1         | 2.27%   |
| Intel Genuine CPU T2400 @ 1.83GHz              | 1         | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 2.27%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 2.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 2.27%   |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 2.27%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 1         | 2.27%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 2.27%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 2.27%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 2.27%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 2.27%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 2.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 1         | 2.27%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 2.27%   |
| Intel Atom CPU N550 @ 1.50GHz                  | 1         | 2.27%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 1         | 2.27%   |
| Intel Atom CPU N2600 @ 1.60GHz                 | 1         | 2.27%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 2.27%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 2.27%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-53     | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 11        | 25%     |
| Intel Pentium M         | 6         | 13.64%  |
| Intel Core 2 Duo        | 6         | 13.64%  |
| Intel Celeron           | 5         | 11.36%  |
| Intel Core i7           | 4         | 9.09%   |
| Intel Genuine           | 2         | 4.55%   |
| Intel Core i5           | 2         | 4.55%   |
| Intel Core i3           | 2         | 4.55%   |
| Other                   | 1         | 2.27%   |
| Intel Pentium Dual      | 1         | 2.27%   |
| Intel Pentium 4         | 1         | 2.27%   |
| Intel Celeron Dual-Core | 1         | 2.27%   |
| AMD E2                  | 1         | 2.27%   |
| AMD Athlon 64 X2        | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 47.73%  |
| 1      | 21        | 47.73%  |
| 4      | 2         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 56.82%  |
| 2      | 19        | 43.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 54.55%  |
| 32-bit         | 20        | 45.45%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 15.91%  |
| 0x6fd      | 4         | 9.09%   |
| 0x6d6      | 4         | 9.09%   |
| 0x1067a    | 4         | 9.09%   |
| 0x306a9    | 3         | 6.82%   |
| 0x106ca    | 3         | 6.82%   |
| 0x6d8      | 2         | 4.55%   |
| 0x66a      | 2         | 4.55%   |
| Unknown    | 2         | 4.55%   |
| 0xf24      | 1         | 2.27%   |
| 0x906e9    | 1         | 2.27%   |
| 0x806e9    | 1         | 2.27%   |
| 0x706a1    | 1         | 2.27%   |
| 0x6e8      | 1         | 2.27%   |
| 0x695      | 1         | 2.27%   |
| 0x306c3    | 1         | 2.27%   |
| 0x30678    | 1         | 2.27%   |
| 0x30661    | 1         | 2.27%   |
| 0x206a7    | 1         | 2.27%   |
| 0x20655    | 1         | 2.27%   |
| 0x10661    | 1         | 2.27%   |
| 0x07030106 | 1         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 11        | 25%     |
| P6            | 8         | 18.18%  |
| Core          | 5         | 11.36%  |
| Penryn        | 4         | 9.09%   |
| IvyBridge     | 3         | 6.82%   |
| Unknown       | 3         | 6.82%   |
| KabyLake      | 2         | 4.55%   |
| Westmere      | 1         | 2.27%   |
| Silvermont    | 1         | 2.27%   |
| SandyBridge   | 1         | 2.27%   |
| Puma          | 1         | 2.27%   |
| NetBurst      | 1         | 2.27%   |
| K8 Hammer     | 1         | 2.27%   |
| Haswell       | 1         | 2.27%   |
| Goldmont plus | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 60.87%  |
| Nvidia                           | 8         | 17.39%  |
| AMD                              | 7         | 15.22%  |
| Neomagic                         | 2         | 4.35%   |
| Silicon Integrated Systems [SiS] | 1         | 2.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 12.96%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 9.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 5.56%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 3.7%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 3.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 3.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 3.7%    |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.7%    |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 3.7%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.85%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.85%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.85%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.85%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.85%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.85%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.85%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.85%   |
| Intel HD Graphics 630                                                         | 1         | 1.85%   |
| Intel HD Graphics 620                                                         | 1         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.85%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.85%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.85%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.85%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.85%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 54.55%  |
| 1 x AMD        | 7         | 15.91%  |
| 1 x Nvidia     | 6         | 13.64%  |
| Other          | 2         | 4.55%   |
| 1 x Neomagic   | 2         | 4.55%   |
| Intel + Nvidia | 2         | 4.55%   |
| 1 x SiS        | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 88.64%  |
| Unknown     | 4         | 9.09%   |
| Proprietary | 1         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 23        | 52.27%  |
| Unknown    | 16        | 36.36%  |
| 1.01-2.0   | 4         | 9.09%   |
| 3.01-4.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 30%     |
| LG Display              | 6         | 20%     |
| Samsung Electronics     | 3         | 10%     |
| HannStar                | 3         | 10%     |
| LG Philips              | 2         | 6.67%   |
| Lenovo                  | 1         | 3.33%   |
| HJW                     | 1         | 3.33%   |
| CPT                     | 1         | 3.33%   |
| Chimei Innolux          | 1         | 3.33%   |
| Chi Mei Optoelectronics | 1         | 3.33%   |
| BOE                     | 1         | 3.33%   |
| Apple                   | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 3.33%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 3.33%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 3.33%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 3.33%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 3.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 3.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 3.33%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 3.33%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 3.33%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 3.33%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 3.33%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 3.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 3.33%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 3.33%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 9         | 31.03%  |
| 1024x600         | 7         | 24.14%  |
| 1280x800 (WXGA)  | 6         | 20.69%  |
| 1920x1080 (FHD)  | 4         | 13.79%  |
| 1440x900 (WXGA+) | 3         | 10.34%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 23.33%  |
| 10     | 6         | 20%     |
| 14     | 4         | 13.33%  |
| 13     | 4         | 13.33%  |
| 17     | 3         | 10%     |
| 12     | 2         | 6.67%   |
| 8      | 2         | 6.67%   |
| 32     | 1         | 3.33%   |
| 11     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 40%     |
| 201-300     | 12        | 40%     |
| 351-400     | 3         | 10%     |
| 101-200     | 2         | 6.67%   |
| 701-800     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 65.52%  |
| 16/10 | 9         | 31.03%  |
| 3/2   | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 23.33%  |
| 81-90          | 6         | 20%     |
| 41-50          | 6         | 20%     |
| 71-80          | 2         | 6.67%   |
| 61-70          | 2         | 6.67%   |
| 1-40           | 2         | 6.67%   |
| 131-140        | 2         | 6.67%   |
| 51-60          | 1         | 3.33%   |
| 351-500        | 1         | 3.33%   |
| 121-130        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 43.33%  |
| 121-160 | 11        | 36.67%  |
| 51-100  | 6         | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 88.89%  |
| 0     | 3         | 6.67%   |
| 2     | 2         | 4.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 26.76%  |
| Qualcomm Atheros                 | 18        | 25.35%  |
| Realtek Semiconductor            | 11        | 15.49%  |
| Broadcom                         | 10        | 14.08%  |
| Silicon Integrated Systems [SiS] | 2         | 2.82%   |
| Nvidia                           | 2         | 2.82%   |
| Marvell Technology Group         | 2         | 2.82%   |
| Texas Instruments                | 1         | 1.41%   |
| Ralink                           | 1         | 1.41%   |
| Qualcomm Atheros Communications  | 1         | 1.41%   |
| MediaTek                         | 1         | 1.41%   |
| Hewlett-Packard                  | 1         | 1.41%   |
| Attansic Technology              | 1         | 1.41%   |
| ASIX Electronics                 | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 8.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 4.44%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 3.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 3.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 3.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 2.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 2.22%   |
| Intel Wireless 7260                                                           | 2         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 2.22%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 2.22%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 2.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 2.22%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.11%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 1.11%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.11%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.11%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.11%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.11%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.11%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 1.11%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.11%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.11%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.11%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.11%   |
| Intel WiFi Link 5100                                                          | 1         | 1.11%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.11%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.11%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 36.96%  |
| Qualcomm Atheros                | 16        | 34.78%  |
| Broadcom                        | 8         | 17.39%  |
| Texas Instruments               | 1         | 2.17%   |
| Realtek Semiconductor           | 1         | 2.17%   |
| Ralink                          | 1         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 2.17%   |
| MediaTek                        | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 17.02%  |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 6.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 6.38%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 6.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 4.26%   |
| Intel Wireless 7260                                                           | 2         | 4.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 4.26%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 4.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 4.26%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.13%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.13%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.13%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.13%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.13%   |
| Intel WiFi Link 5100                                                          | 1         | 2.13%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.13%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.13%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.13%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.13%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 10        | 27.03%  |
| Intel                            | 10        | 27.03%  |
| Broadcom                         | 5         | 13.51%  |
| Qualcomm Atheros                 | 4         | 10.81%  |
| Silicon Integrated Systems [SiS] | 2         | 5.41%   |
| Nvidia                           | 2         | 5.41%   |
| Marvell Technology Group         | 2         | 5.41%   |
| Attansic Technology              | 1         | 2.7%    |
| ASIX Electronics                 | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 13.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 10.81%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 5.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.41%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 5.41%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 5.41%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1         | 2.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.7%    |
| Nvidia MCP89 Ethernet                                             | 1         | 2.7%    |
| Nvidia MCP67 Ethernet                                             | 1         | 2.7%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.7%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.7%    |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.7%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.7%    |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.7%    |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 2.7%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.7%    |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 2.7%    |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 50%     |
| Ethernet | 37        | 43.02%  |
| Modem    | 6         | 6.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 86.36%  |
| Ethernet | 6         | 13.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 79.55%  |
| 1     | 9         | 20.45%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 84.44%  |
| Yes  | 7         | 15.56%  |

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
| Intel                            | 35        | 76.09%  |
| Nvidia                           | 3         | 6.52%   |
| AMD                              | 3         | 6.52%   |
| Silicon Integrated Systems [SiS] | 2         | 4.35%   |
| ESS Technology                   | 2         | 4.35%   |
| VIA Technologies                 | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 22.92%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 8.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 6.25%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 4.17%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.17%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 4.17%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 2.08%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.08%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.08%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.08%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.08%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 21        | 43.75%  |
| SK hynix            | 9         | 18.75%  |
| Unknown             | 5         | 10.42%  |
| Samsung Electronics | 4         | 8.33%   |
| Micron Technology   | 3         | 6.25%   |
| Kingston            | 2         | 4.17%   |
| Crucial             | 2         | 4.17%   |
| Unknown (8A02)      | 1         | 2.08%   |
| Avant               | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 10%     |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 6%      |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 4%      |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 4%      |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 4%      |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 2%      |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 2%      |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 2%      |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 2%      |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2%      |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2%      |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2%      |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2%      |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2%      |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 2%      |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2%      |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2%      |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 2%      |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 2%      |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2%      |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 2%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2%      |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 2%      |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s          | 1         | 2%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 2%      |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2%      |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2%      |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 2%      |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 2%      |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2%      |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s        | 1         | 2%      |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 12        | 29.27%  |
| SDRAM | 9         | 21.95%  |
| DDR2  | 9         | 21.95%  |
| DDR   | 5         | 12.2%   |
| DRAM  | 3         | 7.32%   |
| DDR4  | 3         | 7.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 38        | 92.68%  |
| DIMM   | 3         | 7.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 15        | 31.25%  |
| 1024  | 12        | 25%     |
| 4096  | 6         | 12.5%   |
| 8192  | 4         | 8.33%   |
| 512   | 4         | 8.33%   |
| 256   | 3         | 6.25%   |
| 64    | 2         | 4.17%   |
| 16384 | 1         | 2.08%   |
| 232   | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 42.86%  |
| 1600    | 7         | 16.67%  |
| 1067    | 3         | 7.14%   |
| 667     | 2         | 4.76%   |
| 533     | 2         | 4.76%   |
| 3266    | 1         | 2.38%   |
| 3200    | 1         | 2.38%   |
| 2667    | 1         | 2.38%   |
| 2400    | 1         | 2.38%   |
| 1334    | 1         | 2.38%   |
| 1333    | 1         | 2.38%   |
| 975     | 1         | 2.38%   |
| 800     | 1         | 2.38%   |
| 266     | 1         | 2.38%   |
| 200     | 1         | 2.38%   |

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
| Chicony Electronics                    | 5         | 17.86%  |
| IMC Networks                           | 4         | 14.29%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 14.29%  |
| Microdia                               | 3         | 10.71%  |
| Acer                                   | 3         | 10.71%  |
| Suyin                                  | 2         | 7.14%   |
| Pixart Imaging                         | 2         | 7.14%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| Importek                               | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 7.14%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 7.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 7.14%   |
| Suyin Lenovo EasyCamera                                 | 1         | 3.57%   |
| Suyin Integrated_Webcam_HD                              | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.57%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.57%   |
| Microdia Integrated Webcam                              | 1         | 3.57%   |
| Lenovo Integrated Webcam                                | 1         | 3.57%   |
| Importek FJ Camera                                      | 1         | 3.57%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.57%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 3.57%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.57%   |
| Chicony Integrated HP HD Webcam                         | 1         | 3.57%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.57%   |
| Chicony CNF8243 Webcam                                  | 1         | 3.57%   |
| Chicony CNF7050                                         | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.57%   |
| Apple Built-in iSight                                   | 1         | 3.57%   |
| Acer Lenovo EasyCamera                                  | 1         | 3.57%   |
| Acer Crystal Eye Webcam                                 | 1         | 3.57%   |
| Acer BisonCam, NB Pro                                   | 1         | 3.57%   |

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
| 0     | 32        | 72.73%  |
| 1     | 11        | 25%     |
| 2     | 1         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 6         | 46.15%  |
| Fingerprint reader | 6         | 46.15%  |
| Chipcard           | 1         | 7.69%   |

