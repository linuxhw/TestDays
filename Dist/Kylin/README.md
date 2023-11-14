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

Total: 42

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo    | Yoga 14cACN 2021 82N7       | Convertible | [4f7bb0e30b](https://linux-hardware.org/?probe=4f7bb0e30b) | Nov 06, 2023 |
| ASUSTek   | ROG Flow X13 GV301RE_GV3... | Convertible | [6b3d70f496](https://linux-hardware.org/?probe=6b3d70f496) | Nov 01, 2023 |
| HUAWEI    | KLVDZ-WXX9                  | Notebook    | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| ASUSTek   | TUF Gaming FX505GT          | Notebook    | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
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
| Kylin V10   | 34        | 94.44%  |
| Kylin V10.1 | 2         | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Kylin | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.18-35-generic       | 5         | 13.51%  |
| 5.19.0-32-generic       | 3         | 8.11%   |
| 6.1.0-13-amd64          | 2         | 5.41%   |
| 5.4.18-15-generic       | 2         | 5.41%   |
| 5.19.0-45-generic       | 2         | 5.41%   |
| 6.2.0-33-generic        | 1         | 2.7%    |
| 6.2.0-32-generic        | 1         | 2.7%    |
| 6.2.0-23-generic        | 1         | 2.7%    |
| 6.2.0-21-generic        | 1         | 2.7%    |
| 5.4.96-7-kr9a0          | 1         | 2.7%    |
| 5.4.18-95-generic       | 1         | 2.7%    |
| 5.4.18-85-generic       | 1         | 2.7%    |
| 5.4.18-27-generic       | 1         | 2.7%    |
| 5.4.0-155-generic       | 1         | 2.7%    |
| 5.19.0-46-generic       | 1         | 2.7%    |
| 5.19.0-41-generic       | 1         | 2.7%    |
| 5.15.0-88-generic       | 1         | 2.7%    |
| 5.15.0-73-generic       | 1         | 2.7%    |
| 5.15.0-69-generic       | 1         | 2.7%    |
| 5.15.0-56-generic       | 1         | 2.7%    |
| 5.10.46-marvis          | 1         | 2.7%    |
| 5.10.0-3-generic        | 1         | 2.7%    |
| 5.10.0-23-amd64         | 1         | 2.7%    |
| 5.10.0-20-amd64         | 1         | 2.7%    |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 2.7%    |
| 4.19.71-14-kr990        | 1         | 2.7%    |
| 4.19.260-atzlinux-ft9   | 1         | 2.7%    |
| 4.19.237-atzlinux-ft8   | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.18   | 10        | 27.03%  |
| 5.19.0   | 7         | 18.92%  |
| 6.2.0    | 4         | 10.81%  |
| 5.15.0   | 4         | 10.81%  |
| 5.10.0   | 4         | 10.81%  |
| 6.1.0    | 2         | 5.41%   |
| 5.4.96   | 1         | 2.7%    |
| 5.4.0    | 1         | 2.7%    |
| 5.10.46  | 1         | 2.7%    |
| 4.19.71  | 1         | 2.7%    |
| 4.19.260 | 1         | 2.7%    |
| 4.19.237 | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 12        | 33.33%  |
| 5.19    | 7         | 19.44%  |
| 5.10    | 5         | 13.89%  |
| 6.2     | 4         | 11.11%  |
| 5.15    | 4         | 11.11%  |
| 6.1     | 2         | 5.56%   |
| 4.19    | 2         | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 27        | 75%     |
| aarch64 | 9         | 25%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| UKUI            | 15        | 41.67%  |
| GNOME           | 14        | 38.89%  |
| XFCE            | 2         | 5.56%   |
| KDE5            | 2         | 5.56%   |
| X-Cinnamon      | 1         | 2.78%   |
| Unity           | 1         | 2.78%   |
| GNOME Flashback | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 25        | 67.57%  |
| Wayland | 9         | 24.32%  |
| Tty     | 3         | 8.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 17        | 47.22%  |
| GDM3    | 14        | 38.89%  |
| TDM     | 2         | 5.56%   |
| SDDM    | 2         | 5.56%   |
| GDM     | 1         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| zh_CN | 28        | 77.78%  |
| en_US | 5         | 13.89%  |
| en_HK | 1         | 2.78%   |
| en_CA | 1         | 2.78%   |
| C     | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 86.11%  |
| BIOS | 5         | 13.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 31        | 86.11%  |
| Tmpfs   | 2         | 5.56%   |
| Overlay | 2         | 5.56%   |
| Zfs     | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 34        | 94.44%  |
| MBR     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 72.97%  |
| Yes       | 10        | 27.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 66.67%  |
| Yes       | 12        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 30.56%  |
| ASUSTek Computer    | 5         | 13.89%  |
| HUAWEI              | 4         | 11.11%  |
| Phytium             | 3         | 8.33%   |
| Hewlett-Packard     | 3         | 8.33%   |
| GreatWall           | 3         | 8.33%   |
| Dell                | 3         | 8.33%   |
| Timi                | 1         | 2.78%   |
| THTF                | 1         | 2.78%   |
| Gigabyte Technology | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Phytium FT2000/4                             | 2         | 5.56%   |
| Unknown                                      | 2         | 5.56%   |
| Timi TM1612                                  | 1         | 2.78%   |
| THTF CR F860-T1                              | 1         | 2.78%   |
| Phytium FT-2000/4                            | 1         | 2.78%   |
| Lenovo Yoga 14cACN 2021 82N7                 | 1         | 2.78%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 2.78%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 2.78%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 2.78%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 2.78%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 2.78%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 2.78%   |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 2.78%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 2.78%   |
| Lenovo Legion R9000P2021H 82JQ               | 1         | 2.78%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 2.78%   |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 2.78%   |
| HUAWEI MACH-WX9                              | 1         | 2.78%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 2.78%   |
| HUAWEI KLVDZ-WXX9                            | 1         | 2.78%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 2.78%   |
| HP Tablet 11-be0xxx                          | 1         | 2.78%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 2.78%   |
| GreatWall GW-XXXXXX-XXX                      | 1         | 2.78%   |
| Gigabyte Z97X-SLI                            | 1         | 2.78%   |
| Dell Vostro 5880                             | 1         | 2.78%   |
| Dell Vostro 3350                             | 1         | 2.78%   |
| Dell Inspiron 5468                           | 1         | 2.78%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 2.78%   |
| ASUS UX31LA                                  | 1         | 2.78%   |
| ASUS TUF Gaming FX505GT                      | 1         | 2.78%   |
| ASUS ROG Strix G713PV_G713PV                 | 1         | 2.78%   |
| ASUS ROG Flow X13 GV301RE_GV301RE            | 1         | 2.78%   |
| Apple MacBookPro12,1                         | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 5         | 13.89%  |
| Phytium FT2000          | 2         | 5.56%   |
| Lenovo Legion           | 2         | 5.56%   |
| Dell Vostro             | 2         | 5.56%   |
| ASUS ROG                | 2         | 5.56%   |
| Unknown                 | 2         | 5.56%   |
| Timi TM1612             | 1         | 2.78%   |
| THTF CR                 | 1         | 2.78%   |
| Phytium FT-2000         | 1         | 2.78%   |
| Lenovo Yoga             | 1         | 2.78%   |
| Lenovo XiaoXinPro       | 1         | 2.78%   |
| Lenovo ThinkBook        | 1         | 2.78%   |
| Lenovo IdeaPad          | 1         | 2.78%   |
| HUAWEI QingYun          | 1         | 2.78%   |
| HUAWEI MACH-WX9         | 1         | 2.78%   |
| HUAWEI L410             | 1         | 2.78%   |
| HUAWEI KLVDZ-WXX9       | 1         | 2.78%   |
| HP ZHAN                 | 1         | 2.78%   |
| HP Tablet               | 1         | 2.78%   |
| HP EliteBook            | 1         | 2.78%   |
| GreatWall GW-XXXXXX-XXX | 1         | 2.78%   |
| Gigabyte Z97X-SLI       | 1         | 2.78%   |
| Dell Inspiron           | 1         | 2.78%   |
| ASUS VivoBook           | 1         | 2.78%   |
| ASUS UX31LA             | 1         | 2.78%   |
| ASUS TUF                | 1         | 2.78%   |
| Apple MacBookPro12      | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 10        | 27.78%  |
| 2022    | 6         | 16.67%  |
| 2020    | 4         | 11.11%  |
| 2016    | 3         | 8.33%   |
| 2014    | 3         | 8.33%   |
| Unknown | 3         | 8.33%   |
| 2018    | 2         | 5.56%   |
| 2023    | 1         | 2.78%   |
| 2015    | 1         | 2.78%   |
| 2012    | 1         | 2.78%   |
| 2011    | 1         | 2.78%   |
| 2008    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 26        | 72.22%  |
| Server         | 3         | 8.33%   |
| Convertible    | 2         | 5.56%   |
| Desktop        | 2         | 5.56%   |
| System on chip | 1         | 2.78%   |
| Tablet         | 1         | 2.78%   |
| All in one     | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 32        | 88.89%  |
| Enabled  | 4         | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 12        | 33.33%  |
| 4.01-8.0    | 8         | 22.22%  |
| 16.01-24.0  | 7         | 19.44%  |
| 3.01-4.0    | 6         | 16.67%  |
| 32.01-64.0  | 1         | 2.78%   |
| 24.01-32.0  | 1         | 2.78%   |
| 64.01-256.0 | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 12        | 32.43%  |
| 1.01-2.0  | 9         | 24.32%  |
| 2.01-3.0  | 7         | 18.92%  |
| 4.01-8.0  | 4         | 10.81%  |
| 8.01-16.0 | 3         | 8.11%   |
| 0.51-1.0  | 2         | 5.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 66.67%  |
| 2      | 8         | 22.22%  |
| 4      | 2         | 5.56%   |
| 3      | 2         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 63.89%  |
| No        | 13        | 36.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 80.56%  |
| No        | 7         | 19.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| China     | 29        | 80.56%  |
| Hong Kong | 3         | 8.33%   |
| USA       | 1         | 2.78%   |
| Taiwan    | 1         | 2.78%   |
| Japan     | 1         | 2.78%   |
| Canada    | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Tianjin     | 3         | 8.33%   |
| Shenzhen    | 3         | 8.33%   |
| Beijing     | 3         | 8.33%   |
| Shanghai    | 2         | 5.56%   |
| Jinrongjie  | 2         | 5.56%   |
| Jinan       | 2         | 5.56%   |
| Haidian     | 2         | 5.56%   |
| Central     | 2         | 5.56%   |
| Zhongshan   | 1         | 2.78%   |
| Zhengzhou   | 1         | 2.78%   |
| Xuhui       | 1         | 2.78%   |
| Xiaolou     | 1         | 2.78%   |
| Xi'an       | 1         | 2.78%   |
| Tokyo       | 1         | 2.78%   |
| Shizishan   | 1         | 2.78%   |
| Putuo       | 1         | 2.78%   |
| Mong Kok    | 1         | 2.78%   |
| Markham     | 1         | 2.78%   |
| Los Angeles | 1         | 2.78%   |
| Kunming     | 1         | 2.78%   |
| Harbin      | 1         | 2.78%   |
| Guangzhou   | 1         | 2.78%   |
| Changsha    | 1         | 2.78%   |
| Chancheng   | 1         | 2.78%   |
| Banqiao     | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 23.91%  |
| Toshiba             | 4         | 4      | 8.7%    |
| SanDisk             | 4         | 4      | 8.7%    |
| WDC                 | 3         | 3      | 6.52%   |
| Micron Technology   | 3         | 3      | 6.52%   |
| Unknown             | 2         | 2      | 4.35%   |
| Seagate             | 2         | 2      | 4.35%   |
| Phison              | 2         | 2      | 4.35%   |
| FORESEE             | 2         | 3      | 4.35%   |
| ZX1 1TB             | 1         | 1      | 2.17%   |
| ZHITAI              | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| Pear 2TB            | 1         | 1      | 2.17%   |
| Lenovo              | 1         | 1      | 2.17%   |
| Kingston            | 1         | 1      | 2.17%   |
| Kingchuxing         | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| HISI                | 1         | 4      | 2.17%   |
| Hikvision           | 1         | 1      | 2.17%   |
| Hewlett-Packard     | 1         | 1      | 2.17%   |
| FC-1307             | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 1TB                         | 2         | 4.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 4.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 4.26%   |
| Micron MTFDKBA512TFH 512GB                         | 2         | 4.26%   |
| FORESEE 64GB SSD                                   | 2         | 4.26%   |
| ZX1 1TB Disk 1TB                                   | 1         | 2.13%   |
| ZHITAI TiPlus7100 2TB                              | 1         | 2.13%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB               | 1         | 2.13%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB               | 1         | 2.13%   |
| WDC PC SN530 SDBPNPZ-256G                          | 1         | 2.13%   |
| Unknown NVMe SSD Drive 512GB                       | 1         | 2.13%   |
| Unknown NVMe SSD Drive 256GB                       | 1         | 2.13%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 2.13%   |
| Toshiba MK3261GSYN 320GB                           | 1         | 2.13%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                  | 1         | 2.13%   |
| Toshiba DT01ACA100 1TB                             | 1         | 2.13%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 1         | 2.13%   |
| Seagate ST9500325AS 500GB                          | 1         | 2.13%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1         | 2.13%   |
| SanDisk SD6SP1M256G1102 256GB SSD                  | 1         | 2.13%   |
| SanDisk NVMe SSD Drive 256GB                       | 1         | 2.13%   |
| Samsung PM991 NVMe 256GB                           | 1         | 2.13%   |
| Samsung MZVLW256HEHP-000L2 256GB                   | 1         | 2.13%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 1         | 2.13%   |
| Samsung MZVLB512HAJQ-00000 512GB                   | 1         | 2.13%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                   | 1         | 2.13%   |
| Samsung MZNTY128HDHP-00000 128GB SSD               | 1         | 2.13%   |
| Samsung KLUFG8RHDA-B2D1 512GB                      | 1         | 2.13%   |
| Samsung KLUFG8RHDA-B2D1 1GB                        | 1         | 2.13%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G             | 1         | 2.13%   |
| Phison 511BS0512HB 512GB                           | 1         | 2.13%   |
| Pear 2TB Disk 2TB                                  | 1         | 2.13%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 1         | 2.13%   |
| Lenovo SSD SL500 240G                              | 1         | 2.13%   |
| Kingston OM3PDP3128B-AH 128GB                      | 1         | 2.13%   |
| Kingchuxing SSD 128GB                              | 1         | 2.13%   |
| Intel SSDPEKNW512G8 512GB                          | 1         | 2.13%   |
| HISI THR920GFCV100HAE 256GB                        | 1         | 2.13%   |
| Hikvision HS-SSD-E2000L 512G                       | 1         | 2.13%   |
| HP SSD EX950 1TB                                   | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 50%     |
| Seagate  | 2         | 2      | 33.33%  |
| Pear 2TB | 1         | 1      | 16.67%  |

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
| NVMe    | 25        | 30     | 59.52%  |
| SSD     | 9         | 16     | 21.43%  |
| HDD     | 6         | 6      | 14.29%  |
| Unknown | 2         | 2      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 25        | 30     | 59.52%  |
| SATA | 15        | 22     | 35.71%  |
| SAS  | 2         | 2      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 17     | 68.75%  |
| 0.51-1.0   | 4         | 4      | 25%     |
| 1.01-2.0   | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 12        | 32.43%  |
| 51-100     | 8         | 21.62%  |
| 101-250    | 7         | 18.92%  |
| 501-1000   | 5         | 13.51%  |
| 1001-2000  | 3         | 8.11%   |
| 21-50      | 1         | 2.7%    |
| 1-20       | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 11        | 30.56%  |
| 51-100   | 8         | 22.22%  |
| 1-20     | 7         | 19.44%  |
| 101-250  | 5         | 13.89%  |
| 251-500  | 3         | 8.33%   |
| 501-1000 | 2         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Works    | 27        | 31     | 67.5%   |
| Detected | 12        | 22     | 30%     |
| Malfunc  | 1         | 1      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 10        | 21.74%  |
| Intel                                   | 10        | 21.74%  |
| Sandisk                                 | 6         | 13.04%  |
| Marvell Technology Group                | 4         | 8.7%    |
| Phison Electronics                      | 3         | 6.52%   |
| Micron Technology                       | 3         | 6.52%   |
| AMD                                     | 3         | 6.52%   |
| Yangtze Memory Technologies             | 1         | 2.17%   |
| Toshiba America Info Systems            | 1         | 2.17%   |
| SK hynix                                | 1         | 2.17%   |
| Silicon Motion                          | 1         | 2.17%   |
| Kingston Technology Company             | 1         | 2.17%   |
| Jiangsu Xinsheng Intelligent Technology | 1         | 2.17%   |
| Hefei DATANG Storage Technology         | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 8.33%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller             | 4         | 8.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 3         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 6.25%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 2         | 4.17%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 2         | 4.17%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 4.17%   |
| Yangtze Memory ZHITAI TiPlus7100                                             | 1         | 2.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 2.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.08%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.08%   |
| Sandisk WD PC SN735 NVMe SSD 1TB (DRAM-less)                                 | 1         | 2.08%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 2.08%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                        | 1         | 2.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 2.08%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.08%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 2.08%   |
| Phison E12 NVMe Controller                                                   | 1         | 2.08%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 2.08%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 2.08%   |
| Jiangsu Xinsheng Intelligent EP2000Pro PCIe 3 NVMe SSD (DRAM-less)           | 1         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 2.08%   |
| Intel SSD 660P Series                                                        | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                    | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.08%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                                | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 25        | 56.82%  |
| SATA | 17        | 38.64%  |
| RAID | 1         | 2.27%   |
| IDE  | 1         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 20        | 55.56%  |
| Phytium | 7         | 19.44%  |
| AMD     | 7         | 19.44%  |
| ARM     | 2         | 5.56%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Phytium FT2000/4                        | 2         | 5.56%   |
| Phytium FT-2000/4                       | 2         | 5.56%   |
| Phytium D2000/8 E8C                     | 2         | 5.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 5.56%   |
| ARM Processor                           | 2         | 5.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 5.56%   |
| Phytium D2000/8                         | 1         | 2.78%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 2.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 2.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 2.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 2.78%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 2.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 2.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 2.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 2.78%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 2.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 2.78%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 2.78%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 2.78%   |
| Intel 13th Gen Core i9-13900H           | 1         | 2.78%   |
| Intel 12th Gen Core i7-12700H           | 1         | 2.78%   |
| Intel 12th Gen Core i5-1240P            | 1         | 2.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 2.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 2.78%   |
| AMD Ryzen 9 7845HX with Radeon Graphics | 1         | 2.78%   |
| AMD Ryzen 9 6900HS with Radeon Graphics | 1         | 2.78%   |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 2.78%   |
| AMD Ryzen 7 5800U with Radeon Graphics  | 1         | 2.78%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 14        | 38.89%  |
| Intel Core i7        | 6         | 16.67%  |
| Intel Core i5        | 5         | 13.89%  |
| AMD Ryzen 7          | 4         | 11.11%  |
| AMD Ryzen 9          | 2         | 5.56%   |
| Intel Pentium Silver | 1         | 2.78%   |
| Intel Core m3        | 1         | 2.78%   |
| Intel Core i3        | 1         | 2.78%   |
| Intel Core 2 Duo     | 1         | 2.78%   |
| AMD Ryzen 5          | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 11        | 30.56%  |
| 8      | 10        | 27.78%  |
| 2      | 7         | 19.44%  |
| 6      | 4         | 11.11%  |
| 14     | 2         | 5.56%   |
| 12     | 2         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 91.67%  |
| 3      | 2         | 5.56%   |
| 2      | 1         | 2.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 24        | 66.67%  |
| 1      | 12        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 38.89%  |
| 0x806ec    | 2         | 5.56%   |
| 0x406e3    | 2         | 5.56%   |
| 0x0a50000c | 2         | 5.56%   |
| 0x0a404102 | 2         | 5.56%   |
| 0xa0655    | 1         | 2.78%   |
| 0x906ea    | 1         | 2.78%   |
| 0x906c0    | 1         | 2.78%   |
| 0x906a3    | 1         | 2.78%   |
| 0x806ea    | 1         | 2.78%   |
| 0x806e9    | 1         | 2.78%   |
| 0x806c1    | 1         | 2.78%   |
| 0x40651    | 1         | 2.78%   |
| 0x306d4    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x1067a    | 1         | 2.78%   |
| 0x0a601203 | 1         | 2.78%   |
| 0x0a50000d | 1         | 2.78%   |
| 0x0a50000b | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 14        | 38.89%  |
| KabyLake         | 6         | 16.67%  |
| Zen 3            | 4         | 11.11%  |
| Skylake          | 2         | 5.56%   |
| Haswell          | 2         | 5.56%   |
| Alderlake Hybrid | 2         | 5.56%   |
| Tremont          | 1         | 2.78%   |
| TigerLake        | 1         | 2.78%   |
| SandyBridge      | 1         | 2.78%   |
| Penryn           | 1         | 2.78%   |
| CometLake        | 1         | 2.78%   |
| Broadwell        | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 45.45%  |
| AMD                      | 14        | 31.82%  |
| Nvidia                   | 9         | 20.45%  |
| Jingjia Microelectronics | 1         | 2.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 4         | 9.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 6.82%   |
| Intel UHD Graphics 620                                                                | 2         | 4.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 4.55%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 4.55%   |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 4.55%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 4.55%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 2         | 4.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 2.27%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 2.27%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 2.27%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 2.27%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 1         | 2.27%   |
| Jingjia Microelectronics JM7200 Series GPU                                            | 1         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 2.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.27%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 2.27%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 2.27%   |
| Intel Iris Graphics 6100                                                              | 1         | 2.27%   |
| Intel Iris Graphics 540                                                               | 1         | 2.27%   |
| Intel HD Graphics 620                                                                 | 1         | 2.27%   |
| Intel HD Graphics 515                                                                 | 1         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 2.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 2.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.27%   |
| AMD Raphael                                                                           | 1         | 2.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 2.27%   |
| AMD Caicos                                                                            | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 13        | 36.11%  |
| 1 x AMD                      | 10        | 27.78%  |
| Intel + Nvidia               | 5         | 13.89%  |
| AMD + Nvidia                 | 3         | 8.33%   |
| Other                        | 2         | 5.56%   |
| 1 x Nvidia                   | 1         | 2.78%   |
| 1 x Jingjia Microelectronics | 1         | 2.78%   |
| Intel + AMD                  | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 75%     |
| Proprietary | 5         | 13.89%  |
| Unknown     | 4         | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 55.56%  |
| 1.01-2.0   | 9         | 25%     |
| 3.01-4.0   | 2         | 5.56%   |
| 0.51-1.0   | 2         | 5.56%   |
| 0.01-0.5   | 2         | 5.56%   |
| 5.01-6.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 9         | 23.08%  |
| Dell                 | 4         | 10.26%  |
| CSO                  | 4         | 10.26%  |
| LG Display           | 3         | 7.69%   |
| Lenovo               | 3         | 7.69%   |
| Chimei Innolux       | 3         | 7.69%   |
| Xiaomi               | 2         | 5.13%   |
| AOC                  | 2         | 5.13%   |
| Samsung Electronics  | 1         | 2.56%   |
| PANDA                | 1         | 2.56%   |
| KIG                  | 1         | 2.56%   |
| JDI                  | 1         | 2.56%   |
| CPT                  | 1         | 2.56%   |
| BenQ                 | 1         | 2.56%   |
| AU Optronics         | 1         | 2.56%   |
| Apple                | 1         | 2.56%   |
| Ancor Communications | 1         | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 2         | 5.13%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 2         | 5.13%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 2.56%   |
| PANDA LCD Monitor NCP0042 1920x1080 344x194mm 15.5-inch               | 1         | 2.56%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 2.56%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 2.56%   |
| Lenovo LEN T2224rbA LEN60EA 1920x1080 477x268mm 21.5-inch             | 1         | 2.56%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 2.56%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 2.56%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 2.56%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 2.56%   |
| Dell 1704FPT DEL4005 1280x1024 338x270mm 17.0-inch                    | 1         | 2.56%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 1         | 2.56%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 2.56%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 2.56%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 2.56%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 2.56%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0A0A 2160x1440 233x155mm 11.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0855 1920x1080 309x174mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 2.56%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 2.56%   |
| BenQ LCD Monitor G2400W 1920x1200                                     | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 1         | 2.56%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 2.56%   |
| AOC U27N3G6R4B AOC2703 3840x2160 597x336mm 27.0-inch                  | 1         | 2.56%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 2.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 43.24%  |
| 2560x1600         | 4         | 10.81%  |
| 3840x2160 (4K)    | 3         | 8.11%   |
| 2160x1440         | 2         | 5.41%   |
| 1366x768 (WXGA)   | 2         | 5.41%   |
| 3840x2400         | 1         | 2.7%    |
| 3000x2000         | 1         | 2.7%    |
| 2880x1800         | 1         | 2.7%    |
| 2880x1620         | 1         | 2.7%    |
| 2560x1440 (QHD)   | 1         | 2.7%    |
| 2240x1400         | 1         | 2.7%    |
| 1920x1200 (WUXGA) | 1         | 2.7%    |
| 1600x900 (HD+)    | 1         | 2.7%    |
| 1280x800 (WXGA)   | 1         | 2.7%    |
| 1280x1024 (SXGA)  | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 23.08%  |
| 14      | 6         | 15.38%  |
| 16      | 4         | 10.26%  |
| 27      | 3         | 7.69%   |
| 15      | 3         | 7.69%   |
| 65      | 2         | 5.13%   |
| 24      | 2         | 5.13%   |
| 23      | 2         | 5.13%   |
| 17      | 2         | 5.13%   |
| 12      | 2         | 5.13%   |
| 22      | 1         | 2.56%   |
| 21      | 1         | 2.56%   |
| 11      | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 41.03%  |
| 201-300     | 10        | 25.64%  |
| 501-600     | 7         | 17.95%  |
| 401-500     | 2         | 5.13%   |
| 1001-1500   | 2         | 5.13%   |
| 351-400     | 1         | 2.56%   |
| Unknown     | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 62.86%  |
| 16/10   | 8         | 22.86%  |
| 3/2     | 3         | 8.57%   |
| 5/4     | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 28.21%  |
| 71-80          | 5         | 12.82%  |
| 201-250        | 5         | 12.82%  |
| 111-120        | 4         | 10.26%  |
| 301-350        | 3         | 7.69%   |
| 101-110        | 3         | 7.69%   |
| More than 1000 | 2         | 5.13%   |
| 61-70          | 1         | 2.56%   |
| 51-60          | 1         | 2.56%   |
| 151-200        | 1         | 2.56%   |
| 141-150        | 1         | 2.56%   |
| 121-130        | 1         | 2.56%   |
| Unknown        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 12        | 32.43%  |
| 121-160       | 9         | 24.32%  |
| 51-100        | 7         | 18.92%  |
| More than 240 | 3         | 8.11%   |
| 101-120       | 3         | 8.11%   |
| 1-50          | 2         | 5.41%   |
| Unknown       | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 70.27%  |
| 2     | 7         | 18.92%  |
| 0     | 4         | 10.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 20        | 39.22%  |
| Intel                      | 18        | 35.29%  |
| MediaTek                   | 5         | 9.8%    |
| ASIX Electronics           | 3         | 5.88%   |
| Huawei Technologies        | 2         | 3.92%   |
| Quectel Wireless Solutions | 1         | 1.96%   |
| ICS Advent                 | 1         | 1.96%   |
| Broadcom                   | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 18.97%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 5.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 3.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 3.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 3.45%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.45%   |
| Intel Wireless 8260                                               | 2         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 3.45%   |
| Huawei Network controller                                         | 2         | 3.45%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.72%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.72%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 1.72%   |
| Intel Wireless 7260                                               | 1         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.72%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.72%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 1.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.72%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.72%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.72%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.72%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.72%   |
| ICS Advent 10/100M LAN                                            | 1         | 1.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 17        | 54.84%  |
| Realtek Semiconductor      | 7         | 22.58%  |
| MediaTek                   | 5         | 16.13%  |
| Quectel Wireless Solutions | 1         | 3.23%   |
| Broadcom                   | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 9.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 6.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 6.45%   |
| Intel Wireless 8265 / 8275                                    | 2         | 6.45%   |
| Intel Wireless 8260                                           | 2         | 6.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 6.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.23%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 3.23%   |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 3.23%   |
| Intel Wireless 7260                                           | 1         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 3.23%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 3.23%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 3.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 3.23%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 3.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 64%     |
| Intel                 | 5         | 20%     |
| ASIX Electronics      | 3         | 12%     |
| ICS Advent            | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 44%     |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 12%     |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 8%      |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4%      |
| Intel Ethernet Connection I217-V                                  | 1         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (11) I219-V                             | 1         | 4%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4%      |
| ICS Advent 10/100M LAN                                            | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 54.55%  |
| Ethernet | 23        | 41.82%  |
| Unknown  | 2         | 3.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 78.79%  |
| Ethernet | 7         | 21.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 16        | 44.44%  |
| 1     | 16        | 44.44%  |
| 0     | 4         | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 77.78%  |
| Yes  | 8         | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 55.17%  |
| Foxconn / Hon Hai               | 4         | 13.79%  |
| Realtek Semiconductor           | 3         | 10.34%  |
| IMC Networks                    | 3         | 10.34%  |
| Qualcomm Atheros Communications | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |
| Apple                           | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 17.24%  |
| Intel Bluetooth Device                             | 4         | 13.79%  |
| Intel AX201 Bluetooth                              | 4         | 13.79%  |
| Foxconn / Hon Hai Wireless_Device                  | 4         | 13.79%  |
| Realtek Bluetooth Radio                            | 2         | 6.9%    |
| IMC Networks Bluetooth Radio                       | 2         | 6.9%    |
| Realtek 802.11n WLAN Adapter                       | 1         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 3.45%   |
| Intel AX210 Bluetooth                              | 1         | 3.45%   |
| Intel AX200 Bluetooth                              | 1         | 3.45%   |
| IMC Networks Wireless_Device                       | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.45%   |
| Apple Bluetooth Host Controller                    | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 20        | 46.51%  |
| AMD                                          | 13        | 30.23%  |
| Nvidia                                       | 8         | 18.6%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 4.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 14%     |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 10%     |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 6%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 6%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 6%      |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 4%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 4%      |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 2         | 4%      |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 2%      |
| Nvidia Audio device                                                               | 1         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 2%      |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 2%      |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1         | 2%      |
| Intel Jasper Lake HD Audio                                                        | 1         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 2%      |
| Intel Comet Lake PCH cAVS                                                         | 1         | 2%      |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 2%      |
| Intel Broadwell-U Audio Controller                                                | 1         | 2%      |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 2%      |
| Intel 8 Series HD Audio Controller                                                | 1         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 27.27%  |
| SK hynix            | 8         | 24.24%  |
| Samsung Electronics | 8         | 24.24%  |
| Elpida              | 2         | 6.06%   |
| UNILC               | 1         | 3.03%   |
| UniIC               | 1         | 3.03%   |
| Nanya Technology    | 1         | 3.03%   |
| Longsys             | 1         | 3.03%   |
| A-DATA Technology   | 1         | 3.03%   |
| Unknown             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Micron RAM Not Set 8192MB DIMM DDR4 2668MT/s                        | 2         | 5.88%   |
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                    | 1         | 2.94%   |
| UniIC RAM SCC08GS03H1F1C-26V 8192MB SODIMM DDR4 2666MT/s            | 1         | 2.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                        | 1         | 2.94%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 2.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 2.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 2.94%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s             | 1         | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 2.94%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s    | 1         | 2.94%   |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s     | 1         | 2.94%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 2.94%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 2.94%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                    | 1         | 2.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.94%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.94%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.94%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s          | 1         | 2.94%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s              | 1         | 2.94%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                      | 1         | 2.94%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                     | 1         | 2.94%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s             | 1         | 2.94%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s    | 1         | 2.94%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s       | 1         | 2.94%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 2.94%   |
| Micron RAM 53E512M32D2NP-046 1024MB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 2.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 2.94%   |
| Longsys RAM FD4AU3200C8GTG 8192MB DIMM DDR4 3200MT/s                | 1         | 2.94%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 2.94%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s               | 1         | 2.94%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                          | 1         | 2.94%   |
| Unknown                                                             | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 48.48%  |
| LPDDR4  | 5         | 15.15%  |
| LPDDR5  | 4         | 12.12%  |
| LPDDR3  | 3         | 9.09%   |
| DDR3    | 3         | 9.09%   |
| DDR5    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 51.61%  |
| Row Of Chips | 10        | 32.26%  |
| DIMM         | 5         | 16.13%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 70.97%  |
| 4096  | 5         | 16.13%  |
| 2048  | 3         | 9.68%   |
| 16384 | 1         | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 18.75%  |
| 6400  | 4         | 12.5%   |
| 2667  | 4         | 12.5%   |
| 4266  | 3         | 9.38%   |
| 2668  | 3         | 9.38%   |
| 1867  | 3         | 9.38%   |
| 2666  | 2         | 6.25%   |
| 4800  | 1         | 3.13%   |
| 4267  | 1         | 3.13%   |
| 2400  | 1         | 3.13%   |
| 2133  | 1         | 3.13%   |
| 1600  | 1         | 3.13%   |
| 1067  | 1         | 3.13%   |
| 1066  | 1         | 3.13%   |

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
| IMC Networks                           | 7         | 26.92%  |
| Chicony Electronics                    | 6         | 23.08%  |
| Unknown (0000066029)                   | 2         | 7.69%   |
| Syntek                                 | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| Sonix Technology                       | 1         | 3.85%   |
| Realtek Semiconductor                  | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Luxvisions Innotech Limited            | 1         | 3.85%   |
| Lenovo                                 | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.85%   |
| BL012030059711690428                   | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 11.54%  |
| IMC Networks Integrated Camera                      | 3         | 11.54%  |
| Unknown (0000066029) HD Camera                      | 2         | 7.69%   |
| Syntek Integrated Camera                            | 2         | 7.69%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD                        | 1         | 3.85%   |
| Quanta ov9734_techfront_camera                      | 1         | 3.85%   |
| Microdia USB2.0 Camera                              | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.85%   |
| Lenovo Integrated Webcam                            | 1         | 3.85%   |
| IMC Networks Integrated RGB Camera                  | 1         | 3.85%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 3.85%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.85%   |
| Chicony Integrated Camera                           | 1         | 3.85%   |
| Chicony HP HD Camera                                | 1         | 3.85%   |
| Chicony EasyCamera                                  | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.85%   |
| BL012030059711690428 Integrated Camera              | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 57.14%  |
| Validity Sensors           | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 14.29%  |
| Synaptics UWP WBDI Device                                 | 1         | 14.29%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device                       | 1         | 14.29%  |
| AuthenTec AES2810                                         | 1         | 14.29%  |

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
| 0     | 23        | 63.89%  |
| 1     | 11        | 30.56%  |
| 3     | 1         | 2.78%   |
| 2     | 1         | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 43.75%  |
| Graphics card         | 3         | 18.75%  |
| Net/wireless          | 2         | 12.5%   |
| Multimedia controller | 2         | 12.5%   |
| Camera                | 1         | 6.25%   |
| Bluetooth             | 1         | 6.25%   |

