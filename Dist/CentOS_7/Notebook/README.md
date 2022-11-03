CentOS 7 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 80

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | G752VSK                     | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Dell     | Inspiron 3584               | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell     | Inspiron 3584               | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| HP       | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X712... | [8120719b26](https://linux-hardware.org/?probe=8120719b26) | May 26, 2022 |
| Dell     | Vostro 5581                 | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Lenovo   | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo   | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Acer     | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer     | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell     | Vostro 14 5410              | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| Dell     | Vostro 14 5410              | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| HP       | EliteBook 8540w             | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Dell     | Latitude E6530              | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| Apple    | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| HP       | EliteBook 8540w             | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP       | EliteBook 2740p             | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| HP       | EliteBook 8540w             | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP       | Presario C700               | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Lenovo   | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Lenovo   | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| ASUSTek  | U35JC                       | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo   | ThinkPad X200 7459ZEJ       | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| Lenovo   | IdeaPad 310-15ISK 80UH      | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| Dell     | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| HP       | ProBook 6560b               | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| Lenovo   | ThinkPad T520 4243Y1N       | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| HP       | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Acer     | Aspire E1-572               | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| Toshiba  | Satellite A135              | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo   | ThinkPad X200 7459H92       | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| Dell     | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Samsung  | 300E5EV/300E4EV/270E5EV/... | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Dell     | Latitude E6410              | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| Lenovo   | G500s 20245                 | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell     | Latitude E6410              | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| Dell     | Inspiron 3542               | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell     | Inspiron 3542               | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown  | 34AS1                       | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown  | 34AS1                       | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell     | Inspiron 3542               | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell     | Inspiron 3542               | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP       | EliteBook 6930p             | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell     | Inspiron 5567               | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| Dell     | Inspiron N4050              | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| HP       | Falco                       | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell     | Inspiron N4050              | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| HP       | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| HP       | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| Acer     | Aspire 5750G                | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell     | Latitude E6220              | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell     | Latitude E6220              | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| Toshiba  | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| Dell     | Inspiron 5437               | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell     | Inspiron 5437               | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| Dell     | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Sony     | VGN-N19VP_B                 | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| Lenovo   | ThinkPad P53 20QNS00Y00     | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo   | ThinkPad P53 20QNS00Y00     | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| HP       | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP       | ZBook 17                    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| Sony     | VPCSB19GG                   | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| HP       | EliteBook x360 1040 G6      | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| Lenovo   | Y520-15IKBN 80WK            | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Lenovo   | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell     | System XPS L702X            | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| MSI      | GL63 8SD                    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| Dell     | Vostro 5568                 | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| HP       | Pavilion 15                 | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP       | Pavilion 15                 | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP       | Pavilion 15                 | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| MSI      | GP62MVR 7RFX                | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook | WA50SRQ                     | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| Dell     | Precision M4600             | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| Dell     | Vostro 5470                 | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| ASUSTek  | X540SC                      | [f513215ec6](https://linux-hardware.org/?probe=f513215ec6) | Jan 09, 2019 |
| Lenovo   | ThinkPad T440p 20AWS27B0... | [000dae069a](https://linux-hardware.org/?probe=000dae069a) | Oct 31, 2018 |
| Lenovo   | ThinkPad T530 2394AG6       | [6b8015f1e2](https://linux-hardware.org/?probe=6b8015f1e2) | Oct 26, 2018 |
| Lenovo   | ThinkPad T530 2394AG6       | [c834cadf29](https://linux-hardware.org/?probe=c834cadf29) | Oct 26, 2018 |
| HP       | EliteBook 2740p             | [1b72dbb418](https://linux-hardware.org/?probe=1b72dbb418) | Sep 17, 2017 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                               | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| 3.10.0-957.27.2.el7.x86_64            | 3         | 5%      |
| 3.10.0-957.10.1.el7.x86_64            | 3         | 5%      |
| 3.10.0-1160.66.1.el7.x86_64           | 3         | 5%      |
| 3.10.0-1160.15.2.el7.x86_64           | 3         | 5%      |
| 3.10.0-1127.19.1.el7.x86_64           | 3         | 5%      |
| 3.10.0-957.el7.x86_64                 | 2         | 3.33%   |
| 3.10.0-957.1.3.el7.x86_64             | 2         | 3.33%   |
| 3.10.0-862.14.4.el7.x86_64            | 2         | 3.33%   |
| 3.10.0-1160.45.1.el7.x86_64           | 2         | 3.33%   |
| 3.10.0-1127.el7.x86_64                | 2         | 3.33%   |
| 3.10.0-1127.18.2.el7.x86_64           | 2         | 3.33%   |
| 3.10.0-1127.18.2.el7.centos.plus.i686 | 2         | 3.33%   |
| 3.10.0-1127.13.1.el7.x86_64           | 2         | 3.33%   |
| 3.10.0-1062.9.1.el7.x86_64            | 2         | 3.33%   |
| 3.10.0-1062.4.3.el7.x86_64            | 2         | 3.33%   |
| 3.10.0-1062.12.1.el7.x86_64           | 2         | 3.33%   |
| 5.8.13-1.el7.elrepo.x86_64            | 1         | 1.67%   |
| 5.6.8-1.el7.elrepo.x86_64             | 1         | 1.67%   |
| 5.4.6-1.el7.elrepo.x86_64             | 1         | 1.67%   |
| 5.4.125-200.el7.x86_64                | 1         | 1.67%   |
| 5.4.121-200.el7.x86_64                | 1         | 1.67%   |
| 5.11.0-1.el7.elrepo.x86_64            | 1         | 1.67%   |
| 5.10.75-200.el7.x86_64                | 1         | 1.67%   |
| 4.20.8-1.el7.elrepo.x86_64            | 1         | 1.67%   |
| 4.19.8-1.el7.elrepo.x86_64            | 1         | 1.67%   |
| 3.10.0-957.21.3.el7.x86_64            | 1         | 1.67%   |
| 3.10.0-693.2.2.el7.x86_64             | 1         | 1.67%   |
| 3.10.0-1160.el7.x86_64                | 1         | 1.67%   |
| 3.10.0-1160.62.1.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1160.49.1.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1160.42.2.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1160.2.2.el7.x86_64            | 1         | 1.67%   |
| 3.10.0-1160.11.1.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1127.10.1.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1062.4.1.el7.x86_64            | 1         | 1.67%   |
| 3.10.0-1062.18.1.el7.x86_64           | 1         | 1.67%   |
| 3.10.0-1062.18.1.el7.centos.plus.i686 | 1         | 1.67%   |
| 3.10.0-1062.1.2.el7.x86_64            | 1         | 1.67%   |
| 3.10.0-1062.1.1.el7.x86_64            | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 3.10.0  | 51        | 85%     |
| 5.8.13  | 1         | 1.67%   |
| 5.6.8   | 1         | 1.67%   |
| 5.4.6   | 1         | 1.67%   |
| 5.4.125 | 1         | 1.67%   |
| 5.4.121 | 1         | 1.67%   |
| 5.11.0  | 1         | 1.67%   |
| 5.10.75 | 1         | 1.67%   |
| 4.20.8  | 1         | 1.67%   |
| 4.19.8  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 3.10    | 51        | 86.44%  |
| 5.4     | 2         | 3.39%   |
| 5.8     | 1         | 1.69%   |
| 5.6     | 1         | 1.69%   |
| 5.11    | 1         | 1.69%   |
| 5.10    | 1         | 1.69%   |
| 4.20    | 1         | 1.69%   |
| 4.19    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 94.83%  |
| i686   | 3         | 5.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 18        | 31.03%  |
| KDE4          | 12        | 20.69%  |
| GNOME Classic | 9         | 15.52%  |
| Unknown       | 8         | 13.79%  |
| MATE          | 5         | 8.62%   |
| Cinnamon      | 4         | 6.9%    |
| XFCE          | 2         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 96.55%  |
| Unknown | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 36        | 61.02%  |
| Unknown | 18        | 30.51%  |
| LightDM | 3         | 5.08%   |
| TDM     | 2         | 3.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 26        | 44.07%  |
| Unknown     | 13        | 22.03%  |
| en_GB       | 4         | 6.78%   |
| ru_RU       | 3         | 5.08%   |
| pt_BR       | 2         | 3.39%   |
| pl_PL       | 2         | 3.39%   |
| fr_FR       | 2         | 3.39%   |
| zh_CN       | 1         | 1.69%   |
| pt_PT       | 1         | 1.69%   |
| ja_JP       | 1         | 1.69%   |
| es_ES       | 1         | 1.69%   |
| es_AR       | 1         | 1.69%   |
| en_US.utf-8 | 1         | 1.69%   |
| de_DE       | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 72.88%  |
| EFI  | 16        | 27.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 32        | 54.24%  |
| Ext4    | 20        | 33.9%   |
| Unknown | 5         | 8.47%   |
| Overlay | 1         | 1.69%   |
| Ext2    | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 22        | 37.29%  |
| GPT     | 21        | 35.59%  |
| Unknown | 16        | 27.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 84.48%  |
| Yes       | 9         | 15.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 81.36%  |
| Yes       | 11        | 18.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 18        | 31.03%  |
| Lenovo              | 12        | 20.69%  |
| Hewlett-Packard     | 12        | 20.69%  |
| ASUSTek Computer    | 4         | 6.9%    |
| Toshiba             | 2         | 3.45%   |
| Sony                | 2         | 3.45%   |
| MSI                 | 2         | 3.45%   |
| Acer                | 2         | 3.45%   |
| Samsung Electronics | 1         | 1.72%   |
| Notebook            | 1         | 1.72%   |
| Apple               | 1         | 1.72%   |
| Unknown             | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron N4050                                   | 2         | 3.45%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 1.72%   |
| Toshiba Satellite A135                                | 1         | 1.72%   |
| Sony VPCSB19GG                                        | 1         | 1.72%   |
| Sony VGN-N19VP_B                                      | 1         | 1.72%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.72%   |
| Notebook WA50SRQ                                      | 1         | 1.72%   |
| MSI GP62MVR 7RFX                                      | 1         | 1.72%   |
| MSI GL63 8SD                                          | 1         | 1.72%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 1.72%   |
| Lenovo ThinkPad X61s 7667DB2                          | 1         | 1.72%   |
| Lenovo ThinkPad X200 7459ZEJ                          | 1         | 1.72%   |
| Lenovo ThinkPad X200 7459H92                          | 1         | 1.72%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00              | 1         | 1.72%   |
| Lenovo ThinkPad T61 64665WG                           | 1         | 1.72%   |
| Lenovo ThinkPad T530 2394AG6                          | 1         | 1.72%   |
| Lenovo ThinkPad T520 4243Y1N                          | 1         | 1.72%   |
| Lenovo ThinkPad T440p 20AWS27B0X                      | 1         | 1.72%   |
| Lenovo ThinkPad P53 20QNS00Y00                        | 1         | 1.72%   |
| Lenovo IdeaPad 310-15ISK 80UH                         | 1         | 1.72%   |
| Lenovo G500s 20245                                    | 1         | 1.72%   |
| HP ZBook 17                                           | 1         | 1.72%   |
| HP ProBook 6560b                                      | 1         | 1.72%   |
| HP Presario C700                                      | 1         | 1.72%   |
| HP Pavilion Laptop 14-dv0xxx                          | 1         | 1.72%   |
| HP Pavilion 15                                        | 1         | 1.72%   |
| HP Laptop 15-da0xxx                                   | 1         | 1.72%   |
| HP Falco                                              | 1         | 1.72%   |
| HP EliteBook x360 1040 G6                             | 1         | 1.72%   |
| HP EliteBook 8540w                                    | 1         | 1.72%   |
| HP EliteBook 840 G5                                   | 1         | 1.72%   |
| HP EliteBook 6930p                                    | 1         | 1.72%   |
| HP EliteBook 2740p                                    | 1         | 1.72%   |
| Dell Vostro 5581                                      | 1         | 1.72%   |
| Dell Vostro 5568                                      | 1         | 1.72%   |
| Dell Vostro 5470                                      | 1         | 1.72%   |
| Dell Vostro 14 5410                                   | 1         | 1.72%   |
| Dell System XPS L702X                                 | 1         | 1.72%   |
| Dell Precision M4600                                  | 1         | 1.72%   |
| Dell Precision 7510                                   | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 15.52%  |
| Dell Inspiron      | 6         | 10.34%  |
| HP EliteBook       | 5         | 8.62%   |
| Dell Latitude      | 5         | 8.62%   |
| Dell Vostro        | 4         | 6.9%    |
| Toshiba Satellite  | 2         | 3.45%   |
| HP Pavilion        | 2         | 3.45%   |
| Dell Precision     | 2         | 3.45%   |
| Acer Aspire        | 2         | 3.45%   |
| Sony VPCSB19GG     | 1         | 1.72%   |
| Sony VGN-N19VP     | 1         | 1.72%   |
| Samsung 300E5EV    | 1         | 1.72%   |
| Notebook WA50SRQ   | 1         | 1.72%   |
| MSI GP62MVR        | 1         | 1.72%   |
| MSI GL63           | 1         | 1.72%   |
| Lenovo Y520-15IKBN | 1         | 1.72%   |
| Lenovo IdeaPad     | 1         | 1.72%   |
| Lenovo G500s       | 1         | 1.72%   |
| HP ZBook           | 1         | 1.72%   |
| HP ProBook         | 1         | 1.72%   |
| HP Presario        | 1         | 1.72%   |
| HP Laptop          | 1         | 1.72%   |
| HP Falco           | 1         | 1.72%   |
| Dell System        | 1         | 1.72%   |
| ASUS X540SC        | 1         | 1.72%   |
| ASUS VivoBook      | 1         | 1.72%   |
| ASUS U35JC         | 1         | 1.72%   |
| ASUS G752VSK       | 1         | 1.72%   |
| Apple MacBookPro5  | 1         | 1.72%   |
| Unknown            | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 13.79%  |
| 2011 | 7         | 12.07%  |
| 2016 | 5         | 8.62%   |
| 2014 | 5         | 8.62%   |
| 2010 | 5         | 8.62%   |
| 2019 | 4         | 6.9%    |
| 2018 | 4         | 6.9%    |
| 2021 | 3         | 5.17%   |
| 2012 | 3         | 5.17%   |
| 2008 | 3         | 5.17%   |
| 2007 | 3         | 5.17%   |
| 2017 | 2         | 3.45%   |
| 2015 | 2         | 3.45%   |
| 2006 | 2         | 3.45%   |
| 2009 | 1         | 1.72%   |
| 2001 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 58        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 56        | 96.55%  |
| Enabled  | 2         | 3.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 98.28%  |
| Yes  | 1         | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 44.83%  |
| 3.01-4.0    | 10        | 17.24%  |
| 16.01-24.0  | 6         | 10.34%  |
| 8.01-16.0   | 5         | 8.62%   |
| 32.01-64.0  | 4         | 6.9%    |
| 1.01-2.0    | 3         | 5.17%   |
| 24.01-32.0  | 1         | 1.72%   |
| 2.01-3.0    | 1         | 1.72%   |
| 64.01-256.0 | 1         | 1.72%   |
| 0.51-1.0    | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 16        | 25.81%  |
| 2.01-3.0   | 14        | 22.58%  |
| 4.01-8.0   | 10        | 16.13%  |
| 3.01-4.0   | 10        | 16.13%  |
| 0.51-1.0   | 8         | 12.9%   |
| 32.01-64.0 | 1         | 1.61%   |
| 24.01-32.0 | 1         | 1.61%   |
| 8.01-16.0  | 1         | 1.61%   |
| 0.01-0.5   | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 72.88%  |
| 2      | 12        | 20.34%  |
| 3      | 3         | 5.08%   |
| 0      | 1         | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 56.9%   |
| Yes       | 25        | 43.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 93.1%   |
| No        | 4         | 6.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 72.41%  |
| No        | 16        | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 8         | 13.79%  |
| USA        | 6         | 10.34%  |
| Poland     | 4         | 6.9%    |
| UK         | 3         | 5.17%   |
| France     | 3         | 5.17%   |
| China      | 3         | 5.17%   |
| Ukraine    | 2         | 3.45%   |
| Spain      | 2         | 3.45%   |
| Japan      | 2         | 3.45%   |
| Germany    | 2         | 3.45%   |
| Finland    | 2         | 3.45%   |
| Bulgaria   | 2         | 3.45%   |
| Brazil     | 2         | 3.45%   |
| Australia  | 2         | 3.45%   |
| Taiwan     | 1         | 1.72%   |
| Sweden     | 1         | 1.72%   |
| Portugal   | 1         | 1.72%   |
| Mexico     | 1         | 1.72%   |
| Kazakhstan | 1         | 1.72%   |
| Israel     | 1         | 1.72%   |
| Ireland    | 1         | 1.72%   |
| Iran       | 1         | 1.72%   |
| India      | 1         | 1.72%   |
| Greece     | 1         | 1.72%   |
| Croatia    | 1         | 1.72%   |
| Chile      | 1         | 1.72%   |
| Canada     | 1         | 1.72%   |
| Argentina  | 1         | 1.72%   |
| Algeria    | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Moscow          | 4         | 6.67%   |
| Sofia           | 2         | 3.33%   |
| Krasnodar       | 2         | 3.33%   |
| Helsinki        | 2         | 3.33%   |
| Guangzhou       | 2         | 3.33%   |
| Grovedale       | 2         | 3.33%   |
| Zagreb          | 1         | 1.67%   |
| Yekaterinburg   | 1         | 1.67%   |
| West Chester    | 1         | 1.67%   |
| Tygelsjoe       | 1         | 1.67%   |
| Toyama          | 1         | 1.67%   |
| Toronto         | 1         | 1.67%   |
| Tehran          | 1         | 1.67%   |
| Taichung        | 1         | 1.67%   |
| Skikda          | 1         | 1.67%   |
| Sao Paulo       | 1         | 1.67%   |
| Santiago        | 1         | 1.67%   |
| Rzeszów        | 1         | 1.67%   |
| Poznan          | 1         | 1.67%   |
| Paris           | 1         | 1.67%   |
| Nur-Sultan      | 1         | 1.67%   |
| Nea Filadelfeia | 1         | 1.67%   |
| Mytishchi       | 1         | 1.67%   |
| Mykolayiv       | 1         | 1.67%   |
| Murcia          | 1         | 1.67%   |
| Milwaukee       | 1         | 1.67%   |
| Mexico City     | 1         | 1.67%   |
| Manchester      | 1         | 1.67%   |
| Maidenhead      | 1         | 1.67%   |
| Lodz            | 1         | 1.67%   |
| Lisbon          | 1         | 1.67%   |
| La Serena       | 1         | 1.67%   |
| Kyiv            | 1         | 1.67%   |
| Khimki          | 1         | 1.67%   |
| Hyderabad       | 1         | 1.67%   |
| Hsinchu         | 1         | 1.67%   |
| Herriman        | 1         | 1.67%   |
| Hemmingen       | 1         | 1.67%   |
| Hangzhou        | 1         | 1.67%   |
| Haifa           | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 13        | 16     | 17.81%  |
| Seagate                      | 11        | 12     | 15.07%  |
| Toshiba                      | 9         | 10     | 12.33%  |
| Kingston                     | 8         | 8      | 10.96%  |
| WDC                          | 6         | 6      | 8.22%   |
| Intel                        | 4         | 5      | 5.48%   |
| Hitachi                      | 3         | 3      | 4.11%   |
| Unknown                      | 2         | 2      | 2.74%   |
| StoreJet                     | 2         | 2      | 2.74%   |
| SK hynix                     | 2         | 2      | 2.74%   |
| Micron Technology            | 2         | 2      | 2.74%   |
| Toshiba America Info Systems | 1         | 2      | 1.37%   |
| SPCC                         | 1         | 3      | 1.37%   |
| Smartbuy                     | 1         | 1      | 1.37%   |
| SanDisk                      | 1         | 1      | 1.37%   |
| OCZ                          | 1         | 2      | 1.37%   |
| LITEONIT                     | 1         | 1      | 1.37%   |
| Kingston Technology Company  | 1         | 1      | 1.37%   |
| HGST                         | 1         | 1      | 1.37%   |
| GOODRAM                      | 1         | 1      | 1.37%   |
| Fujitsu                      | 1         | 1      | 1.37%   |
| Crucial                      | 1         | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 3         | 4.05%   |
| Toshiba TR200 240GB SSD                           | 2         | 2.7%    |
| StoreJet Transcend 128GB SSD                      | 2         | 2.7%    |
| Seagate BUP Slim 2TB                              | 2         | 2.7%    |
| WDC WD7500BPKX-00HPJT0 752GB                      | 1         | 1.35%   |
| WDC WD5000BEVT-80A0RT0 500GB                      | 1         | 1.35%   |
| WDC WD5000BEVT-22A0RT0 500GB                      | 1         | 1.35%   |
| WDC WD3200BPVT-75JJ5T0 320GB                      | 1         | 1.35%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 1.35%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB              | 1         | 1.35%   |
| Unknown SDC  4GB                                  | 1         | 1.35%   |
| Unknown SD32G  32GB                               | 1         | 1.35%   |
| Toshiba THNSNC128GMMJ 128GB SSD                   | 1         | 1.35%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 1.35%   |
| Toshiba MQ01ABF050 500GB                          | 1         | 1.35%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 1.35%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 1.35%   |
| Toshiba MK8032GSX 80GB                            | 1         | 1.35%   |
| Toshiba MK5061GSY 500GB                           | 1         | 1.35%   |
| Toshiba America Info Systems KXG60ZNV1T02 NVM 1TB | 1         | 1.35%   |
| SPCC Solid State Disk 256GB                       | 1         | 1.35%   |
| Smartbuy SSD 120GB                                | 1         | 1.35%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 1.35%   |
| SK hynix SC210 mSATA 256GB SSD                    | 1         | 1.35%   |
| Seagate ST980813ASG 80GB                          | 1         | 1.35%   |
| Seagate ST9320328CS 320GB                         | 1         | 1.35%   |
| Seagate ST9320325AS 320GB                         | 1         | 1.35%   |
| Seagate ST9120823AS 120GB                         | 1         | 1.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB               | 1         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.35%   |
| Seagate Expansion 2TB                             | 1         | 1.35%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD               | 1         | 1.35%   |
| Samsung SSD SM871 2.5 7mm 512GB                   | 1         | 1.35%   |
| Samsung SSD 860 EVO M.2 500GB                     | 1         | 1.35%   |
| Samsung SSD 860 EVO 500GB                         | 1         | 1.35%   |
| Samsung SSD 860 EVO 250GB                         | 1         | 1.35%   |
| Samsung SSD 860 EVO 1TB                           | 1         | 1.35%   |
| Samsung SSD 850 EVO 500GB                         | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 39.29%  |
| Toshiba             | 6         | 6      | 21.43%  |
| WDC                 | 5         | 5      | 17.86%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Samsung Electronics | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 25.71%  |
| Kingston            | 7         | 7      | 20%     |
| Toshiba             | 3         | 4      | 8.57%   |
| Intel               | 3         | 4      | 8.57%   |
| StoreJet            | 2         | 2      | 5.71%   |
| SK hynix            | 2         | 2      | 5.71%   |
| Micron Technology   | 2         | 2      | 5.71%   |
| SPCC                | 1         | 3      | 2.86%   |
| Smartbuy            | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| OCZ                 | 1         | 2      | 2.86%   |
| LITEONIT            | 1         | 1      | 2.86%   |
| GOODRAM             | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 40     | 45.71%  |
| HDD  | 28        | 29     | 40%     |
| NVMe | 8         | 12     | 11.43%  |
| MMC  | 2         | 2      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 64     | 76.92%  |
| NVMe | 8         | 12     | 12.31%  |
| SAS  | 5         | 5      | 7.69%   |
| MMC  | 2         | 2      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 54     | 74.14%  |
| 0.51-1.0   | 12        | 12     | 20.69%  |
| 1.01-2.0   | 3         | 3      | 5.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 30%     |
| 251-500        | 15        | 25%     |
| 51-100         | 9         | 15%     |
| 501-1000       | 8         | 13.33%  |
| 1001-2000      | 5         | 8.33%   |
| 21-50          | 3         | 5%      |
| More than 3000 | 1         | 1.67%   |
| 1-20           | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 38.98%  |
| 101-250        | 10        | 16.95%  |
| 251-500        | 8         | 13.56%  |
| 51-100         | 7         | 11.86%  |
| 21-50          | 5         | 8.47%   |
| 501-1000       | 4         | 6.78%   |
| More than 3000 | 1         | 1.69%   |
| 1001-2000      | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 6.67%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 6.67%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 6.67%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 6.67%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 6.67%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 6.67%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 6.67%   |
| Intel SSDSC2KW240H6 240GB                           | 1         | 1      | 6.67%   |
| Intel SSDSC2KW180H6 180GB                           | 1         | 1      | 6.67%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 6.67%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 1      | 6.67%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 6.67%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Intel             | 3         | 4      | 20%     |
| Toshiba           | 2         | 2      | 13.33%  |
| Micron Technology | 2         | 2      | 13.33%  |
| Hitachi           | 2         | 2      | 13.33%  |
| WDC               | 1         | 1      | 6.67%   |
| Smartbuy          | 1         | 1      | 6.67%   |
| SK hynix          | 1         | 1      | 6.67%   |
| Seagate           | 1         | 1      | 6.67%   |
| LITEONIT          | 1         | 1      | 6.67%   |
| Crucial           | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| Seagate | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 9         | 10     | 60%     |
| HDD  | 6         | 6      | 40%     |

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
| Works    | 28        | 39     | 45.16%  |
| Detected | 20        | 28     | 32.26%  |
| Malfunc  | 14        | 16     | 22.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 51        | 83.61%  |
| Samsung Electronics              | 3         | 4.92%   |
| Kingston Technology Company      | 2         | 3.28%   |
| Toshiba America Info Systems     | 1         | 1.64%   |
| Silicon Integrated Systems [SiS] | 1         | 1.64%   |
| SanDisk                          | 1         | 1.64%   |
| Nvidia                           | 1         | 1.64%   |
| AMD                              | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 13.04%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 7.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 7.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 5.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 4.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 4.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 2.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 2.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.45%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.45%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 1.45%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.45%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.45%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.45%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 1.45%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.45%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.45%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 1.45%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 38        | 58.46%  |
| RAID | 10        | 15.38%  |
| IDE  | 9         | 13.85%  |
| NVMe | 8         | 12.31%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz    | 3         | 5.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 3.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 2         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 3.45%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 2         | 3.45%   |
| Intel Core i3-3120M CPU @ 2.50GHz    | 2         | 3.45%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 2         | 3.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 3.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz    | 1         | 1.72%   |
| Intel Pentium CPU N3700 @ 1.60GHz    | 1         | 1.72%   |
| Intel Pentium 4 CPU 2.00GHz          | 1         | 1.72%   |
| Intel Genuine CPU T2060 @ 1.60GHz    | 1         | 1.72%   |
| Intel Genuine CPU T2050 @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 1.72%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 1.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 1         | 1.72%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz   | 1         | 1.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 1         | 1.72%   |
| Intel Core i7-4610M CPU @ 3.00GHz    | 1         | 1.72%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 1         | 1.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz   | 1         | 1.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz    | 1         | 1.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz   | 1         | 1.72%   |
| Intel Core i7 CPU Q 840 @ 1.87GHz    | 1         | 1.72%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz   | 1         | 1.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 1         | 1.72%   |
| Intel Core i3-8145U CPU @ 2.10GHz    | 1         | 1.72%   |
| Intel Core i3-7020U CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i3-6100U CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 1         | 1.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz    | 1         | 1.72%   |
| Intel Core i3-2350M CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i3 CPU M 370 @ 2.40GHz    | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 15        | 25.86%  |
| Intel Core i5    | 15        | 25.86%  |
| Intel Core i3    | 11        | 18.97%  |
| Intel Core 2 Duo | 7         | 12.07%  |
| Other            | 2         | 3.45%   |
| Intel Pentium    | 2         | 3.45%   |
| Intel Genuine    | 2         | 3.45%   |
| Intel Celeron    | 2         | 3.45%   |
| Intel Pentium 4  | 1         | 1.72%   |
| Intel Core i9    | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 67.24%  |
| 4      | 16        | 27.59%  |
| 8      | 1         | 1.72%   |
| 6      | 1         | 1.72%   |
| 1      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 72.41%  |
| 1      | 16        | 27.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 87.93%  |
| Unknown        | 4         | 6.9%    |
| 32-bit         | 3         | 5.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 0x206a7 | 8         | 13.56%  |
| 0x40651 | 5         | 8.47%   |
| 0x306a9 | 5         | 8.47%   |
| 0x306c3 | 4         | 6.78%   |
| 0x20655 | 4         | 6.78%   |
| 0x906e9 | 3         | 5.08%   |
| 0x806ea | 3         | 5.08%   |
| 0x806e9 | 3         | 5.08%   |
| 0x1067a | 3         | 5.08%   |
| 0x806c1 | 2         | 3.39%   |
| 0x10676 | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| 0xf24   | 1         | 1.69%   |
| 0x906ed | 1         | 1.69%   |
| 0x906ea | 1         | 1.69%   |
| 0x806ec | 1         | 1.69%   |
| 0x806eb | 1         | 1.69%   |
| 0x706e5 | 1         | 1.69%   |
| 0x6fd   | 1         | 1.69%   |
| 0x6fb   | 1         | 1.69%   |
| 0x6ec   | 1         | 1.69%   |
| 0x6e8   | 1         | 1.69%   |
| 0x506e3 | 1         | 1.69%   |
| 0x406e3 | 1         | 1.69%   |
| 0x406c3 | 1         | 1.69%   |
| 0x306d4 | 1         | 1.69%   |
| 0x106e5 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 13        | 22.41%  |
| Haswell     | 9         | 15.52%  |
| SandyBridge | 8         | 13.79%  |
| Penryn      | 5         | 8.62%   |
| IvyBridge   | 5         | 8.62%   |
| Westmere    | 4         | 6.9%    |
| Skylake     | 3         | 5.17%   |
| TigerLake   | 2         | 3.45%   |
| P6          | 2         | 3.45%   |
| Core        | 2         | 3.45%   |
| Silvermont  | 1         | 1.72%   |
| NetBurst    | 1         | 1.72%   |
| Nehalem     | 1         | 1.72%   |
| IceLake     | 1         | 1.72%   |
| Broadwell   | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 66.22%  |
| Nvidia                           | 15        | 20.27%  |
| AMD                              | 9         | 12.16%  |
| Silicon Integrated Systems [SiS] | 1         | 1.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 7.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 6.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 5.13%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.56%   |
| Intel HD Graphics 630                                                                    | 2         | 2.56%   |
| Intel HD Graphics 620                                                                    | 2         | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.56%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                | 1         | 1.28%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.28%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.28%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 1.28%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.28%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.28%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 1.28%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.28%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.28%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.28%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.28%   |
| Nvidia GK107M [GeForce 810M]                                                             | 1         | 1.28%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 1.28%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 1.28%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.28%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.28%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 1.28%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.28%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.28%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 56.9%   |
| Intel + Nvidia | 10        | 17.24%  |
| Intel + AMD    | 6         | 10.34%  |
| 1 x Nvidia     | 5         | 8.62%   |
| 1 x AMD        | 3         | 5.17%   |
| 1 x SiS        | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 47        | 81.03%  |
| Unknown     | 7         | 12.07%  |
| Proprietary | 4         | 6.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 65.52%  |
| 1.01-2.0   | 7         | 12.07%  |
| 0.51-1.0   | 7         | 12.07%  |
| 3.01-4.0   | 2         | 3.45%   |
| 0.01-0.5   | 2         | 3.45%   |
| 5.01-6.0   | 1         | 1.72%   |
| 2.01-3.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 12        | 17.91%  |
| AU Optronics        | 10        | 14.93%  |
| Chimei Innolux      | 9         | 13.43%  |
| Samsung Electronics | 8         | 11.94%  |
| Lenovo              | 5         | 7.46%   |
| Dell                | 5         | 7.46%   |
| BOE                 | 4         | 5.97%   |
| Acer                | 3         | 4.48%   |
| InnoLux Display     | 2         | 2.99%   |
| Goldstar            | 2         | 2.99%   |
| Sony                | 1         | 1.49%   |
| Sharp               | 1         | 1.49%   |
| PANDA               | 1         | 1.49%   |
| MIT                 | 1         | 1.49%   |
| LG Philips          | 1         | 1.49%   |
| Hewlett-Packard     | 1         | 1.49%   |
| Apple               | 1         | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 2.94%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch      | 2         | 2.94%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 1.47%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch               | 1         | 1.47%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1         | 1.47%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch  | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.47%   |
| PANDA LCD Monitor NCP0033 1920x1080 344x194mm 15.5-inch               | 1         | 1.47%   |
| MIT LCD Monitor MIT2011 3840x2160 1150x650mm 52.0-inch                | 1         | 1.47%   |
| MIT HDMI Analyzer MIT2011 3840x2160 800x450mm 36.1-inch               | 1         | 1.47%   |
| LG Philips LCD Monitor LPLC700 1280x800 331x207mm 15.4-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD6616 1366x768 277x156mm 12.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch           | 1         | 1.47%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD02FC 1920x1080 380x210mm 17.1-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD02C5 1920x1080 382x215mm 17.3-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0290 1366x768 293x165mm 13.2-inch           | 1         | 1.47%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.47%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.47%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.47%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 1.47%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch               | 1         | 1.47%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch            | 1         | 1.47%   |
| Goldstar W2252 GSM567E 1680x1050 490x320mm 23.0-inch                  | 1         | 1.47%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 1         | 1.47%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 1         | 1.47%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1         | 1.47%   |
| Dell P2016 DEL40D0 1440x900 419x262mm 19.5-inch                       | 1         | 1.47%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 1         | 1.47%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 34.43%  |
| 1366x768 (WXGA)    | 21        | 34.43%  |
| 1280x800 (WXGA)    | 7         | 11.48%  |
| 3840x2160 (4K)     | 3         | 4.92%   |
| 1280x1024 (SXGA)   | 3         | 4.92%   |
| 1600x900 (HD+)     | 2         | 3.28%   |
| 1440x900 (WXGA+)   | 2         | 3.28%   |
| 1920x1200 (WUXGA)  | 1         | 1.64%   |
| 1680x1050 (WSXGA+) | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 25        | 36.76%  |
| 13      | 8         | 11.76%  |
| 14      | 7         | 10.29%  |
| 12      | 6         | 8.82%   |
| 17      | 5         | 7.35%   |
| 24      | 4         | 5.88%   |
| 19      | 4         | 5.88%   |
| 23      | 3         | 4.41%   |
| 55      | 1         | 1.47%   |
| 52      | 1         | 1.47%   |
| 36      | 1         | 1.47%   |
| 27      | 1         | 1.47%   |
| 21      | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 53.73%  |
| 201-300     | 9         | 13.43%  |
| 501-600     | 7         | 10.45%  |
| 351-400     | 7         | 10.45%  |
| 401-500     | 4         | 5.97%   |
| 1001-1500   | 2         | 2.99%   |
| 701-800     | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 73.68%  |
| 16/10   | 9         | 15.79%  |
| 5/4     | 3         | 5.26%   |
| 3/2     | 2         | 3.51%   |
| Unknown | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 37.31%  |
| 81-90          | 13        | 19.4%   |
| 61-70          | 6         | 8.96%   |
| 201-250        | 6         | 8.96%   |
| 151-200        | 4         | 5.97%   |
| 121-130        | 3         | 4.48%   |
| More than 1000 | 2         | 2.99%   |
| 71-80          | 2         | 2.99%   |
| 301-350        | 1         | 1.49%   |
| 251-300        | 1         | 1.49%   |
| 141-150        | 1         | 1.49%   |
| 131-140        | 1         | 1.49%   |
| 501-1000       | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 37.88%  |
| 101-120       | 20        | 30.3%   |
| 51-100        | 17        | 25.76%  |
| More than 240 | 2         | 3.03%   |
| 1-50          | 1         | 1.52%   |
| Unknown       | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 66.67%  |
| 2     | 15        | 25%     |
| 0     | 4         | 6.67%   |
| 3     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 40.21%  |
| Realtek Semiconductor             | 24        | 24.74%  |
| Qualcomm Atheros                  | 16        | 16.49%  |
| Broadcom                          | 4         | 4.12%   |
| TP-Link                           | 3         | 3.09%   |
| Xilinx                            | 1         | 1.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 1.03%   |
| Ralink Technology                 | 1         | 1.03%   |
| Ralink                            | 1         | 1.03%   |
| Qualcomm Atheros Communications   | 1         | 1.03%   |
| Nvidia                            | 1         | 1.03%   |
| Marvell Technology Group          | 1         | 1.03%   |
| Huawei Technologies               | 1         | 1.03%   |
| Ericsson Business Mobile Networks | 1         | 1.03%   |
| Edimax Technology                 | 1         | 1.03%   |
| ASIX Electronics                  | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller        | 11        | 8.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                    | 9         | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                    | 5         | 4.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter               | 4         | 3.25%   |
| Intel Wireless 7260                                                      | 3         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                    | 3         | 2.44%   |
| Intel Ethernet Connection I217-LM                                        | 3         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                             | 3         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                                 | 3         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                                 | 3         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                    | 2         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter               | 2         | 1.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                | 2         | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)  | 2         | 1.63%   |
| Intel Wireless 8260                                                      | 2         | 1.63%   |
| Intel Wireless 7265                                                      | 2         | 1.63%   |
| Intel Wireless 3165                                                      | 2         | 1.63%   |
| Intel Wi-Fi 6 AX200                                                      | 2         | 1.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                  | 2         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                                     | 2         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                           | 2         | 1.63%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                            | 2         | 1.63%   |
| Intel Centrino Advanced-N 6200                                           | 2         | 1.63%   |
| Intel 82566MM Gigabit Network Connection                                 | 2         | 1.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                   | 2         | 1.63%   |
| Xilinx Ethernet controller                                               | 1         | 0.81%   |
| TP-Link USB 10/100 LAN                                                   | 1         | 0.81%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]          | 1         | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]               | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                  | 1         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                 | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                          | 1         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                               | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                          | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                               | 1         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                 | 1         | 0.81%   |
| Ralink Conceptronic C300RU v2 802.11bgn Wireless Adapter [Ralink RT2770] | 1         | 0.81%   |
| Ralink RT2500 Wireless 802.11bg                                          | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                   | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 58.06%  |
| Qualcomm Atheros                | 13        | 20.97%  |
| Realtek Semiconductor           | 5         | 8.06%   |
| Broadcom                        | 3         | 4.84%   |
| TP-Link                         | 1         | 1.61%   |
| Ralink Technology               | 1         | 1.61%   |
| Ralink                          | 1         | 1.61%   |
| Qualcomm Atheros Communications | 1         | 1.61%   |
| Edimax Technology               | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 6.45%   |
| Intel Wireless 7260                                                           | 3         | 4.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 4.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 4.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 3.23%   |
| Intel Wireless 8260                                                           | 2         | 3.23%   |
| Intel Wireless 7265                                                           | 2         | 3.23%   |
| Intel Wireless 3165                                                           | 2         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 3.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.23%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 2         | 3.23%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 3.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 3.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 1.61%   |
| Ralink Conceptronic C300RU v2 802.11bgn Wireless Adapter [Ralink RT2770]      | 1         | 1.61%   |
| Ralink RT2500 Wireless 802.11bg                                               | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.61%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.61%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.61%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.61%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 22        | 37.93%  |
| Intel                            | 22        | 37.93%  |
| Qualcomm Atheros                 | 5         | 8.62%   |
| TP-Link                          | 2         | 3.45%   |
| Xilinx                           | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] | 1         | 1.72%   |
| Nvidia                           | 1         | 1.72%   |
| Marvell Technology Group         | 1         | 1.72%   |
| Huawei Technologies              | 1         | 1.72%   |
| Broadcom                         | 1         | 1.72%   |
| ASIX Electronics                 | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 18.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 15.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 8.47%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 5.08%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 5.08%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 5.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 3.39%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.39%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 3.39%   |
| Xilinx Ethernet controller                                        | 1         | 1.69%   |
| TP-Link USB 10/100 LAN                                            | 1         | 1.69%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.69%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.69%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.69%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.69%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.69%   |
| Huawei LYA-L09                                                    | 1         | 1.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 50.88%  |
| Ethernet | 54        | 47.37%  |
| Modem    | 2         | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 64.06%  |
| Ethernet | 23        | 35.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 87.93%  |
| 1     | 6         | 10.34%  |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 93.33%  |
| Yes  | 4         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 44.19%  |
| Qualcomm Atheros Communications | 8         | 18.6%   |
| Realtek Semiconductor           | 4         | 9.3%    |
| Broadcom                        | 4         | 9.3%    |
| Dell                            | 3         | 6.98%   |
| Lite-On Technology              | 1         | 2.33%   |
| IMC Networks                    | 1         | 2.33%   |
| Foxconn / Hon Hai               | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |
| Apple                           | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 18.6%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 6.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 4.65%   |
| Realtek Bluetooth Radio                                                             | 2         | 4.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 4.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 4.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 4.65%   |
| Intel AX201 Bluetooth                                                               | 2         | 4.65%   |
| Intel AX200 Bluetooth                                                               | 2         | 4.65%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 4.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 4.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 2.33%   |
| IMC Networks Bluetooth Device                                                       | 1         | 2.33%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.33%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 2.33%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 2.33%   |
| Apple Bluetooth Host Controller                                                     | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 80.88%  |
| Nvidia                           | 6         | 8.82%   |
| AMD                              | 3         | 4.41%   |
| Silicon Integrated Systems [SiS] | 1         | 1.47%   |
| Realtek Semiconductor            | 1         | 1.47%   |
| Lenovo                           | 1         | 1.47%   |
| GN Netcom                        | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 10.26%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 10.26%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 6.41%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 6.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.85%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.56%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 1.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.28%   |
| Nvidia stereo controller                                                                          | 1         | 1.28%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.28%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.28%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 1         | 1.28%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.28%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.28%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 28.57%  |
| SK hynix            | 10        | 20.41%  |
| Kingston            | 7         | 14.29%  |
| Unknown             | 5         | 10.2%   |
| Micron Technology   | 3         | 6.12%   |
| Crucial             | 3         | 6.12%   |
| A-DATA Technology   | 2         | 4.08%   |
| Wilk                | 1         | 2.04%   |
| Transcend           | 1         | 2.04%   |
| Ramaxel Technology  | 1         | 2.04%   |
| Elpida              | 1         | 2.04%   |
| Apacer              | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 3.92%   |
| Wilk RAM GR3200S464L22/16G 16384MB SODIMM DDR4 3200MT/s      | 1         | 1.96%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.96%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 1.96%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.96%   |
| Unknown RAM Module 1024MB SODIMM DRAM                        | 1         | 1.96%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s        | 1         | 1.96%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 1.96%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.96%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.96%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2667MT/s               | 1         | 1.96%   |
| Samsung RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.96%   |
| Samsung RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 1.96%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s     | 1         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 1         | 1.96%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 1.96%   |
| Samsung RAM M471A1K44BM0-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 1.96%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB SODIMM LPDDR3 1600MT/s    | 1         | 1.96%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.96%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s     | 1         | 1.96%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s        | 1         | 1.96%   |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1334MT/s       | 1         | 1.96%   |
| Micron RAM 16JTF51264HZ-1G4H1 4GB SODIMM DDR3 1333MT/s       | 1         | 1.96%   |
| Kingston RAM MSI26D4S9D8ME-16 16GB SODIMM DDR4 2667MT/s      | 1         | 1.96%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| Kingston RAM 99U5469-041.A00LF 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 20        | 47.62%  |
| DDR4   | 14        | 33.33%  |
| DDR2   | 4         | 9.52%   |
| LPDDR3 | 2         | 4.76%   |
| SDRAM  | 1         | 2.38%   |
| DRAM   | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 97.62%  |
| Row Of Chips | 1         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 42.22%  |
| 8192  | 10        | 22.22%  |
| 2048  | 8         | 17.78%  |
| 16384 | 5         | 11.11%  |
| 1024  | 2         | 4.44%   |
| 32768 | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 27.08%  |
| 2667    | 11        | 22.92%  |
| 1333    | 5         | 10.42%  |
| 3200    | 3         | 6.25%   |
| 2400    | 3         | 6.25%   |
| 667     | 3         | 6.25%   |
| 3266    | 2         | 4.17%   |
| 1334    | 2         | 4.17%   |
| Unknown | 2         | 4.17%   |
| 4199    | 1         | 2.08%   |
| 2133    | 1         | 2.08%   |
| 1067    | 1         | 2.08%   |
| 800     | 1         | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M288x Series | 1         | 100%    |

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
| Chicony Electronics                    | 7         | 15.22%  |
| Sunplus Innovation Technology          | 5         | 10.87%  |
| Microdia                               | 5         | 10.87%  |
| Realtek Semiconductor                  | 4         | 8.7%    |
| Suyin                                  | 3         | 6.52%   |
| Quanta                                 | 3         | 6.52%   |
| IMC Networks                           | 3         | 6.52%   |
| Acer                                   | 3         | 6.52%   |
| Ricoh                                  | 2         | 4.35%   |
| Logitech                               | 2         | 4.35%   |
| Apple                                  | 2         | 4.35%   |
| Syntek                                 | 1         | 2.17%   |
| Silicon Motion                         | 1         | 2.17%   |
| Microsoft                              | 1         | 2.17%   |
| Lite-On Technology                     | 1         | 2.17%   |
| Generalplus Technology                 | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.17%   |
| Alcor Micro                            | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                  | 3         | 6.52%   |
| Microdia Integrated_Webcam_HD                 | 3         | 6.52%   |
| Suyin Integrated Webcam                       | 2         | 4.35%   |
| IMC Networks Integrated Camera                | 2         | 4.35%   |
| Syntek EasyCamera                             | 1         | 2.17%   |
| Suyin Asus Integrated Webcam [CN031B]         | 1         | 2.17%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 2.17%   |
| Sunplus Integrated Webcam                     | 1         | 2.17%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 2.17%   |
| Ricoh Laptop_Integrated_Webcam_FHD            | 1         | 2.17%   |
| Ricoh HD Webcam                               | 1         | 2.17%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 2.17%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 2.17%   |
| Realtek Lenovo EasyCamera                     | 1         | 2.17%   |
| Realtek Integrated Webcam HD                  | 1         | 2.17%   |
| Quanta Laptop_Integrated_Webcam_2HDM          | 1         | 2.17%   |
| Quanta HP Webcam                              | 1         | 2.17%   |
| Quanta HP Full-HD Camera                      | 1         | 2.17%   |
| Microsoft LifeCam NX-6000                     | 1         | 2.17%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 2.17%   |
| Microdia Dell Integrated HD Webcam            | 1         | 2.17%   |
| Logitech Webcam C170                          | 1         | 2.17%   |
| Logitech C922 Pro Stream Webcam               | 1         | 2.17%   |
| Lite-On HP HD Camera                          | 1         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 2.17%   |
| Generalplus 808 Camera                        | 1         | 2.17%   |
| Chicony USB2.0 Camera                         | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 2.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 2.17%   |
| Chicony HP Wide Vision HD Camera              | 1         | 2.17%   |
| Chicony HP Webcam [2 MP Macro]                | 1         | 2.17%   |
| Chicony HP Truevision HD                      | 1         | 2.17%   |
| Chicony HD WebCam                             | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE                     | 1         | 2.17%   |
| Apple Built-in iSight                         | 1         | 2.17%   |
| Alcor Micro Acer Integrated Webcam            | 1         | 2.17%   |
| Acer SunplusIT INC. Integrated Camera         | 1         | 2.17%   |
| Acer HD Webcam                                | 1         | 2.17%   |
| Acer EasyCamera                               | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 6         | 37.5%   |
| AuthenTec          | 4         | 25%     |
| Synaptics          | 3         | 18.75%  |
| STMicroelectronics | 2         | 12.5%   |
| Upek               | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 3         | 18.75%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 12.5%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 6.25%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 6         | 75%     |
| SCM Microsystems | 1         | 12.5%   |
| Lenovo           | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 50%     |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 49.15%  |
| 0     | 20        | 33.9%   |
| 2     | 7         | 11.86%  |
| 5     | 2         | 3.39%   |
| 4     | 1         | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 31.37%  |
| Graphics card            | 13        | 25.49%  |
| Communication controller | 6         | 11.76%  |
| Net/wireless             | 5         | 9.8%    |
| Chipcard                 | 5         | 9.8%    |
| Storage                  | 2         | 3.92%   |
| Sound                    | 2         | 3.92%   |
| Storage/raid             | 1         | 1.96%   |
| Net/ethernet             | 1         | 1.96%   |

