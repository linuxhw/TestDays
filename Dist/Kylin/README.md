Kylin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Kylin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kylin/Desktop/README.md) and [notebooks](/Dist/Kylin/Notebook/README.md).

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

Total: 38

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | Vostro 3350                 | Notebook    | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| GreatWall | GW-001Y1B-FTF               | All in one  | [7a7a16fc50](https://linux-hardware.org/?probe=7a7a16fc50) | Sep 28, 2023 |
| Lenovo    | Legion R9000P2021H 82JQ     | Notebook    | [5168f99a06](https://linux-hardware.org/?probe=5168f99a06) | Sep 26, 2023 |
| GreatWall | Unknown                     | Soc         | [9b283b5931](https://linux-hardware.org/?probe=9b283b5931) | Sep 18, 2023 |
| ASUSTek   | ROG Strix G713PV_G713PV     | Notebook    | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Apple     | MacBookPro12,1              | Notebook    | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek   | UX31LA                      | Notebook    | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI    | QingYun L420 KLVV-W5821     | Notebook    | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo    | ThinkBook 16 G5+ ARP 21J... | Notebook    | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | Notebook    | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI    | MACH-WX9                    | Notebook    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI    | MACH-WX9                    | Notebook    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell      | Inspiron 5468               | Notebook    | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo    | ThinkPad X200 74574AC       | Notebook    | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K550... | Notebook    | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP        | ZHAN 99 Mobile Workstati... | Notebook    | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | Notebook    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | Notebook    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell      | 0V7K5Y A00                  | Desktop     | [831a493e15](https://linux-hardware.org/?probe=831a493e15) | Feb 24, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | Notebook    | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo    | XiaoXinPro 14ACH 2021 82... | Notebook    | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo    | ThinkPad T480s 20L7A00HH... | Notebook    | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| Gigabyte  | Z97X-SLI-CF                 | Desktop     | [4e829bc252](https://linux-hardware.org/?probe=4e829bc252) | Dec 10, 2022 |
| THTF      | CR F860-T1                  | Notebook    | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| Phytium   | D2000                       | Server      | [e43b580add](https://linux-hardware.org/?probe=e43b580add) | Oct 18, 2022 |
| HUAWEI    | L410 KLVU-WDU0              | Notebook    | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| Phytium   | FT2000/4                    | Server      | [5f7f5d61af](https://linux-hardware.org/?probe=5f7f5d61af) | Oct 02, 2022 |
| Phytium   | FT2000/4                    | Server      | [c8aa4d1457](https://linux-hardware.org/?probe=c8aa4d1457) | Sep 30, 2022 |
| Phytium   | FT2000/4                    | Server      | [ff17710900](https://linux-hardware.org/?probe=ff17710900) | Sep 29, 2022 |
| GreatWall | Unknown                     | Notebook    | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| HP        | Tablet 11-be0xxx            | Tablet      | [e3bcbaf593](https://linux-hardware.org/?probe=e3bcbaf593) | Apr 08, 2022 |
| Timi      | TM1612                      | Notebook    | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| HANWEI    | FT-208-COME-B               | Soc         | [d22caa9915](https://linux-hardware.org/?probe=d22caa9915) | Jan 23, 2022 |
| Phytium   | FT-2000/4 V0001             | Server      | [152a75acd0](https://linux-hardware.org/?probe=152a75acd0) | Jan 19, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20T2A... | Notebook    | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP        | EliteBook 840 G7 Noteboo... | Notebook    | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | Notebook    | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | Notebook    | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Kylin V10   | 30        | 93.75%  |
| Kylin V10.1 | 2         | 6.25%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Kylin | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.18-35-generic       | 5         | 15.15%  |
| 5.19.0-32-generic       | 3         | 9.09%   |
| 5.4.18-15-generic       | 2         | 6.06%   |
| 5.19.0-45-generic       | 2         | 6.06%   |
| 6.2.0-33-generic        | 1         | 3.03%   |
| 6.2.0-32-generic        | 1         | 3.03%   |
| 6.2.0-23-generic        | 1         | 3.03%   |
| 6.2.0-21-generic        | 1         | 3.03%   |
| 5.4.96-7-kr9a0          | 1         | 3.03%   |
| 5.4.18-95-generic       | 1         | 3.03%   |
| 5.4.18-85-generic       | 1         | 3.03%   |
| 5.4.18-27-generic       | 1         | 3.03%   |
| 5.4.0-155-generic       | 1         | 3.03%   |
| 5.19.0-46-generic       | 1         | 3.03%   |
| 5.19.0-41-generic       | 1         | 3.03%   |
| 5.15.0-73-generic       | 1         | 3.03%   |
| 5.15.0-69-generic       | 1         | 3.03%   |
| 5.15.0-56-generic       | 1         | 3.03%   |
| 5.10.46-marvis          | 1         | 3.03%   |
| 5.10.0-23-amd64         | 1         | 3.03%   |
| 5.10.0-20-amd64         | 1         | 3.03%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 3.03%   |
| 4.19.71-14-kr990        | 1         | 3.03%   |
| 4.19.260-atzlinux-ft9   | 1         | 3.03%   |
| 4.19.237-atzlinux-ft8   | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.18   | 10        | 30.3%   |
| 5.19.0   | 7         | 21.21%  |
| 6.2.0    | 4         | 12.12%  |
| 5.15.0   | 3         | 9.09%   |
| 5.10.0   | 3         | 9.09%   |
| 5.4.96   | 1         | 3.03%   |
| 5.4.0    | 1         | 3.03%   |
| 5.10.46  | 1         | 3.03%   |
| 4.19.71  | 1         | 3.03%   |
| 4.19.260 | 1         | 3.03%   |
| 4.19.237 | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 12        | 37.5%   |
| 5.19    | 7         | 21.88%  |
| 6.2     | 4         | 12.5%   |
| 5.10    | 4         | 12.5%   |
| 5.15    | 3         | 9.38%   |
| 4.19    | 2         | 6.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 23        | 71.88%  |
| aarch64 | 9         | 28.13%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| UKUI       | 14        | 43.75%  |
| GNOME      | 14        | 43.75%  |
| KDE5       | 2         | 6.25%   |
| XFCE       | 1         | 3.13%   |
| X-Cinnamon | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 22        | 66.67%  |
| Wayland | 8         | 24.24%  |
| Tty     | 3         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 14        | 43.75%  |
| GDM3    | 13        | 40.63%  |
| TDM     | 2         | 6.25%   |
| SDDM    | 2         | 6.25%   |
| GDM     | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| zh_CN | 25        | 78.13%  |
| en_US | 5         | 15.63%  |
| en_HK | 1         | 3.13%   |
| en_CA | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 27        | 84.38%  |
| BIOS | 5         | 15.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 28        | 87.5%   |
| Tmpfs   | 2         | 6.25%   |
| Overlay | 2         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 30        | 93.75%  |
| MBR     | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 72.73%  |
| Yes       | 9         | 27.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 65.63%  |
| Yes       | 11        | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 31.25%  |
| Phytium             | 3         | 9.38%   |
| HUAWEI              | 3         | 9.38%   |
| Hewlett-Packard     | 3         | 9.38%   |
| GreatWall           | 3         | 9.38%   |
| Dell                | 3         | 9.38%   |
| ASUSTek Computer    | 3         | 9.38%   |
| Timi                | 1         | 3.13%   |
| THTF                | 1         | 3.13%   |
| Gigabyte Technology | 1         | 3.13%   |
| Apple               | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Phytium FT2000/4                             | 2         | 6.25%   |
| Unknown                                      | 2         | 6.25%   |
| Timi TM1612                                  | 1         | 3.13%   |
| THTF CR F860-T1                              | 1         | 3.13%   |
| Phytium FT-2000/4                            | 1         | 3.13%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 3.13%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 3.13%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 3.13%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 3.13%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 3.13%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 3.13%   |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 3.13%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 3.13%   |
| Lenovo Legion R9000P2021H 82JQ               | 1         | 3.13%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 3.13%   |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 3.13%   |
| HUAWEI MACH-WX9                              | 1         | 3.13%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 3.13%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 3.13%   |
| HP Tablet 11-be0xxx                          | 1         | 3.13%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 3.13%   |
| GreatWall GW-XXXXXX-XXX                      | 1         | 3.13%   |
| Gigabyte Z97X-SLI                            | 1         | 3.13%   |
| Dell Vostro 5880                             | 1         | 3.13%   |
| Dell Vostro 3350                             | 1         | 3.13%   |
| Dell Inspiron 5468                           | 1         | 3.13%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 3.13%   |
| ASUS UX31LA                                  | 1         | 3.13%   |
| ASUS ROG Strix G713PV_G713PV                 | 1         | 3.13%   |
| Apple MacBookPro12,1                         | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 5         | 15.63%  |
| Phytium FT2000          | 2         | 6.25%   |
| Lenovo Legion           | 2         | 6.25%   |
| Dell Vostro             | 2         | 6.25%   |
| Unknown                 | 2         | 6.25%   |
| Timi TM1612             | 1         | 3.13%   |
| THTF CR                 | 1         | 3.13%   |
| Phytium FT-2000         | 1         | 3.13%   |
| Lenovo XiaoXinPro       | 1         | 3.13%   |
| Lenovo ThinkBook        | 1         | 3.13%   |
| Lenovo IdeaPad          | 1         | 3.13%   |
| HUAWEI QingYun          | 1         | 3.13%   |
| HUAWEI MACH-WX9         | 1         | 3.13%   |
| HUAWEI L410             | 1         | 3.13%   |
| HP ZHAN                 | 1         | 3.13%   |
| HP Tablet               | 1         | 3.13%   |
| HP EliteBook            | 1         | 3.13%   |
| GreatWall GW-XXXXXX-XXX | 1         | 3.13%   |
| Gigabyte Z97X-SLI       | 1         | 3.13%   |
| Dell Inspiron           | 1         | 3.13%   |
| ASUS VivoBook           | 1         | 3.13%   |
| ASUS UX31LA             | 1         | 3.13%   |
| ASUS ROG                | 1         | 3.13%   |
| Apple MacBookPro12      | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 8         | 25%     |
| 2022    | 5         | 15.63%  |
| 2020    | 3         | 9.38%   |
| 2016    | 3         | 9.38%   |
| 2014    | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |
| 2018    | 2         | 6.25%   |
| 2023    | 1         | 3.13%   |
| 2015    | 1         | 3.13%   |
| 2012    | 1         | 3.13%   |
| 2011    | 1         | 3.13%   |
| 2008    | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 24        | 75%     |
| Server         | 3         | 9.38%   |
| Desktop        | 2         | 6.25%   |
| System on chip | 1         | 3.13%   |
| Tablet         | 1         | 3.13%   |
| All in one     | 1         | 3.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 90.63%  |
| Enabled  | 3         | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 10        | 31.25%  |
| 4.01-8.0    | 8         | 25%     |
| 3.01-4.0    | 6         | 18.75%  |
| 16.01-24.0  | 5         | 15.63%  |
| 32.01-64.0  | 1         | 3.13%   |
| 24.01-32.0  | 1         | 3.13%   |
| 64.01-256.0 | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 12        | 36.36%  |
| 1.01-2.0  | 9         | 27.27%  |
| 2.01-3.0  | 5         | 15.15%  |
| 4.01-8.0  | 3         | 9.09%   |
| 8.01-16.0 | 2         | 6.06%   |
| 0.51-1.0  | 2         | 6.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 65.63%  |
| 2      | 7         | 21.88%  |
| 4      | 2         | 6.25%   |
| 3      | 2         | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 90.63%  |
| Yes       | 3         | 9.38%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 62.5%   |
| No        | 12        | 37.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 81.25%  |
| No        | 6         | 18.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 78.13%  |
| No        | 7         | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| China     | 26        | 81.25%  |
| Hong Kong | 3         | 9.38%   |
| USA       | 1         | 3.13%   |
| Taiwan    | 1         | 3.13%   |
| Canada    | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Tianjin     | 3         | 9.38%   |
| Shenzhen    | 3         | 9.38%   |
| Shanghai    | 2         | 6.25%   |
| Jinrongjie  | 2         | 6.25%   |
| Haidian     | 2         | 6.25%   |
| Central     | 2         | 6.25%   |
| Beijing     | 2         | 6.25%   |
| Zhongshan   | 1         | 3.13%   |
| Zhengzhou   | 1         | 3.13%   |
| Xuhui       | 1         | 3.13%   |
| Xiaolou     | 1         | 3.13%   |
| Xi'an       | 1         | 3.13%   |
| Shizishan   | 1         | 3.13%   |
| Putuo       | 1         | 3.13%   |
| Mong Kok    | 1         | 3.13%   |
| Markham     | 1         | 3.13%   |
| Los Angeles | 1         | 3.13%   |
| Jinan       | 1         | 3.13%   |
| Harbin      | 1         | 3.13%   |
| Guangzhou   | 1         | 3.13%   |
| Changsha    | 1         | 3.13%   |
| Chancheng   | 1         | 3.13%   |
| Banqiao     | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 26.83%  |
| Toshiba             | 4         | 4      | 9.76%   |
| SanDisk             | 3         | 3      | 7.32%   |
| Micron Technology   | 3         | 3      | 7.32%   |
| WDC                 | 2         | 2      | 4.88%   |
| Unknown             | 2         | 2      | 4.88%   |
| FORESEE             | 2         | 3      | 4.88%   |
| ZX1 1TB             | 1         | 1      | 2.44%   |
| ZHITAI              | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Seagate             | 1         | 1      | 2.44%   |
| Phison              | 1         | 1      | 2.44%   |
| Pear 2TB            | 1         | 1      | 2.44%   |
| Lenovo              | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Kingchuxing         | 1         | 1      | 2.44%   |
| HISI                | 1         | 4      | 2.44%   |
| Hikvision           | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| FC-1307             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 4.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 4.76%   |
| Micron MTFDKBA512TFH 512GB                          | 2         | 4.76%   |
| FORESEE 64GB SSD                                    | 2         | 4.76%   |
| ZX1 1TB Disk 1TB                                    | 1         | 2.38%   |
| ZHITAI TiPlus7100 2TB                               | 1         | 2.38%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                | 1         | 2.38%   |
| WDC PC SN530 SDBPNPZ-256G                           | 1         | 2.38%   |
| Unknown NVMe SSD Drive 512GB                        | 1         | 2.38%   |
| Unknown NVMe SSD Drive 256GB                        | 1         | 2.38%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 2.38%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 2.38%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                   | 1         | 2.38%   |
| Toshiba DT01ACA100 1TB                              | 1         | 2.38%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 1         | 2.38%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 2.38%   |
| SanDisk SD6SP1M256G1102 256GB SSD                   | 1         | 2.38%   |
| SanDisk NVMe SSD Drive 256GB                        | 1         | 2.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2.38%   |
| Samsung PM991 NVMe 256GB                            | 1         | 2.38%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 2.38%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 2.38%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 2.38%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                    | 1         | 2.38%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                | 1         | 2.38%   |
| Samsung KLUFG8RHDA-B2D1 512GB                       | 1         | 2.38%   |
| Samsung KLUFG8RHDA-B2D1 1GB                         | 1         | 2.38%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G              | 1         | 2.38%   |
| Pear 2TB Disk 2TB                                   | 1         | 2.38%   |
| Micron 2450_MTFDKBA1T0TFK 1024GB                    | 1         | 2.38%   |
| Lenovo SSD SL500 240G                               | 1         | 2.38%   |
| Kingston OM3PDP3128B-AH 128GB                       | 1         | 2.38%   |
| Kingchuxing SSD 128GB                               | 1         | 2.38%   |
| HISI THR920GFCV100HAE 256GB                         | 1         | 2.38%   |
| Hikvision HS-SSD-E2000L 512G                        | 1         | 2.38%   |
| HP SSD EX950 1TB                                    | 1         | 2.38%   |
| FC-1307 SD to CF Adapter V1.4                       | 1         | 2.38%   |
| Apple SSD SM0256G 256GB                             | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 60%     |
| Seagate  | 1         | 1      | 20%     |
| Pear 2TB | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 5      | 22.22%  |
| FORESEE             | 2         | 3      | 22.22%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Lenovo              | 1         | 1      | 11.11%  |
| Kingchuxing         | 1         | 1      | 11.11%  |
| HISI                | 1         | 4      | 11.11%  |
| Apple               | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 21        | 26     | 56.76%  |
| SSD     | 9         | 16     | 24.32%  |
| HDD     | 5         | 5      | 13.51%  |
| Unknown | 2         | 2      | 5.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 26     | 56.76%  |
| SATA | 14        | 21     | 37.84%  |
| SAS  | 2         | 2      | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 16     | 66.67%  |
| 0.51-1.0   | 4         | 4      | 26.67%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 33.33%  |
| 51-100     | 8         | 24.24%  |
| 101-250    | 7         | 21.21%  |
| 1001-2000  | 3         | 9.09%   |
| 501-1000   | 3         | 9.09%   |
| 21-50      | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 10        | 31.25%  |
| 51-100   | 8         | 25%     |
| 1-20     | 6         | 18.75%  |
| 101-250  | 4         | 12.5%   |
| 251-500  | 3         | 9.38%   |
| 501-1000 | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Works    | 24        | 28     | 68.57%  |
| Detected | 11        | 21     | 31.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 10        | 24.39%  |
| Intel                                   | 9         | 21.95%  |
| SanDisk                                 | 4         | 9.76%   |
| Marvell Technology Group                | 4         | 9.76%   |
| Micron Technology                       | 3         | 7.32%   |
| Phison Electronics                      | 2         | 4.88%   |
| AMD                                     | 2         | 4.88%   |
| Yangtze Memory Technologies             | 1         | 2.44%   |
| Toshiba America Info Systems            | 1         | 2.44%   |
| SK hynix                                | 1         | 2.44%   |
| Silicon Motion                          | 1         | 2.44%   |
| Kingston Technology Company             | 1         | 2.44%   |
| Jiangsu Xinsheng Intelligent Technology | 1         | 2.44%   |
| Hefei DATANG Storage Technology         | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 9.52%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller             | 4         | 9.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 3         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 7.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 4.76%   |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 4.76%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 4.76%   |
| Yangtze Memory ZHITAI TiPlus7100                                             | 1         | 2.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 2.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.38%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 2.38%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                        | 1         | 2.38%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.38%   |
| Samsung NVMe SSD Controller 980                                              | 1         | 2.38%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 2.38%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 2.38%   |
| Jiangsu Xinsheng Intelligent Non-Volatile memory controller                  | 1         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 2.38%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                    | 1         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.38%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                                | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 21        | 55.26%  |
| SATA | 15        | 39.47%  |
| RAID | 1         | 2.63%   |
| IDE  | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 18        | 56.25%  |
| Phytium | 7         | 21.88%  |
| AMD     | 5         | 15.63%  |
| ARM     | 2         | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Phytium FT2000/4                        | 2         | 6.25%   |
| Phytium FT-2000/4                       | 2         | 6.25%   |
| Phytium D2000/8 E8C                     | 2         | 6.25%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 6.25%   |
| ARM Processor                           | 2         | 6.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 6.25%   |
| Phytium D2000/8                         | 1         | 3.13%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 3.13%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 3.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 3.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 3.13%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 3.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 3.13%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 3.13%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 3.13%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 3.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 3.13%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 3.13%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 3.13%   |
| Intel 13th Gen Core i9-13900H           | 1         | 3.13%   |
| Intel 12th Gen Core i7-12700H           | 1         | 3.13%   |
| Intel 12th Gen Core i5-1240P            | 1         | 3.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 3.13%   |
| AMD Ryzen 9 7845HX with Radeon Graphics | 1         | 3.13%   |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 3.13%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 13        | 40.63%  |
| Intel Core i7        | 5         | 15.63%  |
| Intel Core i5        | 5         | 15.63%  |
| AMD Ryzen 7          | 3         | 9.38%   |
| Intel Pentium Silver | 1         | 3.13%   |
| Intel Core m3        | 1         | 3.13%   |
| Intel Core i3        | 1         | 3.13%   |
| Intel Core 2 Duo     | 1         | 3.13%   |
| AMD Ryzen 9          | 1         | 3.13%   |
| AMD Ryzen 5          | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 10        | 31.25%  |
| 8      | 8         | 25%     |
| 2      | 7         | 21.88%  |
| 6      | 3         | 9.38%   |
| 14     | 2         | 6.25%   |
| 12     | 2         | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 90.63%  |
| 3      | 2         | 6.25%   |
| 2      | 1         | 3.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 62.5%   |
| 1      | 12        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 43.75%  |
| 0x806ec    | 2         | 6.25%   |
| 0x406e3    | 2         | 6.25%   |
| 0xa0655    | 1         | 3.13%   |
| 0x906c0    | 1         | 3.13%   |
| 0x906a3    | 1         | 3.13%   |
| 0x806ea    | 1         | 3.13%   |
| 0x806e9    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x306d4    | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x0a601203 | 1         | 3.13%   |
| 0x0a50000d | 1         | 3.13%   |
| 0x0a50000c | 1         | 3.13%   |
| 0x0a50000b | 1         | 3.13%   |
| 0x0a404102 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 13        | 40.63%  |
| KabyLake         | 5         | 15.63%  |
| Zen 3            | 3         | 9.38%   |
| Skylake          | 2         | 6.25%   |
| Haswell          | 2         | 6.25%   |
| Alderlake Hybrid | 2         | 6.25%   |
| Tremont          | 1         | 3.13%   |
| SandyBridge      | 1         | 3.13%   |
| Penryn           | 1         | 3.13%   |
| CometLake        | 1         | 3.13%   |
| Broadwell        | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 46.15%  |
| AMD                      | 12        | 30.77%  |
| Nvidia                   | 8         | 20.51%  |
| Jingjia Microelectronics | 1         | 2.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 7.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 7.69%   |
| Intel UHD Graphics 620                                                                | 2         | 5.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 5.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 5.13%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 5.13%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 2         | 5.13%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 2.56%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 2.56%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 2.56%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 1         | 2.56%   |
| Jingjia Microelectronics JM7200 Series GPU                                            | 1         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.56%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 2.56%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 2.56%   |
| Intel Iris Graphics 6100                                                              | 1         | 2.56%   |
| Intel Iris Graphics 540                                                               | 1         | 2.56%   |
| Intel HD Graphics 620                                                                 | 1         | 2.56%   |
| Intel HD Graphics 515                                                                 | 1         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 2.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.56%   |
| AMD Rembrandt [Radeon 680M]                                                           | 1         | 2.56%   |
| AMD Raphael                                                                           | 1         | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 2.56%   |
| AMD Caicos                                                                            | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 12        | 37.5%   |
| 1 x AMD                      | 8         | 25%     |
| Intel + Nvidia               | 4         | 12.5%   |
| AMD + Nvidia                 | 3         | 9.38%   |
| Other                        | 2         | 6.25%   |
| 1 x Nvidia                   | 1         | 3.13%   |
| 1 x Jingjia Microelectronics | 1         | 3.13%   |
| Intel + AMD                  | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 24        | 75%     |
| Proprietary | 5         | 15.63%  |
| Unknown     | 3         | 9.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 56.25%  |
| 1.01-2.0   | 8         | 25%     |
| 0.51-1.0   | 2         | 6.25%   |
| 0.01-0.5   | 2         | 6.25%   |
| 5.01-6.0   | 1         | 3.13%   |
| 3.01-4.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 7         | 19.44%  |
| Dell                 | 4         | 11.11%  |
| CSO                  | 4         | 11.11%  |
| LG Display           | 3         | 8.33%   |
| Lenovo               | 3         | 8.33%   |
| Chimei Innolux       | 3         | 8.33%   |
| Xiaomi               | 2         | 5.56%   |
| AOC                  | 2         | 5.56%   |
| Samsung Electronics  | 1         | 2.78%   |
| KIG                  | 1         | 2.78%   |
| JDI                  | 1         | 2.78%   |
| CPT                  | 1         | 2.78%   |
| BenQ                 | 1         | 2.78%   |
| AU Optronics         | 1         | 2.78%   |
| Apple                | 1         | 2.78%   |
| Ancor Communications | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 2         | 5.56%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 2         | 5.56%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 2.78%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 2.78%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 2.78%   |
| Lenovo LEN T2224rbA LEN60EA 1920x1080 477x268mm 21.5-inch             | 1         | 2.78%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 2.78%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 2.78%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 2.78%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 2.78%   |
| Dell 1704FPT DEL4005 1280x1024 338x270mm 17.0-inch                    | 1         | 2.78%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 1         | 2.78%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 2.78%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 2.78%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 2.78%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 2.78%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE0A0A 2160x1440 233x155mm 11.0-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 2.78%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 2.78%   |
| BenQ LCD Monitor G2400W 1920x1200                                     | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 1         | 2.78%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 2.78%   |
| AOC Q27B3MA AOC2703 2560x1440 597x336mm 27.0-inch                     | 1         | 2.78%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 2.78%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 41.18%  |
| 2560x1600         | 4         | 11.76%  |
| 3840x2160 (4K)    | 3         | 8.82%   |
| 1366x768 (WXGA)   | 2         | 5.88%   |
| 3840x2400         | 1         | 2.94%   |
| 3000x2000         | 1         | 2.94%   |
| 2880x1800         | 1         | 2.94%   |
| 2880x1620         | 1         | 2.94%   |
| 2560x1440 (QHD)   | 1         | 2.94%   |
| 2240x1400         | 1         | 2.94%   |
| 2160x1440         | 1         | 2.94%   |
| 1920x1200 (WUXGA) | 1         | 2.94%   |
| 1600x900 (HD+)    | 1         | 2.94%   |
| 1280x800 (WXGA)   | 1         | 2.94%   |
| 1280x1024 (SXGA)  | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 25%     |
| 16      | 4         | 11.11%  |
| 14      | 4         | 11.11%  |
| 27      | 3         | 8.33%   |
| 65      | 2         | 5.56%   |
| 24      | 2         | 5.56%   |
| 23      | 2         | 5.56%   |
| 17      | 2         | 5.56%   |
| 15      | 2         | 5.56%   |
| 12      | 2         | 5.56%   |
| 22      | 1         | 2.78%   |
| 21      | 1         | 2.78%   |
| 11      | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 38.89%  |
| 201-300     | 9         | 25%     |
| 501-600     | 7         | 19.44%  |
| 401-500     | 2         | 5.56%   |
| 1001-1500   | 2         | 5.56%   |
| 351-400     | 1         | 2.78%   |
| Unknown     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 20        | 62.5%   |
| 16/10   | 8         | 25%     |
| 3/2     | 2         | 6.25%   |
| 5/4     | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 25%     |
| 71-80          | 5         | 13.89%  |
| 201-250        | 5         | 13.89%  |
| 111-120        | 4         | 11.11%  |
| 301-350        | 3         | 8.33%   |
| More than 1000 | 2         | 5.56%   |
| 101-110        | 2         | 5.56%   |
| 61-70          | 1         | 2.78%   |
| 51-60          | 1         | 2.78%   |
| 151-200        | 1         | 2.78%   |
| 141-150        | 1         | 2.78%   |
| 121-130        | 1         | 2.78%   |
| Unknown        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 11        | 32.35%  |
| 121-160       | 7         | 20.59%  |
| 51-100        | 7         | 20.59%  |
| More than 240 | 3         | 8.82%   |
| 101-120       | 3         | 8.82%   |
| 1-50          | 2         | 5.88%   |
| Unknown       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 69.7%   |
| 2     | 7         | 21.21%  |
| 0     | 3         | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 17        | 38.64%  |
| Intel                      | 16        | 36.36%  |
| MediaTek                   | 3         | 6.82%   |
| ASIX Electronics           | 3         | 6.82%   |
| Huawei Technologies        | 2         | 4.55%   |
| Quectel Wireless Solutions | 1         | 2.27%   |
| ICS Advent                 | 1         | 2.27%   |
| Broadcom                   | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 17.65%  |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 3.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 3.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 3.92%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.92%   |
| Intel Wireless 8260                                               | 2         | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 3.92%   |
| Huawei Network controller                                         | 2         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.96%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.96%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 1.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.96%   |
| Intel Wireless 7260                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 1.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.96%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.96%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.96%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.96%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 15        | 55.56%  |
| Realtek Semiconductor      | 7         | 25.93%  |
| MediaTek                   | 3         | 11.11%  |
| Quectel Wireless Solutions | 1         | 3.7%    |
| Broadcom                   | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 7.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 7.41%   |
| Intel Wireless 8265 / 8275                                    | 2         | 7.41%   |
| Intel Wireless 8260                                           | 2         | 7.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 7.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.7%    |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 3.7%    |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 3.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 3.7%    |
| Intel Wireless 7260                                           | 1         | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 3.7%    |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                           | 1         | 3.7%    |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 3.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 3.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 3.7%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 59.09%  |
| Intel                 | 5         | 22.73%  |
| ASIX Electronics      | 3         | 13.64%  |
| ICS Advent            | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 40.91%  |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 13.64%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.55%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 4.55%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.55%   |
| ICS Advent 10/100M LAN                                            | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 54.17%  |
| Ethernet | 20        | 41.67%  |
| Unknown  | 2         | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 76.67%  |
| Ethernet | 7         | 23.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 14        | 43.75%  |
| 1     | 14        | 43.75%  |
| 0     | 4         | 12.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 78.13%  |
| Yes  | 7         | 21.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 56%     |
| Realtek Semiconductor           | 3         | 12%     |
| Foxconn / Hon Hai               | 3         | 12%     |
| IMC Networks                    | 2         | 8%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Broadcom                        | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 20%     |
| Intel Bluetooth Device                             | 3         | 12%     |
| Intel AX201 Bluetooth                              | 3         | 12%     |
| Realtek Bluetooth Radio                            | 2         | 8%      |
| IMC Networks Bluetooth Radio                       | 2         | 8%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 8%      |
| Realtek 802.11n WLAN Adapter                       | 1         | 4%      |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 4%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 1         | 4%      |
| Intel AX210 Bluetooth                              | 1         | 4%      |
| Intel AX200 Bluetooth                              | 1         | 4%      |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 4%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 4%      |
| Apple Bluetooth Host Controller                    | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 18        | 47.37%  |
| AMD                                          | 11        | 28.95%  |
| Nvidia                                       | 7         | 18.42%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 5.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 11.63%  |
| AMD Family 17h/19h HD Audio Controller                                            | 5         | 11.63%  |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 6.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 6.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 6.98%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 4.65%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 4.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 4.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 2.33%   |
| Nvidia Audio device                                                               | 1         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1         | 2.33%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 2.33%   |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1         | 2.33%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 2.33%   |
| Intel Broadwell-U Audio Controller                                                | 1         | 2.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 2.33%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1         | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 2.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 32.14%  |
| SK hynix            | 6         | 21.43%  |
| Samsung Electronics | 6         | 21.43%  |
| Elpida              | 2         | 7.14%   |
| UNILC               | 1         | 3.57%   |
| UniIC               | 1         | 3.57%   |
| Nanya Technology    | 1         | 3.57%   |
| Longsys             | 1         | 3.57%   |
| Unknown             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM Not Set 8192MB DIMM DDR4 2668MT/s                     | 2         | 6.9%    |
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 3.45%   |
| UniIC RAM SCC08GS03H1F1C-26V 8192MB SODIMM DDR4 2666MT/s         | 1         | 3.45%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 3.45%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 3.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 3.45%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 3.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.45%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.45%   |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 3.45%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 3.45%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.45%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.45%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 3.45%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                   | 1         | 3.45%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 3.45%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 3.45%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips 6400MT/s        | 1         | 3.45%   |
| Micron RAM MT62F1G32D4DR-031 8GB Row Of Chips LPDDR5 6400MT/s    | 1         | 3.45%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 3.45%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 3.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 3.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.45%   |
| Longsys RAM FD4AU3200C8GTG 8192MB DIMM DDR4 3200MT/s             | 1         | 3.45%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 3.45%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.45%   |
| Unknown                                                          | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 48.28%  |
| LPDDR4  | 4         | 13.79%  |
| LPDDR5  | 3         | 10.34%  |
| LPDDR3  | 3         | 10.34%  |
| DDR3    | 3         | 10.34%  |
| DDR5    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 51.85%  |
| Row Of Chips | 8         | 29.63%  |
| DIMM         | 5         | 18.52%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 19        | 70.37%  |
| 4096  | 4         | 14.81%  |
| 2048  | 3         | 11.11%  |
| 16384 | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 5         | 17.86%  |
| 6400  | 3         | 10.71%  |
| 2668  | 3         | 10.71%  |
| 2667  | 3         | 10.71%  |
| 1867  | 3         | 10.71%  |
| 4266  | 2         | 7.14%   |
| 2666  | 2         | 7.14%   |
| 4800  | 1         | 3.57%   |
| 4267  | 1         | 3.57%   |
| 2400  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1600  | 1         | 3.57%   |
| 1067  | 1         | 3.57%   |
| 1066  | 1         | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung M2020 Series    | 1         | 50%     |
| HP DeskJet F4200 series | 1         | 50%     |

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
| Chicony Electronics                    | 6         | 27.27%  |
| IMC Networks                           | 5         | 22.73%  |
| Unknown (0000066029)                   | 2         | 9.09%   |
| Microdia                               | 2         | 9.09%   |
| Syntek                                 | 1         | 4.55%   |
| Sonix Technology                       | 1         | 4.55%   |
| Realtek Semiconductor                  | 1         | 4.55%   |
| Luxvisions Innotech Limited            | 1         | 4.55%   |
| Lenovo                                 | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |
| BL012030059711690428                   | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 3         | 13.64%  |
| Unknown (0000066029) HD Camera                      | 2         | 9.09%   |
| Syntek Integrated Camera                            | 1         | 4.55%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 4.55%   |
| Realtek Integrated_Webcam_HD                        | 1         | 4.55%   |
| Microdia USB2.0 Camera                              | 1         | 4.55%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.55%   |
| Lenovo Integrated Webcam                            | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 4.55%   |
| IMC Networks Integrated RGB Camera                  | 1         | 4.55%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 4.55%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 4.55%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 4.55%   |
| Chicony Integrated Camera                           | 1         | 4.55%   |
| Chicony HP HD Camera                                | 1         | 4.55%   |
| Chicony EasyCamera                                  | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 4.55%   |
| BL012030059711690428 Integrated Camera              | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 4         | 66.67%  |
| Validity Sensors | 1         | 16.67%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 16.67%  |
| Synaptics UWP WBDI Device                                 | 1         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 16.67%  |
| AuthenTec AES2810                                         | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 65.63%  |
| 1     | 9         | 28.13%  |
| 2     | 2         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 46.15%  |
| Graphics card         | 3         | 23.08%  |
| Multimedia controller | 2         | 15.38%  |
| Net/wireless          | 1         | 7.69%   |
| Camera                | 1         | 7.69%   |

