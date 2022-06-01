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

Total: 66

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Linux Lite 5.8 | 9         | 18.37%  |
| Linux Lite 5.4 | 9         | 18.37%  |
| Linux Lite 5.2 | 9         | 18.37%  |
| Linux Lite 5.0 | 8         | 16.33%  |
| Linux Lite 5.6 | 6         | 12.24%  |
| Linux Lite 3.8 | 3         | 6.12%   |
| Linux Lite 6.0 | 2         | 4.08%   |
| Linux Lite 4.8 | 2         | 4.08%   |
| Linux Lite 4.4 | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-40-generic                   | 4         | 7.55%   |
| 5.4.0-70-generic                   | 3         | 5.66%   |
| 5.4.0-52-generic                   | 3         | 5.66%   |
| 5.4.0-109-generic                  | 3         | 5.66%   |
| 5.4.0-90-generic                   | 2         | 3.77%   |
| 5.4.0-81-generic                   | 2         | 3.77%   |
| 5.4.0-74-generic                   | 2         | 3.77%   |
| 5.4.0-58-generic                   | 2         | 3.77%   |
| 5.4.0-42-generic                   | 2         | 3.77%   |
| 5.4.0-104-generic                  | 2         | 3.77%   |
| 5.4.0-96-generic                   | 1         | 1.89%   |
| 5.4.0-94-generic                   | 1         | 1.89%   |
| 5.4.0-91-generic                   | 1         | 1.89%   |
| 5.4.0-88-generic                   | 1         | 1.89%   |
| 5.4.0-77-generic                   | 1         | 1.89%   |
| 5.4.0-71-generic                   | 1         | 1.89%   |
| 5.4.0-66-generic                   | 1         | 1.89%   |
| 5.4.0-65-generic                   | 1         | 1.89%   |
| 5.4.0-56-generic                   | 1         | 1.89%   |
| 5.4.0-48-generic                   | 1         | 1.89%   |
| 5.4.0-33-generic                   | 1         | 1.89%   |
| 5.4.0-110-generic                  | 1         | 1.89%   |
| 5.4.0-107-generic                  | 1         | 1.89%   |
| 5.4.0-105-generic                  | 1         | 1.89%   |
| 5.4.0-100-generic                  | 1         | 1.89%   |
| 5.16.0                             | 1         | 1.89%   |
| 5.15.0-30-generic                  | 1         | 1.89%   |
| 5.15.0-27-generic                  | 1         | 1.89%   |
| 5.13.0-30-lowlatency               | 1         | 1.89%   |
| 5.10.0-051000daily20201222-generic | 1         | 1.89%   |
| 4.4.0-217-generic                  | 1         | 1.89%   |
| 4.4.0-210-generic                  | 1         | 1.89%   |
| 4.15.0-99-generic                  | 1         | 1.89%   |
| 4.15.0-91-generic                  | 1         | 1.89%   |
| 4.15.0-169-generic                 | 1         | 1.89%   |
| 4.15.0-166-generic                 | 1         | 1.89%   |
| 4.15.0-163-generic                 | 1         | 1.89%   |
| 4.15.0-162-generic                 | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 78%     |
| 4.15.0  | 4         | 8%      |
| 5.15.0  | 2         | 4%      |
| 4.4.0   | 2         | 4%      |
| 5.16.0  | 1         | 2%      |
| 5.13.0  | 1         | 2%      |
| 5.10.0  | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 78%     |
| 4.15    | 4         | 8%      |
| 5.15    | 2         | 4%      |
| 4.4     | 2         | 4%      |
| 5.16    | 1         | 2%      |
| 5.13    | 1         | 2%      |
| 5.10    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 95.83%  |
| i686   | 2         | 4.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 34        | 70.83%  |
| GNOME   | 12        | 25%     |
| Deepin  | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 97.92%  |
| Unknown | 1         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 24        | 48%     |
| TDM     | 15        | 30%     |
| Unknown | 10        | 20%     |
| GDM     | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 50%     |
| pl_PL | 4         | 8.33%   |
| fr_FR | 4         | 8.33%   |
| de_DE | 4         | 8.33%   |
| en_GB | 3         | 6.25%   |
| ru_UA | 2         | 4.17%   |
| ru_RU | 2         | 4.17%   |
| es_ES | 2         | 4.17%   |
| pt_BR | 1         | 2.08%   |
| it_IT | 1         | 2.08%   |
| es_CO | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 50%     |
| EFI  | 24        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 41        | 85.42%  |
| Overlay | 5         | 10.42%  |
| Zfs     | 1         | 2.08%   |
| Btrfs   | 1         | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 39.58%  |
| GPT     | 17        | 35.42%  |
| MBR     | 12        | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 83.33%  |
| Yes       | 8         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 69.39%  |
| Yes       | 15        | 30.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 20.83%  |
| ASUSTek Computer    | 10        | 20.83%  |
| Acer                | 9         | 18.75%  |
| Dell                | 7         | 14.58%  |
| Lenovo              | 4         | 8.33%   |
| Samsung Electronics | 2         | 4.17%   |
| TR                  | 1         | 2.08%   |
| Toshiba             | 1         | 2.08%   |
| Minix               | 1         | 2.08%   |
| Insignia            | 1         | 2.08%   |
| Google              | 1         | 2.08%   |
| Fujitsu             | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| TR ST Pro-KN                           | 1         | 2.08%   |
| Toshiba Satellite T215D                | 1         | 2.08%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 2.08%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 2.08%   |
| Minix Z64                              | 1         | 2.08%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 2.08%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 2.08%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 2.08%   |
| Lenovo 3000 V200 0764A11               | 1         | 2.08%   |
| Insignia NS-P11W7100                   | 1         | 2.08%   |
| HP Pavilion dv6500                     | 1         | 2.08%   |
| HP Laptop 17-by2xxx                    | 1         | 2.08%   |
| HP Laptop 15-dw3xxx                    | 1         | 2.08%   |
| HP Laptop 14-cm0xxx                    | 1         | 2.08%   |
| HP EliteBook Folio 9470m               | 1         | 2.08%   |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 2.08%   |
| HP Compaq CQ45                         | 1         | 2.08%   |
| HP Compaq 2510p                        | 1         | 2.08%   |
| HP 655                                 | 1         | 2.08%   |
| HP 15 Notebook PC                      | 1         | 2.08%   |
| Google Chell                           | 1         | 2.08%   |
| Fujitsu LIFEBOOK U747                  | 1         | 2.08%   |
| Dell Vostro1710                        | 1         | 2.08%   |
| Dell MXG071                            | 1         | 2.08%   |
| Dell MXG061                            | 1         | 2.08%   |
| Dell Latitude D530                     | 1         | 2.08%   |
| Dell Inspiron 7559                     | 1         | 2.08%   |
| Dell Inspiron 5452                     | 1         | 2.08%   |
| Dell Inspiron 16 5620                  | 1         | 2.08%   |
| ASUS X751LD                            | 1         | 2.08%   |
| ASUS X541SA                            | 1         | 2.08%   |
| ASUS X540YA                            | 1         | 2.08%   |
| ASUS VivoBook_ASUSLaptop E203NA_E203NA | 1         | 2.08%   |
| ASUS N750JK                            | 1         | 2.08%   |
| ASUS N53Jf                             | 1         | 2.08%   |
| ASUS K54LY                             | 1         | 2.08%   |
| ASUS K50IE                             | 1         | 2.08%   |
| ASUS 900                               | 1         | 2.08%   |
| ASUS 1001PX                            | 1         | 2.08%   |
| Acer Swift SF314-56                    | 1         | 2.08%   |
| Acer Predator PH317-52                 | 1         | 2.08%   |
| Acer Extensa 5220                      | 1         | 2.08%   |
| Acer Aspire V5-552                     | 1         | 2.08%   |
| Acer Aspire ES1-511                    | 1         | 2.08%   |
| Acer Aspire A315-53                    | 1         | 2.08%   |
| Acer Aspire 5750                       | 1         | 2.08%   |
| Acer Aspire 5600                       | 1         | 2.08%   |
| Acer Aspire 1410                       | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 6         | 12.5%   |
| HP Laptop            | 3         | 6.25%   |
| HP Compaq            | 3         | 6.25%   |
| Dell Inspiron        | 3         | 6.25%   |
| Lenovo IdeaPad       | 2         | 4.17%   |
| TR ST                | 1         | 2.08%   |
| Toshiba Satellite    | 1         | 2.08%   |
| Samsung NC110P       | 1         | 2.08%   |
| Samsung 905S3G       | 1         | 2.08%   |
| Minix Z64            | 1         | 2.08%   |
| Lenovo ThinkPad      | 1         | 2.08%   |
| Lenovo 3000          | 1         | 2.08%   |
| Insignia NS-P11W7100 | 1         | 2.08%   |
| HP Pavilion          | 1         | 2.08%   |
| HP EliteBook         | 1         | 2.08%   |
| HP 655               | 1         | 2.08%   |
| HP 15                | 1         | 2.08%   |
| Google Chell         | 1         | 2.08%   |
| Fujitsu LIFEBOOK     | 1         | 2.08%   |
| Dell Vostro1710      | 1         | 2.08%   |
| Dell MXG071          | 1         | 2.08%   |
| Dell MXG061          | 1         | 2.08%   |
| Dell Latitude        | 1         | 2.08%   |
| ASUS X751LD          | 1         | 2.08%   |
| ASUS X541SA          | 1         | 2.08%   |
| ASUS X540YA          | 1         | 2.08%   |
| ASUS VivoBook        | 1         | 2.08%   |
| ASUS N750JK          | 1         | 2.08%   |
| ASUS N53Jf           | 1         | 2.08%   |
| ASUS K54LY           | 1         | 2.08%   |
| ASUS K50IE           | 1         | 2.08%   |
| ASUS 900             | 1         | 2.08%   |
| ASUS 1001PX          | 1         | 2.08%   |
| Acer Swift           | 1         | 2.08%   |
| Acer Predator        | 1         | 2.08%   |
| Acer Extensa         | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 6         | 12.5%   |
| 2018 | 4         | 8.33%   |
| 2016 | 4         | 8.33%   |
| 2014 | 4         | 8.33%   |
| 2012 | 4         | 8.33%   |
| 2010 | 4         | 8.33%   |
| 2007 | 4         | 8.33%   |
| 2020 | 3         | 6.25%   |
| 2017 | 3         | 6.25%   |
| 2015 | 3         | 6.25%   |
| 2011 | 2         | 4.17%   |
| 2006 | 2         | 4.17%   |
| 2022 | 1         | 2.08%   |
| 2021 | 1         | 2.08%   |
| 2019 | 1         | 2.08%   |
| 2013 | 1         | 2.08%   |
| 2004 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 46        | 95.83%  |
| Enabled  | 2         | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 97.92%  |
| Yes  | 1         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 19        | 39.58%  |
| 1.01-2.0   | 10        | 20.83%  |
| 4.01-8.0   | 6         | 12.5%   |
| 16.01-24.0 | 6         | 12.5%   |
| 0.51-1.0   | 3         | 6.25%   |
| 8.01-16.0  | 2         | 4.17%   |
| 32.01-64.0 | 1         | 2.08%   |
| 2.01-3.0   | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 22        | 44%     |
| 2.01-3.0 | 11        | 22%     |
| 0.51-1.0 | 9         | 18%     |
| 3.01-4.0 | 4         | 8%      |
| 0.01-0.5 | 3         | 6%      |
| 4.01-8.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 81.25%  |
| 2      | 8         | 16.67%  |
| 3      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 56.25%  |
| Yes       | 21        | 43.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 87.5%   |
| No        | 6         | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 97.92%  |
| No        | 1         | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 68.75%  |
| No        | 15        | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 5         | 10.42%  |
| USA         | 4         | 8.33%   |
| Ukraine     | 4         | 8.33%   |
| France      | 4         | 8.33%   |
| Brazil      | 4         | 8.33%   |
| UK          | 3         | 6.25%   |
| Spain       | 3         | 6.25%   |
| Russia      | 3         | 6.25%   |
| Romania     | 3         | 6.25%   |
| Poland      | 3         | 6.25%   |
| Turkey      | 1         | 2.08%   |
| Slovakia    | 1         | 2.08%   |
| Philippines | 1         | 2.08%   |
| Netherlands | 1         | 2.08%   |
| Myanmar     | 1         | 2.08%   |
| Mexico      | 1         | 2.08%   |
| Italy       | 1         | 2.08%   |
| Guadeloupe  | 1         | 2.08%   |
| Colombia    | 1         | 2.08%   |
| Chile       | 1         | 2.08%   |
| Canada      | 1         | 2.08%   |
| Australia   | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Pabianice            | 2         | 4.08%   |
| Odessa               | 2         | 4.08%   |
| Yangon               | 1         | 2.04%   |
| Würzburg            | 1         | 2.04%   |
| Wiesbaden            | 1         | 2.04%   |
| Warsaw               | 1         | 2.04%   |
| Wahroonga            | 1         | 2.04%   |
| Voluntari            | 1         | 2.04%   |
| Vinnytsia            | 1         | 2.04%   |
| Varennes-les-Narcy   | 1         | 2.04%   |
| Valencia             | 1         | 2.04%   |
| Teresina             | 1         | 2.04%   |
| Tarragona            | 1         | 2.04%   |
| Sydney               | 1         | 2.04%   |
| Svidník             | 1         | 2.04%   |
| St. Petersburg       | 1         | 2.04%   |
| Shadrinsk            | 1         | 2.04%   |
| Sabadell             | 1         | 2.04%   |
| Queretaro            | 1         | 2.04%   |
| Paris                | 1         | 2.04%   |
| Paranaque City       | 1         | 2.04%   |
| Nudlingen            | 1         | 2.04%   |
| Novaci               | 1         | 2.04%   |
| Moscow               | 1         | 2.04%   |
| Milan                | 1         | 2.04%   |
| Marseille            | 1         | 2.04%   |
| Madrid               | 1         | 2.04%   |
| London               | 1         | 2.04%   |
| Les Abymes           | 1         | 2.04%   |
| La Glacerie          | 1         | 2.04%   |
| Kyiv                 | 1         | 2.04%   |
| Kingston upon Thames | 1         | 2.04%   |
| Jaraguá do Sul      | 1         | 2.04%   |
| Izmir                | 1         | 2.04%   |
| Frankfurt am Main    | 1         | 2.04%   |
| Eggenfelden          | 1         | 2.04%   |
| Edmonton             | 1         | 2.04%   |
| Didsbury             | 1         | 2.04%   |
| Des Moines           | 1         | 2.04%   |
| Cotia                | 1         | 2.04%   |
| Coquimbo             | 1         | 2.04%   |
| Constanța           | 1         | 2.04%   |
| Cheboksary           | 1         | 2.04%   |
| Cabedelo             | 1         | 2.04%   |
| Brooklyn             | 1         | 2.04%   |
| Bogotá              | 1         | 2.04%   |
| Unknown              | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 21.82%  |
| WDC                 | 8         | 11     | 14.55%  |
| Toshiba             | 7         | 8      | 12.73%  |
| Samsung Electronics | 5         | 6      | 9.09%   |
| Kingston            | 4         | 4      | 7.27%   |
| Unknown             | 3         | 4      | 5.45%   |
| SanDisk             | 2         | 2      | 3.64%   |
| Micron Technology   | 2         | 3      | 3.64%   |
| Hitachi             | 2         | 2      | 3.64%   |
| HGST                | 2         | 2      | 3.64%   |
| GOODRAM             | 2         | 2      | 3.64%   |
| SK Hynix            | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| Crucial             | 1         | 1      | 1.82%   |
| ASUS-PHISON         | 1         | 2      | 1.82%   |
| ASMT                | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB              | 3         | 5.26%   |
| Unknown MMC Card  32GB                | 2         | 3.51%   |
| Seagate ST9320325AS 320GB             | 2         | 3.51%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 3.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1.75%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1.75%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 1.75%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.75%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.75%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.75%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 1.75%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 1.75%   |
| Unknown SD64G  64GB                   | 1         | 1.75%   |
| Unknown NCard  32GB                   | 1         | 1.75%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1.75%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.75%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 1.75%   |
| Toshiba MK1011GAH 100GB               | 1         | 1.75%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.75%   |
| Seagate ST9500423AS 500GB             | 1         | 1.75%   |
| Seagate ST9160823ASG 160GB            | 1         | 1.75%   |
| Seagate ST9160301AS 160GB             | 1         | 1.75%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 1.75%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1.75%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1.75%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1.75%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 1.75%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1.75%   |
| SanDisk Z400s M.2 2280 128GB SSD      | 1         | 1.75%   |
| SanDisk DF4032  32GB                  | 1         | 1.75%   |
| Samsung SSD 980 250GB                 | 1         | 1.75%   |
| Samsung PM991a NVMe 1024GB            | 1         | 1.75%   |
| Samsung MZVKW512HMJP-00007 512GB      | 1         | 1.75%   |
| Samsung MZMTD128HAFV-000 128GB SSD    | 1         | 1.75%   |
| Samsung HM160HI 160GB                 | 1         | 1.75%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 1         | 1.75%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD   | 1         | 1.75%   |
| LITEON CV5-8Q512 512GB SSD            | 1         | 1.75%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1.75%   |
| Kingston RBUSNS8154P3128GJ1 128GB     | 1         | 1.75%   |
| Intel SSDSA2CW080G3 80GB              | 1         | 1.75%   |
| Hitachi HTS723216L9SA60 160GB         | 1         | 1.75%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1.75%   |
| HGST HTS725050A7E630 500GB            | 1         | 1.75%   |
| HGST HTS721010A9E630 1TB              | 1         | 1.75%   |
| GOODRAM SSDPR-CL100-120-G3 120GB      | 1         | 1.75%   |
| GOODRAM IR-SSDPR-S25A-240 240GB       | 1         | 1.75%   |
| Crucial CT120BX500SSD1 120GB          | 1         | 1.75%   |
| ASUS-PHISON SSD 16GB                  | 1         | 1.75%   |
| ASUS-PHISON OB S 4GB SSD              | 1         | 1.75%   |
| ASMT USB 3.0 Destop H 1TB SSD         | 1         | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 41.38%  |
| Toshiba             | 7         | 8      | 24.14%  |
| WDC                 | 5         | 7      | 17.24%  |
| Hitachi             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 2      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 18.75%  |
| Micron Technology   | 2         | 3      | 12.5%   |
| GOODRAM             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| SK Hynix            | 1         | 1      | 6.25%   |
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
| HDD  | 29        | 33     | 54.72%  |
| SSD  | 15        | 18     | 28.3%   |
| NVMe | 5         | 7      | 9.43%   |
| MMC  | 4         | 5      | 7.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 49     | 78%     |
| NVMe | 5         | 7      | 10%     |
| MMC  | 4         | 5      | 8%      |
| SAS  | 2         | 2      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 40     | 75%     |
| 0.51-1.0   | 10        | 10     | 22.73%  |
| 1.01-2.0   | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 32.65%  |
| 251-500        | 13        | 26.53%  |
| 1-20           | 7         | 14.29%  |
| 51-100         | 5         | 10.2%   |
| 21-50          | 4         | 8.16%   |
| 501-1000       | 3         | 6.12%   |
| More than 3000 | 1         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 62%     |
| 21-50     | 7         | 14%     |
| 51-100    | 6         | 12%     |
| 101-250   | 5         | 10%     |
| 2001-3000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB        | 1         | 1      | 16.67%  |
| Seagate ST9500423AS 500GB       | 1         | 1      | 16.67%  |
| Seagate ST9320325AS 320GB       | 1         | 1      | 16.67%  |
| Seagate ST9160823ASG 160GB      | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 16.67%  |
| Hitachi HTS545016B9A300 160GB   | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

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
| Detected | 23        | 33     | 46.94%  |
| Works    | 20        | 24     | 40.82%  |
| Malfunc  | 6         | 6      | 12.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 36        | 72%     |
| AMD                         | 7         | 14%     |
| Samsung Electronics         | 3         | 6%      |
| Sandisk                     | 2         | 4%      |
| Nvidia                      | 1         | 2%      |
| Kingston Technology Company | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 11.48%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 9.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 6.56%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.28%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 3.28%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 3.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 3.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 3.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.64%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.64%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.64%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.64%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.64%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.64%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 64.91%  |
| IDE  | 12        | 21.05%  |
| NVMe | 5         | 8.77%   |
| RAID | 3         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 85.42%  |
| AMD    | 7         | 14.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core 2 CPU T7600 @ 2.33GHz                | 2         | 4.17%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 2.08%   |
| Intel Pentium CPU N3710 @ 1.60GHz               | 1         | 2.08%   |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 2.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 2.08%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2.08%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 2.08%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz                | 1         | 2.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.08%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 2.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 2.08%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 2.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.08%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 2.08%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 2.08%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 2.08%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 2.08%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 2.08%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 2.08%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2.08%   |
| Intel Celeron M processor 900MHz                | 1         | 2.08%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 2.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 2.08%   |
| Intel Celeron CPU B830 @ 1.80GHz                | 1         | 2.08%   |
| Intel Celeron CPU 723 @ 1.20GHz                 | 1         | 2.08%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 2.08%   |
| Intel Atom CPU Z3735F @ 1.33GHz                 | 1         | 2.08%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 1         | 2.08%   |
| Intel Atom CPU N2600 @ 1.60GHz                  | 1         | 2.08%   |
| Intel 12th Gen Core i7-1255U                    | 1         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2.08%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 1         | 2.08%   |
| AMD Quad-Core Processor (up to 1.4GHz)          | 1         | 2.08%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G   | 1         | 2.08%   |
| AMD E2-1800 APU with Radeon HD Graphics         | 1         | 2.08%   |
| AMD Athlon II Neo K125 Processor                | 1         | 2.08%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.08%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 2.08%   |
| AMD A10-5757M APU with Radeon HD Graphics       | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 8         | 16.67%  |
| Intel Core i7           | 5         | 10.42%  |
| Intel Pentium           | 4         | 8.33%   |
| Intel Core i3           | 4         | 8.33%   |
| Intel Celeron           | 4         | 8.33%   |
| Intel Atom              | 4         | 8.33%   |
| Other                   | 3         | 6.25%   |
| Intel Core i5           | 3         | 6.25%   |
| Intel Core 2            | 2         | 4.17%   |
| AMD E2                  | 2         | 4.17%   |
| Intel Pentium Dual-Core | 1         | 2.08%   |
| Intel Genuine           | 1         | 2.08%   |
| Intel Core m7           | 1         | 2.08%   |
| Intel Celeron M         | 1         | 2.08%   |
| AMD Quad-Core           | 1         | 2.08%   |
| AMD Athlon II Neo       | 1         | 2.08%   |
| AMD A8                  | 1         | 2.08%   |
| AMD A12                 | 1         | 2.08%   |
| AMD A10                 | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 60.42%  |
| 4      | 13        | 27.08%  |
| 1      | 4         | 8.33%   |
| 10     | 1         | 2.08%   |
| 6      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 58.33%  |
| 2      | 20        | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 95.83%  |
| 32-bit         | 2         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x6fd      | 3         | 6.25%   |
| 0x30678    | 3         | 6.25%   |
| 0x206a7    | 3         | 6.25%   |
| 0x1067a    | 3         | 6.25%   |
| Unknown    | 3         | 6.25%   |
| 0x806c1    | 2         | 4.17%   |
| 0x6fb      | 2         | 4.17%   |
| 0x6f6      | 2         | 4.17%   |
| 0x406c3    | 2         | 4.17%   |
| 0x10676    | 2         | 4.17%   |
| 0x906ea    | 1         | 2.08%   |
| 0x906e9    | 1         | 2.08%   |
| 0x906a4    | 1         | 2.08%   |
| 0x806ec    | 1         | 2.08%   |
| 0x806eb    | 1         | 2.08%   |
| 0x806ea    | 1         | 2.08%   |
| 0x806e9    | 1         | 2.08%   |
| 0x6d8      | 1         | 2.08%   |
| 0x506e3    | 1         | 2.08%   |
| 0x506c9    | 1         | 2.08%   |
| 0x406e3    | 1         | 2.08%   |
| 0x406c4    | 1         | 2.08%   |
| 0x40651    | 1         | 2.08%   |
| 0x306c3    | 1         | 2.08%   |
| 0x306a9    | 1         | 2.08%   |
| 0x30661    | 1         | 2.08%   |
| 0x20655    | 1         | 2.08%   |
| 0x106ca    | 1         | 2.08%   |
| 0x06006705 | 1         | 2.08%   |
| 0x06006118 | 1         | 2.08%   |
| 0x06001119 | 1         | 2.08%   |
| 0x05000119 | 1         | 2.08%   |
| 0x010000c8 | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Core             | 7         | 14.58%  |
| Silvermont       | 6         | 12.5%   |
| KabyLake         | 6         | 12.5%   |
| Penryn           | 5         | 10.42%  |
| SandyBridge      | 3         | 6.25%   |
| TigerLake        | 2         | 4.17%   |
| Skylake          | 2         | 4.17%   |
| P6               | 2         | 4.17%   |
| Haswell          | 2         | 4.17%   |
| Excavator        | 2         | 4.17%   |
| Bonnell          | 2         | 4.17%   |
| Westmere         | 1         | 2.08%   |
| Puma             | 1         | 2.08%   |
| Piledriver       | 1         | 2.08%   |
| K10              | 1         | 2.08%   |
| Jaguar           | 1         | 2.08%   |
| IvyBridge        | 1         | 2.08%   |
| Goldmont         | 1         | 2.08%   |
| Bobcat           | 1         | 2.08%   |
| Alderlake Hybrid | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 64.81%  |
| Nvidia | 11        | 20.37%  |
| AMD    | 8         | 14.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 8.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 8.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 5%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.33%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.67%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.67%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1.67%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.67%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1.67%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1.67%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.67%   |
| Intel VGA compatible controller                                                          | 1         | 1.67%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.67%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.67%   |
| Intel HD Graphics 630                                                                    | 1         | 1.67%   |
| Intel HD Graphics 620                                                                    | 1         | 1.67%   |
| Intel HD Graphics 530                                                                    | 1         | 1.67%   |
| Intel HD Graphics 515                                                                    | 1         | 1.67%   |
| Intel HD Graphics 500                                                                    | 1         | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.67%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.67%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.67%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 60.42%  |
| 1 x AMD        | 8         | 16.67%  |
| Intel + Nvidia | 6         | 12.5%   |
| 1 x Nvidia     | 5         | 10.42%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 41        | 83.67%  |
| Proprietary | 7         | 14.29%  |
| Unknown     | 1         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 64.58%  |
| 0.01-0.5   | 9         | 18.75%  |
| 0.51-1.0   | 3         | 6.25%   |
| 3.01-4.0   | 2         | 4.17%   |
| 1.01-2.0   | 2         | 4.17%   |
| 5.01-6.0   | 1         | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 19.61%  |
| Samsung Electronics     | 8         | 15.69%  |
| LG Display              | 8         | 15.69%  |
| Chi Mei Optoelectronics | 5         | 9.8%    |
| Chimei Innolux          | 4         | 7.84%   |
| BOE                     | 4         | 7.84%   |
| Goldstar                | 2         | 3.92%   |
| Sony                    | 1         | 1.96%   |
| Seiko/Epson             | 1         | 1.96%   |
| Sanyo                   | 1         | 1.96%   |
| LG Philips              | 1         | 1.96%   |
| Lenovo                  | 1         | 1.96%   |
| HannStar                | 1         | 1.96%   |
| eMachines               | 1         | 1.96%   |
| CPT                     | 1         | 1.96%   |
| BenQ                    | 1         | 1.96%   |
| Unknown                 | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sony TV *00 SNY8004 3840x2160 1218x685mm 55.0-inch                        | 1         | 1.96%   |
| Seiko/Epson LCD Monitor                                                   | 1         | 1.96%   |
| Sanyo LCD SAN1207 1360x768                                                | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch     | 1         | 1.96%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD03E3 1366x768 310x174mm 14.0-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 1         | 1.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 1.96%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                      | 1         | 1.96%   |
| Goldstar 22EA53 GSM59A5 1920x1080 480x270mm 21.7-inch                     | 1         | 1.96%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                   | 1         | 1.96%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch           | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch           | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1221 1280x800 261x163mm 12.1-inch  | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.96%   |
| BOE LCD Monitor BOE09D2 1920x1080 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 1.96%   |
| BOE LCD Monitor BOE0662 1366x768 344x194mm 15.5-inch                      | 1         | 1.96%   |
| BenQ BL2411 BNQ8011 1920x1200 518x324mm 24.1-inch                         | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO44ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO3014 1280x800 261x163mm 12.1-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO219C 1920x1200 344x215mm 16.0-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO152C 1366x768 293x164mm 13.2-inch             | 1         | 1.96%   |
| Unknown                                                                   | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 19        | 37.25%  |
| 1920x1080 (FHD)   | 12        | 23.53%  |
| 1920x1200 (WUXGA) | 6         | 11.76%  |
| 1280x800 (WXGA)   | 5         | 9.8%    |
| 3840x2160 (4K)    | 2         | 3.92%   |
| 1600x900 (HD+)    | 2         | 3.92%   |
| 3200x1800 (QHD+)  | 1         | 1.96%   |
| 1440x900 (WXGA+)  | 1         | 1.96%   |
| 1360x768          | 1         | 1.96%   |
| 1024x600          | 1         | 1.96%   |
| Unknown           | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 18        | 35.29%  |
| 17      | 7         | 13.73%  |
| 14      | 6         | 11.76%  |
| 13      | 3         | 5.88%   |
| 11      | 3         | 5.88%   |
| Unknown | 3         | 5.88%   |
| 21      | 2         | 3.92%   |
| 12      | 2         | 3.92%   |
| 10      | 2         | 3.92%   |
| 65      | 1         | 1.96%   |
| 40      | 1         | 1.96%   |
| 24      | 1         | 1.96%   |
| 19      | 1         | 1.96%   |
| 16      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 50.98%  |
| 201-300     | 9         | 17.65%  |
| 351-400     | 7         | 13.73%  |
| 401-500     | 3         | 5.88%   |
| Unknown     | 3         | 5.88%   |
| 801-900     | 1         | 1.96%   |
| 501-600     | 1         | 1.96%   |
| 1001-1500   | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 72.34%  |
| 16/10   | 11        | 23.4%   |
| Unknown | 2         | 4.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 35.29%  |
| 81-90          | 7         | 13.73%  |
| 131-140        | 4         | 7.84%   |
| 51-60          | 3         | 5.88%   |
| 121-130        | 3         | 5.88%   |
| Unknown        | 3         | 5.88%   |
| 71-80          | 2         | 3.92%   |
| 61-70          | 2         | 3.92%   |
| 41-50          | 2         | 3.92%   |
| 201-250        | 2         | 3.92%   |
| More than 1000 | 1         | 1.96%   |
| 251-300        | 1         | 1.96%   |
| 151-200        | 1         | 1.96%   |
| 111-120        | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 36.73%  |
| 101-120       | 16        | 32.65%  |
| 51-100        | 9         | 18.37%  |
| Unknown       | 3         | 6.12%   |
| More than 240 | 2         | 4.08%   |
| 161-240       | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 87.76%  |
| 2     | 6         | 12.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 32.47%  |
| Intel                 | 19        | 24.68%  |
| Qualcomm Atheros      | 18        | 23.38%  |
| Broadcom              | 8         | 10.39%  |
| Broadcom Limited      | 3         | 3.9%    |
| Sierra Wireless       | 1         | 1.3%    |
| Ralink Technology     | 1         | 1.3%    |
| Ralink                | 1         | 1.3%    |
| D-Link                | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 16        | 17.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 7         | 7.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 5.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 4.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 2.15%   |
| Intel Wireless 3165                                                                           | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.15%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.08%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 1.08%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.08%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 1.08%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 1.08%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.08%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.08%   |
| Intel Wireless 7265                                                                           | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.08%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                                      | 1         | 1.08%   |
| Intel 82566MM Gigabit Network Connection                                                      | 1         | 1.08%   |
| D-Link WLAN controller                                                                        | 1         | 1.08%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                                      | 1         | 1.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                                       | 1         | 1.08%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                           | 1         | 1.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 1         | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                               | 1         | 1.08%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express                              | 1         | 1.08%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express                              | 1         | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 17        | 34%     |
| Intel                 | 17        | 34%     |
| Realtek Semiconductor | 8         | 16%     |
| Broadcom              | 3         | 6%      |
| Sierra Wireless       | 1         | 2%      |
| Ralink Technology     | 1         | 2%      |
| Ralink                | 1         | 2%      |
| D-Link                | 1         | 2%      |
| Broadcom Limited      | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 10%     |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 8%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 6%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 6%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 2         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 4%      |
| Intel Wireless 3165                                                                           | 2         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 4%      |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2%      |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 2%      |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 2%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2%      |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 2%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 2%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 2%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 2%      |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 2%      |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2%      |
| Intel Wireless 7265                                                                           | 1         | 2%      |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 2%      |
| Intel Centrino Wireless-N 130                                                                 | 1         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 2%      |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 2%      |
| D-Link WLAN controller                                                                        | 1         | 2%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 59.52%  |
| Qualcomm Atheros      | 6         | 14.29%  |
| Broadcom              | 5         | 11.9%   |
| Intel                 | 4         | 9.52%   |
| Broadcom Limited      | 2         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 37.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 16.28%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.65%   |
| Realtek USB 10/100 LAN                                            | 1         | 2.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.33%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express          | 1         | 2.33%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.33%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 2.33%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 52.81%  |
| Ethernet | 42        | 47.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 73.08%  |
| Ethernet | 14        | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 83.33%  |
| 1     | 7         | 14.58%  |
| 0     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 85.42%  |
| Yes  | 7         | 14.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 30.3%   |
| Realtek Semiconductor           | 6         | 18.18%  |
| Qualcomm Atheros Communications | 3         | 9.09%   |
| Lite-On Technology              | 3         | 9.09%   |
| IMC Networks                    | 3         | 9.09%   |
| Broadcom                        | 3         | 9.09%   |
| Hewlett-Packard                 | 2         | 6.06%   |
| Dell                            | 2         | 6.06%   |
| Toshiba                         | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 4         | 12.12%  |
| Intel Bluetooth wireless interface               | 4         | 12.12%  |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 6.06%   |
| IMC Networks Bluetooth Device                    | 2         | 6.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 2         | 6.06%   |
| Dell Wireless 355 Bluetooth                      | 2         | 6.06%   |
| Broadcom BCM2045 Bluetooth                       | 2         | 6.06%   |
| Toshiba Askey Bluetooth Module                   | 1         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 3.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 3.03%   |
| Lite-On Bluetooth Device                         | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 3.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.03%   |
| Intel Bluetooth Device                           | 1         | 3.03%   |
| Intel AX201 Bluetooth                            | 1         | 3.03%   |
| IMC Networks Bluetooth USB Host Controller       | 1         | 3.03%   |
| Broadcom HP Portable Valentine                   | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 38        | 74.51%  |
| AMD              | 8         | 15.69%  |
| Nvidia           | 4         | 7.84%   |
| Blue Microphones | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 11.48%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 8.2%    |
| AMD FCH Azalia Controller                                                                         | 4         | 6.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 4.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 3.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 3.28%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.64%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.64%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.64%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.64%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.64%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 1.64%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.64%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.64%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 23.81%  |
| SK Hynix            | 7         | 16.67%  |
| Micron Technology   | 6         | 14.29%  |
| Unknown             | 5         | 11.9%   |
| Kingston            | 5         | 11.9%   |
| Nanya Technology    | 2         | 4.76%   |
| Elpida              | 2         | 4.76%   |
| A-DATA Technology   | 2         | 4.76%   |
| Transcend           | 1         | 2.38%   |
| Qimonda             | 1         | 2.38%   |
| Unknown             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 4.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 1         | 2.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s             | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s              | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s              | 1         | 2.33%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s              | 1         | 2.33%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s       | 1         | 2.33%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 2.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 2.33%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 2.33%   |
| SK Hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s       | 1         | 2.33%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 2.33%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s   | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 1         | 2.33%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s  | 1         | 2.33%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s   | 1         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 2.33%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s      | 1         | 2.33%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s     | 1         | 2.33%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s      | 1         | 2.33%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s   | 1         | 2.33%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s       | 1         | 2.33%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 2048MT/s        | 1         | 2.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 1         | 2.33%   |
| Micron RAM 4KTF25664HZ-1G6P1 2GB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 1         | 2.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s      | 1         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s       | 1         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 1         | 2.33%   |
| Kingston RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 2.33%   |
| Kingston RAM Module 2048MB SODIMM DDR 667MT/s              | 1         | 2.33%   |
| Kingston RAM KN2M64-ETB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Kingston RAM ASU1333D3S9DR8/2G 2048MB SODIMM DDR3 4199MT/s | 1         | 2.33%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s | 1         | 2.33%   |
| ELPIDA RAM FCJ41UG6BBU0-DJ-F 4GB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Elpida RAM EBE21UE8ACUA-8G-E 2GB SODIMM DDR2 975MT/s       | 1         | 2.33%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s       | 1         | 2.33%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s       | 1         | 2.33%   |
| Unknown                                                    | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 12        | 33.33%  |
| DDR4    | 9         | 25%     |
| DDR2    | 8         | 22.22%  |
| SDRAM   | 4         | 11.11%  |
| LPDDR4  | 1         | 2.78%   |
| DDR     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 33        | 97.06%  |
| DIMM   | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 13        | 33.33%  |
| 4096  | 11        | 28.21%  |
| 8192  | 8         | 20.51%  |
| 1024  | 6         | 15.38%  |
| 16384 | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 26.32%  |
| 2667    | 5         | 13.16%  |
| 3200    | 4         | 10.53%  |
| 667     | 4         | 10.53%  |
| 975     | 3         | 7.89%   |
| 4199    | 2         | 5.26%   |
| 2048    | 2         | 5.26%   |
| 3266    | 1         | 2.63%   |
| 2400    | 1         | 2.63%   |
| 1866    | 1         | 2.63%   |
| 1333    | 1         | 2.63%   |
| 1066    | 1         | 2.63%   |
| 800     | 1         | 2.63%   |
| 400     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

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
| Chicony Electronics                    | 10        | 26.32%  |
| Quanta                                 | 5         | 13.16%  |
| Suyin                                  | 4         | 10.53%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 10.53%  |
| IMC Networks                           | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Silicon Motion                         | 2         | 5.26%   |
| Alcor Micro                            | 2         | 5.26%   |
| Realtek Semiconductor                  | 1         | 2.63%   |
| OmniVision Technologies                | 1         | 2.63%   |
| Microdia                               | 1         | 2.63%   |
| Logitech                               | 1         | 2.63%   |
| Aveo Technology                        | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 7.89%   |
| Quanta HP TrueVision HD Camera                              | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 5.26%   |
| Suyin USB 2.0 Camera                                        | 1         | 2.63%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.63%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 1         | 2.63%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.63%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.63%   |
| Sunplus HD WebCam                                           | 1         | 2.63%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 2.63%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 2.63%   |
| Realtek USB Camera                                          | 1         | 2.63%   |
| Quanta VGA WebCam                                           | 1         | 2.63%   |
| Quanta HP Truevision HD                                     | 1         | 2.63%   |
| Quanta HD Webcam                                            | 1         | 2.63%   |
| OmniVision OV2640 Webcam                                    | 1         | 2.63%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 2.63%   |
| Logitech HD Webcam C615                                     | 1         | 2.63%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.63%   |
| IMC Networks EasyCamera                                     | 1         | 2.63%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.63%   |
| Chicony VGA Webcam                                          | 1         | 2.63%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.63%   |
| Chicony Integrated Camera                                   | 1         | 2.63%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 2.63%   |
| Chicony HD WebCam                                           | 1         | 2.63%   |
| Chicony FJ Camera                                           | 1         | 2.63%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.63%   |
| Aveo USB2.0 Camera                                          | 1         | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 2.63%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.63%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 3         | 75%     |
| LighTuning Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 50%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 25%     |
| AuthenTec AES1600                           | 1         | 25%     |

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
| 0     | 37        | 75.51%  |
| 1     | 10        | 20.41%  |
| 2     | 2         | 4.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 4         | 28.57%  |
| Net/wireless             | 3         | 21.43%  |
| Storage                  | 1         | 7.14%   |
| Sound                    | 1         | 7.14%   |
| Net/ethernet             | 1         | 7.14%   |
| Graphics card            | 1         | 7.14%   |
| Dvb card                 | 1         | 7.14%   |
| Communication controller | 1         | 7.14%   |
| Chipcard                 | 1         | 7.14%   |

