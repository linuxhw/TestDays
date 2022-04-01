Alpine - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Haier    | U144S                       | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer     | Aspire E5-553G              | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo   | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell     | XPS 15 7590                 | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek  | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| ASUSTek  | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP       | EliteBook 1040 G3 Notebo... | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| MSI      | GL72M 7REX                  | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Lenovo   | ThinkPad W700 2752RZ2       | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Dell     | Inspiron MM061              | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| ASUSTek  | X550EA                      | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP       | Compaq Mini CQ10-600        | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo   | IdeaPad 320-15AST 80XV      | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo   | Yoga 14sARH 2021 82LB       | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown  | Unknown                     | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| Pegatron | Deepcam                     | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| HP       | EliteBook 2740p             | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP       | EliteBook 2740p             | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek  | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP       | Laptop 14-dq1xxx            | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM      | 264070A                     | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP       | Mini 110-3500               | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP       | ENVY Sleekbook 6 PC         | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Acer     | Aspire ES1-512              | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer     | Aspire 5920G                | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP       | Compaq Mini CQ10-600        | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway  | MX3631m                     | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell     | Studio 1747                 | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| Dell     | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell     | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek  | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM      | 26446AG                     | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM      | 26446AG                     | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| Google   | Samus                       | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Dell     | Inspiron 5566               | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Apple    | MacBook7,1                  | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Lenovo   | ThinkPad 11e 20ED001HUS     | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer     | Aspire ES1-111M             | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| Lenovo   | ThinkPad E485 20KUCTO1WW    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| HP       | ZBook 15 G5                 | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology | DS1019+                     | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology | DS1019+                     | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology | DS1019+                     | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.15.0               | 5         | 13.51%  |
| Alpine 3.15.0_alpha20210804 | 4         | 10.81%  |
| Alpine 3.14.0               | 4         | 10.81%  |
| Alpine 3.12.0               | 4         | 10.81%  |
| Alpine 3.14.2               | 2         | 5.41%   |
| Alpine 3.13.5               | 2         | 5.41%   |
| Alpine 3.13.0_alpha20201218 | 2         | 5.41%   |
| Alpine 3.13.0_alpha20200917 | 2         | 5.41%   |
| Alpine 3.11.2               | 2         | 5.41%   |
| Alpine 3.16.0_alpha20220316 | 1         | 2.7%    |
| Alpine 3.15.2               | 1         | 2.7%    |
| Alpine 3.15.0_rc5           | 1         | 2.7%    |
| Alpine 3.14.0_alpha20210212 | 1         | 2.7%    |
| Alpine 3.13.1               | 1         | 2.7%    |
| Alpine 3.13.0_rc2           | 1         | 2.7%    |
| Alpine 3.13.0_alpha20200626 | 1         | 2.7%    |
| Alpine 3.12.3               | 1         | 2.7%    |
| Alpine 3.12.1               | 1         | 2.7%    |
| Alpine 3.11.5               | 1         | 2.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.4.83-0-lts           | 2         | 5.26%   |
| 5.4.43-1-lts           | 2         | 5.26%   |
| 5.15.4-0-lts           | 2         | 5.26%   |
| 5.8.12-0-edge          | 1         | 2.63%   |
| 5.6.2-xanmod1-1-xanmod | 1         | 2.63%   |
| 5.4.84-0-lts           | 1         | 2.63%   |
| 5.4.72-0-lts           | 1         | 2.63%   |
| 5.4.64-0-lts           | 1         | 2.63%   |
| 5.4.46-0-lts           | 1         | 2.63%   |
| 5.4.27-0-lts           | 1         | 2.63%   |
| 5.17.0-0-edge          | 1         | 2.63%   |
| 5.16.12-may            | 1         | 2.63%   |
| 5.16.1-may             | 1         | 2.63%   |
| 5.15.30-0-lts          | 1         | 2.63%   |
| 5.15.28-0-lts          | 1         | 2.63%   |
| 5.15.26-0-lts          | 1         | 2.63%   |
| 5.15.16-0-lts          | 1         | 2.63%   |
| 5.15.12-0-lts          | 1         | 2.63%   |
| 5.14.8-0-edge          | 1         | 2.63%   |
| 5.13.0-0-edge          | 1         | 2.63%   |
| 5.12.8-0-edge          | 1         | 2.63%   |
| 5.10.70-0-lts          | 1         | 2.63%   |
| 5.10.69-0-lts          | 1         | 2.63%   |
| 5.10.68-0-lts          | 1         | 2.63%   |
| 5.10.61-0-lts          | 1         | 2.63%   |
| 5.10.5-0-lts           | 1         | 2.63%   |
| 5.10.44-0-lts          | 1         | 2.63%   |
| 5.10.43-0-lts          | 1         | 2.63%   |
| 5.10.42-0-legacy       | 1         | 2.63%   |
| 5.10.4-0-lts           | 1         | 2.63%   |
| 5.10.38-0-lts          | 1         | 2.63%   |
| 5.10.29-0-lts          | 1         | 2.63%   |
| 5.10.11-0-lts          | 1         | 2.63%   |
| 4.4.59+                | 1         | 2.63%   |
| 3.10.18                | 1         | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.83  | 2         | 5.26%   |
| 5.4.43  | 2         | 5.26%   |
| 5.15.4  | 2         | 5.26%   |
| 5.8.12  | 1         | 2.63%   |
| 5.6.2   | 1         | 2.63%   |
| 5.4.84  | 1         | 2.63%   |
| 5.4.72  | 1         | 2.63%   |
| 5.4.64  | 1         | 2.63%   |
| 5.4.46  | 1         | 2.63%   |
| 5.4.27  | 1         | 2.63%   |
| 5.17.0  | 1         | 2.63%   |
| 5.16.12 | 1         | 2.63%   |
| 5.16.1  | 1         | 2.63%   |
| 5.15.30 | 1         | 2.63%   |
| 5.15.28 | 1         | 2.63%   |
| 5.15.26 | 1         | 2.63%   |
| 5.15.16 | 1         | 2.63%   |
| 5.15.12 | 1         | 2.63%   |
| 5.14.8  | 1         | 2.63%   |
| 5.13.0  | 1         | 2.63%   |
| 5.12.8  | 1         | 2.63%   |
| 5.10.70 | 1         | 2.63%   |
| 5.10.69 | 1         | 2.63%   |
| 5.10.68 | 1         | 2.63%   |
| 5.10.61 | 1         | 2.63%   |
| 5.10.5  | 1         | 2.63%   |
| 5.10.44 | 1         | 2.63%   |
| 5.10.43 | 1         | 2.63%   |
| 5.10.42 | 1         | 2.63%   |
| 5.10.4  | 1         | 2.63%   |
| 5.10.38 | 1         | 2.63%   |
| 5.10.29 | 1         | 2.63%   |
| 5.10.11 | 1         | 2.63%   |
| 4.4.59  | 1         | 2.63%   |
| 3.10.18 | 1         | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 11        | 30.56%  |
| 5.4     | 9         | 25%     |
| 5.15    | 7         | 19.44%  |
| 5.8     | 1         | 2.78%   |
| 5.6     | 1         | 2.78%   |
| 5.17    | 1         | 2.78%   |
| 5.16    | 1         | 2.78%   |
| 5.14    | 1         | 2.78%   |
| 5.13    | 1         | 2.78%   |
| 5.12    | 1         | 2.78%   |
| 4.4     | 1         | 2.78%   |
| 3.10    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 88.89%  |
| i686   | 2         | 5.56%   |
| i586   | 1         | 2.78%   |
| armv7l | 1         | 2.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 77.78%  |
| GNOME   | 4         | 11.11%  |
| XFCE    | 3         | 8.33%   |
| KDE5    | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 54.05%  |
| X11     | 13        | 35.14%  |
| Wayland | 4         | 10.81%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 88.89%  |
| XDM     | 1         | 2.78%   |
| SDDM    | 1         | 2.78%   |
| LXDM    | 1         | 2.78%   |
| GDM     | 1         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 19        | 52.78%  |
| Unknown | 11        | 30.56%  |
| en_US   | 4         | 11.11%  |
| ru_RU   | 1         | 2.78%   |
| en_GB   | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 66.67%  |
| EFI  | 12        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 28        | 77.78%  |
| Btrfs   | 4         | 11.11%  |
| Tmpfs   | 1         | 2.78%   |
| F2fs    | 1         | 2.78%   |
| Ext2    | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 54.05%  |
| GPT     | 12        | 32.43%  |
| MBR     | 5         | 13.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 19.44%  |
| Hewlett-Packard  | 7         | 19.44%  |
| Dell             | 5         | 13.89%  |
| ASUSTek Computer | 4         | 11.11%  |
| Acer             | 4         | 11.11%  |
| IBM              | 2         | 5.56%   |
| Synology         | 1         | 2.78%   |
| Pegatron         | 1         | 2.78%   |
| MSI              | 1         | 2.78%   |
| Haier            | 1         | 2.78%   |
| Google           | 1         | 2.78%   |
| Gateway          | 1         | 2.78%   |
| Unknown          | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Synology DS1019+                         | 1         | 2.78%   |
| Pegatron Deepcam                         | 1         | 2.78%   |
| MSI GL72M 7REX                           | 1         | 2.78%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 2.78%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 2.78%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 2.78%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 2.78%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 2.78%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 2.78%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 2.78%   |
| IBM 26446AG                              | 1         | 2.78%   |
| IBM 264070A                              | 1         | 2.78%   |
| HP ZBook 15 G5                           | 1         | 2.78%   |
| HP Mini 110-3500                         | 1         | 2.78%   |
| HP Laptop 14-dq1xxx                      | 1         | 2.78%   |
| HP ENVY Sleekbook 6 PC                   | 1         | 2.78%   |
| HP EliteBook 2740p                       | 1         | 2.78%   |
| HP EliteBook 1040 G3 Notebook PC         | 1         | 2.78%   |
| HP Compaq Mini CQ10-600                  | 1         | 2.78%   |
| Haier U144S                              | 1         | 2.78%   |
| Google Samus                             | 1         | 2.78%   |
| Gateway MX3631m                          | 1         | 2.78%   |
| Dell XPS 15 7590                         | 1         | 2.78%   |
| Dell Studio 1747                         | 1         | 2.78%   |
| Dell Inspiron MM061                      | 1         | 2.78%   |
| Dell Inspiron 5566                       | 1         | 2.78%   |
| Dell Inspiron 3180                       | 1         | 2.78%   |
| ASUS ZenBook UX431FA                     | 1         | 2.78%   |
| ASUS X550EA                              | 1         | 2.78%   |
| ASUS X200MA                              | 1         | 2.78%   |
| ASUS E502SA                              | 1         | 2.78%   |
| Acer Aspire ES1-512                      | 1         | 2.78%   |
| Acer Aspire ES1-111M                     | 1         | 2.78%   |
| Acer Aspire E5-553G                      | 1         | 2.78%   |
| Acer Aspire 5920G                        | 1         | 2.78%   |
| Unknown                                  | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 5         | 13.89%  |
| Acer Aspire      | 4         | 11.11%  |
| Dell Inspiron    | 3         | 8.33%   |
| HP EliteBook     | 2         | 5.56%   |
| Synology DS1019+ | 1         | 2.78%   |
| Pegatron Deepcam | 1         | 2.78%   |
| MSI GL72M        | 1         | 2.78%   |
| Lenovo Yoga      | 1         | 2.78%   |
| Lenovo IdeaPad   | 1         | 2.78%   |
| IBM 26446AG      | 1         | 2.78%   |
| IBM 264070A      | 1         | 2.78%   |
| HP ZBook         | 1         | 2.78%   |
| HP Mini          | 1         | 2.78%   |
| HP Laptop        | 1         | 2.78%   |
| HP ENVY          | 1         | 2.78%   |
| HP Compaq        | 1         | 2.78%   |
| Haier U144S      | 1         | 2.78%   |
| Google Samus     | 1         | 2.78%   |
| Gateway MX3631m  | 1         | 2.78%   |
| Dell XPS         | 1         | 2.78%   |
| Dell Studio      | 1         | 2.78%   |
| ASUS ZenBook     | 1         | 2.78%   |
| ASUS X550EA      | 1         | 2.78%   |
| ASUS X200MA      | 1         | 2.78%   |
| ASUS E502SA      | 1         | 2.78%   |
| Unknown          | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 5         | 13.89%  |
| 2018    | 5         | 13.89%  |
| 2014    | 4         | 11.11%  |
| 2017    | 3         | 8.33%   |
| 2010    | 3         | 8.33%   |
| 2021    | 2         | 5.56%   |
| 2016    | 2         | 5.56%   |
| 2012    | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| 2015    | 1         | 2.78%   |
| 2013    | 1         | 2.78%   |
| 2011    | 1         | 2.78%   |
| 2009    | 1         | 2.78%   |
| 2007    | 1         | 2.78%   |
| 2006    | 1         | 2.78%   |
| 2005    | 1         | 2.78%   |
| 1999    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 36        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 97.22%  |
| Yes  | 1         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 10        | 27.03%  |
| 3.01-4.0    | 9         | 24.32%  |
| 8.01-16.0   | 5         | 13.51%  |
| 16.01-24.0  | 4         | 10.81%  |
| 1.01-2.0    | 3         | 8.11%   |
| 0.51-1.0    | 2         | 5.41%   |
| 0.01-0.5    | 2         | 5.41%   |
| 32.01-64.0  | 1         | 2.7%    |
| 64.01-256.0 | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 10        | 27.03%  |
| 1.01-2.0  | 7         | 18.92%  |
| 2.01-3.0  | 5         | 13.51%  |
| 4.01-8.0  | 4         | 10.81%  |
| 0.51-1.0  | 4         | 10.81%  |
| 3.01-4.0  | 3         | 8.11%   |
| 0         | 2         | 5.41%   |
| 8.01-16.0 | 1         | 2.7%    |
| Unknown   | 1         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 72.22%  |
| 2      | 8         | 22.22%  |
| 7      | 1         | 2.78%   |
| 0      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 77.78%  |
| Yes       | 8         | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 77.78%  |
| No        | 8         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 91.67%  |
| No        | 3         | 8.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 61.11%  |
| No        | 14        | 38.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| USA       | 11        | 30.56%  |
| Canada    | 5         | 13.89%  |
| Russia    | 4         | 11.11%  |
| UK        | 2         | 5.56%   |
| Brazil    | 2         | 5.56%   |
| Venezuela | 1         | 2.78%   |
| Slovakia  | 1         | 2.78%   |
| Portugal  | 1         | 2.78%   |
| Poland    | 1         | 2.78%   |
| Mexico    | 1         | 2.78%   |
| Italy     | 1         | 2.78%   |
| Guatemala | 1         | 2.78%   |
| Germany   | 1         | 2.78%   |
| France    | 1         | 2.78%   |
| Egypt     | 1         | 2.78%   |
| Czechia   | 1         | 2.78%   |
| Australia | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| St Petersburg  | 3         | 8.33%   |
| Stratford      | 2         | 5.56%   |
| Verona         | 1         | 2.78%   |
| Vernon         | 1         | 2.78%   |
| Tymovskoye     | 1         | 2.78%   |
| Tanvald        | 1         | 2.78%   |
| Tampa          | 1         | 2.78%   |
| Sydney         | 1         | 2.78%   |
| Street         | 1         | 2.78%   |
| Sisteron       | 1         | 2.78%   |
| San Mateo      | 1         | 2.78%   |
| RzeszГіw     | 1         | 2.78%   |
| Rostock        | 1         | 2.78%   |
| MГ©rida      | 1         | 2.78%   |
| Merrill        | 1         | 2.78%   |
| Manitowoc      | 1         | 2.78%   |
| Mamaroneck     | 1         | 2.78%   |
| Lincoln        | 1         | 2.78%   |
| Larkspur       | 1         | 2.78%   |
| Kitchener      | 1         | 2.78%   |
| Indaiatuba     | 1         | 2.78%   |
| Hampstead      | 1         | 2.78%   |
| Guatemala City | 1         | 2.78%   |
| Funchal        | 1         | 2.78%   |
| Franklin       | 1         | 2.78%   |
| Ecatepec       | 1         | 2.78%   |
| Dallas         | 1         | 2.78%   |
| Chapel Hill    | 1         | 2.78%   |
| Cairo          | 1         | 2.78%   |
| Brockport      | 1         | 2.78%   |
| Bratislava     | 1         | 2.78%   |
| Boucherville   | 1         | 2.78%   |
| Belém         | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 13.64%  |
| Seagate             | 4         | 13     | 9.09%   |
| Kingston            | 4         | 4      | 9.09%   |
| Hitachi             | 4         | 4      | 9.09%   |
| WDC                 | 3         | 4      | 6.82%   |
| Unknown             | 3         | 4      | 6.82%   |
| Toshiba             | 2         | 3      | 4.55%   |
| Intel               | 2         | 4      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| Crucial             | 2         | 2      | 4.55%   |
| SPCC                | 1         | 1      | 2.27%   |
| SK Hynix            | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| KC600               | 1         | 1      | 2.27%   |
| JMicron             | 1         | 1      | 2.27%   |
| Intenso             | 1         | 1      | 2.27%   |
| IBM                 | 1         | 1      | 2.27%   |
| Dell                | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| AMD                 | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                    | 2         | 4.35%   |
| Crucial CT500MX500SSD1 500GB              | 2         | 4.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 2.17%   |
| WDC WD5000BEVT-22ZAT0 500GB               | 1         | 2.17%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB      | 1         | 2.17%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 2.17%   |
| Toshiba NVMe SSD Drive 256GB              | 1         | 2.17%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 2.17%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 2.17%   |
| SPCC Solid State Disk 256GB               | 1         | 2.17%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 2.17%   |
| Seagate ST98823A 80GB                     | 1         | 2.17%   |
| Seagate ST8000VN004-2M2101 8TB            | 1         | 2.17%   |
| Seagate ST2000LM015-2E81 2TB              | 1         | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 2.17%   |
| SanDisk SSD PLUS 480GB                    | 1         | 2.17%   |
| Samsung SSD 970 EVO Plus 250GB            | 1         | 2.17%   |
| Samsung Portable SSD T5 1TB               | 1         | 2.17%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 2.17%   |
| Samsung MZVLB256HAHQ-000L7 256GB          | 1         | 2.17%   |
| Samsung MZ7LF120 120GB SSD                | 1         | 2.17%   |
| Samsung HM160HI 160GB                     | 1         | 2.17%   |
| LITEON CV1-8B128-HP 128GB SSD             | 1         | 2.17%   |
| Kingston SUV500MS480G 480GB SSD           | 1         | 2.17%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 2.17%   |
| Kingston RBU-SUS151S364GD 64GB SSD        | 1         | 2.17%   |
| Kingston KC600 128GB SSD                  | 1         | 2.17%   |
| KC600 SSD 128GB                           | 1         | 2.17%   |
| JMicron Generic 2TB                       | 1         | 2.17%   |
| Intenso SSD 128GB                         | 1         | 2.17%   |
| Intel SSDPEKKA256G7 256GB                 | 1         | 2.17%   |
| Intel HBRPEKNX0101AHO 16GB                | 1         | 2.17%   |
| Intel HBRPEKNX0101AH 256GB                | 1         | 2.17%   |
| IBM DARA-212000 12GB                      | 1         | 2.17%   |
| Hitachi HTS725025A9A364 250GB             | 1         | 2.17%   |
| Hitachi HTS72101 99GB                     | 1         | 2.17%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 2.17%   |
| Hitachi HTS541040G9AT00 40GB              | 1         | 2.17%   |
| HGST HTS545050A7E380 500GB                | 1         | 2.17%   |
| HGST HTS541010B7E610 1TB                  | 1         | 2.17%   |
| Dell WR202KD032G E70290F5 32GB SSD        | 1         | 2.17%   |
| China SSD 120GB                           | 1         | 2.17%   |
| AMD R5M120G8 120GB SSD                    | 1         | 2.17%   |
| A-DATA SU800 128GB SSD                    | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 13     | 28.57%  |
| Hitachi             | 4         | 4      | 28.57%  |
| HGST                | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |
| IBM                 | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 21.05%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Crucial             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| SPCC                | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| LITEON              | 1         | 1      | 5.26%   |
| KC600               | 1         | 1      | 5.26%   |
| JMicron             | 1         | 1      | 5.26%   |
| Intenso             | 1         | 1      | 5.26%   |
| Dell                | 1         | 1      | 5.26%   |
| China               | 1         | 1      | 5.26%   |
| AMD                 | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 16        | 19     | 40%     |
| HDD  | 14        | 24     | 35%     |
| NVMe | 8         | 14     | 20%     |
| MMC  | 2         | 2      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 40     | 67.5%   |
| NVMe | 8         | 14     | 20%     |
| SAS  | 3         | 3      | 7.5%    |
| MMC  | 2         | 2      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 27     | 77.42%  |
| 0.51-1.0   | 4         | 4      | 12.9%   |
| 1.01-2.0   | 2         | 2      | 6.45%   |
| 4.01-10.0  | 1         | 10     | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 27.78%  |
| 251-500    | 6         | 16.67%  |
| 1-20       | 5         | 13.89%  |
| 21-50      | 4         | 11.11%  |
| Unknown    | 4         | 11.11%  |
| 501-1000   | 3         | 8.33%   |
| 1001-2000  | 2         | 5.56%   |
| 51-100     | 2         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 22        | 61.11%  |
| 21-50    | 4         | 11.11%  |
| Unknown  | 4         | 11.11%  |
| 51-100   | 3         | 8.33%   |
| 101-250  | 2         | 5.56%   |
| 501-1000 | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST2000LM015-2E81 2TB      | 1         | 1      | 20%     |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 20%     |
| Hitachi HTS725025A9A364 250GB     | 1         | 1      | 20%     |
| Hitachi HTS72101 99GB             | 1         | 1      | 20%     |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 40%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 2      | 20%     |
| HGST                | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 40%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 2      | 20%     |
| HGST                | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 100%    |

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
| Works    | 25        | 42     | 64.1%   |
| Detected | 9         | 11     | 23.08%  |
| Malfunc  | 5         | 6      | 12.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 26        | 65%     |
| AMD                          | 6         | 15%     |
| Samsung Electronics          | 3         | 7.5%    |
| Toshiba America Info Systems | 1         | 2.5%    |
| SK Hynix                     | 1         | 2.5%    |
| Sandisk                      | 1         | 2.5%    |
| Marvell Technology Group     | 1         | 2.5%    |
| ADATA Technology             | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 13.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 6.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 6.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 6.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 4.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 4.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 4.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 4.65%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2         | 4.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 4.65%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.33%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 2.33%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 2.33%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.33%   |
| Intel SSD 600P Series                                                            | 1         | 2.33%   |
| Intel Non-Volatile memory controller                                             | 1         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 2.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 26        | 63.41%  |
| NVMe | 8         | 19.51%  |
| IDE  | 5         | 12.2%   |
| RAID | 2         | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 77.78%  |
| AMD    | 7         | 19.44%  |
| ARM    | 1         | 2.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz                      | 2         | 5.56%   |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 5.56%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                       | 1         | 2.78%   |
| Intel Pentium M processor 1.60GHz                      | 1         | 2.78%   |
| Intel Pentium III (Coppermine)                         | 1         | 2.78%   |
| Intel Pentium CPU N3710 @ 1.60GHz                      | 1         | 2.78%   |
| Intel Mobile Pentium MMX                               | 1         | 2.78%   |
| Intel Core i9-9980HK CPU @ 2.40GHz                     | 1         | 2.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz                      | 1         | 2.78%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz                      | 1         | 2.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz                      | 1         | 2.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz                      | 1         | 2.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                     | 1         | 2.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz                      | 1         | 2.78%   |
| Intel Core i5-3317U CPU @ 1.70GHz                      | 1         | 2.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz                      | 1         | 2.78%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz                     | 1         | 2.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                      | 1         | 2.78%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 2.78%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                   | 1         | 2.78%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                       | 1         | 2.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1         | 2.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz                      | 1         | 2.78%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 1         | 2.78%   |
| Intel Atom Processor E3930 @ 1.30GHz                   | 1         | 2.78%   |
| ARM NVIDIA Tegra SoC (Flattened Device Tree) Processor | 1         | 2.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics                 | 1         | 2.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx          | 1         | 2.78%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1         | 2.78%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G          | 1         | 2.78%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics            | 1         | 2.78%   |
| AMD A4-5000 APU with Radeon HD Graphics                | 1         | 2.78%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G        | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 9         | 25%     |
| Intel Celeron     | 5         | 13.89%  |
| Other             | 3         | 8.33%   |
| Intel Atom        | 3         | 8.33%   |
| Intel Core i7     | 2         | 5.56%   |
| Intel Core 2 Duo  | 2         | 5.56%   |
| AMD A4            | 2         | 5.56%   |
| Intel Xeon        | 1         | 2.78%   |
| Intel Pentium M   | 1         | 2.78%   |
| Intel Pentium III | 1         | 2.78%   |
| Intel Pentium     | 1         | 2.78%   |
| Intel Core i9     | 1         | 2.78%   |
| Intel Core 2      | 1         | 2.78%   |
| AMD Ryzen 7       | 1         | 2.78%   |
| AMD Ryzen 5       | 1         | 2.78%   |
| AMD A6            | 1         | 2.78%   |
| AMD A10           | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 47.22%  |
| 4      | 10        | 27.78%  |
| 1      | 5         | 13.89%  |
| 8      | 2         | 5.56%   |
| 6      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 55.56%  |
| 2      | 16        | 44.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 56.76%  |
| Unknown        | 14        | 37.84%  |
| 32-bit         | 2         | 5.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 51.35%  |
| 0x30678    | 3         | 8.11%   |
| 0x106ca    | 2         | 5.41%   |
| 0x06006704 | 2         | 5.41%   |
| 0x906ea    | 1         | 2.7%    |
| 0x806eb    | 1         | 2.7%    |
| 0x706e5    | 1         | 2.7%    |
| 0x683      | 1         | 2.7%    |
| 0x506c9    | 1         | 2.7%    |
| 0x406c4    | 1         | 2.7%    |
| 0x306d4    | 1         | 2.7%    |
| 0x306a9    | 1         | 2.7%    |
| 0x206a7    | 1         | 2.7%    |
| 0x106e5    | 1         | 2.7%    |
| 0x0810100b | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 16.67%  |
| Silvermont  | 4         | 11.11%  |
| Goldmont    | 3         | 8.33%   |
| Excavator   | 3         | 8.33%   |
| Penryn      | 2         | 5.56%   |
| P6          | 2         | 5.56%   |
| Bonnell     | 2         | 5.56%   |
| Unknown     | 2         | 5.56%   |
| Zen 2       | 1         | 2.78%   |
| Zen         | 1         | 2.78%   |
| Westmere    | 1         | 2.78%   |
| Skylake     | 1         | 2.78%   |
| SandyBridge | 1         | 2.78%   |
| Puma        | 1         | 2.78%   |
| Nehalem     | 1         | 2.78%   |
| Jaguar      | 1         | 2.78%   |
| IvyBridge   | 1         | 2.78%   |
| IceLake     | 1         | 2.78%   |
| Core        | 1         | 2.78%   |
| Broadwell   | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 22        | 56.41%  |
| AMD      | 11        | 28.21%  |
| Nvidia   | 4         | 10.26%  |
| Neomagic | 2         | 5.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 3         | 7.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 7.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 5%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 2.5%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 2.5%    |
| Nvidia G92GLM [Quadro FX 3700M]                                                          | 1         | 2.5%    |
| Neomagic NM2200 [MagicGraph 256AV]                                                       | 1         | 2.5%    |
| Neomagic NM2160 [MagicGraph 128XD]                                                       | 1         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.5%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 2.5%    |
| Intel Iris Plus Graphics G7                                                              | 1         | 2.5%    |
| Intel HD Graphics 630                                                                    | 1         | 2.5%    |
| Intel HD Graphics 620                                                                    | 1         | 2.5%    |
| Intel HD Graphics 5500                                                                   | 1         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.5%    |
| Intel Coffee Lake UHD Graphics P630                                                      | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.5%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 2.5%    |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 2.5%    |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 2.5%    |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 2.5%    |
| AMD Renoir                                                                               | 1         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.5%    |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 2.5%    |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 47.22%  |
| 1 x AMD        | 9         | 25%     |
| Intel + Nvidia | 3         | 8.33%   |
| 1 x Neomagic   | 2         | 5.56%   |
| Other          | 1         | 2.78%   |
| 2 x Intel      | 1         | 2.78%   |
| 2 x AMD        | 1         | 2.78%   |
| 1 x Nvidia     | 1         | 2.78%   |
| Intel + AMD    | 1         | 2.78%   |

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
| Unknown    | 31        | 86.11%  |
| 0.01-0.5   | 3         | 8.33%   |
| 1.01-2.0   | 1         | 2.78%   |
| 0.51-1.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 22.86%  |
| Chimei Innolux          | 5         | 14.29%  |
| LG Display              | 4         | 11.43%  |
| BOE                     | 4         | 11.43%  |
| Samsung Electronics     | 2         | 5.71%   |
| LG Philips              | 2         | 5.71%   |
| Chi Mei Optoelectronics | 2         | 5.71%   |
| Lenovo                  | 1         | 2.86%   |
| InfoVision              | 1         | 2.86%   |
| HannStar                | 1         | 2.86%   |
| Goldstar                | 1         | 2.86%   |
| Envision                | 1         | 2.86%   |
| DENON                   | 1         | 2.86%   |
| CSO                     | 1         | 2.86%   |
| Acer                    | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 2.86%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch              | 1         | 2.86%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 2.86%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 2.86%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 2.86%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 1         | 2.86%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 2.86%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch                 | 1         | 2.86%   |
| Envision LE24M1475/25 EPI1475 1360x768 708x398mm 32.0-inch               | 1         | 2.86%   |
| DENON AVR DON004B 3840x2160 697x392mm 31.5-inch                          | 1         | 2.86%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO1033 1024x600 222x125mm 10.0-inch | 1         | 2.86%   |
| BOE LCD Monitor BOE08A0 1280x800 261x163mm 12.1-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO132C 1366x768 293x164mm 13.2-inch            | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch           | 1         | 2.86%   |
| Acer V173 ACR002F 1280x1024 338x270mm 17.0-inch                          | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 13        | 37.14%  |
| 1920x1080 (FHD)   | 5         | 14.29%  |
| 1280x800 (WXGA)   | 3         | 8.57%   |
| 3840x2160 (4K)    | 2         | 5.71%   |
| 1600x900 (HD+)    | 2         | 5.71%   |
| 1024x600          | 2         | 5.71%   |
| 2880x1800         | 1         | 2.86%   |
| 2560x1700         | 1         | 2.86%   |
| 2560x1440 (QHD)   | 1         | 2.86%   |
| 2560x1080         | 1         | 2.86%   |
| 1920x1200 (WUXGA) | 1         | 2.86%   |
| 1360x768          | 1         | 2.86%   |
| 1280x768          | 1         | 2.86%   |
| 1280x1024 (SXGA)  | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 31.43%  |
| 13     | 6         | 17.14%  |
| 17     | 4         | 11.43%  |
| 14     | 4         | 11.43%  |
| 11     | 3         | 8.57%   |
| 12     | 2         | 5.71%   |
| 10     | 2         | 5.71%   |
| 32     | 1         | 2.86%   |
| 31     | 1         | 2.86%   |
| 29     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 60%     |
| 201-300     | 8         | 22.86%  |
| 351-400     | 3         | 8.57%   |
| 601-700     | 2         | 5.71%   |
| 701-800     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 76.47%  |
| 16/10 | 5         | 14.71%  |
| 5/4   | 1         | 2.94%   |
| 3/2   | 1         | 2.94%   |
| 21/9  | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 31.43%  |
| 81-90          | 9         | 25.71%  |
| 51-60          | 3         | 8.57%   |
| 71-80          | 2         | 5.71%   |
| 351-500        | 2         | 5.71%   |
| 41-50          | 2         | 5.71%   |
| 121-130        | 2         | 5.71%   |
| 61-70          | 1         | 2.86%   |
| 301-350        | 1         | 2.86%   |
| 141-150        | 1         | 2.86%   |
| 131-140        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 13        | 37.14%  |
| 121-160       | 12        | 34.29%  |
| 51-100        | 5         | 14.29%  |
| More than 240 | 2         | 5.71%   |
| 161-240       | 2         | 5.71%   |
| 1-50          | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 77.78%  |
| 2     | 4         | 11.11%  |
| 0     | 4         | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 37.29%  |
| Intel                           | 15        | 25.42%  |
| Qualcomm Atheros                | 11        | 18.64%  |
| Broadcom                        | 6         | 10.17%  |
| Qualcomm Atheros Communications | 1         | 1.69%   |
| Marvell Technology Group        | 1         | 1.69%   |
| LSI                             | 1         | 1.69%   |
| Dresden Elektronik              | 1         | 1.69%   |
| Broadcom Limited                | 1         | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 9         | 13.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 3.03%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 1.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 1.52%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 1.52%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 1.52%   |
| LSI WinModem 56k                                                               | 1         | 1.52%   |
| Intel Wireless-AC 9260                                                         | 1         | 1.52%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 1.52%   |
| Intel Wireless 8260                                                            | 1         | 1.52%   |
| Intel Wireless 7260                                                            | 1         | 1.52%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 1.52%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 1.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller               | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.52%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.52%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                  | 1         | 1.52%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express                          | 1         | 1.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 1.52%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 1.52%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 41.18%  |
| Qualcomm Atheros                | 10        | 29.41%  |
| Broadcom                        | 4         | 11.76%  |
| Realtek Semiconductor           | 3         | 8.82%   |
| Qualcomm Atheros Communications | 1         | 2.94%   |
| Marvell Technology Group        | 1         | 2.94%   |
| Broadcom Limited                | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 17.65%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 5.88%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 5.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 2.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 2.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 2.94%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 2.94%   |
| Marvell Group Marvell WLAN controller                                          | 1         | 2.94%   |
| Intel Wireless-AC 9260                                                         | 1         | 2.94%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 2.94%   |
| Intel Wireless 8260                                                            | 1         | 2.94%   |
| Intel Wireless 7260                                                            | 1         | 2.94%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 2.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 2.94%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1         | 2.94%   |
| Intel Centrino Wireless-N 2230                                                 | 1         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 1         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 1         | 2.94%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                     | 1         | 2.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 2.94%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 65.52%  |
| Intel                 | 6         | 20.69%  |
| Broadcom              | 3         | 10.34%  |
| Qualcomm Atheros      | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 31.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 20.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 10.34%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.45%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.45%   |
| Broadcom NetLink BCM5789 Gigabit Ethernet PCI Express             | 1         | 3.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.45%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 52.38%  |
| Ethernet | 27        | 42.86%  |
| Modem    | 3         | 4.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 60%     |
| Ethernet | 18        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 66.67%  |
| 1     | 9         | 25%     |
| 0     | 3         | 8.33%   |

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


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 40.91%  |
| Qualcomm Atheros Communications | 3         | 13.64%  |
| Lite-On Technology              | 3         | 13.64%  |
| IMC Networks                    | 2         | 9.09%   |
| Broadcom                        | 2         | 9.09%   |
| Realtek Semiconductor           | 1         | 4.55%   |
| Marvell Semiconductor           | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 3         | 13.64%  |
| Intel Bluetooth wireless interface                  | 3         | 13.64%  |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 9.09%   |
| Intel AX200 Bluetooth                               | 2         | 9.09%   |
| Realtek Bluetooth Radio                             | 1         | 4.55%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 4.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| IMC Networks Bluetooth Device                       | 1         | 4.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 4.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 4.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 4.55%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 25        | 67.57%  |
| AMD                       | 9         | 24.32%  |
| Sennheiser Communications | 1         | 2.7%    |
| Realtek Semiconductor     | 1         | 2.7%    |
| Cirrus Logic              | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 6.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 6.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 6.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 6.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 6.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 4.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.55%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.55%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 4.55%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 2.27%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 2.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 2.27%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.27%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.27%   |
| Cirrus Logic CS 4614/22/24/30 [CrystalClear SoundFusion Audio Accelerator]                        | 1         | 2.27%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 2.27%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 7         | 23.33%  |
| Samsung Electronics | 7         | 23.33%  |
| Unknown             | 4         | 13.33%  |
| Elpida              | 4         | 13.33%  |
| Micron Technology   | 2         | 6.67%   |
| Crucial             | 2         | 6.67%   |
| A-DATA Technology   | 2         | 6.67%   |
| Unknown (ABCD)      | 1         | 3.33%   |
| Kingston            | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 2         | 6.45%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 3.23%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                       | 1         | 3.23%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 3.23%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 3.23%   |
| Unknown RAM Module 128MB DIMM DRAM                                  | 1         | 3.23%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 3.23%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 3.23%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 3.23%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 3.23%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 3.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 3.23%   |
| Samsung RAM M4 70T2953CZ3-CD5 1GB SODIMM DDR2 533MT/s               | 1         | 3.23%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.23%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 3.23%   |
| Micron RAM 8KTF51264HDZ-1G9P1 4096MB SODIMM DDR3 1400MT/s           | 1         | 3.23%   |
| Micron RAM 8JTF5126 4HZ-1GD 1 4GB SODIMM DDR3 1600MT/s              | 1         | 3.23%   |
| Kingston RAM 9905417-074.A00G 4GB SODIMM DDR3 1333MT/s              | 1         | 3.23%   |
| Elpida RAM EDFB232A1MA-GD-F 8192MB SODIMM LPDDR3 1600MT/s           | 1         | 3.23%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 1         | 3.23%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 1         | 3.23%   |
| Elpida RAM EBJ21UE8BBS0-AE-F 2GB SODIMM DDR3 1067MT/s               | 1         | 3.23%   |
| Crucial RAM CT8G4SFD824A.C16FBD2 8GB SODIMM DDR4 2400MT/s           | 1         | 3.23%   |
| Crucial RAM CT102464BF186D.M16 8GB SODIMM DDR3 1867MT/s             | 1         | 3.23%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                          | 1         | 3.23%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s                | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 42.86%  |
| DDR4   | 8         | 28.57%  |
| LPDDR3 | 3         | 10.71%  |
| LPDDR4 | 2         | 7.14%   |
| DRAM   | 1         | 3.57%   |
| DDR2   | 1         | 3.57%   |
| DDR    | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 85.71%  |
| Row Of Chips | 3         | 10.71%  |
| DIMM         | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 11        | 36.67%  |
| 4096 | 11        | 36.67%  |
| 2048 | 4         | 13.33%  |
| 1024 | 2         | 6.67%   |
| 256  | 1         | 3.33%   |
| 128  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 5         | 17.86%  |
| 2400    | 4         | 14.29%  |
| 2133    | 4         | 14.29%  |
| 1334    | 3         | 10.71%  |
| 2667    | 2         | 7.14%   |
| 1333    | 2         | 7.14%   |
| Unknown | 2         | 7.14%   |
| 3200    | 1         | 3.57%   |
| 1867    | 1         | 3.57%   |
| 1400    | 1         | 3.57%   |
| 1200    | 1         | 3.57%   |
| 1067    | 1         | 3.57%   |
| 533     | 1         | 3.57%   |

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
| Chicony Electronics                    | 9         | 32.14%  |
| Realtek Semiconductor                  | 4         | 14.29%  |
| Suyin                                  | 2         | 7.14%   |
| Microdia                               | 2         | 7.14%   |
| IMC Networks                           | 2         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.14%   |
| Syntek                                 | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 2         | 7.14%   |
| Chicony Integrated Camera                        | 2         | 7.14%   |
| Chicony HD WebCam                                | 2         | 7.14%   |
| Syntek EasyCamera                                | 1         | 3.57%   |
| Suyin HP TrueVision HD                           | 1         | 3.57%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 3.57%   |
| Sunplus HD WebCam                                | 1         | 3.57%   |
| Silicon Motion NCM-G102                          | 1         | 3.57%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 3.57%   |
| Realtek Acer 640 x 480 laptop camera             | 1         | 3.57%   |
| Quanta HP TrueVision HD Camera                   | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_2M             | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                    | 1         | 3.57%   |
| Lenovo Integrated Webcam                         | 1         | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                | 1         | 3.57%   |
| IMC Networks Integrated Camera                   | 1         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.57%   |
| Chicony USB2.0 FHD UVC WebCam                    | 1         | 3.57%   |
| Chicony Integrated Camera (1280x720@30)          | 1         | 3.57%   |
| Chicony HP Webcam [2 MP Macro]                   | 1         | 3.57%   |
| Chicony HP HD Camera                             | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE                        | 1         | 3.57%   |
| Acer HP Webcam                                   | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Synaptics        | 1         | 20%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 20%     |
| AuthenTec AES2810                                                          | 1         | 20%     |

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
| 0     | 21        | 56.76%  |
| 1     | 11        | 29.73%  |
| 2     | 4         | 10.81%  |
| 3     | 1         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 5         | 23.81%  |
| Modem                    | 3         | 14.29%  |
| Graphics card            | 3         | 14.29%  |
| Camera                   | 2         | 9.52%   |
| Unclassified device      | 1         | 4.76%   |
| Storage                  | 1         | 4.76%   |
| Sound                    | 1         | 4.76%   |
| Net/wireless             | 1         | 4.76%   |
| Multimedia controller    | 1         | 4.76%   |
| Communication controller | 1         | 4.76%   |
| Chipcard                 | 1         | 4.76%   |
| Bluetooth                | 1         | 4.76%   |

