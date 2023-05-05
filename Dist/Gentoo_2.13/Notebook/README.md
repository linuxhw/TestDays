Gentoo 2.13 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.13.

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

Total: 82

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo    | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| HP        | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek   | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell      | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| TUXEDO    | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer      | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP        | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HUAWEI    | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Dell      | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| Lenovo    | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HUAWEI    | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| Dell      | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| ASUSTek   | ROG Strix G513RM_G513RM     | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek   | ASUS TUF Gaming F17 FX70... | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba   | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA   | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| HP        | OMEN by Laptop              | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| Dell      | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell      | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| MAXDATA   | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI    | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer      | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Dell      | Precision 7770              | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| HUAWEI    | KPL-W0X                     | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| HP        | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo    | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo    | ThinkPad T470p 20J7S25C0... | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell      | XPS 13 9305                 | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| Lenovo    | ThinkPad P51 20HHCTO1WW     | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| Acer      | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| HP        | EliteBook 745 G6            | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| Dell      | Latitude 7480               | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP        | EliteBook 745 G6            | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo    | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| HP        | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| HP        | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Unknown   | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Lenovo    | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs | StarBook                    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell      | Precision 7770              | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell      | Precision 7770              | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| Lenovo    | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP        | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell      | Precision 7770              | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| Dell      | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| Dell      | Precision 7770              | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| Dell      | Precision 7770              | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Acer      | Aspire 7750G                | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| MSI       | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI       | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI       | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| realme    | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Valve     | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI       | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI       | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI       | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP        | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Dell      | Precision 7770              | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve     | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek   | ROG Strix G732LXS_G732LX... | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek   | Strix 17 GL703GE            | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| MSI       | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi      | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| Unknown   | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown   | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell      | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP        | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi      | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi      | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Dell      | Precision 7770              | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell      | Precision 7770              | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell      | Precision 7770              | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Dell      | Precision 7770              | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| HP        | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo    | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 6.1.19-gentoo-x86_64       | 6         | 10.17%  |
| 6.1.12-gentoo              | 4         | 6.78%   |
| 6.1.19-gentoo              | 3         | 5.08%   |
| 6.1.12-gentoo-dist         | 3         | 5.08%   |
| 6.2.8-gentoo-x86_64        | 2         | 3.39%   |
| 6.1.9-gentoo-x86_64        | 2         | 3.39%   |
| 6.1.22-gentoo-dist         | 2         | 3.39%   |
| 6.1.19-gentoo-dist         | 2         | 3.39%   |
| 6.1.12-gentoo-x86_64       | 2         | 3.39%   |
| 6.1.10-gentoo-x86_64       | 2         | 3.39%   |
| 6.3.0-gentoo               | 1         | 1.69%   |
| 6.2.9-gentoo               | 1         | 1.69%   |
| 6.2.7-gentoo-dist          | 1         | 1.69%   |
| 6.2.6-gentoo-dist          | 1         | 1.69%   |
| 6.2.3-gentoo               | 1         | 1.69%   |
| 6.2.2-gentoo-x86_64        | 1         | 1.69%   |
| 6.2.2-gentoo               | 1         | 1.69%   |
| 6.2.2-dist                 | 1         | 1.69%   |
| 6.2.11-zen1                | 1         | 1.69%   |
| 6.2.11-tkg-cfs             | 1         | 1.69%   |
| 6.2.11-gentoo-x86_64       | 1         | 1.69%   |
| 6.2.11-gentoo-dist         | 1         | 1.69%   |
| 6.2.11-gentoo              | 1         | 1.69%   |
| 6.2.10-gentoo-dist         | 1         | 1.69%   |
| 6.2.1-gentoo-x86_64        | 1         | 1.69%   |
| 6.2.0-rc6-gentoo-p14       | 1         | 1.69%   |
| 6.1.9-gentoo-dist          | 1         | 1.69%   |
| 6.1.4-gentoo-x86_64        | 1         | 1.69%   |
| 6.1.19-gentoo.ae           | 1         | 1.69%   |
| 6.1.19-gentoo-x86_64.ver_1 | 1         | 1.69%   |
| 6.1.13-pentoo              | 1         | 1.69%   |
| 6.1.12-gentoo-Vector       | 1         | 1.69%   |
| 6.1.11-gentoo-x86_64       | 1         | 1.69%   |
| 6.1.11-gentoo-tir_na_nog   | 1         | 1.69%   |
| 6.1.11-gentoo-dist         | 1         | 1.69%   |
| 6.1.10-gentoo              | 1         | 1.69%   |
| 5.15.94-gentoo             | 1         | 1.69%   |
| 5.15.93-gentoo-117         | 1         | 1.69%   |
| 5.15.88-gentoo             | 1         | 1.69%   |
| 5.15.80-gentoo-x86_64      | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.19  | 13        | 22.03%  |
| 6.1.12  | 10        | 16.95%  |
| 6.2.11  | 5         | 8.47%   |
| 6.2.2   | 3         | 5.08%   |
| 6.1.9   | 3         | 5.08%   |
| 6.1.11  | 3         | 5.08%   |
| 6.1.10  | 3         | 5.08%   |
| 6.2.8   | 2         | 3.39%   |
| 6.1.22  | 2         | 3.39%   |
| 5.15.80 | 2         | 3.39%   |
| 6.3.0   | 1         | 1.69%   |
| 6.2.9   | 1         | 1.69%   |
| 6.2.7   | 1         | 1.69%   |
| 6.2.6   | 1         | 1.69%   |
| 6.2.3   | 1         | 1.69%   |
| 6.2.10  | 1         | 1.69%   |
| 6.2.1   | 1         | 1.69%   |
| 6.2.0   | 1         | 1.69%   |
| 6.1.4   | 1         | 1.69%   |
| 6.1.13  | 1         | 1.69%   |
| 5.15.94 | 1         | 1.69%   |
| 5.15.93 | 1         | 1.69%   |
| 5.15.88 | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 36        | 62.07%  |
| 6.2     | 16        | 27.59%  |
| 5.15    | 5         | 8.62%   |
| 6.3     | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 96.43%  |
| i686   | 2         | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 17        | 30.36%  |
| Unknown   | 15        | 26.79%  |
| XFCE      | 5         | 8.93%   |
| GNOME     | 5         | 8.93%   |
| MATE      | 4         | 7.14%   |
| DWM       | 4         | 7.14%   |
| Trinity   | 2         | 3.57%   |
| ratpoison | 1         | 1.79%   |
| KDE       | 1         | 1.79%   |
| ICEWM     | 1         | 1.79%   |
| i3        | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 28        | 50%     |
| Wayland | 13        | 23.21%  |
| Tty     | 9         | 16.07%  |
| Unknown | 6         | 10.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 20        | 35.09%  |
| Unknown | 18        | 31.58%  |
| LightDM | 8         | 14.04%  |
| GDM     | 5         | 8.77%   |
| TDM     | 3         | 5.26%   |
| SLiM    | 2         | 3.51%   |
| XDM     | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 22        | 39.29%  |
| Unknown | 7         | 12.5%   |
| C.UTF8  | 5         | 8.93%   |
| fr_FR   | 4         | 7.14%   |
| en_GB   | 4         | 7.14%   |
| cs_CZ   | 4         | 7.14%   |
| ru_RU   | 2         | 3.57%   |
| de_DE   | 2         | 3.57%   |
| C       | 2         | 3.57%   |
| ro_RO   | 1         | 1.79%   |
| it_IT   | 1         | 1.79%   |
| en_AU   | 1         | 1.79%   |
| el_GR   | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 78.57%  |
| BIOS | 12        | 21.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 57.14%  |
| Btrfs   | 22        | 39.29%  |
| XXXXXXX | 1         | 1.79%   |
| Xfs     | 1         | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 47        | 82.46%  |
| MBR     | 8         | 14.04%  |
| Unknown | 2         | 3.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 67.86%  |
| Yes       | 18        | 32.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 64.91%  |
| Yes       | 20        | 35.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 19.64%  |
| Hewlett-Packard  | 10        | 17.86%  |
| Dell             | 9         | 16.07%  |
| ASUSTek Computer | 8         | 14.29%  |
| Acer             | 4         | 7.14%   |
| HUAWEI           | 3         | 5.36%   |
| MSI              | 2         | 3.57%   |
| Unknown          | 2         | 3.57%   |
| Valve            | 1         | 1.79%   |
| TUXEDO           | 1         | 1.79%   |
| Toshiba          | 1         | 1.79%   |
| Timi             | 1         | 1.79%   |
| Star Labs        | 1         | 1.79%   |
| realme           | 1         | 1.79%   |
| MAXDATA          | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Precision 7770                         | 2         | 3.57%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II       | 2         | 3.57%   |
| Unknown                                     | 2         | 3.57%   |
| Valve Jupiter                               | 1         | 1.79%   |
| TUXEDO Polaris AMD Gen3 (CZN)               | 1         | 1.79%   |
| Toshiba Satellite L850                      | 1         | 1.79%   |
| Timi RedmiBook Pro 15S                      | 1         | 1.79%   |
| Star Labs StarBook                          | 1         | 1.79%   |
| realme RMNBXXXX                             | 1         | 1.79%   |
| MSI Vector GP66 12UEO                       | 1         | 1.79%   |
| MSI GS66 Stealth 10UE                       | 1         | 1.79%   |
| MAXDATA o.max_5xs                           | 1         | 1.79%   |
| Lenovo ThinkPad X200 7459L61                | 1         | 1.79%   |
| Lenovo ThinkPad X13 Gen 3 21CM0024US        | 1         | 1.79%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001JUS | 1         | 1.79%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW   | 1         | 1.79%   |
| Lenovo ThinkPad T470p 20J7S25C00            | 1         | 1.79%   |
| Lenovo ThinkPad T16 Gen 1 21CH000FUS        | 1         | 1.79%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.79%   |
| Lenovo ThinkPad P14s Gen 2a 21A0000JMH      | 1         | 1.79%   |
| Lenovo ThinkPad Edge E330 3354AMG           | 1         | 1.79%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF            | 1         | 1.79%   |
| Lenovo IdeaPad Yoga 13 20175                | 1         | 1.79%   |
| HUAWEI NBLK-WAX9X                           | 1         | 1.79%   |
| HUAWEI KPL-W0X                              | 1         | 1.79%   |
| HUAWEI CREM-WXX9                            | 1         | 1.79%   |
| HP ZBook 17 G3                              | 1         | 1.79%   |
| HP Victus by Laptop 16-e0xxx                | 1         | 1.79%   |
| HP Victus by Gaming Laptop 15-fb0xxx        | 1         | 1.79%   |
| HP Pavilion Notebook                        | 1         | 1.79%   |
| HP OMEN by Laptop                           | 1         | 1.79%   |
| HP Laptop 17-cp0xxx                         | 1         | 1.79%   |
| HP G62                                      | 1         | 1.79%   |
| HP EliteBook 8570p                          | 1         | 1.79%   |
| HP EliteBook 840 G3                         | 1         | 1.79%   |
| HP EliteBook 745 G6                         | 1         | 1.79%   |
| Dell XPS 15 9520                            | 1         | 1.79%   |
| Dell XPS 13 9305                            | 1         | 1.79%   |
| Dell Latitude E6540                         | 1         | 1.79%   |
| Dell Latitude 7480                          | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 16.07%  |
| ASUS ROG           | 4         | 7.14%   |
| Acer Aspire        | 4         | 7.14%   |
| HP EliteBook       | 3         | 5.36%   |
| Dell Latitude      | 3         | 5.36%   |
| HP Victus          | 2         | 3.57%   |
| Dell XPS           | 2         | 3.57%   |
| Dell Precision     | 2         | 3.57%   |
| Dell Inspiron      | 2         | 3.57%   |
| Unknown            | 2         | 3.57%   |
| Valve Jupiter      | 1         | 1.79%   |
| TUXEDO Polaris     | 1         | 1.79%   |
| Toshiba Satellite  | 1         | 1.79%   |
| Timi RedmiBook     | 1         | 1.79%   |
| Star Labs StarBook | 1         | 1.79%   |
| realme RMNBXXXX    | 1         | 1.79%   |
| MSI Vector         | 1         | 1.79%   |
| MSI GS66           | 1         | 1.79%   |
| MAXDATA o.max      | 1         | 1.79%   |
| Lenovo Legion      | 1         | 1.79%   |
| Lenovo IdeaPad     | 1         | 1.79%   |
| HUAWEI NBLK-WAX9X  | 1         | 1.79%   |
| HUAWEI KPL-W0X     | 1         | 1.79%   |
| HUAWEI CREM-WXX9   | 1         | 1.79%   |
| HP ZBook           | 1         | 1.79%   |
| HP Pavilion        | 1         | 1.79%   |
| HP OMEN            | 1         | 1.79%   |
| HP Laptop          | 1         | 1.79%   |
| HP G62             | 1         | 1.79%   |
| ASUS VivoBook      | 1         | 1.79%   |
| ASUS Strix         | 1         | 1.79%   |
| ASUS N550JX        | 1         | 1.79%   |
| ASUS ASUS          | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 21.43%  |
| 2021 | 11        | 19.64%  |
| 2019 | 6         | 10.71%  |
| 2020 | 5         | 8.93%   |
| 2018 | 4         | 7.14%   |
| 2012 | 4         | 7.14%   |
| 2017 | 3         | 5.36%   |
| 2010 | 3         | 5.36%   |
| 2016 | 2         | 3.57%   |
| 2023 | 1         | 1.79%   |
| 2015 | 1         | 1.79%   |
| 2013 | 1         | 1.79%   |
| 2011 | 1         | 1.79%   |
| 2008 | 1         | 1.79%   |
| 2007 | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 56        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 56        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 98.21%  |
| Yes  | 1         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 12        | 21.43%  |
| 32.01-64.0  | 11        | 19.64%  |
| 8.01-16.0   | 11        | 19.64%  |
| 4.01-8.0    | 10        | 17.86%  |
| 24.01-32.0  | 5         | 8.93%   |
| 3.01-4.0    | 3         | 5.36%   |
| 64.01-256.0 | 2         | 3.57%   |
| 2.01-3.0    | 1         | 1.79%   |
| 0.51-1.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 21.05%  |
| 2.01-3.0  | 10        | 17.54%  |
| 0.51-1.0  | 8         | 14.04%  |
| 4.01-8.0  | 7         | 12.28%  |
| 8.01-16.0 | 7         | 12.28%  |
| 0.01-0.5  | 7         | 12.28%  |
| 3.01-4.0  | 6         | 10.53%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 66.07%  |
| 2      | 18        | 32.14%  |
| 3      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 85.71%  |
| Yes       | 8         | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 82.14%  |
| No        | 10        | 17.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 89.29%  |
| No        | 6         | 10.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 28.57%  |
| Russia      | 5         | 8.93%   |
| France      | 5         | 8.93%   |
| Canada      | 5         | 8.93%   |
| Spain       | 3         | 5.36%   |
| Czechia     | 3         | 5.36%   |
| Italy       | 2         | 3.57%   |
| Germany     | 2         | 3.57%   |
| UK          | 1         | 1.79%   |
| Romania     | 1         | 1.79%   |
| Poland      | 1         | 1.79%   |
| Norway      | 1         | 1.79%   |
| New Zealand | 1         | 1.79%   |
| Netherlands | 1         | 1.79%   |
| Lithuania   | 1         | 1.79%   |
| Iceland     | 1         | 1.79%   |
| Hungary     | 1         | 1.79%   |
| Hong Kong   | 1         | 1.79%   |
| Greece      | 1         | 1.79%   |
| China       | 1         | 1.79%   |
| Brazil      | 1         | 1.79%   |
| Australia   | 1         | 1.79%   |
| Algeria     | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Taganrog           | 2         | 3.57%   |
| St Petersburg      | 2         | 3.57%   |
| Ponetovice         | 2         | 3.57%   |
| Oviedo             | 2         | 3.57%   |
| Milan              | 2         | 3.57%   |
| Kippens            | 2         | 3.57%   |
| Wessington Springs | 1         | 1.79%   |
| Wesseling          | 1         | 1.79%   |
| Welwyn Garden City | 1         | 1.79%   |
| Vilnius            | 1         | 1.79%   |
| Verona             | 1         | 1.79%   |
| Urbana             | 1         | 1.79%   |
| Toronto            | 1         | 1.79%   |
| Sun Prairie        | 1         | 1.79%   |
| Seattle            | 1         | 1.79%   |
| Reykjavik          | 1         | 1.79%   |
| Reims              | 1         | 1.79%   |
| Rapid City         | 1         | 1.79%   |
| Prague             | 1         | 1.79%   |
| Pittsburgh         | 1         | 1.79%   |
| Paris              | 1         | 1.79%   |
| Oslo               | 1         | 1.79%   |
| Omsk               | 1         | 1.79%   |
| Miami              | 1         | 1.79%   |
| Melbourne          | 1         | 1.79%   |
| Mangalia           | 1         | 1.79%   |
| Majadahonda        | 1         | 1.79%   |
| Madrid             | 1         | 1.79%   |
| Lomme              | 1         | 1.79%   |
| Krakow             | 1         | 1.79%   |
| Kobrasol           | 1         | 1.79%   |
| Hamilton           | 1         | 1.79%   |
| Girona             | 1         | 1.79%   |
| Gatineau           | 1         | 1.79%   |
| Frankfurt am Main  | 1         | 1.79%   |
| Ewirgol            | 1         | 1.79%   |
| Enschede           | 1         | 1.79%   |
| El Paso            | 1         | 1.79%   |
| Concord            | 1         | 1.79%   |
| Cognac             | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 16        | 25     | 23.19%  |
| SanDisk                     | 12        | 12     | 17.39%  |
| Seagate                     | 6         | 6      | 8.7%    |
| SK hynix                    | 5         | 5      | 7.25%   |
| WDC                         | 3         | 3      | 4.35%   |
| Phison Electronics          | 3         | 4      | 4.35%   |
| Micron Technology           | 3         | 3      | 4.35%   |
| Intel                       | 3         | 4      | 4.35%   |
| HGST                        | 3         | 3      | 4.35%   |
| Unknown                     | 2         | 2      | 2.9%    |
| Kingston Technology Company | 2         | 2      | 2.9%    |
| China                       | 2         | 3      | 2.9%    |
| A-DATA Technology           | 2         | 2      | 2.9%    |
| Toshiba                     | 1         | 1      | 1.45%   |
| Micron/Crucial Technology   | 1         | 1      | 1.45%   |
| KIOXIA                      | 1         | 1      | 1.45%   |
| Intenso                     | 1         | 1      | 1.45%   |
| Hitachi                     | 1         | 1      | 1.45%   |
| Dogfish                     | 1         | 1      | 1.45%   |
| Crucial                     | 1         | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 8         | 11.11%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 6         | 8.33%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 3         | 4.17%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 3         | 4.17%   |
| Seagate ST1000LM035-1RK172 970GB                   | 2         | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 2.78%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 2         | 2.78%   |
| HGST HTS725050A7E630 500GB                         | 2         | 2.78%   |
| China SSD 1TB                                      | 2         | 2.78%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                   | 1         | 1.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 1.39%   |
| WDC WD20 SPZX-22CRAT0 2TB                          | 1         | 1.39%   |
| Unknown NVMe SSD Drive 1TB                         | 1         | 1.39%   |
| Unknown MMC Card  128GB                            | 1         | 1.39%   |
| Toshiba MK5056GSY 500GB                            | 1         | 1.39%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB            | 1         | 1.39%   |
| SK hynix SC311 SATA 128GB SSD                      | 1         | 1.39%   |
| SK hynix PC801 NVMe 1TB                            | 1         | 1.39%   |
| SK hynix PC711 HFS512GDE9X073N 512GB               | 1         | 1.39%   |
| SK hynix BC711 NVMe 512GB                          | 1         | 1.39%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 1.39%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 1.39%   |
| Sandisk WD_BLACK SN850X 2000GB                     | 1         | 1.39%   |
| Sandisk WD_BLACK SN850X 1000GB                     | 1         | 1.39%   |
| Sandisk WDC PC SN530 SDBPTPZ-512G-1002 512GB       | 1         | 1.39%   |
| SanDisk SDSSDHII960G 960GB                         | 1         | 1.39%   |
| SanDisk SD9SN8W256G1027 256GB SSD                  | 1         | 1.39%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                | 1         | 1.39%   |
| Samsung SSD 980 1TB                                | 1         | 1.39%   |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 1         | 1.39%   |
| Samsung MZVLQ1T0HBLB-00B00 1024GB                  | 1         | 1.39%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD               | 1         | 1.39%   |
| Samsung MZ7TE256HMHP-000H1 256GB SSD               | 1         | 1.39%   |
| Phison PS5013 E13 NVMe Controller 500GB            | 1         | 1.39%   |
| Phison PCIe SSD 8TB                                | 1         | 1.39%   |
| Phison E12 NVMe Controller 512GB                   | 1         | 1.39%   |
| Micron/Crucial P1 NVMe PCIe SSD 500GB              | 1         | 1.39%   |
| Micron 2450 NVMe 512GB                             | 1         | 1.39%   |
| KIOXIA KBG40ZNV512G 512GB                          | 1         | 1.39%   |
| Kingston Company SNV2S2000G 2TB                    | 1         | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 50%     |
| HGST    | 3         | 3      | 25%     |
| WDC     | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| China               | 2         | 3      | 13.33%  |
| A-DATA Technology   | 2         | 2      | 13.33%  |
| SK hynix            | 1         | 1      | 6.67%   |
| Intenso             | 1         | 1      | 6.67%   |
| Dogfish             | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 52     | 57.81%  |
| SSD  | 14        | 16     | 21.88%  |
| HDD  | 12        | 12     | 18.75%  |
| MMC  | 1         | 1      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 52     | 58.73%  |
| SATA | 24        | 27     | 38.1%   |
| SAS  | 1         | 1      | 1.59%   |
| MMC  | 1         | 1      | 1.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 15     | 53.85%  |
| 0.51-1.0   | 8         | 8      | 30.77%  |
| 1.01-2.0   | 4         | 5      | 15.38%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 28.57%  |
| 501-1000       | 13        | 23.21%  |
| 101-250        | 9         | 16.07%  |
| 1001-2000      | 8         | 14.29%  |
| More than 3000 | 2         | 3.57%   |
| 2001-3000      | 2         | 3.57%   |
| 51-100         | 2         | 3.57%   |
| Unknown        | 2         | 3.57%   |
| 21-50          | 1         | 1.79%   |
| 1-20           | 1         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 12        | 20.69%  |
| 1-20      | 12        | 20.69%  |
| 251-500   | 9         | 15.52%  |
| 101-250   | 9         | 15.52%  |
| 501-1000  | 7         | 12.07%  |
| 51-100    | 6         | 10.34%  |
| Unknown   | 2         | 3.45%   |
| 1001-2000 | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 28.57%  |
| HGST HTS725050A7E630 500GB           | 2         | 2      | 28.57%  |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 14.29%  |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 3         | 3      | 42.86%  |
| Seagate  | 2         | 2      | 28.57%  |
| Toshiba  | 1         | 1      | 14.29%  |
| SK hynix | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 50%     |
| Seagate | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 85.71%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Works    | 46        | 66     | 77.97%  |
| Malfunc  | 7         | 7      | 11.86%  |
| Detected | 6         | 8      | 10.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 26        | 35.62%  |
| Samsung Electronics         | 14        | 19.18%  |
| SanDisk                     | 9         | 12.33%  |
| AMD                         | 9         | 12.33%  |
| SK hynix                    | 4         | 5.48%   |
| Phison Electronics          | 3         | 4.11%   |
| Micron Technology           | 3         | 4.11%   |
| Kingston Technology Company | 2         | 2.74%   |
| Micron/Crucial Technology   | 1         | 1.37%   |
| KIOXIA                      | 1         | 1.37%   |
| INNOGRIT                    | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 10%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 6.25%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 3.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 3.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.75%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.75%   |
| Micron NVMe Storage Controller                                                 | 3         | 3.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 3.75%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 2         | 2.5%    |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.5%    |
| Intel Non-Volatile memory controller                                           | 2         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 2.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.5%    |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 1.25%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.25%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.25%   |
| Phison NVMe Storage Controller                                                 | 1         | 1.25%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.25%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.25%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.25%   |
| Intel SSD 660P Series                                                          | 1         | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.25%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.25%   |
| INNOGRIT Non-Volatile memory controller                                        | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 37        | 51.39%  |
| SATA | 29        | 40.28%  |
| RAID | 5         | 6.94%   |
| IDE  | 1         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 67.86%  |
| AMD    | 18        | 32.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                   | 4         | 7.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 4         | 7.14%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 2         | 3.57%   |
| Intel 12th Gen Core i7-12850HX                  | 2         | 3.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 3.57%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz            | 1         | 1.79%   |
| Intel Pentium Silver N6000 @ 1.10GHz            | 1         | 1.79%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 1         | 1.79%   |
| Intel Core i9-10885H CPU @ 2.40GHz              | 1         | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.79%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1         | 1.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.79%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 1.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 1.79%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 1.79%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 1.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 1.79%   |
| Intel Core i5-3360M CPU @ 2.80GHz               | 1         | 1.79%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 1.79%   |
| Intel Core i3-2328M CPU @ 2.20GHz               | 1         | 1.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 1         | 1.79%   |
| Intel Core Duo CPU T2450 @ 2.00GHz              | 1         | 1.79%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 1.79%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 1.79%   |
| Intel 12th Gen Core i7-1260P                    | 1         | 1.79%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 1.79%   |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz         | 1         | 1.79%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics      | 1         | 1.79%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics      | 1         | 1.79%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.79%   |
| AMD Ryzen 7 6800H with Radeon Graphics          | 1         | 1.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 1.79%   |
| AMD Ryzen 7 4800HS with Radeon Graphics         | 1         | 1.79%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 13        | 23.21%  |
| Intel Core i7        | 11        | 19.64%  |
| AMD Ryzen 7          | 8         | 14.29%  |
| Intel Core i5        | 6         | 10.71%  |
| AMD Ryzen 5          | 4         | 7.14%   |
| AMD Ryzen 7 PRO      | 3         | 5.36%   |
| Intel Core i3        | 2         | 3.57%   |
| Intel Xeon           | 1         | 1.79%   |
| Intel Pentium Silver | 1         | 1.79%   |
| Intel Pentium        | 1         | 1.79%   |
| Intel Core i9        | 1         | 1.79%   |
| Intel Core Duo       | 1         | 1.79%   |
| Intel Core 2 Duo     | 1         | 1.79%   |
| Intel Atom           | 1         | 1.79%   |
| AMD Ryzen 5 PRO      | 1         | 1.79%   |
| AMD Athlon II        | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 19        | 33.93%  |
| 8      | 12        | 21.43%  |
| 2      | 11        | 19.64%  |
| 6      | 6         | 10.71%  |
| 14     | 4         | 7.14%   |
| 16     | 2         | 3.57%   |
| 12     | 1         | 1.79%   |
| 1      | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 91.07%  |
| 1      | 5         | 8.93%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 96.43%  |
| 32-bit         | 2         | 3.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 32.76%  |
| 0x806c1    | 5         | 8.62%   |
| 0x0a50000c | 5         | 8.62%   |
| 0x906ea    | 3         | 5.17%   |
| 0x906e9    | 3         | 5.17%   |
| 0xa0652    | 2         | 3.45%   |
| 0x906a3    | 2         | 3.45%   |
| 0x90672    | 2         | 3.45%   |
| 0x206a7    | 2         | 3.45%   |
| 0x08608103 | 2         | 3.45%   |
| 0x806e9    | 1         | 1.72%   |
| 0x506e3    | 1         | 1.72%   |
| 0x406e3    | 1         | 1.72%   |
| 0x306d4    | 1         | 1.72%   |
| 0x306a9    | 1         | 1.72%   |
| 0x20655    | 1         | 1.72%   |
| 0x0a50000d | 1         | 1.72%   |
| 0x0a404102 | 1         | 1.72%   |
| 0x08900201 | 1         | 1.72%   |
| 0x08701021 | 1         | 1.72%   |
| 0x08600104 | 1         | 1.72%   |
| 0x08108109 | 1         | 1.72%   |
| 0x08101007 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 12.5%   |
| Alderlake Hybrid | 7         | 12.5%   |
| Unknown          | 7         | 12.5%   |
| Zen 3            | 6         | 10.71%  |
| TigerLake        | 5         | 8.93%   |
| SandyBridge      | 4         | 7.14%   |
| CometLake        | 3         | 5.36%   |
| Zen+             | 2         | 3.57%   |
| Zen 2            | 2         | 3.57%   |
| Skylake          | 2         | 3.57%   |
| IvyBridge        | 2         | 3.57%   |
| Haswell          | 2         | 3.57%   |
| Zen              | 1         | 1.79%   |
| Westmere         | 1         | 1.79%   |
| Penryn           | 1         | 1.79%   |
| P6               | 1         | 1.79%   |
| K10              | 1         | 1.79%   |
| Broadwell        | 1         | 1.79%   |
| Bonnell          | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 42.11%  |
| Nvidia | 23        | 30.26%  |
| AMD    | 21        | 27.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 5         | 6.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 5         | 6.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 6.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 4.94%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 2.47%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 2.47%   |
| Nvidia GA104GLM [RTX A3000 12GB Laptop GPU]                                   | 2         | 2.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 2.47%   |
| Intel HD Graphics 630                                                         | 2         | 2.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 2.47%   |
| AMD Renoir                                                                    | 2         | 2.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.47%   |
| AMD Lucienne                                                                  | 2         | 2.47%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 1.23%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.23%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 1.23%   |
| Nvidia GM204GLM [Quadro M3000M]                                               | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.23%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 1.23%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 1.23%   |
| Nvidia GA104M [Geforce RTX 3070 Ti Laptop GPU]                                | 1         | 1.23%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                   | 1         | 1.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.23%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.23%   |
| Intel HD Graphics P630                                                        | 1         | 1.23%   |
| Intel HD Graphics 620                                                         | 1         | 1.23%   |
| Intel HD Graphics 5500                                                        | 1         | 1.23%   |
| Intel HD Graphics 530                                                         | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 15        | 26.79%  |
| 1 x AMD        | 14        | 25%     |
| 1 x Intel      | 12        | 21.43%  |
| 1 x Nvidia     | 6         | 10.71%  |
| 2 x Intel      | 3         | 5.36%   |
| 2 x AMD        | 2         | 3.57%   |
| Intel + AMD    | 2         | 3.57%   |
| AMD + Nvidia   | 2         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 44        | 78.57%  |
| Proprietary | 11        | 19.64%  |
| Unknown     | 1         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 48.21%  |
| 3.01-4.0   | 7         | 12.5%   |
| 0.51-1.0   | 7         | 12.5%   |
| 1.01-2.0   | 5         | 8.93%   |
| 0.01-0.5   | 5         | 8.93%   |
| 5.01-6.0   | 2         | 3.57%   |
| 8.01-16.0  | 2         | 3.57%   |
| 7.01-8.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 17.46%  |
| BOE                     | 9         | 14.29%  |
| AU Optronics            | 8         | 12.7%   |
| Samsung Electronics     | 5         | 7.94%   |
| LG Display              | 5         | 7.94%   |
| Sharp                   | 3         | 4.76%   |
| PANDA                   | 2         | 3.17%   |
| Dell                    | 2         | 3.17%   |
| BOE Technology Group    | 2         | 3.17%   |
| Valve                   | 1         | 1.59%   |
| TMX                     | 1         | 1.59%   |
| Sony                    | 1         | 1.59%   |
| Philips                 | 1         | 1.59%   |
| Lenovo                  | 1         | 1.59%   |
| InfoVision              | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| Goldstar                | 1         | 1.59%   |
| ELSA                    | 1         | 1.59%   |
| Eizo                    | 1         | 1.59%   |
| CTO                     | 1         | 1.59%   |
| CSO                     | 1         | 1.59%   |
| Chi Mei Optoelectronics | 1         | 1.59%   |
| ASUSTek Computer        | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |
| Unknown                 | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE Technology Group LCD Monitor 1920x1080                            | 2         | 3.13%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.56%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 1.56%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 1.56%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch               | 1         | 1.56%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 1.56%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 1.56%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.56%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 1         | 1.56%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.56%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD058C 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 1.56%   |
| InfoVision LCD Monitor IVO8C69 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1         | 1.56%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 600x340mm 27.2-inch              | 1         | 1.56%   |
| ELSA EL271Q ELS0270 1920x1080 597x336mm 27.0-inch                     | 1         | 1.56%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                     | 1         | 1.56%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                     | 1         | 1.56%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 1         | 1.56%   |
| Dell S3422DW DELD104 3440x1440 797x334mm 34.0-inch                    | 1         | 1.56%   |
| CTO LCD Monitor CTO3391 1920x1200 286x179mm 13.3-inch                 | 1         | 1.56%   |
| CSO LCD Monitor CSO160E 2560x1600 344x215mm 16.0-inch                 | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1606 1920x1080 355x199mm 16.0-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D1 1366x768 309x173mm 13.9-inch       | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 34        | 55.74%  |
| 2560x1440 (QHD)   | 4         | 6.56%   |
| 1366x768 (WXGA)   | 4         | 6.56%   |
| 2560x1600         | 3         | 4.92%   |
| 1600x900 (HD+)    | 3         | 4.92%   |
| 3840x2160 (4K)    | 2         | 3.28%   |
| 800x1280          | 1         | 1.64%   |
| 3456x2160         | 1         | 1.64%   |
| 3440x1440         | 1         | 1.64%   |
| 3200x2000         | 1         | 1.64%   |
| 2520x1680         | 1         | 1.64%   |
| 2160x1440         | 1         | 1.64%   |
| 1920x540          | 1         | 1.64%   |
| 1920x1200 (WUXGA) | 1         | 1.64%   |
| 1280x800 (WXGA)   | 1         | 1.64%   |
| 1280x1024 (SXGA)  | 1         | 1.64%   |
| 1024x600          | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 17        | 26.98%  |
| 17      | 10        | 15.87%  |
| 13      | 10        | 15.87%  |
| 14      | 6         | 9.52%   |
| 16      | 4         | 6.35%   |
| 27      | 3         | 4.76%   |
| Unknown | 3         | 4.76%   |
| 23      | 2         | 3.17%   |
| 34      | 1         | 1.59%   |
| 31      | 1         | 1.59%   |
| 25      | 1         | 1.59%   |
| 24      | 1         | 1.59%   |
| 12      | 1         | 1.59%   |
| 10      | 1         | 1.59%   |
| 8       | 1         | 1.59%   |
| 7       | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 50.79%  |
| 351-400     | 10        | 15.87%  |
| 501-600     | 7         | 11.11%  |
| 201-300     | 7         | 11.11%  |
| Unknown     | 3         | 4.76%   |
| 701-800     | 1         | 1.59%   |
| 601-700     | 1         | 1.59%   |
| 101-200     | 1         | 1.59%   |
| 1-100       | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 74.58%  |
| 16/10   | 6         | 10.17%  |
| 3/2     | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| 5/4     | 1         | 1.69%   |
| 32/9    | 1         | 1.69%   |
| 21/9    | 1         | 1.69%   |
| 0.67    | 1         | 1.69%   |
| 0.62    | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 28.57%  |
| 81-90          | 12        | 19.05%  |
| 121-130        | 9         | 14.29%  |
| 71-80          | 4         | 6.35%   |
| 301-350        | 3         | 4.76%   |
| 201-250        | 3         | 4.76%   |
| 111-120        | 3         | 4.76%   |
| Unknown        | 3         | 4.76%   |
| 351-500        | 2         | 3.17%   |
| 1-40           | 2         | 3.17%   |
| 61-70          | 1         | 1.59%   |
| 41-50          | 1         | 1.59%   |
| 251-300        | 1         | 1.59%   |
| 141-150        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 47.62%  |
| 161-240       | 10        | 15.87%  |
| 101-120       | 9         | 14.29%  |
| 51-100        | 7         | 11.11%  |
| More than 240 | 4         | 6.35%   |
| Unknown       | 3         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 85.71%  |
| 2     | 7         | 12.5%   |
| 3     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 42.7%   |
| Realtek Semiconductor | 31        | 34.83%  |
| Qualcomm Atheros      | 4         | 4.49%   |
| Xiaomi                | 3         | 3.37%   |
| MediaTek              | 3         | 3.37%   |
| Qualcomm              | 2         | 2.25%   |
| Broadcom              | 2         | 2.25%   |
| ICS Advent            | 1         | 1.12%   |
| Edimax Technology     | 1         | 1.12%   |
| Dell                  | 1         | 1.12%   |
| Broadcom Limited      | 1         | 1.12%   |
| ASIX Electronics      | 1         | 1.12%   |
| Arduino SA            | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 17        | 15.74%  |
| Intel Wi-Fi 6 AX200                                                     | 10        | 9.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 4.63%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.78%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.85%   |
| Intel Wireless 8260                                                     | 2         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.85%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 1.85%   |
| Intel Ethernet Connection (17) I219-LM                                  | 2         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.93%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.93%   |
| Intel Wireless 7265                                                     | 1         | 0.93%   |
| Intel Wireless 7260                                                     | 1         | 0.93%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                     | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.93%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.93%   |
| Intel Ethernet Connection (16) I219-LM                                  | 1         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 62.07%  |
| Realtek Semiconductor | 9         | 15.52%  |
| Qualcomm Atheros      | 3         | 5.17%   |
| MediaTek              | 3         | 5.17%   |
| Qualcomm              | 2         | 3.45%   |
| Broadcom              | 2         | 3.45%   |
| Edimax Technology     | 1         | 1.72%   |
| Dell                  | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 17.24%  |
| Intel Wireless 8265 / 8275                                              | 4         | 6.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.17%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 5.17%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 5.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 3.45%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 3.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 3.45%   |
| Intel Wireless 8260                                                     | 2         | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 3.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.72%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                  | 1         | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.72%   |
| Intel Wireless 7265                                                     | 1         | 1.72%   |
| Intel Wireless 7260                                                     | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.72%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.72%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 56.25%  |
| Intel                 | 14        | 29.17%  |
| Xiaomi                | 3         | 6.25%   |
| Qualcomm Atheros      | 2         | 4.17%   |
| ICS Advent            | 1         | 2.08%   |
| ASIX Electronics      | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 34.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 10.2%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 6.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 6.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 4.08%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 4.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.04%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 2.04%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.04%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.04%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1         | 2.04%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.04%   |
| ICS Advent 10/100M LAN                                            | 1         | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 54.37%  |
| Ethernet | 46        | 44.66%  |
| Modem    | 1         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 70.69%  |
| Ethernet | 17        | 29.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 66.07%  |
| 1     | 17        | 30.36%  |
| 3     | 1         | 1.79%   |
| 0     | 1         | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 69.64%  |
| Yes  | 17        | 30.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 34        | 66.67%  |
| Realtek Semiconductor   | 4         | 7.84%   |
| USI                     | 2         | 3.92%   |
| Realtek                 | 2         | 3.92%   |
| Lite-On Technology      | 2         | 3.92%   |
| IMC Networks            | 2         | 3.92%   |
| Foxconn / Hon Hai       | 2         | 3.92%   |
| Dell                    | 1         | 1.96%   |
| Cambridge Silicon Radio | 1         | 1.96%   |
| Broadcom                | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 10        | 19.61%  |
| Intel Bluetooth wireless interface                  | 8         | 15.69%  |
| Intel Bluetooth Device                              | 5         | 9.8%    |
| Intel AX201 Bluetooth                               | 5         | 9.8%    |
| Realtek Bluetooth Radio                             | 4         | 7.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 7.84%   |
| USI Bluetooth Device                                | 2         | 3.92%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 3.92%   |
| Intel AX210 Bluetooth                               | 2         | 3.92%   |
| Lite-On Wireless_Device                             | 1         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.96%   |
| IMC Networks Wireless_Device                        | 1         | 1.96%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.96%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.96%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.96%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 38        | 48.72%  |
| AMD                 | 20        | 25.64%  |
| Nvidia              | 16        | 20.51%  |
| ASUSTek Computer    | 2         | 2.56%   |
| C-Media Electronics | 1         | 1.28%   |
| AudioQuest          | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 16%     |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 9%      |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 5%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 5%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5%      |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 3%      |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3%      |
| Intel CM238 HD Audio Controller                                            | 3         | 3%      |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 3%      |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2%      |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2%      |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2%      |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1%      |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1%      |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1%      |
| Intel Jasper Lake HD Audio                                                 | 1         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 1         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1%      |
| AudioQuest DragonFly Red                                                   | 1         | 1%      |
| ASUSTek Computer TUF H3 Wireless                                           | 1         | 1%      |
| ASUSTek Computer C-Media Audio                                             | 1         | 1%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1%      |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1%      |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 31.15%  |
| SK hynix            | 14        | 22.95%  |
| Micron Technology   | 9         | 14.75%  |
| Crucial             | 6         | 9.84%   |
| Unknown             | 3         | 4.92%   |
| G.Skill             | 2         | 3.28%   |
| Corsair             | 2         | 3.28%   |
| Team                | 1         | 1.64%   |
| Patriot             | 1         | 1.64%   |
| Nanya Technology    | 1         | 1.64%   |
| Kingston            | 1         | 1.64%   |
| GSkill              | 1         | 1.64%   |
| Elpida              | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 3         | 4.76%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 2         | 3.17%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s   | 2         | 3.17%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 3.17%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 2         | 3.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 2         | 3.17%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 1.59%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 1         | 1.59%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s        | 1         | 1.59%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.59%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.59%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s    | 1         | 1.59%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 1.59%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16GB SODIMM DDR4 2400MT/s      | 1         | 1.59%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.59%   |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.59%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.59%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Samsung RAM M471A5244BB0-CRC 4GB Row Of Chips DDR4 2400MT/s  | 1         | 1.59%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.59%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.59%   |
| Patriot RAM Module 2GB SODIMM DDR2 533MT/s                   | 1         | 1.59%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 1         | 1.59%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 1         | 1.59%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 1         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 50.94%  |
| DDR3   | 11        | 20.75%  |
| DDR5   | 7         | 13.21%  |
| LPDDR4 | 4         | 7.55%   |
| LPDDR5 | 2         | 3.77%   |
| DDR2   | 2         | 3.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 83.33%  |
| Row Of Chips | 8         | 14.81%  |
| DIMM         | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 21        | 36.84%  |
| 16384 | 15        | 26.32%  |
| 4096  | 10        | 17.54%  |
| 32768 | 5         | 8.77%   |
| 2048  | 5         | 8.77%   |
| 1024  | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 16        | 28.57%  |
| 2667    | 8         | 14.29%  |
| 4800    | 7         | 12.5%   |
| 1600    | 7         | 12.5%   |
| 4267    | 4         | 7.14%   |
| 2400    | 4         | 7.14%   |
| 6400    | 2         | 3.57%   |
| 1334    | 2         | 3.57%   |
| 3600    | 1         | 1.79%   |
| 2133    | 1         | 1.79%   |
| 1333    | 1         | 1.79%   |
| 1067    | 1         | 1.79%   |
| 533     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 14        | 29.79%  |
| Microdia                      | 8         | 17.02%  |
| Luxvisions Innotech Limited   | 4         | 8.51%   |
| Sunplus Innovation Technology | 3         | 6.38%   |
| Quanta                        | 3         | 6.38%   |
| IMC Networks                  | 3         | 6.38%   |
| Bison Electronics             | 2         | 4.26%   |
| SunplusIT                     | 1         | 2.13%   |
| Sunplus Technology            | 1         | 2.13%   |
| ShineTech                     | 1         | 2.13%   |
| Microsoft                     | 1         | 2.13%   |
| Logitech                      | 1         | 2.13%   |
| Lite-On Technology            | 1         | 2.13%   |
| Holitech                      | 1         | 2.13%   |
| Genesys Logic                 | 1         | 2.13%   |
| Apple                         | 1         | 2.13%   |
| Acer                          | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 8.51%   |
| Microdia Integrated_Webcam_HD                        | 3         | 6.38%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 4.26%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 2         | 4.26%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 4.26%   |
| Chicony HP HD Camera                                 | 2         | 4.26%   |
| SunplusIT 720p HD Camera                             | 1         | 2.13%   |
| Sunplus 1.3M HD WebCam                               | 1         | 2.13%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 2.13%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 2.13%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 2.13%   |
| ShineTech HD Camera                                  | 1         | 2.13%   |
| Quanta VGA WebCam                                    | 1         | 2.13%   |
| Quanta hm1091_techfront                              | 1         | 2.13%   |
| Quanta HD User Facing                                | 1         | 2.13%   |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 2.13%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 2.13%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 2.13%   |
| Logitech HD Pro Webcam C920                          | 1         | 2.13%   |
| Lite-On HP HD Camera                                 | 1         | 2.13%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 2.13%   |
| Holitech USB2.0 HD UVC WebCam                        | 1         | 2.13%   |
| Genesys Logic Digital Microscope                     | 1         | 2.13%   |
| Chicony Webcam-101                                   | 1         | 2.13%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 2.13%   |
| Chicony Lenovo EasyCamera                            | 1         | 2.13%   |
| Chicony HP Wide Vision HD                            | 1         | 2.13%   |
| Chicony HP TrueVision HD Camera                      | 1         | 2.13%   |
| Chicony HP Truevision HD                             | 1         | 2.13%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 2.13%   |
| Chicony HD Webcam                                    | 1         | 2.13%   |
| Bison HD Webcam                                      | 1         | 2.13%   |
| Bison HD Camera                                      | 1         | 2.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 1         | 2.13%   |
| Acer Lenovo Integrated Webcam                        | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 38.46%  |
| Synaptics                  | 5         | 38.46%  |
| Shenzhen Goodix Technology | 3         | 23.08%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 15.38%  |
| Validity Sensors Synaptics WBDI                            | 2         | 15.38%  |
| Synaptics UWP WBDI Device                                  | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 15.38%  |
| Validity Sensors VFS491                                    | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 25        | 43.1%   |
| 1     | 14        | 24.14%  |
| 4     | 6         | 10.34%  |
| 2     | 6         | 10.34%  |
| 3     | 5         | 8.62%   |
| 6     | 2         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 17.14%  |
| Bluetooth                | 12        | 17.14%  |
| Graphics card            | 11        | 15.71%  |
| Camera                   | 10        | 14.29%  |
| Chipcard                 | 6         | 8.57%   |
| Net/wireless             | 5         | 7.14%   |
| Communication controller | 5         | 7.14%   |
| Multimedia controller    | 4         | 5.71%   |
| Sound                    | 2         | 2.86%   |
| Card reader              | 2         | 2.86%   |
| Network                  | 1         | 1.43%   |

