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

Total: 71

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6530              | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| HP            | Laptop 15-bs2xx             | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
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
| Devuan 4                | 26        | 44.83%  |
| Devuan 3                | 14        | 24.14%  |
| Devuan Testing/unstable | 8         | 13.79%  |
| Devuan 5                | 6         | 10.34%  |
| Devuan                  | 2         | 3.45%   |
| Devuan 3.0              | 1         | 1.72%   |
| Devuan 2.1              | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 4         | 6.45%   |
| 5.10.0-16-amd64           | 4         | 6.45%   |
| 5.10.0-13-amd64           | 4         | 6.45%   |
| 4.19.0-9-amd64            | 4         | 6.45%   |
| 5.7.0-2-amd64             | 3         | 4.84%   |
| 5.10.0-8-amd64            | 3         | 4.84%   |
| 5.10.0-10-amd64           | 3         | 4.84%   |
| 5.18.0-2-amd64            | 2         | 3.23%   |
| 5.10.0-19-amd64           | 2         | 3.23%   |
| 5.10.0-18-amd64           | 2         | 3.23%   |
| 5.10.0-11-amd64           | 2         | 3.23%   |
| 4.19.0-17-amd64           | 2         | 3.23%   |
| 4.19.0-16-amd64           | 2         | 3.23%   |
| 4.19.0-14-amd64           | 2         | 3.23%   |
| 5.9.0-4-amd64             | 1         | 1.61%   |
| 5.8.0-1-amd64             | 1         | 1.61%   |
| 5.7.0-0.bpo.2-amd64       | 1         | 1.61%   |
| 5.6.0-2-amd64             | 1         | 1.61%   |
| 5.19.0-2-amd64            | 1         | 1.61%   |
| 5.18.0-1-amd64            | 1         | 1.61%   |
| 5.15.5-xanmod1            | 1         | 1.61%   |
| 5.15.0-2-amd64            | 1         | 1.61%   |
| 5.14.0-4-amd64            | 1         | 1.61%   |
| 5.10.0-7-amd64            | 1         | 1.61%   |
| 5.10.0-4-amd64            | 1         | 1.61%   |
| 5.10.0-15-amd64           | 1         | 1.61%   |
| 5.10.0-14-amd64           | 1         | 1.61%   |
| 5.10.0-1-amd64            | 1         | 1.61%   |
| 5.1.21                    | 1         | 1.61%   |
| 4.9.0-14-amd64            | 1         | 1.61%   |
| 4.9.0-11-amd64            | 1         | 1.61%   |
| 4.9.0-11-686              | 1         | 1.61%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.61%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.61%   |
| 4.19.0-17-686-pae         | 1         | 1.61%   |
| 4.19.0-12-amd64           | 1         | 1.61%   |
| 4.19.0-10-amd64           | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 26        | 44.07%  |
| 4.19.0  | 13        | 22.03%  |
| 5.7.0   | 4         | 6.78%   |
| 4.9.0   | 4         | 6.78%   |
| 5.18.0  | 3         | 5.08%   |
| 5.9.0   | 1         | 1.69%   |
| 5.8.0   | 1         | 1.69%   |
| 5.6.0   | 1         | 1.69%   |
| 5.19.0  | 1         | 1.69%   |
| 5.15.5  | 1         | 1.69%   |
| 5.15.0  | 1         | 1.69%   |
| 5.14.0  | 1         | 1.69%   |
| 5.1.21  | 1         | 1.69%   |
| 4.4.195 | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 26        | 44.07%  |
| 4.19    | 13        | 22.03%  |
| 5.7     | 4         | 6.78%   |
| 4.9     | 4         | 6.78%   |
| 5.18    | 3         | 5.08%   |
| 5.15    | 2         | 3.39%   |
| 5.9     | 1         | 1.69%   |
| 5.8     | 1         | 1.69%   |
| 5.6     | 1         | 1.69%   |
| 5.19    | 1         | 1.69%   |
| 5.14    | 1         | 1.69%   |
| 5.1     | 1         | 1.69%   |
| 4.4     | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 92.59%  |
| i686   | 3         | 5.56%   |
| armv7l | 1         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| XFCE     | 21        | 36.84%  |
| KDE5     | 10        | 17.54%  |
| MATE     | 8         | 14.04%  |
| Unknown  | 8         | 14.04%  |
| LXDE     | 3         | 5.26%   |
| i3       | 3         | 5.26%   |
| Openbox  | 1         | 1.75%   |
| LXQt     | 1         | 1.75%   |
| GNOME    | 1         | 1.75%   |
| Cinnamon | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 94.55%  |
| Unknown | 2         | 3.64%   |
| Tty     | 1         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 31.58%  |
| SLiM    | 16        | 28.07%  |
| LightDM | 16        | 28.07%  |
| SDDM    | 5         | 8.77%   |
| XDM     | 1         | 1.75%   |
| GDM3    | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 21        | 38.18%  |
| en_GB       | 11        | 20%     |
| ru_RU       | 6         | 10.91%  |
| pt_BR       | 3         | 5.45%   |
| it_IT       | 2         | 3.64%   |
| es_ES       | 2         | 3.64%   |
| Unknown     | 2         | 3.64%   |
| ru_UA       | 1         | 1.82%   |
| pl_PL       | 1         | 1.82%   |
| fr_BE       | 1         | 1.82%   |
| es_SV       | 1         | 1.82%   |
| en_US.utf-8 | 1         | 1.82%   |
| de_DE       | 1         | 1.82%   |
| de_AT       | 1         | 1.82%   |
| C           | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 56.36%  |
| EFI  | 24        | 43.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 85.19%  |
| Btrfs   | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| OveXlay | 1         | 1.85%   |
| Ext2    | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 26        | 46.43%  |
| MBR     | 21        | 37.5%   |
| Unknown | 9         | 16.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 88.89%  |
| Yes       | 6         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 76.36%  |
| Yes       | 13        | 23.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 31.48%  |
| Dell                | 9         | 16.67%  |
| Hewlett-Packard     | 5         | 9.26%   |
| Acer                | 4         | 7.41%   |
| Toshiba             | 3         | 5.56%   |
| ASUSTek Computer    | 3         | 5.56%   |
| MSI                 | 2         | 3.7%    |
| Fujitsu Siemens     | 2         | 3.7%    |
| Teclast             | 1         | 1.85%   |
| Sony                | 1         | 1.85%   |
| Samsung Electronics | 1         | 1.85%   |
| Notebook            | 1         | 1.85%   |
| Nokia               | 1         | 1.85%   |
| MTC                 | 1         | 1.85%   |
| IBM                 | 1         | 1.85%   |
| Fujitsu             | 1         | 1.85%   |
| CCE                 | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 1.85%   |
| Toshiba Satellite M40X                                                                   | 1         | 1.85%   |
| Toshiba Satellite L655                                                                   | 1         | 1.85%   |
| Teclast F6 Plus                                                                          | 1         | 1.85%   |
| Sony VPCEE23FX                                                                           | 1         | 1.85%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.85%   |
| Notebook W230ST                                                                          | 1         | 1.85%   |
| Nokia N900                                                                               | 1         | 1.85%   |
| MTC Montara-GML                                                                          | 1         | 1.85%   |
| MSI MS-1688                                                                              | 1         | 1.85%   |
| MSI Modern 15 A5M                                                                        | 1         | 1.85%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1.85%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.85%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.85%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.85%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.85%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.85%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.85%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.85%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.85%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 1.85%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.85%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.85%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.85%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.85%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.85%   |
| Lenovo G50-30 80G0                                                                       | 1         | 1.85%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.85%   |
| HP ProBook 6475b                                                                         | 1         | 1.85%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.85%   |
| HP Notebook                                                                              | 1         | 1.85%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 1.85%   |
| HP Laptop 15-bs2xx                                                                       | 1         | 1.85%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.85%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.85%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.85%   |
| Dell Precision 7530                                                                      | 1         | 1.85%   |
| Dell Latitude E7250                                                                      | 1         | 1.85%   |
| Dell Latitude E7240                                                                      | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 22.22%  |
| Dell Latitude           | 7         | 12.96%  |
| Toshiba Satellite       | 3         | 5.56%   |
| Lenovo IdeaPad          | 3         | 5.56%   |
| Acer Aspire             | 3         | 5.56%   |
| HP Laptop               | 2         | 3.7%    |
| Teclast F6              | 1         | 1.85%   |
| Sony VPCEE23FX          | 1         | 1.85%   |
| Samsung 355V4C          | 1         | 1.85%   |
| Notebook W230ST         | 1         | 1.85%   |
| Nokia N900              | 1         | 1.85%   |
| MTC Montara-GML         | 1         | 1.85%   |
| MSI MS-1688             | 1         | 1.85%   |
| MSI Modern              | 1         | 1.85%   |
| Lenovo V310-14ISK       | 1         | 1.85%   |
| Lenovo G50-30           | 1         | 1.85%   |
| IBM ThinkPad            | 1         | 1.85%   |
| HP ProBook              | 1         | 1.85%   |
| HP Pavilion             | 1         | 1.85%   |
| HP Notebook             | 1         | 1.85%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.85%   |
| Fujitsu Siemens AMILO   | 1         | 1.85%   |
| Fujitsu LIFEBOOK        | 1         | 1.85%   |
| Dell Precision          | 1         | 1.85%   |
| Dell Inspiron           | 1         | 1.85%   |
| CCE Capella             | 1         | 1.85%   |
| ASUS X555LJ             | 1         | 1.85%   |
| ASUS K55VJ              | 1         | 1.85%   |
| ASUS K52F               | 1         | 1.85%   |
| Acer Extensa            | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 8         | 14.81%  |
| 2019    | 5         | 9.26%   |
| 2017    | 4         | 7.41%   |
| 2014    | 4         | 7.41%   |
| 2011    | 4         | 7.41%   |
| 2010    | 4         | 7.41%   |
| 2018    | 3         | 5.56%   |
| 2015    | 3         | 5.56%   |
| 2009    | 3         | 5.56%   |
| 2021    | 2         | 3.7%    |
| 2016    | 2         | 3.7%    |
| 2013    | 2         | 3.7%    |
| 2008    | 2         | 3.7%    |
| 2006    | 2         | 3.7%    |
| 2005    | 2         | 3.7%    |
| 2022    | 1         | 1.85%   |
| 2020    | 1         | 1.85%   |
| 2007    | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 54        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 52        | 96.3%   |
| Enabled  | 2         | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 96.3%   |
| Yes  | 2         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 24.07%  |
| 3.01-4.0    | 12        | 22.22%  |
| 8.01-16.0   | 11        | 20.37%  |
| 16.01-24.0  | 8         | 14.81%  |
| 2.01-3.0    | 3         | 5.56%   |
| 1.01-2.0    | 3         | 5.56%   |
| 0.01-0.5    | 2         | 3.7%    |
| 32.01-64.0  | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 25        | 41.67%  |
| 4.01-8.0   | 12        | 20%     |
| 2.01-3.0   | 9         | 15%     |
| 0.51-1.0   | 5         | 8.33%   |
| 3.01-4.0   | 4         | 6.67%   |
| 0.01-0.5   | 3         | 5%      |
| 32.01-64.0 | 1         | 1.67%   |
| 8.01-16.0  | 1         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 70.91%  |
| 2      | 12        | 21.82%  |
| 3      | 4         | 7.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 56.36%  |
| Yes       | 24        | 43.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 90.74%  |
| No        | 5         | 9.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 96.3%   |
| No        | 2         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 56.36%  |
| No        | 24        | 43.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 6         | 10.91%  |
| Germany     | 6         | 10.91%  |
| USA         | 5         | 9.09%   |
| Brazil      | 5         | 9.09%   |
| Ukraine     | 4         | 7.27%   |
| Grenada     | 3         | 5.45%   |
| Spain       | 2         | 3.64%   |
| Poland      | 2         | 3.64%   |
| Netherlands | 2         | 3.64%   |
| Italy       | 2         | 3.64%   |
| Hungary     | 2         | 3.64%   |
| Finland     | 2         | 3.64%   |
| Vietnam     | 1         | 1.82%   |
| UK          | 1         | 1.82%   |
| Slovakia    | 1         | 1.82%   |
| Serbia      | 1         | 1.82%   |
| Portugal    | 1         | 1.82%   |
| Norway      | 1         | 1.82%   |
| Mexico      | 1         | 1.82%   |
| Israel      | 1         | 1.82%   |
| Indonesia   | 1         | 1.82%   |
| Greece      | 1         | 1.82%   |
| France      | 1         | 1.82%   |
| El Salvador | 1         | 1.82%   |
| Belarus     | 1         | 1.82%   |
| Austria     | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Saint George's     | 3         | 5.45%   |
| Nadudvar           | 2         | 3.64%   |
| Milan              | 2         | 3.64%   |
| Kyiv               | 2         | 3.64%   |
| Amsterdam          | 2         | 3.64%   |
| Yakutsk            | 1         | 1.82%   |
| Wroclaw            | 1         | 1.82%   |
| Wildberg           | 1         | 1.82%   |
| Trubchëvsk        | 1         | 1.82%   |
| Thessaloniki       | 1         | 1.82%   |
| Tel Aviv           | 1         | 1.82%   |
| Staunton           | 1         | 1.82%   |
| St Petersburg      | 1         | 1.82%   |
| Sao Paulo          | 1         | 1.82%   |
| San Salvador       | 1         | 1.82%   |
| Rio de Janeiro     | 1         | 1.82%   |
| Praia Grande       | 1         | 1.82%   |
| Oslo               | 1         | 1.82%   |
| Novopskov          | 1         | 1.82%   |
| Muenster-Sarmsheim | 1         | 1.82%   |
| Moscow             | 1         | 1.82%   |
| Maladzyechna       | 1         | 1.82%   |
| Madrid             | 1         | 1.82%   |
| Leonding           | 1         | 1.82%   |
| Leipzig            | 1         | 1.82%   |
| Krasnodar          | 1         | 1.82%   |
| Kouvola            | 1         | 1.82%   |
| Kharkiv            | 1         | 1.82%   |
| Katzenbach         | 1         | 1.82%   |
| Katowice           | 1         | 1.82%   |
| Jyväskylä        | 1         | 1.82%   |
| Hermosillo         | 1         | 1.82%   |
| Hayden             | 1         | 1.82%   |
| Hanoi              | 1         | 1.82%   |
| Gijón             | 1         | 1.82%   |
| Fulham             | 1         | 1.82%   |
| Forest Grove       | 1         | 1.82%   |
| Cologne            | 1         | 1.82%   |
| Chicago            | 1         | 1.82%   |
| Cherepovets        | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 13.89%  |
| Samsung Electronics | 8         | 13     | 11.11%  |
| Unknown             | 7         | 8      | 9.72%   |
| Kingston            | 6         | 6      | 8.33%   |
| Seagate             | 4         | 4      | 5.56%   |
| SanDisk             | 4         | 4      | 5.56%   |
| PNY                 | 3         | 3      | 4.17%   |
| Hitachi             | 3         | 3      | 4.17%   |
| HGST                | 3         | 3      | 4.17%   |
| Toshiba             | 2         | 2      | 2.78%   |
| Team                | 2         | 2      | 2.78%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Fujitsu             | 2         | 2      | 2.78%   |
| Crucial             | 2         | 2      | 2.78%   |
| Union Memory        | 1         | 2      | 1.39%   |
| UMIS                | 1         | 1      | 1.39%   |
| Teclast             | 1         | 1      | 1.39%   |
| Smart               | 1         | 1      | 1.39%   |
| SABRENT             | 1         | 2      | 1.39%   |
| Patriot             | 1         | 1      | 1.39%   |
| Mushkin             | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| LITEON              | 1         | 4      | 1.39%   |
| KIOXIA              | 1         | 1      | 1.39%   |
| KingFast            | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| HXY                 | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                    | 3         | 4.05%   |
| Unknown MMC Card  128GB                | 2         | 2.7%    |
| Kingston SA400S37480G 480GB SSD        | 2         | 2.7%    |
| Kingston SA400S37240G 240GB SSD        | 2         | 2.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 1.35%   |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 1.35%   |
| WDC WD5000BPVT-24HXZT3 500GB           | 1         | 1.35%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 1         | 1.35%   |
| WDC WD3200BEVT-22A23T0 320GB           | 1         | 1.35%   |
| WDC WD3200BEVE-00A0HT0 320GB           | 1         | 1.35%   |
| WDC WD2500BEKT-00A25T0 250GB           | 1         | 1.35%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 1.35%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 1.35%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB   | 1         | 1.35%   |
| Unknown SD04G  4GB                     | 1         | 1.35%   |
| Unknown SD  8GB                        | 1         | 1.35%   |
| Unknown MMC32G  32GB                   | 1         | 1.35%   |
| Unknown MMC Card  8GB                  | 1         | 1.35%   |
| Unknown MMC Card  32GB                 | 1         | 1.35%   |
| Unknown MMC Card  16GB                 | 1         | 1.35%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 1.35%   |
| UMIS RPFTJ256PDD2MWX 256GB             | 1         | 1.35%   |
| Toshiba MK5065GSX 500GB                | 1         | 1.35%   |
| Toshiba MK1252GSX 120GB                | 1         | 1.35%   |
| Teclast 256GB NS550-2242 SSD           | 1         | 1.35%   |
| Team T253X1120G 120GB SSD              | 1         | 1.35%   |
| Team T253TD240G 240GB SSD              | 1         | 1.35%   |
| Smart SSD SZ9MSE mSATA 256GB           | 1         | 1.35%   |
| SK hynix SC311 SATA 256GB SSD          | 1         | 1.35%   |
| SK hynix PC611 NVMe 1TB                | 1         | 1.35%   |
| Seagate ST9250410AS 250GB              | 1         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB        | 1         | 1.35%   |
| Seagate ST250VT000-1DK141 250GB        | 1         | 1.35%   |
| Seagate Expansion Desk 8TB             | 1         | 1.35%   |
| SanDisk X300 MSATA 256GB SSD           | 1         | 1.35%   |
| SanDisk SSD PLUS 480GB                 | 1         | 1.35%   |
| SanDisk SDSSDHII240G 240GB             | 1         | 1.35%   |
| SanDisk SDSSDH3500G 500GB              | 1         | 1.35%   |
| Samsung SSD PM851 mSATA 128GB          | 1         | 1.35%   |
| Samsung SSD 980 1TB                    | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 36.36%  |
| Seagate | 4         | 4      | 18.18%  |
| Hitachi | 3         | 3      | 13.64%  |
| HGST    | 3         | 3      | 13.64%  |
| Toshiba | 2         | 2      | 9.09%   |
| Fujitsu | 2         | 2      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 18.18%  |
| Samsung Electronics | 5         | 5      | 15.15%  |
| SanDisk             | 4         | 4      | 12.12%  |
| PNY                 | 3         | 3      | 9.09%   |
| Team                | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| WDC                 | 1         | 2      | 3.03%   |
| Union Memory        | 1         | 2      | 3.03%   |
| Teclast             | 1         | 1      | 3.03%   |
| Smart               | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Mushkin             | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| LITEON              | 1         | 4      | 3.03%   |
| HXY                 | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 29        | 38     | 42.65%  |
| HDD     | 22        | 22     | 32.35%  |
| NVMe    | 9         | 15     | 13.24%  |
| MMC     | 7         | 8      | 10.29%  |
| Unknown | 1         | 1      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 60     | 73.02%  |
| NVMe | 8         | 13     | 12.7%   |
| MMC  | 7         | 8      | 11.11%  |
| SAS  | 2         | 3      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 45     | 79.17%  |
| 0.51-1.0   | 7         | 12     | 14.58%  |
| 1.01-2.0   | 2         | 2      | 4.17%   |
| 4.01-10.0  | 1         | 1      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 24.56%  |
| 101-250        | 14        | 24.56%  |
| 501-1000       | 7         | 12.28%  |
| 51-100         | 7         | 12.28%  |
| 1001-2000      | 4         | 7.02%   |
| 21-50          | 3         | 5.26%   |
| Unknown        | 3         | 5.26%   |
| 2001-3000      | 2         | 3.51%   |
| 1-20           | 2         | 3.51%   |
| More than 3000 | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 30.36%  |
| 51-100    | 10        | 17.86%  |
| 101-250   | 9         | 16.07%  |
| 21-50     | 6         | 10.71%  |
| 251-500   | 5         | 8.93%   |
| 1001-2000 | 3         | 5.36%   |
| Unknown   | 3         | 5.36%   |
| 501-1000  | 2         | 3.57%   |
| 2001-3000 | 1         | 1.79%   |

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
| Works    | 42        | 58     | 67.74%  |
| Detected | 15        | 21     | 24.19%  |
| Malfunc  | 5         | 5      | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 42        | 72.41%  |
| AMD                     | 8         | 13.79%  |
| Samsung Electronics     | 3         | 5.17%   |
| VIA Technologies        | 1         | 1.72%   |
| Union Memory (Shenzhen) | 1         | 1.72%   |
| SK hynix                | 1         | 1.72%   |
| SanDisk                 | 1         | 1.72%   |
| KIOXIA                  | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 9.52%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 9.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 6.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 6.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 4.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 3.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 3.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.17%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 3.17%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.59%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.59%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.59%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.59%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.59%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.59%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 41        | 68.33%  |
| NVMe | 8         | 13.33%  |
| IDE  | 8         | 13.33%  |
| RAID | 3         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 81.48%  |
| AMD    | 9         | 16.67%  |
| ARM    | 1         | 1.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 5.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 5.56%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 3.7%    |
| Intel Pentium M processor 1700MHz           | 1         | 1.85%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.85%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.85%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.85%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.85%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.85%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.85%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.85%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 1.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.85%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.85%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.85%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.85%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.85%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.85%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.85%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.85%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.85%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.85%   |
| Intel Celeron M processor 1.40GHz           | 1         | 1.85%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.85%   |
| ARM Nokia RX-51 board Processor             | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 20.37%  |
| Intel Core i7           | 10        | 18.52%  |
| Intel Core i3           | 9         | 16.67%  |
| Intel Core 2            | 3         | 5.56%   |
| Intel Celeron           | 3         | 5.56%   |
| Other                   | 2         | 3.7%    |
| Intel Pentium M         | 2         | 3.7%    |
| Intel Pentium           | 2         | 3.7%    |
| Intel Pentium Dual-Core | 1         | 1.85%   |
| Intel Pentium Dual      | 1         | 1.85%   |
| Intel Core i9           | 1         | 1.85%   |
| Intel Celeron M         | 1         | 1.85%   |
| AMD Ryzen 7             | 1         | 1.85%   |
| AMD Ryzen 5             | 1         | 1.85%   |
| AMD E2                  | 1         | 1.85%   |
| AMD E                   | 1         | 1.85%   |
| AMD Athlon II           | 1         | 1.85%   |
| AMD A8                  | 1         | 1.85%   |
| AMD A6                  | 1         | 1.85%   |
| AMD A10                 | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 66.67%  |
| 4      | 9         | 16.67%  |
| 1      | 5         | 9.26%   |
| 6      | 3         | 5.56%   |
| 8      | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 61.11%  |
| 1      | 21        | 38.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 90.74%  |
| 32-bit         | 3         | 5.56%   |
| Unknown        | 2         | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 25%     |
| 0x406e3    | 4         | 7.14%   |
| 0x306d4    | 3         | 5.36%   |
| 0x306a9    | 3         | 5.36%   |
| 0x206a7    | 3         | 5.36%   |
| 0x906ea    | 2         | 3.57%   |
| 0x806ec    | 2         | 3.57%   |
| 0x706a1    | 2         | 3.57%   |
| 0x6f6      | 2         | 3.57%   |
| 0x40651    | 2         | 3.57%   |
| 0x306c3    | 2         | 3.57%   |
| 0x30678    | 2         | 3.57%   |
| 0x20655    | 2         | 3.57%   |
| 0x1067a    | 2         | 3.57%   |
| 0x08608103 | 2         | 3.57%   |
| 0x906ed    | 1         | 1.79%   |
| 0x6d8      | 1         | 1.79%   |
| 0x695      | 1         | 1.79%   |
| 0x20652    | 1         | 1.79%   |
| 0x07030105 | 1         | 1.79%   |
| 0x0600611a | 1         | 1.79%   |
| 0x05000119 | 1         | 1.79%   |
| 0x05000101 | 1         | 1.79%   |
| 0x010000b6 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 11.11%  |
| IvyBridge     | 6         | 11.11%  |
| Westmere      | 5         | 9.26%   |
| Skylake       | 4         | 7.41%   |
| Haswell       | 4         | 7.41%   |
| Broadwell     | 4         | 7.41%   |
| SandyBridge   | 3         | 5.56%   |
| P6            | 3         | 5.56%   |
| Core          | 3         | 5.56%   |
| Unknown       | 3         | 5.56%   |
| Silvermont    | 2         | 3.7%    |
| Penryn        | 2         | 3.7%    |
| Goldmont plus | 2         | 3.7%    |
| Excavator     | 2         | 3.7%    |
| Bobcat        | 2         | 3.7%    |
| Puma          | 1         | 1.85%   |
| Piledriver    | 1         | 1.85%   |
| K10           | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 63.49%  |
| AMD    | 14        | 22.22%  |
| Nvidia | 9         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 6         | 9.09%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 7.58%   |
| Intel HD Graphics 5500                                                                | 4         | 6.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 4.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 3.03%   |
| AMD Lucienne                                                                          | 2         | 3.03%   |
| Nvidia GP107M [GeForce MX150]                                                         | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.52%   |
| Nvidia GM108M [GeForce 930M]                                                          | 1         | 1.52%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.52%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.52%   |
| Nvidia GF108M [NVS 5400M]                                                             | 1         | 1.52%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.52%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.52%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.52%   |
| Intel HD Graphics 620                                                                 | 1         | 1.52%   |
| Intel HD Graphics 520                                                                 | 1         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.52%   |
| Intel 82852/855GM Integrated Graphics Device                                          | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 7340]                                                         | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 1.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.52%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                       | 1         | 1.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.52%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                  | 1         | 1.52%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                 | 1         | 1.52%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.52%   |
| AMD R520/M58 [Mobility Radeon X1800]                                                  | 1         | 1.52%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                          | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 51.85%  |
| 1 x AMD        | 11        | 20.37%  |
| Intel + Nvidia | 9         | 16.67%  |
| Other          | 2         | 3.7%    |
| 2 x AMD        | 2         | 3.7%    |
| 2 x Intel      | 1         | 1.85%   |
| Intel + AMD    | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 90.74%  |
| Proprietary | 3         | 5.56%   |
| Unknown     | 2         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 69.09%  |
| 0.01-0.5   | 8         | 14.55%  |
| 1.01-2.0   | 4         | 7.27%   |
| 0.51-1.0   | 4         | 7.27%   |
| 3.01-4.0   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 25.86%  |
| AU Optronics            | 11        | 18.97%  |
| Samsung Electronics     | 6         | 10.34%  |
| Chimei Innolux          | 6         | 10.34%  |
| BOE                     | 4         | 6.9%    |
| PANDA                   | 2         | 3.45%   |
| Lenovo                  | 2         | 3.45%   |
| Goldstar                | 2         | 3.45%   |
| Chi Mei Optoelectronics | 2         | 3.45%   |
| Unknown                 | 1         | 1.72%   |
| STD                     | 1         | 1.72%   |
| MStar                   | 1         | 1.72%   |
| InnoLux Display         | 1         | 1.72%   |
| InfoVision              | 1         | 1.72%   |
| Hisense                 | 1         | 1.72%   |
| Dell                    | 1         | 1.72%   |
| AOC                     | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 3.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 1         | 1.72%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 1.72%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.72%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                  | 1         | 1.72%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch                  | 1         | 1.72%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                        | 1         | 1.72%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.72%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 1.72%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch              | 1         | 1.72%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 1         | 1.72%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch                  | 1         | 1.72%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 1.72%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 1.72%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                    | 1         | 1.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 1.72%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                     | 1         | 1.72%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                        | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch          | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 1.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 28        | 49.12%  |
| 1920x1080 (FHD)  | 19        | 33.33%  |
| 3840x2160 (4K)   | 4         | 7.02%   |
| 1600x900 (HD+)   | 2         | 3.51%   |
| 1280x800 (WXGA)  | 2         | 3.51%   |
| 2288x1287        | 1         | 1.75%   |
| 1440x900 (WXGA+) | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 24        | 41.38%  |
| 12     | 8         | 13.79%  |
| 14     | 6         | 10.34%  |
| 13     | 6         | 10.34%  |
| 17     | 3         | 5.17%   |
| 24     | 2         | 3.45%   |
| 23     | 2         | 3.45%   |
| 21     | 2         | 3.45%   |
| 142    | 1         | 1.72%   |
| 52     | 1         | 1.72%   |
| 31     | 1         | 1.72%   |
| 27     | 1         | 1.72%   |
| 11     | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 33        | 56.9%   |
| 201-300        | 12        | 20.69%  |
| 501-600        | 5         | 8.62%   |
| 351-400        | 3         | 5.17%   |
| 401-500        | 2         | 3.45%   |
| More than 2000 | 1         | 1.72%   |
| 601-700        | 1         | 1.72%   |
| 1001-1500      | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 92%     |
| 16/10 | 3         | 6%      |
| 1.00  | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 41.38%  |
| 81-90          | 9         | 15.52%  |
| 61-70          | 8         | 13.79%  |
| 201-250        | 5         | 8.62%   |
| 71-80          | 3         | 5.17%   |
| More than 1000 | 2         | 3.45%   |
| 121-130        | 2         | 3.45%   |
| 51-60          | 1         | 1.72%   |
| 351-500        | 1         | 1.72%   |
| 301-350        | 1         | 1.72%   |
| 151-200        | 1         | 1.72%   |
| 131-140        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 23        | 40.35%  |
| 121-160 | 20        | 35.09%  |
| 51-100  | 8         | 14.04%  |
| 161-240 | 4         | 7.02%   |
| 1-50    | 2         | 3.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 82.14%  |
| 2     | 8         | 14.29%  |
| 3     | 1         | 1.79%   |
| 0     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 27        | 31.4%   |
| Realtek Semiconductor      | 25        | 29.07%  |
| Qualcomm Atheros           | 19        | 22.09%  |
| Ralink Technology          | 2         | 2.33%   |
| MediaTek                   | 2         | 2.33%   |
| Broadcom                   | 2         | 2.33%   |
| ZTE WCDMA Technologies MSM | 1         | 1.16%   |
| VIA Technologies           | 1         | 1.16%   |
| TP-Link                    | 1         | 1.16%   |
| Sierra Wireless            | 1         | 1.16%   |
| Samsung Electronics        | 1         | 1.16%   |
| Ralink                     | 1         | 1.16%   |
| NetGear                    | 1         | 1.16%   |
| JMicron Technology         | 1         | 1.16%   |
| Broadcom Limited           | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 14        | 12.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 6.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.64%   |
| Intel Wireless 7260                                                     | 4         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.73%   |
| Intel Wireless 7265                                                     | 3         | 2.73%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.73%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.82%   |
| Intel Wireless 8260                                                     | 2         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.82%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.82%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                           | 1         | 0.91%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.91%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.91%   |
| Sierra Wireless EM7455                                                  | 1         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.91%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.91%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.91%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.91%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 37.04%  |
| Qualcomm Atheros      | 18        | 33.33%  |
| Realtek Semiconductor | 6         | 11.11%  |
| Ralink Technology     | 2         | 3.7%    |
| MediaTek              | 2         | 3.7%    |
| Broadcom              | 2         | 3.7%    |
| Sierra Wireless       | 1         | 1.85%   |
| Ralink                | 1         | 1.85%   |
| NetGear               | 1         | 1.85%   |
| Broadcom Limited      | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 9.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 7.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 7.41%   |
| Intel Wireless 7260                                                     | 4         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 5.56%   |
| Intel Wireless 7265                                                     | 3         | 5.56%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 3.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.7%    |
| Intel Wireless 8260                                                     | 2         | 3.7%    |
| Sierra Wireless EM7455                                                  | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.85%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.85%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.85%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.85%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 23        | 43.4%   |
| Intel                      | 22        | 41.51%  |
| Qualcomm Atheros           | 3         | 5.66%   |
| ZTE WCDMA Technologies MSM | 1         | 1.89%   |
| VIA Technologies           | 1         | 1.89%   |
| TP-Link                    | 1         | 1.89%   |
| Samsung Electronics        | 1         | 1.89%   |
| JMicron Technology         | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 26.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 13.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 11.32%  |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 5.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 3.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.77%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1         | 1.89%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.89%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.89%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.89%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.89%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 50%     |
| Ethernet | 49        | 47.12%  |
| Modem    | 3         | 2.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 67.24%  |
| Ethernet | 19        | 32.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 87.04%  |
| 1     | 5         | 9.26%   |
| 0     | 2         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 90.74%  |
| Yes  | 5         | 9.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 31.25%  |
| Realtek Semiconductor           | 4         | 12.5%   |
| Qualcomm Atheros Communications | 4         | 12.5%   |
| Broadcom                        | 4         | 12.5%   |
| Lite-On Technology              | 2         | 6.25%   |
| Dell                            | 2         | 6.25%   |
| Cambridge Silicon Radio         | 2         | 6.25%   |
| Ralink                          | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Foxconn International           | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 25%     |
| Realtek Bluetooth Radio                             | 4         | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 9.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 6.25%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.13%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.13%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 3.13%   |
| Foxconn / Hon Hai BT                                | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 68.75%  |
| AMD                   | 11        | 17.19%  |
| Nvidia                | 5         | 7.81%   |
| Realtek Semiconductor | 1         | 1.56%   |
| GYROCOM C&C           | 1         | 1.56%   |
| C-Media Electronics   | 1         | 1.56%   |
| Blue Microphones      | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 7.5%    |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 6.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 5%      |
| Intel Broadwell-U Audio Controller                                         | 4         | 5%      |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.75%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.5%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.5%    |
| Realtek Semiconductor USB Audio                                            | 1         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.25%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 1.25%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 1.25%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1.25%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.25%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.25%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.25%   |
| AMD High Definition Audio Controller                                       | 1         | 1.25%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 33.33%  |
| Unknown             | 7         | 14.58%  |
| SK hynix            | 6         | 12.5%   |
| Crucial             | 4         | 8.33%   |
| A-DATA Technology   | 4         | 8.33%   |
| Kingston            | 3         | 6.25%   |
| G.Skill             | 2         | 4.17%   |
| Unknown (ABCD)      | 1         | 2.08%   |
| Smart               | 1         | 2.08%   |
| Ramaxel Technology  | 1         | 2.08%   |
| Nanya Technology    | 1         | 2.08%   |
| Micron Technology   | 1         | 2.08%   |
| Apacer              | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 5.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 3.57%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 3.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 3.57%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.79%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.79%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.79%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.79%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 1.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s        | 1         | 1.79%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.79%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4096MB SODIMM DDR3 1067MT/s      | 1         | 1.79%   |
| Kingston RAM KHYXPX-MIE 8192MB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Kingston RAM ACR16D3LS1NGG/2G 2GB SODIMM DDR3 1333MT/s           | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 51.16%  |
| DDR4    | 12        | 27.91%  |
| SDRAM   | 2         | 4.65%   |
| DDR2    | 2         | 4.65%   |
| DDR     | 2         | 4.65%   |
| LPDDR4  | 1         | 2.33%   |
| LPDDR3  | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

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
| 8192  | 21        | 40.38%  |
| 4096  | 13        | 25%     |
| 2048  | 9         | 17.31%  |
| 16384 | 4         | 7.69%   |
| 1024  | 3         | 5.77%   |
| 32768 | 1         | 1.92%   |
| 512   | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 32.61%  |
| 2667    | 8         | 17.39%  |
| Unknown | 5         | 10.87%  |
| 2400    | 4         | 8.7%    |
| 1333    | 3         | 6.52%   |
| 1067    | 3         | 6.52%   |
| 4199    | 2         | 4.35%   |
| 3200    | 2         | 4.35%   |
| 2133    | 1         | 2.17%   |
| 1334    | 1         | 2.17%   |
| 1200    | 1         | 2.17%   |
| 800     | 1         | 2.17%   |

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
| Chicony Electronics                    | 19        | 44.19%  |
| Sunplus Innovation Technology          | 4         | 9.3%    |
| Microdia                               | 4         | 9.3%    |
| Acer                                   | 4         | 9.3%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.98%   |
| Suyin                                  | 2         | 4.65%   |
| Realtek Semiconductor                  | 2         | 4.65%   |
| Samsung Electronics                    | 1         | 2.33%   |
| Quanta                                 | 1         | 2.33%   |
| Mustek Systems                         | 1         | 2.33%   |
| Logitech                               | 1         | 2.33%   |
| IMC Networks                           | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 16.28%  |
| Chicony HD Webcam                                               | 2         | 4.65%   |
| Chicony EasyCamera                                              | 2         | 4.65%   |
| Acer BisonCam, NB Pro                                           | 2         | 4.65%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 2.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 2.33%   |
| Sunplus Laptop Integrated Webcam HD                             | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.33%   |
| Sunplus FHD Camera Microphone                                   | 1         | 2.33%   |
| Sunplus Asus Webcam                                             | 1         | 2.33%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 2.33%   |
| Realtek Lenovo EasyCamera                                       | 1         | 2.33%   |
| Realtek Integrated Webcam_HD                                    | 1         | 2.33%   |
| Quanta Sony Visual Communication Camera                         | 1         | 2.33%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 2.33%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 2.33%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.33%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.33%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 2.33%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.33%   |
| IMC Networks Integrated Webcam                                  | 1         | 2.33%   |
| Chicony WebCam                                                  | 1         | 2.33%   |
| Chicony VGA WebCam                                              | 1         | 2.33%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 2.33%   |
| Chicony Thinkpad T430 camera                                    | 1         | 2.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 2.33%   |
| Chicony Lenovo EasyCamera                                       | 1         | 2.33%   |
| Chicony HP TrueVision HD                                        | 1         | 2.33%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 2.33%   |
| Acer ThinkPad Integrated Camera                                 | 1         | 2.33%   |
| Acer Integrated Camera                                          | 1         | 2.33%   |

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
| Broadcom    | 7         | 70%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 64.29%  |
| 1     | 12        | 21.43%  |
| 2     | 6         | 10.71%  |
| 5     | 1         | 1.79%   |
| 3     | 1         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 7         | 30.43%  |
| Fingerprint reader       | 4         | 17.39%  |
| Net/wireless             | 3         | 13.04%  |
| Graphics card            | 3         | 13.04%  |
| Communication controller | 2         | 8.7%    |
| Camera                   | 2         | 8.7%    |
| Bluetooth                | 2         | 8.7%    |

