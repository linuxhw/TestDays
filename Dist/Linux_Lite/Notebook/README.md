Linux Lite - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux Lite.

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

Total: 68

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Samsung  | 530XBB                      | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Minix    | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Dell     | Inspiron 16 5620            | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix    | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell     | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo   | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer     | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Acer     | Aspire 1410                 | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo   | ThinkPad T400 6475E13       | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell     | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| Insignia | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell     | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| HP       | 15 Notebook PC              | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| HP       | Compaq CQ45                 | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek  | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer     | Aspire A315-53              | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| Acer     | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| HP       | Compaq nw9440 (EY615ET#A... | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP       | Pavilion dv6500             | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek  | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek  | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| ASUSTek  | X541SA                      | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP       | Pavilion dv6500             | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| Acer     | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| HP       | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP       | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung  | 905S3G/906S3G/915S3G/930... | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer     | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell     | MXG061                      | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Acer     | Swift SF314-56              | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer     | Swift SF314-56              | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| Dell     | Vostro1710                  | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell     | Inspiron 5452               | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| HP       | EliteBook Folio 9470m       | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek  | X541SA                      | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP       | Laptop 14-cm0xxx            | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP       | Laptop 14-cm0xxx            | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu  | LIFEBOOK U747               | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop E203... | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek  | K50IE                       | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| ASUSTek  | K54LY                       | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer     | Aspire V5-552               | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP       | Compaq 6735b                | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell     | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP       | Laptop 17-by2xxx            | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer     | Predator PH317-52           | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| HP       | 655                         | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP       | 655                         | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba  | Satellite T215D             | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba  | Satellite T215D             | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Lenovo   | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek  | 1001PX                      | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer     | Aspire 5750                 | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer     | Aspire 5750                 | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| Dell     | Latitude D530               | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| Acer     | Aspire ES1-511              | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google   | Chell                       | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek  | X751LD                      | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek  | X751LD                      | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo   | 3000 V200 0764A11           | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR       | ST Pro-KN                   | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| ASUSTek  | N750JK                      | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung  | NC110P/NC108P/NC111P        | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek  | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 10        | 19.61%  |
| Linux Lite 5.4 | 9         | 17.65%  |
| Linux Lite 5.2 | 9         | 17.65%  |
| Linux Lite 5.0 | 8         | 15.69%  |
| Linux Lite 5.6 | 6         | 11.76%  |
| Linux Lite 6.0 | 3         | 5.88%   |
| Linux Lite 3.8 | 3         | 5.88%   |
| Linux Lite 4.8 | 2         | 3.92%   |
| Linux Lite 4.4 | 1         | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-40-generic                   | 4         | 7.27%   |
| 5.4.0-70-generic                   | 3         | 5.45%   |
| 5.4.0-52-generic                   | 3         | 5.45%   |
| 5.4.0-109-generic                  | 3         | 5.45%   |
| 5.4.0-90-generic                   | 2         | 3.64%   |
| 5.4.0-81-generic                   | 2         | 3.64%   |
| 5.4.0-74-generic                   | 2         | 3.64%   |
| 5.4.0-58-generic                   | 2         | 3.64%   |
| 5.4.0-42-generic                   | 2         | 3.64%   |
| 5.4.0-104-generic                  | 2         | 3.64%   |
| 5.4.0-96-generic                   | 1         | 1.82%   |
| 5.4.0-94-generic                   | 1         | 1.82%   |
| 5.4.0-91-generic                   | 1         | 1.82%   |
| 5.4.0-88-generic                   | 1         | 1.82%   |
| 5.4.0-77-generic                   | 1         | 1.82%   |
| 5.4.0-71-generic                   | 1         | 1.82%   |
| 5.4.0-66-generic                   | 1         | 1.82%   |
| 5.4.0-65-generic                   | 1         | 1.82%   |
| 5.4.0-56-generic                   | 1         | 1.82%   |
| 5.4.0-48-generic                   | 1         | 1.82%   |
| 5.4.0-33-generic                   | 1         | 1.82%   |
| 5.4.0-113-generic                  | 1         | 1.82%   |
| 5.4.0-110-generic                  | 1         | 1.82%   |
| 5.4.0-107-generic                  | 1         | 1.82%   |
| 5.4.0-105-generic                  | 1         | 1.82%   |
| 5.4.0-100-generic                  | 1         | 1.82%   |
| 5.16.0                             | 1         | 1.82%   |
| 5.15.0-33-generic                  | 1         | 1.82%   |
| 5.15.0-30-generic                  | 1         | 1.82%   |
| 5.15.0-27-generic                  | 1         | 1.82%   |
| 5.13.0-30-lowlatency               | 1         | 1.82%   |
| 5.10.0-051000daily20201222-generic | 1         | 1.82%   |
| 4.4.0-217-generic                  | 1         | 1.82%   |
| 4.4.0-210-generic                  | 1         | 1.82%   |
| 4.15.0-99-generic                  | 1         | 1.82%   |
| 4.15.0-91-generic                  | 1         | 1.82%   |
| 4.15.0-169-generic                 | 1         | 1.82%   |
| 4.15.0-166-generic                 | 1         | 1.82%   |
| 4.15.0-163-generic                 | 1         | 1.82%   |
| 4.15.0-162-generic                 | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 76.92%  |
| 4.15.0  | 4         | 7.69%   |
| 5.15.0  | 3         | 5.77%   |
| 4.4.0   | 2         | 3.85%   |
| 5.16.0  | 1         | 1.92%   |
| 5.13.0  | 1         | 1.92%   |
| 5.10.0  | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 40        | 76.92%  |
| 4.15    | 4         | 7.69%   |
| 5.15    | 3         | 5.77%   |
| 4.4     | 2         | 3.85%   |
| 5.16    | 1         | 1.92%   |
| 5.13    | 1         | 1.92%   |
| 5.10    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 96%     |
| i686   | 2         | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 36        | 72%     |
| GNOME   | 12        | 24%     |
| Deepin  | 1         | 2%      |
| Unknown | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 49        | 98%     |
| Unknown | 1         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 26        | 50%     |
| TDM     | 15        | 28.85%  |
| Unknown | 10        | 19.23%  |
| GDM     | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 25        | 50%     |
| pl_PL | 4         | 8%      |
| fr_FR | 4         | 8%      |
| de_DE | 4         | 8%      |
| en_GB | 3         | 6%      |
| ru_UA | 2         | 4%      |
| ru_RU | 2         | 4%      |
| pt_BR | 2         | 4%      |
| es_ES | 2         | 4%      |
| it_IT | 1         | 2%      |
| es_CO | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 52%     |
| BIOS | 24        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 42        | 84%     |
| Overlay | 6         | 12%     |
| Zfs     | 1         | 2%      |
| Btrfs   | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 40%     |
| GPT     | 17        | 34%     |
| MBR     | 13        | 26%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 84%     |
| Yes       | 8         | 16%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 68.63%  |
| Yes       | 16        | 31.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 22%     |
| ASUSTek Computer    | 10        | 20%     |
| Acer                | 9         | 18%     |
| Dell                | 7         | 14%     |
| Lenovo              | 4         | 8%      |
| Samsung Electronics | 3         | 6%      |
| TR                  | 1         | 2%      |
| Toshiba             | 1         | 2%      |
| Minix               | 1         | 2%      |
| Insignia            | 1         | 2%      |
| Google              | 1         | 2%      |
| Fujitsu             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| TR ST Pro-KN                           | 1         | 2%      |
| Toshiba Satellite T215D                | 1         | 2%      |
| Samsung NC110P/NC108P/NC111P           | 1         | 2%      |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 2%      |
| Samsung 530XBB                         | 1         | 2%      |
| Minix Z64                              | 1         | 2%      |
| Lenovo ThinkPad T400 6475E13           | 1         | 2%      |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 2%      |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 2%      |
| Lenovo 3000 V200 0764A11               | 1         | 2%      |
| Insignia NS-P11W7100                   | 1         | 2%      |
| HP Pavilion dv6500                     | 1         | 2%      |
| HP Laptop 17-by2xxx                    | 1         | 2%      |
| HP Laptop 15-dw3xxx                    | 1         | 2%      |
| HP Laptop 14-cm0xxx                    | 1         | 2%      |
| HP EliteBook Folio 9470m               | 1         | 2%      |
| HP EliteBook 8440p                     | 1         | 2%      |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 2%      |
| HP Compaq CQ45                         | 1         | 2%      |
| HP Compaq 2510p                        | 1         | 2%      |
| HP 655                                 | 1         | 2%      |
| HP 15 Notebook PC                      | 1         | 2%      |
| Google Chell                           | 1         | 2%      |
| Fujitsu LIFEBOOK U747                  | 1         | 2%      |
| Dell Vostro1710                        | 1         | 2%      |
| Dell MXG071                            | 1         | 2%      |
| Dell MXG061                            | 1         | 2%      |
| Dell Latitude D530                     | 1         | 2%      |
| Dell Inspiron 7559                     | 1         | 2%      |
| Dell Inspiron 5452                     | 1         | 2%      |
| Dell Inspiron 16 5620                  | 1         | 2%      |
| ASUS X751LD                            | 1         | 2%      |
| ASUS X541SA                            | 1         | 2%      |
| ASUS X540YA                            | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop E203NA_E203NA | 1         | 2%      |
| ASUS N750JK                            | 1         | 2%      |
| ASUS N53Jf                             | 1         | 2%      |
| ASUS K54LY                             | 1         | 2%      |
| ASUS K50IE                             | 1         | 2%      |
| ASUS 900                               | 1         | 2%      |
| ASUS 1001PX                            | 1         | 2%      |
| Acer Swift SF314-56                    | 1         | 2%      |
| Acer Predator PH317-52                 | 1         | 2%      |
| Acer Extensa 5220                      | 1         | 2%      |
| Acer Aspire V5-552                     | 1         | 2%      |
| Acer Aspire ES1-511                    | 1         | 2%      |
| Acer Aspire A315-53                    | 1         | 2%      |
| Acer Aspire 5750                       | 1         | 2%      |
| Acer Aspire 5600                       | 1         | 2%      |
| Acer Aspire 1410                       | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 6         | 12%     |
| HP Laptop            | 3         | 6%      |
| HP Compaq            | 3         | 6%      |
| Dell Inspiron        | 3         | 6%      |
| Lenovo IdeaPad       | 2         | 4%      |
| HP EliteBook         | 2         | 4%      |
| TR ST                | 1         | 2%      |
| Toshiba Satellite    | 1         | 2%      |
| Samsung NC110P       | 1         | 2%      |
| Samsung 905S3G       | 1         | 2%      |
| Samsung 530XBB       | 1         | 2%      |
| Minix Z64            | 1         | 2%      |
| Lenovo ThinkPad      | 1         | 2%      |
| Lenovo 3000          | 1         | 2%      |
| Insignia NS-P11W7100 | 1         | 2%      |
| HP Pavilion          | 1         | 2%      |
| HP 655               | 1         | 2%      |
| HP 15                | 1         | 2%      |
| Google Chell         | 1         | 2%      |
| Fujitsu LIFEBOOK     | 1         | 2%      |
| Dell Vostro1710      | 1         | 2%      |
| Dell MXG071          | 1         | 2%      |
| Dell MXG061          | 1         | 2%      |
| Dell Latitude        | 1         | 2%      |
| ASUS X751LD          | 1         | 2%      |
| ASUS X541SA          | 1         | 2%      |
| ASUS X540YA          | 1         | 2%      |
| ASUS VivoBook        | 1         | 2%      |
| ASUS N750JK          | 1         | 2%      |
| ASUS N53Jf           | 1         | 2%      |
| ASUS K54LY           | 1         | 2%      |
| ASUS K50IE           | 1         | 2%      |
| ASUS 900             | 1         | 2%      |
| ASUS 1001PX          | 1         | 2%      |
| Acer Swift           | 1         | 2%      |
| Acer Predator        | 1         | 2%      |
| Acer Extensa         | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 6         | 12%     |
| 2010 | 5         | 10%     |
| 2018 | 4         | 8%      |
| 2016 | 4         | 8%      |
| 2014 | 4         | 8%      |
| 2012 | 4         | 8%      |
| 2007 | 4         | 8%      |
| 2020 | 3         | 6%      |
| 2017 | 3         | 6%      |
| 2015 | 3         | 6%      |
| 2019 | 2         | 4%      |
| 2011 | 2         | 4%      |
| 2006 | 2         | 4%      |
| 2022 | 1         | 2%      |
| 2021 | 1         | 2%      |
| 2013 | 1         | 2%      |
| 2004 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 50        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 48        | 96%     |
| Enabled  | 2         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 21        | 42%     |
| 1.01-2.0   | 10        | 20%     |
| 4.01-8.0   | 6         | 12%     |
| 16.01-24.0 | 6         | 12%     |
| 0.51-1.0   | 3         | 6%      |
| 8.01-16.0  | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |
| 2.01-3.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 44.23%  |
| 2.01-3.0 | 12        | 23.08%  |
| 0.51-1.0 | 9         | 17.31%  |
| 3.01-4.0 | 4         | 7.69%   |
| 0.01-0.5 | 3         | 5.77%   |
| 4.01-8.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 82%     |
| 2      | 8         | 16%     |
| 3      | 1         | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 56%     |
| Yes       | 22        | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 86%     |
| No        | 7         | 14%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 98%     |
| No        | 1         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 70%     |
| No        | 15        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 5         | 10%     |
| Brazil      | 5         | 10%     |
| USA         | 4         | 8%      |
| Ukraine     | 4         | 8%      |
| France      | 4         | 8%      |
| UK          | 3         | 6%      |
| Spain       | 3         | 6%      |
| Russia      | 3         | 6%      |
| Romania     | 3         | 6%      |
| Poland      | 3         | 6%      |
| Turkey      | 1         | 2%      |
| Slovakia    | 1         | 2%      |
| Philippines | 1         | 2%      |
| Netherlands | 1         | 2%      |
| Myanmar     | 1         | 2%      |
| Mexico      | 1         | 2%      |
| Italy       | 1         | 2%      |
| Iran        | 1         | 2%      |
| Guadeloupe  | 1         | 2%      |
| Colombia    | 1         | 2%      |
| Chile       | 1         | 2%      |
| Canada      | 1         | 2%      |
| Australia   | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Pabianice            | 2         | 3.92%   |
| Odessa               | 2         | 3.92%   |
| Yangon               | 1         | 1.96%   |
| Würzburg            | 1         | 1.96%   |
| Wiesbaden            | 1         | 1.96%   |
| Warsaw               | 1         | 1.96%   |
| Wahroonga            | 1         | 1.96%   |
| Voluntari            | 1         | 1.96%   |
| Vinnytsia            | 1         | 1.96%   |
| Varennes-les-Narcy   | 1         | 1.96%   |
| Valencia             | 1         | 1.96%   |
| Teresina             | 1         | 1.96%   |
| Tarragona            | 1         | 1.96%   |
| Sydney               | 1         | 1.96%   |
| Svidník             | 1         | 1.96%   |
| St. Petersburg       | 1         | 1.96%   |
| Shadrinsk            | 1         | 1.96%   |
| Sao Paulo            | 1         | 1.96%   |
| Sabadell             | 1         | 1.96%   |
| Queretaro            | 1         | 1.96%   |
| Paris                | 1         | 1.96%   |
| Paranaque City       | 1         | 1.96%   |
| Nudlingen            | 1         | 1.96%   |
| Novaci               | 1         | 1.96%   |
| Moscow               | 1         | 1.96%   |
| Milan                | 1         | 1.96%   |
| Marseille            | 1         | 1.96%   |
| Madrid               | 1         | 1.96%   |
| London               | 1         | 1.96%   |
| Les Abymes           | 1         | 1.96%   |
| La Glacerie          | 1         | 1.96%   |
| Kyiv                 | 1         | 1.96%   |
| Kingston upon Thames | 1         | 1.96%   |
| Jaraguá do Sul      | 1         | 1.96%   |
| Izmir                | 1         | 1.96%   |
| Gorgan               | 1         | 1.96%   |
| Frankfurt am Main    | 1         | 1.96%   |
| Eggenfelden          | 1         | 1.96%   |
| Edmonton             | 1         | 1.96%   |
| Didsbury             | 1         | 1.96%   |
| Des Moines           | 1         | 1.96%   |
| Cotia                | 1         | 1.96%   |
| Coquimbo             | 1         | 1.96%   |
| Constanța           | 1         | 1.96%   |
| Cheboksary           | 1         | 1.96%   |
| Cabedelo             | 1         | 1.96%   |
| Brooklyn             | 1         | 1.96%   |
| Bogotá              | 1         | 1.96%   |
| Unknown              | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 21.05%  |
| WDC                 | 8         | 11     | 14.04%  |
| Toshiba             | 8         | 9      | 14.04%  |
| Samsung Electronics | 5         | 6      | 8.77%   |
| Unknown             | 4         | 5      | 7.02%   |
| Kingston            | 4         | 4      | 7.02%   |
| SanDisk             | 2         | 2      | 3.51%   |
| Micron Technology   | 2         | 3      | 3.51%   |
| Hitachi             | 2         | 2      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| Goodram             | 2         | 2      | 3.51%   |
| SK hynix            | 1         | 1      | 1.75%   |
| LITEON              | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Crucial             | 1         | 1      | 1.75%   |
| ASUS-PHISON         | 1         | 2      | 1.75%   |
| ASMT                | 1         | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB              | 3         | 5.08%   |
| Unknown MMC Card  32GB                | 2         | 3.39%   |
| Seagate ST9320325AS 320GB             | 2         | 3.39%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 3.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1.69%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1.69%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 1.69%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.69%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.69%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.69%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 1.69%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 1.69%   |
| Unknown SD64G  64GB                   | 1         | 1.69%   |
| Unknown NCard  32GB                   | 1         | 1.69%   |
| Unknown DA4064  64GB                  | 1         | 1.69%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1.69%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.69%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1.69%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 1.69%   |
| Toshiba MK1011GAH 100GB               | 1         | 1.69%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.69%   |
| Seagate ST9500423AS 500GB             | 1         | 1.69%   |
| Seagate ST9160823ASG 160GB            | 1         | 1.69%   |
| Seagate ST9160301AS 160GB             | 1         | 1.69%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 1.69%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1.69%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1.69%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1.69%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 1.69%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1.69%   |
| SanDisk Z400s M.2 2280 128GB SSD      | 1         | 1.69%   |
| SanDisk DF4032  32GB                  | 1         | 1.69%   |
| Samsung SSD 980 250GB                 | 1         | 1.69%   |
| Samsung PM991a NVMe 1024GB            | 1         | 1.69%   |
| Samsung MZVKW512HMJP-00007 512GB      | 1         | 1.69%   |
| Samsung MZMTD128HAFV-000 128GB SSD    | 1         | 1.69%   |
| Samsung HM160HI 160GB                 | 1         | 1.69%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 1         | 1.69%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD   | 1         | 1.69%   |
| LITEON CV5-8Q512 512GB SSD            | 1         | 1.69%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1.69%   |
| Kingston RBUSNS8154P3128GJ1 128GB     | 1         | 1.69%   |
| Intel SSDSA2CW080G3 80GB              | 1         | 1.69%   |
| Hitachi HTS723216L9SA60 160GB         | 1         | 1.69%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1.69%   |
| HGST HTS725050A7E630 500GB            | 1         | 1.69%   |
| HGST HTS721010A9E630 1TB              | 1         | 1.69%   |
| Goodram SSDPR-CL100-120-G3 120GB      | 1         | 1.69%   |
| Goodram IR-SSDPR-S25A-240 240GB       | 1         | 1.69%   |
| Crucial CT120BX500SSD1 120GB          | 1         | 1.69%   |
| ASUS-PHISON SSD 16GB                  | 1         | 1.69%   |
| ASUS-PHISON OB S 4GB SSD              | 1         | 1.69%   |
| ASMT USB 3.0 Destop H 1TB SSD         | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 40%     |
| Toshiba             | 8         | 9      | 26.67%  |
| WDC                 | 5         | 7      | 16.67%  |
| Hitachi             | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Samsung Electronics | 1         | 2      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 18.75%  |
| Micron Technology   | 2         | 3      | 12.5%   |
| Goodram             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |
| ASUS-PHISON         | 1         | 2      | 6.25%   |
| ASMT                | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 34     | 54.55%  |
| SSD  | 15        | 18     | 27.27%  |
| MMC  | 5         | 6      | 9.09%   |
| NVMe | 5         | 7      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 50     | 76.92%  |
| NVMe | 5         | 7      | 9.62%   |
| MMC  | 5         | 6      | 9.62%   |
| SAS  | 2         | 2      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 41     | 75.56%  |
| 0.51-1.0   | 10        | 10     | 22.22%  |
| 1.01-2.0   | 1         | 1      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 33.33%  |
| 251-500        | 13        | 25.49%  |
| 1-20           | 7         | 13.73%  |
| 51-100         | 6         | 11.76%  |
| 21-50          | 4         | 7.84%   |
| 501-1000       | 3         | 5.88%   |
| More than 3000 | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 59.62%  |
| 21-50     | 8         | 15.38%  |
| 51-100    | 7         | 13.46%  |
| 101-250   | 5         | 9.62%   |
| 2001-3000 | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB        | 1         | 1      | 14.29%  |
| Toshiba MQ01ABD050 500GB        | 1         | 1      | 14.29%  |
| Seagate ST9500423AS 500GB       | 1         | 1      | 14.29%  |
| Seagate ST9320325AS 320GB       | 1         | 1      | 14.29%  |
| Seagate ST9160823ASG 160GB      | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 14.29%  |
| Hitachi HTS545016B9A300 160GB   | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 100%    |

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
| Detected | 24        | 34     | 47.06%  |
| Works    | 20        | 24     | 39.22%  |
| Malfunc  | 7         | 7      | 13.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 38        | 73.08%  |
| AMD                         | 7         | 13.46%  |
| Samsung Electronics         | 3         | 5.77%   |
| SanDisk                     | 2         | 3.85%   |
| Nvidia                      | 1         | 1.92%   |
| Kingston Technology Company | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 10.94%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 9.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 6.25%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 3.13%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 3.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.56%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.56%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.56%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.56%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 38        | 64.41%  |
| IDE  | 13        | 22.03%  |
| NVMe | 5         | 8.47%   |
| RAID | 3         | 5.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 86%     |
| AMD    | 7         | 14%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core 2 CPU T7600 @ 2.33GHz                | 2         | 4%      |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 2%      |
| Intel Pentium CPU N3710 @ 1.60GHz               | 1         | 2%      |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 2%      |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 2%      |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2%      |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2%      |
| Intel Core m7-6Y75 CPU @ 1.20GHz                | 1         | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2%      |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 2%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 2%      |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2%      |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 2%      |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 2%      |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 2%      |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 2%      |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 2%      |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2%      |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 2%      |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 1         | 2%      |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 2%      |
| Intel Celeron M processor 900MHz                | 1         | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 2%      |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 2%      |
| Intel Celeron CPU B830 @ 1.80GHz                | 1         | 2%      |
| Intel Celeron CPU 723 @ 1.20GHz                 | 1         | 2%      |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2%      |
| Intel Atom CPU Z3735F @ 1.33GHz                 | 1         | 2%      |
| Intel Atom CPU N450 @ 1.66GHz                   | 1         | 2%      |
| Intel Atom CPU N2600 @ 1.60GHz                  | 1         | 2%      |
| Intel 12th Gen Core i7-1255U                    | 1         | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2%      |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 1         | 2%      |
| AMD Quad-Core Processor (up to 1.4GHz)          | 1         | 2%      |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G   | 1         | 2%      |
| AMD E2-1800 APU with Radeon HD Graphics         | 1         | 2%      |
| AMD Athlon II Neo K125 Processor                | 1         | 2%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2%      |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 2%      |
| AMD A10-5757M APU with Radeon HD Graphics       | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 8         | 16%     |
| Intel Core i7           | 5         | 10%     |
| Intel Celeron           | 5         | 10%     |
| Intel Pentium           | 4         | 8%      |
| Intel Core i5           | 4         | 8%      |
| Intel Core i3           | 4         | 8%      |
| Intel Atom              | 4         | 8%      |
| Other                   | 3         | 6%      |
| Intel Core 2            | 2         | 4%      |
| AMD E2                  | 2         | 4%      |
| Intel Pentium Dual-Core | 1         | 2%      |
| Intel Genuine           | 1         | 2%      |
| Intel Core m7           | 1         | 2%      |
| Intel Celeron M         | 1         | 2%      |
| AMD Quad-Core           | 1         | 2%      |
| AMD Athlon II Neo       | 1         | 2%      |
| AMD A8                  | 1         | 2%      |
| AMD A12                 | 1         | 2%      |
| AMD A10                 | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 62%     |
| 4      | 13        | 26%     |
| 1      | 4         | 8%      |
| 10     | 1         | 2%      |
| 6      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 58%     |
| 2      | 21        | 42%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 96%     |
| 32-bit         | 2         | 4%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x6fd      | 3         | 6%      |
| 0x30678    | 3         | 6%      |
| 0x206a7    | 3         | 6%      |
| 0x1067a    | 3         | 6%      |
| Unknown    | 3         | 6%      |
| 0x806c1    | 2         | 4%      |
| 0x6fb      | 2         | 4%      |
| 0x6f6      | 2         | 4%      |
| 0x406c3    | 2         | 4%      |
| 0x20655    | 2         | 4%      |
| 0x10676    | 2         | 4%      |
| 0x906ea    | 1         | 2%      |
| 0x906e9    | 1         | 2%      |
| 0x906a4    | 1         | 2%      |
| 0x806ec    | 1         | 2%      |
| 0x806eb    | 1         | 2%      |
| 0x806ea    | 1         | 2%      |
| 0x806e9    | 1         | 2%      |
| 0x706a1    | 1         | 2%      |
| 0x6d8      | 1         | 2%      |
| 0x506e3    | 1         | 2%      |
| 0x506c9    | 1         | 2%      |
| 0x406e3    | 1         | 2%      |
| 0x406c4    | 1         | 2%      |
| 0x40651    | 1         | 2%      |
| 0x306c3    | 1         | 2%      |
| 0x306a9    | 1         | 2%      |
| 0x30661    | 1         | 2%      |
| 0x106ca    | 1         | 2%      |
| 0x06006705 | 1         | 2%      |
| 0x06006118 | 1         | 2%      |
| 0x06001119 | 1         | 2%      |
| 0x05000119 | 1         | 2%      |
| 0x010000c8 | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Core             | 7         | 14%     |
| Silvermont       | 6         | 12%     |
| KabyLake         | 6         | 12%     |
| Penryn           | 5         | 10%     |
| SandyBridge      | 3         | 6%      |
| Westmere         | 2         | 4%      |
| TigerLake        | 2         | 4%      |
| Skylake          | 2         | 4%      |
| P6               | 2         | 4%      |
| Haswell          | 2         | 4%      |
| Excavator        | 2         | 4%      |
| Bonnell          | 2         | 4%      |
| Puma             | 1         | 2%      |
| Piledriver       | 1         | 2%      |
| K10              | 1         | 2%      |
| Jaguar           | 1         | 2%      |
| IvyBridge        | 1         | 2%      |
| Goldmont plus    | 1         | 2%      |
| Goldmont         | 1         | 2%      |
| Bobcat           | 1         | 2%      |
| Alderlake Hybrid | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 66.07%  |
| Nvidia | 11        | 19.64%  |
| AMD    | 8         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 8.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 8.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 4.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.23%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.61%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.61%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1.61%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.61%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1.61%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1.61%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.61%   |
| Intel VGA compatible controller                                                          | 1         | 1.61%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.61%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.61%   |
| Intel HD Graphics 630                                                                    | 1         | 1.61%   |
| Intel HD Graphics 620                                                                    | 1         | 1.61%   |
| Intel HD Graphics 530                                                                    | 1         | 1.61%   |
| Intel HD Graphics 515                                                                    | 1         | 1.61%   |
| Intel HD Graphics 500                                                                    | 1         | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.61%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.61%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.61%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.61%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.61%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.61%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 62%     |
| 1 x AMD        | 8         | 16%     |
| Intel + Nvidia | 6         | 12%     |
| 1 x Nvidia     | 5         | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 84.31%  |
| Proprietary | 7         | 13.73%  |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 66%     |
| 0.01-0.5   | 9         | 18%     |
| 0.51-1.0   | 3         | 6%      |
| 3.01-4.0   | 2         | 4%      |
| 1.01-2.0   | 2         | 4%      |
| 5.01-6.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 20.75%  |
| Samsung Electronics     | 8         | 15.09%  |
| LG Display              | 8         | 15.09%  |
| Chi Mei Optoelectronics | 5         | 9.43%   |
| Chimei Innolux          | 4         | 7.55%   |
| BOE                     | 4         | 7.55%   |
| Goldstar                | 2         | 3.77%   |
| Sony                    | 1         | 1.89%   |
| Seiko/Epson             | 1         | 1.89%   |
| SANYO                   | 1         | 1.89%   |
| PANDA                   | 1         | 1.89%   |
| LG Philips              | 1         | 1.89%   |
| Lenovo                  | 1         | 1.89%   |
| HannStar                | 1         | 1.89%   |
| eMachines               | 1         | 1.89%   |
| CPT                     | 1         | 1.89%   |
| BenQ                    | 1         | 1.89%   |
| Unknown                 | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                        | 1         | 1.89%   |
| Seiko/Epson LCD Monitor                                                   | 1         | 1.89%   |
| SANYO LCD SAN1207 1360x768                                                | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch      | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch      | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch      | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch     | 1         | 1.89%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch                   | 1         | 1.89%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD03E3 1366x768 309x174mm 14.0-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch               | 1         | 1.89%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 1         | 1.89%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 1.89%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                      | 1         | 1.89%   |
| Goldstar 22EA53 GSM59A5 1920x1080 480x270mm 21.7-inch                     | 1         | 1.89%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                   | 1         | 1.89%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                      | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch           | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch           | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1221 1280x800 261x163mm 12.1-inch  | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.89%   |
| BOE LCD Monitor BOE09D2 1920x1080 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 1.89%   |
| BOE LCD Monitor BOE0662 1366x768 344x194mm 15.5-inch                      | 1         | 1.89%   |
| BenQ BL2411 BNQ8011 1920x1200 518x324mm 24.1-inch                         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO44ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO3014 1280x800 261x163mm 12.1-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO219C 1920x1200 344x215mm 16.0-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO152C 1366x768 293x164mm 13.2-inch             | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO143C 1366x768 309x173mm 13.9-inch             | 1         | 1.89%   |
| Unknown                                                                   | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 20        | 37.74%  |
| 1920x1080 (FHD)   | 13        | 24.53%  |
| 1920x1200 (WUXGA) | 6         | 11.32%  |
| 1280x800 (WXGA)   | 5         | 9.43%   |
| 3840x2160 (4K)    | 2         | 3.77%   |
| 1600x900 (HD+)    | 2         | 3.77%   |
| 3840x2400         | 1         | 1.89%   |
| 1440x900 (WXGA+)  | 1         | 1.89%   |
| 1360x768          | 1         | 1.89%   |
| 1024x600          | 1         | 1.89%   |
| Unknown           | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 18        | 33.96%  |
| 17      | 7         | 13.21%  |
| 14      | 7         | 13.21%  |
| 13      | 4         | 7.55%   |
| 11      | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |
| 21      | 2         | 3.77%   |
| 12      | 2         | 3.77%   |
| 10      | 2         | 3.77%   |
| 65      | 1         | 1.89%   |
| 46      | 1         | 1.89%   |
| 24      | 1         | 1.89%   |
| 19      | 1         | 1.89%   |
| 16      | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 52.83%  |
| 201-300     | 9         | 16.98%  |
| 351-400     | 7         | 13.21%  |
| 401-500     | 3         | 5.66%   |
| Unknown     | 3         | 5.66%   |
| 1001-1500   | 2         | 3.77%   |
| 501-600     | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 71.43%  |
| 16/10   | 12        | 24.49%  |
| Unknown | 2         | 4.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 33.96%  |
| 81-90          | 9         | 16.98%  |
| 131-140        | 4         | 7.55%   |
| 51-60          | 3         | 5.66%   |
| 121-130        | 3         | 5.66%   |
| Unknown        | 3         | 5.66%   |
| 71-80          | 2         | 3.77%   |
| 61-70          | 2         | 3.77%   |
| 41-50          | 2         | 3.77%   |
| 201-250        | 2         | 3.77%   |
| More than 1000 | 1         | 1.89%   |
| 251-300        | 1         | 1.89%   |
| 151-200        | 1         | 1.89%   |
| 111-120        | 1         | 1.89%   |
| 501-1000       | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 35.29%  |
| 101-120       | 17        | 33.33%  |
| 51-100        | 8         | 15.69%  |
| Unknown       | 3         | 5.88%   |
| More than 240 | 2         | 3.92%   |
| 161-240       | 2         | 3.92%   |
| 1-50          | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 45        | 88.24%  |
| 2     | 6         | 11.76%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 31.65%  |
| Intel                 | 21        | 26.58%  |
| Qualcomm Atheros      | 18        | 22.78%  |
| Broadcom              | 8         | 10.13%  |
| Broadcom Limited      | 3         | 3.8%    |
| Sierra Wireless       | 1         | 1.27%   |
| Ralink Technology     | 1         | 1.27%   |
| Ralink                | 1         | 1.27%   |
| D-Link                | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 16        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7         | 7.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 5.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 2.08%   |
| Intel Wireless 3165                                                                           | 2         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.08%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.04%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 1.04%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.04%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 1.04%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 1.04%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.04%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.04%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.04%   |
| Intel Wireless 7265                                                                           | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.04%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 1.04%   |
| Intel Centrino Advanced-N 6200                                                                | 1         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                                      | 1         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                                                      | 1         | 1.04%   |
| Intel 82566MM Gigabit Network Connection                                                      | 1         | 1.04%   |
| D-Link WLAN controller                                                                        | 1         | 1.04%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                                      | 1         | 1.04%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                                       | 1         | 1.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                           | 1         | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                               | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express                              | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express                              | 1         | 1.04%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.04%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 36.54%  |
| Qualcomm Atheros      | 17        | 32.69%  |
| Realtek Semiconductor | 8         | 15.38%  |
| Broadcom              | 3         | 5.77%   |
| Sierra Wireless       | 1         | 1.92%   |
| Ralink Technology     | 1         | 1.92%   |
| Ralink                | 1         | 1.92%   |
| D-Link                | 1         | 1.92%   |
| Broadcom Limited      | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 9.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 5.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 3.85%   |
| Intel Wireless 3165                                                                           | 2         | 3.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 3.85%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.92%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.92%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.92%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.92%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.92%   |
| Intel Wireless 7265                                                                           | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.92%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 1.92%   |
| Intel Centrino Advanced-N 6200                                                                | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 1.92%   |
| D-Link WLAN controller                                                                        | 1         | 1.92%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.92%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 58.14%  |
| Qualcomm Atheros      | 6         | 13.95%  |
| Intel                 | 5         | 11.63%  |
| Broadcom              | 5         | 11.63%  |
| Broadcom Limited      | 2         | 4.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 36.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 15.91%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.55%   |
| Realtek USB 10/100 LAN                                            | 1         | 2.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.27%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.27%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express          | 1         | 2.27%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.27%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 2.27%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 53.26%  |
| Ethernet | 43        | 46.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 74.07%  |
| Ethernet | 14        | 25.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 82%     |
| 1     | 8         | 16%     |
| 0     | 1         | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 84%     |
| Yes  | 8         | 16%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 31.43%  |
| Realtek Semiconductor           | 6         | 17.14%  |
| Qualcomm Atheros Communications | 3         | 8.57%   |
| Lite-On Technology              | 3         | 8.57%   |
| IMC Networks                    | 3         | 8.57%   |
| Hewlett-Packard                 | 3         | 8.57%   |
| Broadcom                        | 3         | 8.57%   |
| Dell                            | 2         | 5.71%   |
| Toshiba                         | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 4         | 11.43%  |
| Realtek Bluetooth Radio                          | 3         | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 8.57%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 5.71%   |
| Intel Bluetooth Device                           | 2         | 5.71%   |
| IMC Networks Bluetooth Device                    | 2         | 5.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 2         | 5.71%   |
| Dell Wireless 355 Bluetooth                      | 2         | 5.71%   |
| Broadcom BCM2045 Bluetooth                       | 2         | 5.71%   |
| Toshiba Askey Bluetooth Module                   | 1         | 2.86%   |
| Realtek RTL8821A Bluetooth                       | 1         | 2.86%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 2.86%   |
| Lite-On Bluetooth Device                         | 1         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 2.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 2.86%   |
| IMC Networks Bluetooth USB Host Controller       | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 2.86%   |
| Broadcom HP Portable Valentine                   | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 40        | 75.47%  |
| AMD              | 8         | 15.09%  |
| Nvidia           | 4         | 7.55%   |
| Blue Microphones | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 11.11%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 7.94%   |
| AMD FCH Azalia Controller                                                                         | 4         | 6.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 3.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 3.17%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.59%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.59%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.59%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.59%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 1.59%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.59%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.59%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.59%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 25%     |
| SK hynix            | 7         | 15.91%  |
| Micron Technology   | 6         | 13.64%  |
| Unknown             | 5         | 11.36%  |
| Kingston            | 5         | 11.36%  |
| Nanya Technology    | 2         | 4.55%   |
| Elpida              | 2         | 4.55%   |
| A-DATA Technology   | 2         | 4.55%   |
| Unknown (ABCD)      | 1         | 2.27%   |
| Transcend           | 1         | 2.27%   |
| Qimonda             | 1         | 2.27%   |
| Unknown             | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 4.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 2.22%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                      | 1         | 2.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 2.22%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 2.22%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.22%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 2.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s            | 1         | 2.22%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.22%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.22%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s                | 1         | 2.22%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 2.22%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 2.22%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 2.22%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 2.22%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 2.22%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 2.22%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s              | 1         | 2.22%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 2048MT/s              | 1         | 2.22%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s            | 1         | 2.22%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 2.22%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2048MB SODIMM DDR2 2048MT/s             | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 2.22%   |
| Micron RAM 4KTF25664HZ-1G6P1 2GB SODIMM DDR3 1600MT/s               | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 2.22%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 2.22%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 2.22%   |
| Kingston RAM Module 2048MB SODIMM DDR2 667MT/s                      | 1         | 2.22%   |
| Kingston RAM Module 2048MB SODIMM DDR 667MT/s                       | 1         | 2.22%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.22%   |
| Kingston RAM ASU1333D3S9DR8/2G 2048MB SODIMM DDR3 4199MT/s          | 1         | 2.22%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 1         | 2.22%   |
| Elpida RAM FCJ41UG6BBU0-DJ-F 4GB SODIMM DDR3 1600MT/s               | 1         | 2.22%   |
| Elpida RAM EBE21UE8ACUA-8G-E 2GB SODIMM DDR2 975MT/s                | 1         | 2.22%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s                | 1         | 2.22%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s                | 1         | 2.22%   |
| Unknown                                                             | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 34.21%  |
| DDR4    | 9         | 23.68%  |
| DDR2    | 8         | 21.05%  |
| SDRAM   | 4         | 10.53%  |
| LPDDR4  | 2         | 5.26%   |
| DDR     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 35        | 97.22%  |
| DIMM   | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 14        | 34.15%  |
| 4096  | 12        | 29.27%  |
| 8192  | 8         | 19.51%  |
| 1024  | 6         | 14.63%  |
| 16384 | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 25%     |
| 2667    | 5         | 12.5%   |
| 3200    | 4         | 10%     |
| 667     | 4         | 10%     |
| 975     | 3         | 7.5%    |
| 4199    | 2         | 5%      |
| 2400    | 2         | 5%      |
| 2048    | 2         | 5%      |
| 3266    | 1         | 2.5%    |
| 1866    | 1         | 2.5%    |
| 1334    | 1         | 2.5%    |
| 1333    | 1         | 2.5%    |
| 1066    | 1         | 2.5%    |
| 800     | 1         | 2.5%    |
| 400     | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

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
| Chicony Electronics                    | 10        | 25.64%  |
| Quanta                                 | 5         | 12.82%  |
| Suyin                                  | 4         | 10.26%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 10.26%  |
| Silicon Motion                         | 3         | 7.69%   |
| IMC Networks                           | 3         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Alcor Micro                            | 2         | 5.13%   |
| Realtek Semiconductor                  | 1         | 2.56%   |
| OmniVision Technologies                | 1         | 2.56%   |
| Microdia                               | 1         | 2.56%   |
| Logitech                               | 1         | 2.56%   |
| Aveo Technology                        | 1         | 2.56%   |
| Apple                                  | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 7.69%   |
| Quanta HP TrueVision HD Camera                              | 2         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 5.13%   |
| Suyin USB 2.0 Camera                                        | 1         | 2.56%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.56%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 2.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.56%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.56%   |
| Sunplus HD WebCam                                           | 1         | 2.56%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 2.56%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 2.56%   |
| Silicon Motion Web Camera                                   | 1         | 2.56%   |
| Realtek USB Camera                                          | 1         | 2.56%   |
| Quanta VGA WebCam                                           | 1         | 2.56%   |
| Quanta HP Truevision HD                                     | 1         | 2.56%   |
| Quanta HD Webcam                                            | 1         | 2.56%   |
| OmniVision OV2640 Webcam                                    | 1         | 2.56%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 2.56%   |
| Logitech HD Webcam C615                                     | 1         | 2.56%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.56%   |
| IMC Networks EasyCamera                                     | 1         | 2.56%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.56%   |
| Chicony VGA Webcam                                          | 1         | 2.56%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.56%   |
| Chicony Integrated Camera                                   | 1         | 2.56%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 2.56%   |
| Chicony HD WebCam                                           | 1         | 2.56%   |
| Chicony FJ Camera                                           | 1         | 2.56%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.56%   |
| Aveo USB2.0 Camera                                          | 1         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 2.56%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.56%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 3         | 50%     |
| Validity Sensors      | 1         | 16.67%  |
| Samsung Electronics   | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 33.33%  |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 16.67%  |
| Samsung Fingerprint Device                  | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 16.67%  |
| AuthenTec AES1600                           | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 37        | 72.55%  |
| 1     | 12        | 23.53%  |
| 2     | 2         | 3.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 37.5%   |
| Net/wireless             | 3         | 18.75%  |
| Storage                  | 1         | 6.25%   |
| Sound                    | 1         | 6.25%   |
| Net/ethernet             | 1         | 6.25%   |
| Graphics card            | 1         | 6.25%   |
| Dvb card                 | 1         | 6.25%   |
| Communication controller | 1         | 6.25%   |
| Chipcard                 | 1         | 6.25%   |

