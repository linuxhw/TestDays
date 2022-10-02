Devuan - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Devuan.

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

Total: 67

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| ASUSTek       | K55VJ                       | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASUSTek       | X555LJ                      | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| Toshiba       | Satellite M40X              | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | K55VJ                       | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| ASUSTek       | K55VJ                       | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| HP            | ProBook 6475b               | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Teclast       | F6 Plus                     | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Dell          | Precision 7530              | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| ASUSTek       | K52F                        | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| Dell          | Inspiron 1564               | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 24        | 43.64%  |
| Devuan 3                | 14        | 25.45%  |
| Devuan Testing/unstable | 8         | 14.55%  |
| Devuan 5                | 5         | 9.09%   |
| Devuan                  | 2         | 3.64%   |
| Devuan 3.0              | 1         | 1.82%   |
| Devuan 2.1              | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 4         | 6.78%   |
| 5.10.0-16-amd64           | 4         | 6.78%   |
| 5.10.0-13-amd64           | 4         | 6.78%   |
| 4.19.0-9-amd64            | 4         | 6.78%   |
| 5.7.0-2-amd64             | 3         | 5.08%   |
| 5.10.0-8-amd64            | 3         | 5.08%   |
| 5.10.0-10-amd64           | 3         | 5.08%   |
| 5.18.0-2-amd64            | 2         | 3.39%   |
| 5.10.0-18-amd64           | 2         | 3.39%   |
| 5.10.0-11-amd64           | 2         | 3.39%   |
| 4.19.0-17-amd64           | 2         | 3.39%   |
| 4.19.0-16-amd64           | 2         | 3.39%   |
| 4.19.0-14-amd64           | 2         | 3.39%   |
| 5.9.0-4-amd64             | 1         | 1.69%   |
| 5.8.0-1-amd64             | 1         | 1.69%   |
| 5.7.0-0.bpo.2-amd64       | 1         | 1.69%   |
| 5.6.0-2-amd64             | 1         | 1.69%   |
| 5.18.0-1-amd64            | 1         | 1.69%   |
| 5.15.5-xanmod1            | 1         | 1.69%   |
| 5.15.0-2-amd64            | 1         | 1.69%   |
| 5.14.0-4-amd64            | 1         | 1.69%   |
| 5.10.0-7-amd64            | 1         | 1.69%   |
| 5.10.0-4-amd64            | 1         | 1.69%   |
| 5.10.0-15-amd64           | 1         | 1.69%   |
| 5.10.0-14-amd64           | 1         | 1.69%   |
| 5.10.0-1-amd64            | 1         | 1.69%   |
| 5.1.21                    | 1         | 1.69%   |
| 4.9.0-14-amd64            | 1         | 1.69%   |
| 4.9.0-11-amd64            | 1         | 1.69%   |
| 4.9.0-11-686              | 1         | 1.69%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.69%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.69%   |
| 4.19.0-17-686-pae         | 1         | 1.69%   |
| 4.19.0-12-amd64           | 1         | 1.69%   |
| 4.19.0-10-amd64           | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 42.86%  |
| 4.19.0  | 13        | 23.21%  |
| 5.7.0   | 4         | 7.14%   |
| 4.9.0   | 4         | 7.14%   |
| 5.18.0  | 3         | 5.36%   |
| 5.9.0   | 1         | 1.79%   |
| 5.8.0   | 1         | 1.79%   |
| 5.6.0   | 1         | 1.79%   |
| 5.15.5  | 1         | 1.79%   |
| 5.15.0  | 1         | 1.79%   |
| 5.14.0  | 1         | 1.79%   |
| 5.1.21  | 1         | 1.79%   |
| 4.4.195 | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 42.86%  |
| 4.19    | 13        | 23.21%  |
| 5.7     | 4         | 7.14%   |
| 4.9     | 4         | 7.14%   |
| 5.18    | 3         | 5.36%   |
| 5.15    | 2         | 3.57%   |
| 5.9     | 1         | 1.79%   |
| 5.8     | 1         | 1.79%   |
| 5.6     | 1         | 1.79%   |
| 5.14    | 1         | 1.79%   |
| 5.1     | 1         | 1.79%   |
| 4.4     | 1         | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 47        | 92.16%  |
| i686   | 3         | 5.88%   |
| armv7l | 1         | 1.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| XFCE     | 21        | 38.89%  |
| KDE5     | 9         | 16.67%  |
| MATE     | 8         | 14.81%  |
| Unknown  | 7         | 12.96%  |
| i3       | 3         | 5.56%   |
| LXDE     | 2         | 3.7%    |
| Openbox  | 1         | 1.85%   |
| LXQt     | 1         | 1.85%   |
| GNOME    | 1         | 1.85%   |
| Cinnamon | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 49        | 94.23%  |
| Unknown | 2         | 3.85%   |
| Tty     | 1         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 16        | 29.63%  |
| Unknown | 16        | 29.63%  |
| LightDM | 15        | 27.78%  |
| SDDM    | 5         | 9.26%   |
| XDM     | 1         | 1.85%   |
| GDM3    | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 19        | 36.54%  |
| en_GB       | 11        | 21.15%  |
| ru_RU       | 6         | 11.54%  |
| pt_BR       | 3         | 5.77%   |
| it_IT       | 2         | 3.85%   |
| es_ES       | 2         | 3.85%   |
| Unknown     | 2         | 3.85%   |
| pl_PL       | 1         | 1.92%   |
| fr_BE       | 1         | 1.92%   |
| es_SV       | 1         | 1.92%   |
| en_US.utf-8 | 1         | 1.92%   |
| de_DE       | 1         | 1.92%   |
| de_AT       | 1         | 1.92%   |
| C           | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 29        | 55.77%  |
| EFI  | 23        | 44.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 84.31%  |
| Btrfs   | 3         | 5.88%   |
| Unknown | 3         | 5.88%   |
| OveXlay | 1         | 1.96%   |
| Ext2    | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 24        | 45.28%  |
| MBR     | 21        | 39.62%  |
| Unknown | 8         | 15.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 88.24%  |
| Yes       | 6         | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 75%     |
| Yes       | 13        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 31.37%  |
| Dell                | 8         | 15.69%  |
| Hewlett-Packard     | 4         | 7.84%   |
| Acer                | 4         | 7.84%   |
| Toshiba             | 3         | 5.88%   |
| ASUSTek Computer    | 3         | 5.88%   |
| MSI                 | 2         | 3.92%   |
| Fujitsu Siemens     | 2         | 3.92%   |
| Teclast             | 1         | 1.96%   |
| Sony                | 1         | 1.96%   |
| Samsung Electronics | 1         | 1.96%   |
| Notebook            | 1         | 1.96%   |
| Nokia               | 1         | 1.96%   |
| MTC                 | 1         | 1.96%   |
| IBM                 | 1         | 1.96%   |
| Fujitsu             | 1         | 1.96%   |
| CCE                 | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 1.96%   |
| Toshiba Satellite M40X                                                                   | 1         | 1.96%   |
| Toshiba Satellite L655                                                                   | 1         | 1.96%   |
| Teclast F6 Plus                                                                          | 1         | 1.96%   |
| Sony VPCEE23FX                                                                           | 1         | 1.96%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.96%   |
| Notebook W230ST                                                                          | 1         | 1.96%   |
| Nokia N900                                                                               | 1         | 1.96%   |
| MTC Montara-GML                                                                          | 1         | 1.96%   |
| MSI MS-1688                                                                              | 1         | 1.96%   |
| MSI Modern 15 A5M                                                                        | 1         | 1.96%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1.96%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.96%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.96%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.96%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.96%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.96%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.96%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.96%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.96%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.96%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 1.96%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.96%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.96%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.96%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.96%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.96%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.96%   |
| HP ProBook 6475b                                                                         | 1         | 1.96%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.96%   |
| HP Notebook                                                                              | 1         | 1.96%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 1.96%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.96%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.96%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.96%   |
| Dell Precision 7530                                                                      | 1         | 1.96%   |
| Dell Latitude E7250                                                                      | 1         | 1.96%   |
| Dell Latitude E7240                                                                      | 1         | 1.96%   |
| Dell Latitude E6430                                                                      | 1         | 1.96%   |
| Dell Latitude E5540                                                                      | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 23.53%  |
| Dell Latitude           | 6         | 11.76%  |
| Toshiba Satellite       | 3         | 5.88%   |
| Lenovo IdeaPad          | 3         | 5.88%   |
| Acer Aspire             | 3         | 5.88%   |
| Teclast F6              | 1         | 1.96%   |
| Sony VPCEE23FX          | 1         | 1.96%   |
| Samsung 355V4C          | 1         | 1.96%   |
| Notebook W230ST         | 1         | 1.96%   |
| Nokia N900              | 1         | 1.96%   |
| MTC Montara-GML         | 1         | 1.96%   |
| MSI MS-1688             | 1         | 1.96%   |
| MSI Modern              | 1         | 1.96%   |
| Lenovo V310-14ISK       | 1         | 1.96%   |
| IBM ThinkPad            | 1         | 1.96%   |
| HP ProBook              | 1         | 1.96%   |
| HP Pavilion             | 1         | 1.96%   |
| HP Notebook             | 1         | 1.96%   |
| HP Laptop               | 1         | 1.96%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.96%   |
| Fujitsu Siemens AMILO   | 1         | 1.96%   |
| Fujitsu LIFEBOOK        | 1         | 1.96%   |
| Dell Precision          | 1         | 1.96%   |
| Dell Inspiron           | 1         | 1.96%   |
| CCE Capella             | 1         | 1.96%   |
| ASUS X555LJ             | 1         | 1.96%   |
| ASUS K55VJ              | 1         | 1.96%   |
| ASUS K52F               | 1         | 1.96%   |
| Acer Extensa            | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 7         | 13.73%  |
| 2019    | 5         | 9.8%    |
| 2017    | 4         | 7.84%   |
| 2011    | 4         | 7.84%   |
| 2010    | 4         | 7.84%   |
| 2015    | 3         | 5.88%   |
| 2014    | 3         | 5.88%   |
| 2009    | 3         | 5.88%   |
| 2021    | 2         | 3.92%   |
| 2018    | 2         | 3.92%   |
| 2016    | 2         | 3.92%   |
| 2013    | 2         | 3.92%   |
| 2008    | 2         | 3.92%   |
| 2006    | 2         | 3.92%   |
| 2005    | 2         | 3.92%   |
| 2022    | 1         | 1.96%   |
| 2020    | 1         | 1.96%   |
| 2007    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 51        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 96.08%  |
| Enabled  | 2         | 3.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 96.08%  |
| Yes  | 2         | 3.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 21.57%  |
| 3.01-4.0    | 11        | 21.57%  |
| 8.01-16.0   | 11        | 21.57%  |
| 16.01-24.0  | 8         | 15.69%  |
| 2.01-3.0    | 3         | 5.88%   |
| 1.01-2.0    | 3         | 5.88%   |
| 0.01-0.5    | 2         | 3.92%   |
| 32.01-64.0  | 1         | 1.96%   |
| 64.01-256.0 | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 23        | 40.35%  |
| 4.01-8.0   | 12        | 21.05%  |
| 2.01-3.0   | 9         | 15.79%  |
| 0.51-1.0   | 5         | 8.77%   |
| 3.01-4.0   | 3         | 5.26%   |
| 0.01-0.5   | 3         | 5.26%   |
| 32.01-64.0 | 1         | 1.75%   |
| 8.01-16.0  | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 71.15%  |
| 2      | 12        | 23.08%  |
| 3      | 3         | 5.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 57.69%  |
| Yes       | 22        | 42.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 90.2%   |
| No        | 5         | 9.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 96.08%  |
| No        | 2         | 3.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 53.85%  |
| No        | 24        | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 6         | 11.54%  |
| Russia      | 5         | 9.62%   |
| Brazil      | 5         | 9.62%   |
| USA         | 4         | 7.69%   |
| Ukraine     | 4         | 7.69%   |
| Grenada     | 3         | 5.77%   |
| Spain       | 2         | 3.85%   |
| Poland      | 2         | 3.85%   |
| Italy       | 2         | 3.85%   |
| Hungary     | 2         | 3.85%   |
| Finland     | 2         | 3.85%   |
| Vietnam     | 1         | 1.92%   |
| UK          | 1         | 1.92%   |
| Slovakia    | 1         | 1.92%   |
| Serbia      | 1         | 1.92%   |
| Portugal    | 1         | 1.92%   |
| Norway      | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Mexico      | 1         | 1.92%   |
| Israel      | 1         | 1.92%   |
| Indonesia   | 1         | 1.92%   |
| Greece      | 1         | 1.92%   |
| France      | 1         | 1.92%   |
| El Salvador | 1         | 1.92%   |
| Belarus     | 1         | 1.92%   |
| Austria     | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Saint George's     | 3         | 5.77%   |
| Nadudvar           | 2         | 3.85%   |
| Milan              | 2         | 3.85%   |
| Kyiv               | 2         | 3.85%   |
| Yakutsk            | 1         | 1.92%   |
| Wroclaw            | 1         | 1.92%   |
| Wildberg           | 1         | 1.92%   |
| Trubchëvsk        | 1         | 1.92%   |
| Thessaloniki       | 1         | 1.92%   |
| Tel Aviv           | 1         | 1.92%   |
| Staunton           | 1         | 1.92%   |
| St Petersburg      | 1         | 1.92%   |
| Sao Paulo          | 1         | 1.92%   |
| San Salvador       | 1         | 1.92%   |
| Rio de Janeiro     | 1         | 1.92%   |
| Praia Grande       | 1         | 1.92%   |
| Oslo               | 1         | 1.92%   |
| Novopskov          | 1         | 1.92%   |
| Muenster-Sarmsheim | 1         | 1.92%   |
| Moscow             | 1         | 1.92%   |
| Maladzyechna       | 1         | 1.92%   |
| Madrid             | 1         | 1.92%   |
| Leonding           | 1         | 1.92%   |
| Leipzig            | 1         | 1.92%   |
| Kouvola            | 1         | 1.92%   |
| Kharkiv            | 1         | 1.92%   |
| Katzenbach         | 1         | 1.92%   |
| Katowice           | 1         | 1.92%   |
| Jyväskylä        | 1         | 1.92%   |
| Hermosillo         | 1         | 1.92%   |
| Hayden             | 1         | 1.92%   |
| Hanoi              | 1         | 1.92%   |
| Gijón             | 1         | 1.92%   |
| Fulham             | 1         | 1.92%   |
| Forest Grove       | 1         | 1.92%   |
| Cologne            | 1         | 1.92%   |
| Cherepovets        | 1         | 1.92%   |
| Bratislava         | 1         | 1.92%   |
| Belgrade           | 1         | 1.92%   |
| Belford Roxo       | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 14.93%  |
| Samsung Electronics | 7         | 12     | 10.45%  |
| Unknown             | 6         | 7      | 8.96%   |
| Kingston            | 5         | 5      | 7.46%   |
| Seagate             | 4         | 4      | 5.97%   |
| SanDisk             | 4         | 4      | 5.97%   |
| PNY                 | 3         | 3      | 4.48%   |
| Hitachi             | 3         | 3      | 4.48%   |
| Toshiba             | 2         | 2      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| HGST                | 2         | 2      | 2.99%   |
| Fujitsu             | 2         | 2      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Union Memory        | 1         | 2      | 1.49%   |
| UMIS                | 1         | 1      | 1.49%   |
| Teclast             | 1         | 1      | 1.49%   |
| Team                | 1         | 1      | 1.49%   |
| Smart               | 1         | 1      | 1.49%   |
| SABRENT             | 1         | 2      | 1.49%   |
| Patriot             | 1         | 1      | 1.49%   |
| Mushkin             | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| LITEON              | 1         | 4      | 1.49%   |
| KIOXIA              | 1         | 1      | 1.49%   |
| KingFast            | 1         | 1      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| HXY                 | 1         | 1      | 1.49%   |
| Hewlett-Packard     | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                    | 3         | 4.35%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 2.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 1.45%   |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 1.45%   |
| WDC WD5000BPVT-24HXZT3 500GB           | 1         | 1.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 1         | 1.45%   |
| WDC WD3200BEVT-22A23T0 320GB           | 1         | 1.45%   |
| WDC WD3200BEVE-00A0HT0 320GB           | 1         | 1.45%   |
| WDC WD2500BEKT-00A25T0 250GB           | 1         | 1.45%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 1.45%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 1.45%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB   | 1         | 1.45%   |
| Unknown SD04G  4GB                     | 1         | 1.45%   |
| Unknown SD  8GB                        | 1         | 1.45%   |
| Unknown MMC32G  32GB                   | 1         | 1.45%   |
| Unknown MMC Card  8GB                  | 1         | 1.45%   |
| Unknown MMC Card  32GB                 | 1         | 1.45%   |
| Unknown MMC Card  16GB                 | 1         | 1.45%   |
| Unknown MMC Card  128GB                | 1         | 1.45%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 1.45%   |
| UMIS RPFTJ256PDD2MWX 256GB             | 1         | 1.45%   |
| Toshiba MK5065GSX 500GB                | 1         | 1.45%   |
| Toshiba MK1252GSX 120GB                | 1         | 1.45%   |
| Teclast 256GB NS550-2242 SSD           | 1         | 1.45%   |
| Team T253X1120G 120GB SSD              | 1         | 1.45%   |
| Smart SSD SZ9MSE mSATA 256GB           | 1         | 1.45%   |
| SK hynix SC311 SATA 256GB SSD          | 1         | 1.45%   |
| SK hynix PC611 NVMe 1TB                | 1         | 1.45%   |
| Seagate ST9250410AS 250GB              | 1         | 1.45%   |
| Seagate ST500LT012-1DG142 500GB        | 1         | 1.45%   |
| Seagate ST250VT000-1DK141 250GB        | 1         | 1.45%   |
| Seagate Expansion Desk 2TB             | 1         | 1.45%   |
| SanDisk X300 MSATA 256GB SSD           | 1         | 1.45%   |
| SanDisk SSD PLUS 480GB                 | 1         | 1.45%   |
| SanDisk SDSSDHII240G 240GB             | 1         | 1.45%   |
| SanDisk SDSSDH3500G 500GB              | 1         | 1.45%   |
| Samsung SSD PM851 mSATA 128GB          | 1         | 1.45%   |
| Samsung SSD 980 1TB                    | 1         | 1.45%   |
| Samsung SSD 970 PRO 1TB                | 1         | 1.45%   |
| Samsung SSD 970 EVO Plus 500GB         | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 38.1%   |
| Seagate | 4         | 4      | 19.05%  |
| Hitachi | 3         | 3      | 14.29%  |
| Toshiba | 2         | 2      | 9.52%   |
| HGST    | 2         | 2      | 9.52%   |
| Fujitsu | 2         | 2      | 9.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 16.67%  |
| SanDisk             | 4         | 4      | 13.33%  |
| Samsung Electronics | 4         | 4      | 13.33%  |
| PNY                 | 3         | 3      | 10%     |
| Crucial             | 2         | 2      | 6.67%   |
| WDC                 | 1         | 2      | 3.33%   |
| Union Memory        | 1         | 2      | 3.33%   |
| Teclast             | 1         | 1      | 3.33%   |
| Team                | 1         | 1      | 3.33%   |
| Smart               | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Patriot             | 1         | 1      | 3.33%   |
| Mushkin             | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| LITEON              | 1         | 4      | 3.33%   |
| HXY                 | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 26        | 35     | 41.27%  |
| HDD     | 21        | 21     | 33.33%  |
| NVMe    | 9         | 15     | 14.29%  |
| MMC     | 6         | 7      | 9.52%   |
| Unknown | 1         | 1      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 56     | 72.88%  |
| NVMe | 8         | 13     | 13.56%  |
| MMC  | 6         | 7      | 10.17%  |
| SAS  | 2         | 3      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 41     | 77.78%  |
| 0.51-1.0   | 7         | 12     | 15.56%  |
| 1.01-2.0   | 3         | 3      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 24.07%  |
| 101-250        | 13        | 24.07%  |
| 51-100         | 7         | 12.96%  |
| 501-1000       | 6         | 11.11%  |
| 1001-2000      | 4         | 7.41%   |
| 21-50          | 3         | 5.56%   |
| Unknown        | 3         | 5.56%   |
| 2001-3000      | 2         | 3.7%    |
| 1-20           | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 30.19%  |
| 101-250   | 9         | 16.98%  |
| 51-100    | 9         | 16.98%  |
| 21-50     | 6         | 11.32%  |
| 251-500   | 4         | 7.55%   |
| 1001-2000 | 3         | 5.66%   |
| Unknown   | 3         | 5.66%   |
| 501-1000  | 2         | 3.77%   |
| 2001-3000 | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB  | 1         | 1      | 20%     |
| WDC WD3200BEVT-22A23T0 320GB  | 1         | 1      | 20%     |
| WDC WD10JPCX-24UE4T0 1TB      | 1         | 1      | 20%     |
| Hitachi HTS727575A9E364 752GB | 1         | 1      | 20%     |
| Hitachi HTS726060M9AT00 56GB  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Hitachi | 2         | 2      | 40%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Hitachi | 2         | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Works    | 40        | 56     | 67.8%   |
| Detected | 14        | 18     | 23.73%  |
| Malfunc  | 5         | 5      | 8.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 39        | 70.91%  |
| AMD                     | 8         | 14.55%  |
| Samsung Electronics     | 3         | 5.45%   |
| VIA Technologies        | 1         | 1.82%   |
| Union Memory (Shenzhen) | 1         | 1.82%   |
| SK hynix                | 1         | 1.82%   |
| SanDisk                 | 1         | 1.82%   |
| KIOXIA                  | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 10%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 8.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 6.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 5%      |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.33%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 3.33%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.67%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.67%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.67%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.67%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.67%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.67%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.67%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 38        | 66.67%  |
| NVMe | 8         | 14.04%  |
| IDE  | 8         | 14.04%  |
| RAID | 3         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 80.39%  |
| AMD    | 9         | 17.65%  |
| ARM    | 1         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 5.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 5.88%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 3.92%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.96%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.96%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.96%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.96%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.96%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.96%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.96%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.96%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.96%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.96%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.96%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.96%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.96%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.96%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.96%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.96%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.96%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.96%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.96%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.96%   |
| Intel Celeron M processor 1.40GHz           | 1         | 1.96%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.96%   |
| ARM Nokia RX-51 board Processor             | 1         | 1.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 1         | 1.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 1         | 1.96%   |
| AMD E2-1800 APU with Radeon HD Graphics     | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 21.57%  |
| Intel Core i7           | 9         | 17.65%  |
| Intel Core i3           | 9         | 17.65%  |
| Intel Core 2            | 3         | 5.88%   |
| Other                   | 2         | 3.92%   |
| Intel Pentium M         | 2         | 3.92%   |
| Intel Celeron           | 2         | 3.92%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Pentium Dual      | 1         | 1.96%   |
| Intel Pentium           | 1         | 1.96%   |
| Intel Core i9           | 1         | 1.96%   |
| Intel Celeron M         | 1         | 1.96%   |
| AMD Ryzen 7             | 1         | 1.96%   |
| AMD Ryzen 5             | 1         | 1.96%   |
| AMD E2                  | 1         | 1.96%   |
| AMD E                   | 1         | 1.96%   |
| AMD Athlon II           | 1         | 1.96%   |
| AMD A8                  | 1         | 1.96%   |
| AMD A6                  | 1         | 1.96%   |
| AMD A10                 | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 66.67%  |
| 4      | 8         | 15.69%  |
| 1      | 5         | 9.8%    |
| 6      | 3         | 5.88%   |
| 8      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 62.75%  |
| 1      | 19        | 37.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 90.2%   |
| 32-bit         | 3         | 5.88%   |
| Unknown        | 2         | 3.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 24.53%  |
| 0x406e3    | 4         | 7.55%   |
| 0x306d4    | 3         | 5.66%   |
| 0x306a9    | 3         | 5.66%   |
| 0x206a7    | 3         | 5.66%   |
| 0x906ea    | 2         | 3.77%   |
| 0x806ec    | 2         | 3.77%   |
| 0x6f6      | 2         | 3.77%   |
| 0x40651    | 2         | 3.77%   |
| 0x306c3    | 2         | 3.77%   |
| 0x20655    | 2         | 3.77%   |
| 0x1067a    | 2         | 3.77%   |
| 0x08608103 | 2         | 3.77%   |
| 0x906ed    | 1         | 1.89%   |
| 0x706a1    | 1         | 1.89%   |
| 0x6d8      | 1         | 1.89%   |
| 0x695      | 1         | 1.89%   |
| 0x30678    | 1         | 1.89%   |
| 0x20652    | 1         | 1.89%   |
| 0x07030105 | 1         | 1.89%   |
| 0x0600611a | 1         | 1.89%   |
| 0x05000119 | 1         | 1.89%   |
| 0x05000101 | 1         | 1.89%   |
| 0x010000b6 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 11.76%  |
| Westmere      | 5         | 9.8%    |
| IvyBridge     | 5         | 9.8%    |
| Skylake       | 4         | 7.84%   |
| Haswell       | 4         | 7.84%   |
| Broadwell     | 4         | 7.84%   |
| SandyBridge   | 3         | 5.88%   |
| P6            | 3         | 5.88%   |
| Core          | 3         | 5.88%   |
| Unknown       | 3         | 5.88%   |
| Penryn        | 2         | 3.92%   |
| Excavator     | 2         | 3.92%   |
| Bobcat        | 2         | 3.92%   |
| Silvermont    | 1         | 1.96%   |
| Puma          | 1         | 1.96%   |
| Piledriver    | 1         | 1.96%   |
| K10           | 1         | 1.96%   |
| Goldmont plus | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 63.79%  |
| AMD    | 14        | 24.14%  |
| Nvidia | 7         | 12.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 8.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 8.2%    |
| Intel HD Graphics 5500                                                                | 4         | 6.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 4.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 4.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 3.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 3.28%   |
| AMD Lucienne                                                                          | 2         | 3.28%   |
| Nvidia GP107M [GeForce MX150]                                                         | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.64%   |
| Nvidia GM108M [GeForce 930M]                                                          | 1         | 1.64%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.64%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 1.64%   |
| Nvidia GF108M [NVS 5400M]                                                             | 1         | 1.64%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.64%   |
| Intel HD Graphics 620                                                                 | 1         | 1.64%   |
| Intel HD Graphics 520                                                                 | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.64%   |
| Intel 82852/855GM Integrated Graphics Device                                          | 1         | 1.64%   |
| AMD Wrestler [Radeon HD 7340]                                                         | 1         | 1.64%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 1.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.64%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                       | 1         | 1.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.64%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                  | 1         | 1.64%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                 | 1         | 1.64%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.64%   |
| AMD R520/M58 [Mobility Radeon X1800]                                                  | 1         | 1.64%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 1         | 1.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.64%   |
| AMD Baffin [Radeon Pro WX 4130/4150]                                                  | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 52.94%  |
| 1 x AMD        | 11        | 21.57%  |
| Intel + Nvidia | 7         | 13.73%  |
| Other          | 2         | 3.92%   |
| 2 x AMD        | 2         | 3.92%   |
| 2 x Intel      | 1         | 1.96%   |
| Intel + AMD    | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 90.2%   |
| Proprietary | 3         | 5.88%   |
| Unknown     | 2         | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 69.23%  |
| 0.01-0.5   | 8         | 15.38%  |
| 1.01-2.0   | 4         | 7.69%   |
| 0.51-1.0   | 3         | 5.77%   |
| 3.01-4.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 27.27%  |
| AU Optronics            | 10        | 18.18%  |
| Chimei Innolux          | 6         | 10.91%  |
| Samsung Electronics     | 4         | 7.27%   |
| BOE                     | 4         | 7.27%   |
| PANDA                   | 2         | 3.64%   |
| Lenovo                  | 2         | 3.64%   |
| Goldstar                | 2         | 3.64%   |
| Chi Mei Optoelectronics | 2         | 3.64%   |
| Unknown                 | 1         | 1.82%   |
| STD                     | 1         | 1.82%   |
| MStar                   | 1         | 1.82%   |
| InnoLux Display         | 1         | 1.82%   |
| InfoVision              | 1         | 1.82%   |
| Hisense                 | 1         | 1.82%   |
| Dell                    | 1         | 1.82%   |
| AOC                     | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 3.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 1.82%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 1.82%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch        | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                  | 1         | 1.82%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.82%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 1.82%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch              | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                  | 1         | 1.82%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 1.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 1.82%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                    | 1         | 1.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 1.82%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                     | 1         | 1.82%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE0953 1920x1080 382x215mm 17.3-inch                    | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 27        | 50%     |
| 1920x1080 (FHD)  | 19        | 35.19%  |
| 3840x2160 (4K)   | 3         | 5.56%   |
| 1280x800 (WXGA)  | 2         | 3.7%    |
| 2288x1287        | 1         | 1.85%   |
| 1600x900 (HD+)   | 1         | 1.85%   |
| 1440x900 (WXGA+) | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 40%     |
| 12     | 8         | 14.55%  |
| 14     | 6         | 10.91%  |
| 13     | 6         | 10.91%  |
| 24     | 2         | 3.64%   |
| 23     | 2         | 3.64%   |
| 21     | 2         | 3.64%   |
| 17     | 2         | 3.64%   |
| 142    | 1         | 1.82%   |
| 52     | 1         | 1.82%   |
| 31     | 1         | 1.82%   |
| 27     | 1         | 1.82%   |
| 11     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 31        | 56.36%  |
| 201-300        | 12        | 21.82%  |
| 501-600        | 5         | 9.09%   |
| 401-500        | 2         | 3.64%   |
| 351-400        | 2         | 3.64%   |
| More than 2000 | 1         | 1.82%   |
| 601-700        | 1         | 1.82%   |
| 1001-1500      | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 91.49%  |
| 16/10 | 3         | 6.38%   |
| 1.00  | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 40%     |
| 81-90          | 9         | 16.36%  |
| 61-70          | 8         | 14.55%  |
| 201-250        | 5         | 9.09%   |
| 71-80          | 3         | 5.45%   |
| More than 1000 | 2         | 3.64%   |
| 51-60          | 1         | 1.82%   |
| 351-500        | 1         | 1.82%   |
| 301-350        | 1         | 1.82%   |
| 151-200        | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 37.04%  |
| 101-120 | 20        | 37.04%  |
| 51-100  | 8         | 14.81%  |
| 161-240 | 4         | 7.41%   |
| 1-50    | 2         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 81.13%  |
| 2     | 8         | 15.09%  |
| 3     | 1         | 1.89%   |
| 0     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 31.25%  |
| Realtek Semiconductor      | 23        | 28.75%  |
| Qualcomm Atheros           | 19        | 23.75%  |
| MediaTek                   | 2         | 2.5%    |
| ZTE WCDMA Technologies MSM | 1         | 1.25%   |
| VIA Technologies           | 1         | 1.25%   |
| TP-Link                    | 1         | 1.25%   |
| Sierra Wireless            | 1         | 1.25%   |
| Samsung Electronics        | 1         | 1.25%   |
| Ralink Technology          | 1         | 1.25%   |
| Ralink                     | 1         | 1.25%   |
| NetGear                    | 1         | 1.25%   |
| JMicron Technology         | 1         | 1.25%   |
| Broadcom Limited           | 1         | 1.25%   |
| Broadcom                   | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12        | 11.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 5.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.88%   |
| Intel Wireless 7260                                                     | 4         | 3.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.91%   |
| Intel Wireless 7265                                                     | 3         | 2.91%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.91%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.94%   |
| Intel Wireless 8260                                                     | 2         | 1.94%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.94%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.94%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.94%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                             | 1         | 0.97%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.97%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.97%   |
| Sierra Wireless EM7455                                                  | 1         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.97%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.97%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.97%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 18        | 36%     |
| Intel                 | 18        | 36%     |
| Realtek Semiconductor | 6         | 12%     |
| MediaTek              | 2         | 4%      |
| Sierra Wireless       | 1         | 2%      |
| Ralink Technology     | 1         | 2%      |
| Ralink                | 1         | 2%      |
| NetGear               | 1         | 2%      |
| Broadcom Limited      | 1         | 2%      |
| Broadcom              | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 8%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 8%      |
| Intel Wireless 7260                                                     | 4         | 8%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 6%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 6%      |
| Intel Wireless 7265                                                     | 3         | 6%      |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 4%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4%      |
| Intel Wireless 8260                                                     | 2         | 4%      |
| Sierra Wireless EM7455                                                  | 1         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2%      |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 2%      |
| Ralink RT5370 Wireless Adapter                                          | 1         | 2%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2%      |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 2%      |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 2%      |
| Intel Wireless 8265 / 8275                                              | 1         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2%      |
| Intel Centrino Advanced-N 6200                                          | 1         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 21        | 42%     |
| Intel                      | 21        | 42%     |
| Qualcomm Atheros           | 3         | 6%      |
| ZTE WCDMA Technologies MSM | 1         | 2%      |
| VIA Technologies           | 1         | 2%      |
| TP-Link                    | 1         | 2%      |
| Samsung Electronics        | 1         | 2%      |
| JMicron Technology         | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 24%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 12%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 12%     |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 6%      |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4%      |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 2%      |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 2%      |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2%      |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2%      |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 50%     |
| Ethernet | 46        | 46.94%  |
| Modem    | 3         | 3.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 65.45%  |
| Ethernet | 19        | 34.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 44        | 86.27%  |
| 1     | 5         | 9.8%    |
| 0     | 2         | 3.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 90.2%   |
| Yes  | 5         | 9.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 31.03%  |
| Realtek Semiconductor           | 4         | 13.79%  |
| Qualcomm Atheros Communications | 4         | 13.79%  |
| Broadcom                        | 4         | 13.79%  |
| Lite-On Technology              | 2         | 6.9%    |
| Cambridge Silicon Radio         | 2         | 6.9%    |
| Ralink                          | 1         | 3.45%   |
| IMC Networks                    | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Dell                            | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 27.59%  |
| Realtek Bluetooth Radio                             | 4         | 13.79%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 10.34%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 6.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 6.9%    |
| Ralink RT3290 Bluetooth                             | 1         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.45%   |
| Foxconn / Hon Hai BT                                | 1         | 3.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 68.33%  |
| AMD                   | 11        | 18.33%  |
| Nvidia                | 4         | 6.67%   |
| Realtek Semiconductor | 1         | 1.67%   |
| GYROCOM C&C           | 1         | 1.67%   |
| C-Media Electronics   | 1         | 1.67%   |
| Blue Microphones      | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 6.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 5.26%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 5.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.95%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.63%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.63%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.32%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.32%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 1.32%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 1.32%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1.32%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.32%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.32%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.32%   |
| AMD High Definition Audio Controller                                       | 1         | 1.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.32%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 34.04%  |
| Unknown             | 7         | 14.89%  |
| SK hynix            | 6         | 12.77%  |
| Crucial             | 4         | 8.51%   |
| A-DATA Technology   | 4         | 8.51%   |
| Kingston            | 3         | 6.38%   |
| G.Skill             | 2         | 4.26%   |
| Unknown (ABCD)      | 1         | 2.13%   |
| Smart               | 1         | 2.13%   |
| Nanya Technology    | 1         | 2.13%   |
| Micron Technology   | 1         | 2.13%   |
| Apacer              | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 5.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 3.64%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 3.64%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 3.64%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.82%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 1.82%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.82%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.82%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 1.82%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.82%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s      | 1         | 1.82%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.82%   |
| Kingston RAM ACR16D3LS1NGG/2G 2GB SODIMM DDR3 1333MT/s           | 1         | 1.82%   |
| Kingston RAM 9905428-426.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 52.38%  |
| DDR4    | 11        | 26.19%  |
| SDRAM   | 2         | 4.76%   |
| DDR2    | 2         | 4.76%   |
| DDR     | 2         | 4.76%   |
| LPDDR4  | 1         | 2.38%   |
| LPDDR3  | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 97.56%  |
| Row Of Chips | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 37.25%  |
| 4096  | 14        | 27.45%  |
| 2048  | 9         | 17.65%  |
| 16384 | 4         | 7.84%   |
| 1024  | 3         | 5.88%   |
| 32768 | 1         | 1.96%   |
| 512   | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 33.33%  |
| 2667    | 8         | 17.78%  |
| Unknown | 5         | 11.11%  |
| 2400    | 3         | 6.67%   |
| 1333    | 3         | 6.67%   |
| 1067    | 3         | 6.67%   |
| 4199    | 2         | 4.44%   |
| 3200    | 2         | 4.44%   |
| 2133    | 1         | 2.22%   |
| 1334    | 1         | 2.22%   |
| 1200    | 1         | 2.22%   |
| 800     | 1         | 2.22%   |

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
| Chicony Electronics                    | 19        | 45.24%  |
| Sunplus Innovation Technology          | 4         | 9.52%   |
| Microdia                               | 4         | 9.52%   |
| Acer                                   | 4         | 9.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.14%   |
| Suyin                                  | 2         | 4.76%   |
| Samsung Electronics                    | 1         | 2.38%   |
| Realtek Semiconductor                  | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Mustek Systems                         | 1         | 2.38%   |
| Logitech                               | 1         | 2.38%   |
| IMC Networks                           | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 16.67%  |
| Chicony HD Webcam                                               | 2         | 4.76%   |
| Chicony EasyCamera                                              | 2         | 4.76%   |
| Acer BisonCam, NB Pro                                           | 2         | 4.76%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 2.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 2.38%   |
| Sunplus Laptop Integrated Webcam HD                             | 1         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.38%   |
| Sunplus HK 1080P K20Pro                                         | 1         | 2.38%   |
| Sunplus ASUS USB2.0 Webcam                                      | 1         | 2.38%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 2.38%   |
| Realtek Integrated Webcam_HD                                    | 1         | 2.38%   |
| Quanta Sony Visual Communication Camera                         | 1         | 2.38%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 2.38%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 2.38%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.38%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.38%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 2.38%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.38%   |
| IMC Networks Integrated Webcam                                  | 1         | 2.38%   |
| Chicony WebCam                                                  | 1         | 2.38%   |
| Chicony VGA WebCam                                              | 1         | 2.38%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 2.38%   |
| Chicony Thinkpad T430 camera                                    | 1         | 2.38%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 2.38%   |
| Chicony Lenovo EasyCamera                                       | 1         | 2.38%   |
| Chicony HP TrueVision HD                                        | 1         | 2.38%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 2.38%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 2.38%   |
| Acer Integrated Camera                                          | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 25%     |
| Upek               | 1         | 25%     |
| Synaptics          | 1         | 25%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 2         | 22.22%  |
| Lenovo      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 58200                                                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 35        | 66.04%  |
| 1     | 13        | 24.53%  |
| 2     | 4         | 7.55%   |
| 3     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 6         | 30%     |
| Fingerprint reader       | 4         | 20%     |
| Net/wireless             | 2         | 10%     |
| Graphics card            | 2         | 10%     |
| Communication controller | 2         | 10%     |
| Camera                   | 2         | 10%     |
| Bluetooth                | 2         | 10%     |

