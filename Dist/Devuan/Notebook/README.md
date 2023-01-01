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

Total: 74

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9370                 | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
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
| Devuan 4                | 27        | 44.26%  |
| Devuan 3                | 14        | 22.95%  |
| Devuan Testing/unstable | 8         | 13.11%  |
| Devuan 5                | 8         | 13.11%  |
| Devuan                  | 2         | 3.28%   |
| Devuan 3.0              | 1         | 1.64%   |
| Devuan 2.1              | 1         | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 4         | 6.15%   |
| 5.10.0-16-amd64           | 4         | 6.15%   |
| 5.10.0-13-amd64           | 4         | 6.15%   |
| 4.19.0-9-amd64            | 4         | 6.15%   |
| 5.7.0-2-amd64             | 3         | 4.62%   |
| 5.10.0-8-amd64            | 3         | 4.62%   |
| 5.10.0-18-amd64           | 3         | 4.62%   |
| 5.10.0-10-amd64           | 3         | 4.62%   |
| 5.18.0-2-amd64            | 2         | 3.08%   |
| 5.10.0-19-amd64           | 2         | 3.08%   |
| 5.10.0-11-amd64           | 2         | 3.08%   |
| 4.19.0-17-amd64           | 2         | 3.08%   |
| 4.19.0-16-amd64           | 2         | 3.08%   |
| 4.19.0-14-amd64           | 2         | 3.08%   |
| 6.0.0-5-amd64             | 1         | 1.54%   |
| 6.0.0-2-amd64             | 1         | 1.54%   |
| 5.9.0-4-amd64             | 1         | 1.54%   |
| 5.8.0-1-amd64             | 1         | 1.54%   |
| 5.7.0-0.bpo.2-amd64       | 1         | 1.54%   |
| 5.6.0-2-amd64             | 1         | 1.54%   |
| 5.19.0-2-amd64            | 1         | 1.54%   |
| 5.18.0-1-amd64            | 1         | 1.54%   |
| 5.15.5-xanmod1            | 1         | 1.54%   |
| 5.15.0-2-amd64            | 1         | 1.54%   |
| 5.14.0-4-amd64            | 1         | 1.54%   |
| 5.10.0-7-amd64            | 1         | 1.54%   |
| 5.10.0-4-amd64            | 1         | 1.54%   |
| 5.10.0-15-amd64           | 1         | 1.54%   |
| 5.10.0-14-amd64           | 1         | 1.54%   |
| 5.10.0-1-amd64            | 1         | 1.54%   |
| 5.1.21                    | 1         | 1.54%   |
| 4.9.0-14-amd64            | 1         | 1.54%   |
| 4.9.0-11-amd64            | 1         | 1.54%   |
| 4.9.0-11-686              | 1         | 1.54%   |
| 4.9.0-0.bpo.4-686-pae     | 1         | 1.54%   |
| 4.4.195-antix.1-amd64-smp | 1         | 1.54%   |
| 4.19.0-17-686-pae         | 1         | 1.54%   |
| 4.19.0-12-amd64           | 1         | 1.54%   |
| 4.19.0-10-amd64           | 1         | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 27        | 43.55%  |
| 4.19.0  | 13        | 20.97%  |
| 5.7.0   | 4         | 6.45%   |
| 4.9.0   | 4         | 6.45%   |
| 5.18.0  | 3         | 4.84%   |
| 6.0.0   | 2         | 3.23%   |
| 5.9.0   | 1         | 1.61%   |
| 5.8.0   | 1         | 1.61%   |
| 5.6.0   | 1         | 1.61%   |
| 5.19.0  | 1         | 1.61%   |
| 5.15.5  | 1         | 1.61%   |
| 5.15.0  | 1         | 1.61%   |
| 5.14.0  | 1         | 1.61%   |
| 5.1.21  | 1         | 1.61%   |
| 4.4.195 | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 43.55%  |
| 4.19    | 13        | 20.97%  |
| 5.7     | 4         | 6.45%   |
| 4.9     | 4         | 6.45%   |
| 5.18    | 3         | 4.84%   |
| 6.0     | 2         | 3.23%   |
| 5.15    | 2         | 3.23%   |
| 5.9     | 1         | 1.61%   |
| 5.8     | 1         | 1.61%   |
| 5.6     | 1         | 1.61%   |
| 5.19    | 1         | 1.61%   |
| 5.14    | 1         | 1.61%   |
| 5.1     | 1         | 1.61%   |
| 4.4     | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 92.98%  |
| i686   | 3         | 5.26%   |
| armv7l | 1         | 1.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| XFCE     | 24        | 40%     |
| KDE5     | 10        | 16.67%  |
| MATE     | 8         | 13.33%  |
| Unknown  | 8         | 13.33%  |
| LXDE     | 3         | 5%      |
| i3       | 3         | 5%      |
| Openbox  | 1         | 1.67%   |
| LXQt     | 1         | 1.67%   |
| GNOME    | 1         | 1.67%   |
| Cinnamon | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 93.1%   |
| Tty     | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 18        | 30%     |
| Unknown | 18        | 30%     |
| SLiM    | 17        | 28.33%  |
| SDDM    | 5         | 8.33%   |
| XDM     | 1         | 1.67%   |
| GDM3    | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 23        | 39.66%  |
| en_GB       | 11        | 18.97%  |
| ru_RU       | 7         | 12.07%  |
| pt_BR       | 3         | 5.17%   |
| it_IT       | 2         | 3.45%   |
| es_ES       | 2         | 3.45%   |
| Unknown     | 2         | 3.45%   |
| ru_UA       | 1         | 1.72%   |
| pl_PL       | 1         | 1.72%   |
| fr_BE       | 1         | 1.72%   |
| es_SV       | 1         | 1.72%   |
| en_US.utf-8 | 1         | 1.72%   |
| de_DE       | 1         | 1.72%   |
| de_AT       | 1         | 1.72%   |
| C           | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 32        | 55.17%  |
| EFI  | 26        | 44.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 49        | 85.96%  |
| Btrfs   | 3         | 5.26%   |
| Unknown | 3         | 5.26%   |
| OveXlay | 1         | 1.75%   |
| Ext2    | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 47.46%  |
| MBR     | 22        | 37.29%  |
| Unknown | 9         | 15.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 89.47%  |
| Yes       | 6         | 10.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 77.59%  |
| Yes       | 13        | 22.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 29.82%  |
| Dell                | 10        | 17.54%  |
| Hewlett-Packard     | 7         | 12.28%  |
| Acer                | 4         | 7.02%   |
| Toshiba             | 3         | 5.26%   |
| ASUSTek Computer    | 3         | 5.26%   |
| MSI                 | 2         | 3.51%   |
| Fujitsu Siemens     | 2         | 3.51%   |
| Teclast             | 1         | 1.75%   |
| Sony                | 1         | 1.75%   |
| Samsung Electronics | 1         | 1.75%   |
| Notebook            | 1         | 1.75%   |
| Nokia               | 1         | 1.75%   |
| MTC                 | 1         | 1.75%   |
| IBM                 | 1         | 1.75%   |
| Fujitsu             | 1         | 1.75%   |
| CCE                 | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite Pro A50-C                                                              | 1         | 1.75%   |
| Toshiba Satellite M40X                                                                   | 1         | 1.75%   |
| Toshiba Satellite L655                                                                   | 1         | 1.75%   |
| Teclast F6 Plus                                                                          | 1         | 1.75%   |
| Sony VPCEE23FX                                                                           | 1         | 1.75%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 1.75%   |
| Notebook W230ST                                                                          | 1         | 1.75%   |
| Nokia N900                                                                               | 1         | 1.75%   |
| MTC Montara-GML                                                                          | 1         | 1.75%   |
| MSI MS-1688                                                                              | 1         | 1.75%   |
| MSI Modern 15 A5M                                                                        | 1         | 1.75%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 1.75%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 1.75%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 1.75%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 1.75%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 1.75%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 1.75%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 1.75%   |
| Lenovo ThinkPad T550 20CJS1VD01                                                          | 1         | 1.75%   |
| Lenovo ThinkPad T470s 20HGS00P00                                                         | 1         | 1.75%   |
| Lenovo ThinkPad T440p                                                                    | 1         | 1.75%   |
| Lenovo ThinkPad T430 2349I46                                                             | 1         | 1.75%   |
| Lenovo ThinkPad T420 4180AG3                                                             | 1         | 1.75%   |
| Lenovo IdeaPad Z370                                                                      | 1         | 1.75%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                                                    | 1         | 1.75%   |
| Lenovo IdeaPad 130-15AST 81H5                                                            | 1         | 1.75%   |
| Lenovo G50-30 80G0                                                                       | 1         | 1.75%   |
| IBM ThinkPad T41p 2373GHG                                                                | 1         | 1.75%   |
| HP ProBook 6475b                                                                         | 1         | 1.75%   |
| HP Pavilion 11 x360 PC                                                                   | 1         | 1.75%   |
| HP Notebook                                                                              | 1         | 1.75%   |
| HP Laptop 17-cp0xxx                                                                      | 1         | 1.75%   |
| HP Laptop 15-bs2xx                                                                       | 1         | 1.75%   |
| HP Laptop 14-df0xxx                                                                      | 1         | 1.75%   |
| HP 250 G8 Notebook PC                                                                    | 1         | 1.75%   |
| Fujitsu Siemens ESPRIMO Mobile V6535                                                     | 1         | 1.75%   |
| Fujitsu Siemens AMILO Xi 1546                                                            | 1         | 1.75%   |
| Fujitsu LIFEBOOK U7510                                                                   | 1         | 1.75%   |
| Dell XPS 13 9370                                                                         | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 21.05%  |
| Dell Latitude           | 7         | 12.28%  |
| Toshiba Satellite       | 3         | 5.26%   |
| Lenovo IdeaPad          | 3         | 5.26%   |
| HP Laptop               | 3         | 5.26%   |
| Acer Aspire             | 3         | 5.26%   |
| Teclast F6              | 1         | 1.75%   |
| Sony VPCEE23FX          | 1         | 1.75%   |
| Samsung 355V4C          | 1         | 1.75%   |
| Notebook W230ST         | 1         | 1.75%   |
| Nokia N900              | 1         | 1.75%   |
| MTC Montara-GML         | 1         | 1.75%   |
| MSI MS-1688             | 1         | 1.75%   |
| MSI Modern              | 1         | 1.75%   |
| Lenovo V310-14ISK       | 1         | 1.75%   |
| Lenovo G50-30           | 1         | 1.75%   |
| IBM ThinkPad            | 1         | 1.75%   |
| HP ProBook              | 1         | 1.75%   |
| HP Pavilion             | 1         | 1.75%   |
| HP Notebook             | 1         | 1.75%   |
| HP 250                  | 1         | 1.75%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.75%   |
| Fujitsu Siemens AMILO   | 1         | 1.75%   |
| Fujitsu LIFEBOOK        | 1         | 1.75%   |
| Dell XPS                | 1         | 1.75%   |
| Dell Precision          | 1         | 1.75%   |
| Dell Inspiron           | 1         | 1.75%   |
| CCE Capella             | 1         | 1.75%   |
| ASUS X555LJ             | 1         | 1.75%   |
| ASUS K55VJ              | 1         | 1.75%   |
| ASUS K52F               | 1         | 1.75%   |
| Acer Extensa            | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 8         | 14.04%  |
| 2019    | 5         | 8.77%   |
| 2018    | 5         | 8.77%   |
| 2017    | 4         | 7.02%   |
| 2014    | 4         | 7.02%   |
| 2011    | 4         | 7.02%   |
| 2010    | 4         | 7.02%   |
| 2015    | 3         | 5.26%   |
| 2009    | 3         | 5.26%   |
| 2021    | 2         | 3.51%   |
| 2020    | 2         | 3.51%   |
| 2016    | 2         | 3.51%   |
| 2013    | 2         | 3.51%   |
| 2008    | 2         | 3.51%   |
| 2006    | 2         | 3.51%   |
| 2005    | 2         | 3.51%   |
| 2022    | 1         | 1.75%   |
| 2007    | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 55        | 96.49%  |
| Enabled  | 2         | 3.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 96.49%  |
| Yes  | 2         | 3.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 24.56%  |
| 3.01-4.0    | 12        | 21.05%  |
| 8.01-16.0   | 12        | 21.05%  |
| 16.01-24.0  | 9         | 15.79%  |
| 2.01-3.0    | 3         | 5.26%   |
| 1.01-2.0    | 3         | 5.26%   |
| 0.01-0.5    | 2         | 3.51%   |
| 32.01-64.0  | 1         | 1.75%   |
| 64.01-256.0 | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 26        | 41.27%  |
| 4.01-8.0   | 13        | 20.63%  |
| 2.01-3.0   | 9         | 14.29%  |
| 3.01-4.0   | 5         | 7.94%   |
| 0.51-1.0   | 5         | 7.94%   |
| 0.01-0.5   | 3         | 4.76%   |
| 32.01-64.0 | 1         | 1.59%   |
| 8.01-16.0  | 1         | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 72.41%  |
| 2      | 12        | 20.69%  |
| 3      | 4         | 6.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 58.62%  |
| Yes       | 24        | 41.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 89.47%  |
| No        | 6         | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 96.49%  |
| No        | 2         | 3.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 58.62%  |
| No        | 24        | 41.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 10.34%  |
| Russia      | 6         | 10.34%  |
| Germany     | 6         | 10.34%  |
| Brazil      | 5         | 8.62%   |
| Ukraine     | 4         | 6.9%    |
| Grenada     | 3         | 5.17%   |
| Spain       | 2         | 3.45%   |
| Poland      | 2         | 3.45%   |
| Netherlands | 2         | 3.45%   |
| Italy       | 2         | 3.45%   |
| Hungary     | 2         | 3.45%   |
| France      | 2         | 3.45%   |
| Finland     | 2         | 3.45%   |
| Vietnam     | 1         | 1.72%   |
| UK          | 1         | 1.72%   |
| Slovakia    | 1         | 1.72%   |
| Serbia      | 1         | 1.72%   |
| Portugal    | 1         | 1.72%   |
| Norway      | 1         | 1.72%   |
| Mexico      | 1         | 1.72%   |
| Israel      | 1         | 1.72%   |
| Indonesia   | 1         | 1.72%   |
| Greece      | 1         | 1.72%   |
| Georgia     | 1         | 1.72%   |
| El Salvador | 1         | 1.72%   |
| Belarus     | 1         | 1.72%   |
| Austria     | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Saint George's     | 3         | 5.17%   |
| Nadudvar           | 2         | 3.45%   |
| Milan              | 2         | 3.45%   |
| Kyiv               | 2         | 3.45%   |
| Bagnolet           | 2         | 3.45%   |
| Amsterdam          | 2         | 3.45%   |
| Yakutsk            | 1         | 1.72%   |
| Wroclaw            | 1         | 1.72%   |
| Wildberg           | 1         | 1.72%   |
| Trubchëvsk        | 1         | 1.72%   |
| Thessaloniki       | 1         | 1.72%   |
| Tel Aviv           | 1         | 1.72%   |
| Tbilisi            | 1         | 1.72%   |
| Staunton           | 1         | 1.72%   |
| St Petersburg      | 1         | 1.72%   |
| Sao Paulo          | 1         | 1.72%   |
| San Salvador       | 1         | 1.72%   |
| Rio de Janeiro     | 1         | 1.72%   |
| Praia Grande       | 1         | 1.72%   |
| Oslo               | 1         | 1.72%   |
| Novopskov          | 1         | 1.72%   |
| Muenster-Sarmsheim | 1         | 1.72%   |
| Mountain View      | 1         | 1.72%   |
| Moscow             | 1         | 1.72%   |
| Maladzyechna       | 1         | 1.72%   |
| Madrid             | 1         | 1.72%   |
| Leonding           | 1         | 1.72%   |
| Leipzig            | 1         | 1.72%   |
| Krasnodar          | 1         | 1.72%   |
| Kouvola            | 1         | 1.72%   |
| Kharkiv            | 1         | 1.72%   |
| Katzenbach         | 1         | 1.72%   |
| Katowice           | 1         | 1.72%   |
| Jyväskylä        | 1         | 1.72%   |
| Hermosillo         | 1         | 1.72%   |
| Hayden             | 1         | 1.72%   |
| Hanoi              | 1         | 1.72%   |
| Gijón             | 1         | 1.72%   |
| Fulham             | 1         | 1.72%   |
| Forest Grove       | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 13.33%  |
| Samsung Electronics | 10        | 15     | 13.33%  |
| Unknown             | 7         | 8      | 9.33%   |
| Kingston            | 6         | 6      | 8%      |
| Seagate             | 4         | 4      | 5.33%   |
| SanDisk             | 4         | 4      | 5.33%   |
| SK hynix            | 3         | 3      | 4%      |
| PNY                 | 3         | 3      | 4%      |
| Hitachi             | 3         | 3      | 4%      |
| HGST                | 3         | 3      | 4%      |
| Toshiba             | 2         | 2      | 2.67%   |
| Team                | 2         | 2      | 2.67%   |
| Fujitsu             | 2         | 2      | 2.67%   |
| Crucial             | 2         | 2      | 2.67%   |
| Union Memory        | 1         | 2      | 1.33%   |
| UMIS                | 1         | 1      | 1.33%   |
| Teclast             | 1         | 1      | 1.33%   |
| Smart               | 1         | 1      | 1.33%   |
| SABRENT             | 1         | 2      | 1.33%   |
| Patriot             | 1         | 1      | 1.33%   |
| Mushkin             | 1         | 1      | 1.33%   |
| LITEONIT            | 1         | 1      | 1.33%   |
| LITEON              | 1         | 4      | 1.33%   |
| KIOXIA              | 1         | 1      | 1.33%   |
| KingFast            | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| HXY                 | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| PNY CS900 240GB SSD                    | 3         | 3.9%    |
| Unknown MMC Card  128GB                | 2         | 2.6%    |
| Kingston SA400S37480G 480GB SSD        | 2         | 2.6%    |
| Kingston SA400S37240G 240GB SSD        | 2         | 2.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 1.3%    |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 1.3%    |
| WDC WD5000BPVT-24HXZT3 500GB           | 1         | 1.3%    |
| WDC WD3200BPVT-22JJ5T0 320GB           | 1         | 1.3%    |
| WDC WD3200BEVT-22A23T0 320GB           | 1         | 1.3%    |
| WDC WD3200BEVE-00A0HT0 320GB           | 1         | 1.3%    |
| WDC WD2500BEKT-00A25T0 250GB           | 1         | 1.3%    |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 1.3%    |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 1.3%    |
| WDC PC SN540 SDDPNPF-512G-1032 512GB   | 1         | 1.3%    |
| Unknown SD04G  4GB                     | 1         | 1.3%    |
| Unknown SD  8GB                        | 1         | 1.3%    |
| Unknown MMC32G  32GB                   | 1         | 1.3%    |
| Unknown MMC Card  8GB                  | 1         | 1.3%    |
| Unknown MMC Card  32GB                 | 1         | 1.3%    |
| Unknown MMC Card  16GB                 | 1         | 1.3%    |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 1.3%    |
| UMIS RPFTJ256PDD2MWX 256GB             | 1         | 1.3%    |
| Toshiba MK5065GSX 500GB                | 1         | 1.3%    |
| Toshiba MK1252GSX 120GB                | 1         | 1.3%    |
| Teclast 256GB NS550-2242 SSD           | 1         | 1.3%    |
| Team T253X1120G 120GB SSD              | 1         | 1.3%    |
| Team T253TD240G 240GB SSD              | 1         | 1.3%    |
| Smart SSD SZ9MSE mSATA 256GB           | 1         | 1.3%    |
| SK hynix SC311 SATA 256GB SSD          | 1         | 1.3%    |
| SK hynix PC611 NVMe 1TB                | 1         | 1.3%    |
| SK hynix PC401 NVMe 512GB              | 1         | 1.3%    |
| Seagate ST9250410AS 250GB              | 1         | 1.3%    |
| Seagate ST500LT012-1DG142 500GB        | 1         | 1.3%    |
| Seagate ST250VT000-1DK141 250GB        | 1         | 1.3%    |
| Seagate Expansion Desk 5TB             | 1         | 1.3%    |
| SanDisk X300 MSATA 256GB SSD           | 1         | 1.3%    |
| SanDisk SSD PLUS 480GB                 | 1         | 1.3%    |
| SanDisk SDSSDHII240G 240GB             | 1         | 1.3%    |
| SanDisk SDSSDH3500G 500GB              | 1         | 1.3%    |
| Samsung SSD PM851 mSATA 128GB          | 1         | 1.3%    |

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
| Samsung Electronics | 6         | 6      | 17.65%  |
| Kingston            | 6         | 6      | 17.65%  |
| SanDisk             | 4         | 4      | 11.76%  |
| PNY                 | 3         | 3      | 8.82%   |
| Team                | 2         | 2      | 5.88%   |
| Crucial             | 2         | 2      | 5.88%   |
| WDC                 | 1         | 2      | 2.94%   |
| Union Memory        | 1         | 2      | 2.94%   |
| Teclast             | 1         | 1      | 2.94%   |
| Smart               | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Mushkin             | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| LITEON              | 1         | 4      | 2.94%   |
| HXY                 | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 30        | 39     | 42.25%  |
| HDD     | 22        | 22     | 30.99%  |
| NVMe    | 11        | 17     | 15.49%  |
| MMC     | 7         | 8      | 9.86%   |
| Unknown | 1         | 1      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 61     | 71.21%  |
| NVMe | 10        | 15     | 15.15%  |
| MMC  | 7         | 8      | 10.61%  |
| SAS  | 2         | 3      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 46     | 79.59%  |
| 0.51-1.0   | 7         | 12     | 14.29%  |
| 1.01-2.0   | 2         | 2      | 4.08%   |
| 4.01-10.0  | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 26.67%  |
| 101-250        | 14        | 23.33%  |
| 501-1000       | 8         | 13.33%  |
| 51-100         | 7         | 11.67%  |
| 1001-2000      | 4         | 6.67%   |
| 21-50          | 3         | 5%      |
| Unknown        | 3         | 5%      |
| 2001-3000      | 2         | 3.33%   |
| 1-20           | 2         | 3.33%   |
| More than 3000 | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 17        | 28.81%  |
| 101-250   | 10        | 16.95%  |
| 51-100    | 10        | 16.95%  |
| 251-500   | 7         | 11.86%  |
| 21-50     | 6         | 10.17%  |
| 1001-2000 | 3         | 5.08%   |
| Unknown   | 3         | 5.08%   |
| 501-1000  | 2         | 3.39%   |
| 2001-3000 | 1         | 1.69%   |

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
| Works    | 45        | 61     | 69.23%  |
| Detected | 15        | 21     | 23.08%  |
| Malfunc  | 5         | 5      | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 44        | 70.97%  |
| AMD                     | 8         | 12.9%   |
| Samsung Electronics     | 4         | 6.45%   |
| SK hynix                | 2         | 3.23%   |
| VIA Technologies        | 1         | 1.61%   |
| Union Memory (Shenzhen) | 1         | 1.61%   |
| SanDisk                 | 1         | 1.61%   |
| KIOXIA                  | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 8.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 5.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 4.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 4.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 2.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 2.94%   |
| VIA VT6421 IDE/SATA Controller                                                         | 1         | 1.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.47%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 1.47%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 1.47%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.47%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.47%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.47%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.47%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 42        | 64.62%  |
| NVMe | 10        | 15.38%  |
| IDE  | 8         | 12.31%  |
| RAID | 5         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 82.46%  |
| AMD    | 9         | 15.79%  |
| ARM    | 1         | 1.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 5.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 5.26%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 3.51%   |
| Intel Pentium M processor 1700MHz           | 1         | 1.75%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.75%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.75%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.75%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.75%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.75%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 1.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.75%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 1.75%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.75%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.75%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-10310U CPU @ 1.70GHz          | 1         | 1.75%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.75%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.75%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.75%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.75%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.75%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.75%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.75%   |
| Intel Celeron M processor 1.40GHz           | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 11        | 19.3%   |
| Intel Core i5           | 11        | 19.3%   |
| Intel Core i3           | 10        | 17.54%  |
| Other                   | 3         | 5.26%   |
| Intel Core 2            | 3         | 5.26%   |
| Intel Celeron           | 3         | 5.26%   |
| Intel Pentium M         | 2         | 3.51%   |
| Intel Pentium           | 2         | 3.51%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Pentium Dual      | 1         | 1.75%   |
| Intel Core i9           | 1         | 1.75%   |
| Intel Celeron M         | 1         | 1.75%   |
| AMD Ryzen 7             | 1         | 1.75%   |
| AMD Ryzen 5             | 1         | 1.75%   |
| AMD E2                  | 1         | 1.75%   |
| AMD E                   | 1         | 1.75%   |
| AMD Athlon II           | 1         | 1.75%   |
| AMD A8                  | 1         | 1.75%   |
| AMD A6                  | 1         | 1.75%   |
| AMD A10                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 64.91%  |
| 4      | 11        | 19.3%   |
| 1      | 5         | 8.77%   |
| 6      | 3         | 5.26%   |
| 8      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 63.16%  |
| 1      | 21        | 36.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 91.23%  |
| 32-bit         | 3         | 5.26%   |
| Unknown        | 2         | 3.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 27.12%  |
| 0x406e3    | 4         | 6.78%   |
| 0x306d4    | 3         | 5.08%   |
| 0x306a9    | 3         | 5.08%   |
| 0x206a7    | 3         | 5.08%   |
| 0x906ea    | 2         | 3.39%   |
| 0x806ec    | 2         | 3.39%   |
| 0x706a1    | 2         | 3.39%   |
| 0x6f6      | 2         | 3.39%   |
| 0x40651    | 2         | 3.39%   |
| 0x306c3    | 2         | 3.39%   |
| 0x30678    | 2         | 3.39%   |
| 0x20655    | 2         | 3.39%   |
| 0x1067a    | 2         | 3.39%   |
| 0x08608103 | 2         | 3.39%   |
| 0x906ed    | 1         | 1.69%   |
| 0x806c1    | 1         | 1.69%   |
| 0x6d8      | 1         | 1.69%   |
| 0x695      | 1         | 1.69%   |
| 0x20652    | 1         | 1.69%   |
| 0x07030105 | 1         | 1.69%   |
| 0x0600611a | 1         | 1.69%   |
| 0x05000119 | 1         | 1.69%   |
| 0x05000101 | 1         | 1.69%   |
| 0x010000b6 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 14.04%  |
| IvyBridge     | 6         | 10.53%  |
| Westmere      | 5         | 8.77%   |
| Skylake       | 4         | 7.02%   |
| Haswell       | 4         | 7.02%   |
| Broadwell     | 4         | 7.02%   |
| SandyBridge   | 3         | 5.26%   |
| P6            | 3         | 5.26%   |
| Core          | 3         | 5.26%   |
| Unknown       | 3         | 5.26%   |
| Silvermont    | 2         | 3.51%   |
| Penryn        | 2         | 3.51%   |
| Goldmont plus | 2         | 3.51%   |
| Excavator     | 2         | 3.51%   |
| Bobcat        | 2         | 3.51%   |
| TigerLake     | 1         | 1.75%   |
| Puma          | 1         | 1.75%   |
| Piledriver    | 1         | 1.75%   |
| K10           | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 65.15%  |
| AMD    | 14        | 21.21%  |
| Nvidia | 9         | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 6         | 8.7%    |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 7.25%   |
| Intel HD Graphics 5500                                                                | 4         | 5.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 4.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 4.35%   |
| Intel HD Graphics 620                                                                 | 2         | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 2.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 2.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 2.9%    |
| AMD Lucienne                                                                          | 2         | 2.9%    |
| Nvidia GP107M [GeForce MX150]                                                         | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.45%   |
| Nvidia GM108M [GeForce 930M]                                                          | 1         | 1.45%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 1.45%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.45%   |
| Nvidia GF108M [NVS 5400M]                                                             | 1         | 1.45%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.45%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.45%   |
| Intel UHD Graphics 620                                                                | 1         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.45%   |
| Intel HD Graphics 520                                                                 | 1         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.45%   |
| Intel 82852/855GM Integrated Graphics Device                                          | 1         | 1.45%   |
| AMD Wrestler [Radeon HD 7340]                                                         | 1         | 1.45%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 1.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.45%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                       | 1         | 1.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.45%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 1.45%   |
| AMD RV380/M24 [Mobility Radeon X600]                                                  | 1         | 1.45%   |
| AMD RV350/M10 GL [Mobility FireGL T2]                                                 | 1         | 1.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 54.39%  |
| 1 x AMD        | 11        | 19.3%   |
| Intel + Nvidia | 9         | 15.79%  |
| Other          | 2         | 3.51%   |
| 2 x AMD        | 2         | 3.51%   |
| 2 x Intel      | 1         | 1.75%   |
| Intel + AMD    | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 91.23%  |
| Proprietary | 3         | 5.26%   |
| Unknown     | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 70.69%  |
| 0.01-0.5   | 8         | 13.79%  |
| 1.01-2.0   | 4         | 6.9%    |
| 0.51-1.0   | 4         | 6.9%    |
| 3.01-4.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 23.81%  |
| AU Optronics            | 12        | 19.05%  |
| Samsung Electronics     | 7         | 11.11%  |
| Chimei Innolux          | 6         | 9.52%   |
| BOE                     | 4         | 6.35%   |
| PANDA                   | 3         | 4.76%   |
| MStar                   | 2         | 3.17%   |
| Lenovo                  | 2         | 3.17%   |
| Goldstar                | 2         | 3.17%   |
| Chi Mei Optoelectronics | 2         | 3.17%   |
| Unknown                 | 1         | 1.59%   |
| STD                     | 1         | 1.59%   |
| Sharp                   | 1         | 1.59%   |
| InnoLux Display         | 1         | 1.59%   |
| InfoVision              | 1         | 1.59%   |
| Hisense                 | 1         | 1.59%   |
| Dell                    | 1         | 1.59%   |
| AOC                     | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch    | 2         | 3.17%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 2         | 3.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 3.17%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 1.59%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                    | 1         | 1.59%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch              | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch | 1         | 1.59%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 1.59%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 1.59%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD02C0 1366x768 293x165mm 13.2-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch          | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch              | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch              | 1         | 1.59%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 1.59%   |
| Hisense Hisense HSE4000 1920x1080 591x355mm 27.1-inch                | 1         | 1.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1         | 1.59%   |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                 | 1         | 1.59%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                    | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch     | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 28        | 45.9%   |
| 1920x1080 (FHD)  | 22        | 36.07%  |
| 3840x2160 (4K)   | 5         | 8.2%    |
| 1600x900 (HD+)   | 2         | 3.28%   |
| 1280x800 (WXGA)  | 2         | 3.28%   |
| 2288x1287        | 1         | 1.64%   |
| 1440x900 (WXGA+) | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 39.68%  |
| 12     | 8         | 12.7%   |
| 14     | 7         | 11.11%  |
| 13     | 7         | 11.11%  |
| 24     | 3         | 4.76%   |
| 17     | 3         | 4.76%   |
| 52     | 2         | 3.17%   |
| 23     | 2         | 3.17%   |
| 21     | 2         | 3.17%   |
| 142    | 1         | 1.59%   |
| 31     | 1         | 1.59%   |
| 27     | 1         | 1.59%   |
| 11     | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 35        | 55.56%  |
| 201-300        | 13        | 20.63%  |
| 501-600        | 6         | 9.52%   |
| 351-400        | 3         | 4.76%   |
| 401-500        | 2         | 3.17%   |
| 1001-1500      | 2         | 3.17%   |
| More than 2000 | 1         | 1.59%   |
| 601-700        | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 92.45%  |
| 16/10 | 3         | 5.66%   |
| 1.00  | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 39.68%  |
| 81-90          | 10        | 15.87%  |
| 61-70          | 8         | 12.7%   |
| 201-250        | 6         | 9.52%   |
| 71-80          | 4         | 6.35%   |
| More than 1000 | 3         | 4.76%   |
| 121-130        | 2         | 3.17%   |
| 51-60          | 1         | 1.59%   |
| 351-500        | 1         | 1.59%   |
| 301-350        | 1         | 1.59%   |
| 151-200        | 1         | 1.59%   |
| 131-140        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 23        | 37.1%   |
| 121-160 | 22        | 35.48%  |
| 51-100  | 9         | 14.52%  |
| 161-240 | 5         | 8.06%   |
| 1-50    | 3         | 4.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 81.36%  |
| 2     | 8         | 13.56%  |
| 3     | 2         | 3.39%   |
| 0     | 1         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 28        | 31.11%  |
| Realtek Semiconductor      | 27        | 30%     |
| Qualcomm Atheros           | 20        | 22.22%  |
| Ralink Technology          | 2         | 2.22%   |
| MediaTek                   | 2         | 2.22%   |
| Broadcom                   | 2         | 2.22%   |
| ZTE WCDMA Technologies MSM | 1         | 1.11%   |
| VIA Technologies           | 1         | 1.11%   |
| TP-Link                    | 1         | 1.11%   |
| Sierra Wireless            | 1         | 1.11%   |
| Samsung Electronics        | 1         | 1.11%   |
| Ralink                     | 1         | 1.11%   |
| NetGear                    | 1         | 1.11%   |
| JMicron Technology         | 1         | 1.11%   |
| Broadcom Limited           | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 16        | 13.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 6.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 5.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.48%   |
| Intel Wireless 7260                                                     | 4         | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.61%   |
| Intel Wireless 7265                                                     | 3         | 2.61%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.74%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.74%   |
| Intel Wireless 8260                                                     | 2         | 1.74%   |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.74%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.74%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                             | 1         | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 1         | 0.87%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.87%   |
| Sierra Wireless EM7455                                                  | 1         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.87%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.87%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.87%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 0.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.87%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 36.84%  |
| Qualcomm Atheros      | 19        | 33.33%  |
| Realtek Semiconductor | 7         | 12.28%  |
| Ralink Technology     | 2         | 3.51%   |
| MediaTek              | 2         | 3.51%   |
| Broadcom              | 2         | 3.51%   |
| Sierra Wireless       | 1         | 1.75%   |
| Ralink                | 1         | 1.75%   |
| NetGear               | 1         | 1.75%   |
| Broadcom Limited      | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 8.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 7.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 7.02%   |
| Intel Wireless 7260                                                     | 4         | 7.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 5.26%   |
| Intel Wireless 7265                                                     | 3         | 5.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 3.51%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 3.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.51%   |
| Intel Wireless 8260                                                     | 2         | 3.51%   |
| Sierra Wireless EM7455                                                  | 1         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.75%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 1.75%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.75%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.75%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 1         | 1.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.75%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.75%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.75%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 25        | 45.45%  |
| Intel                      | 22        | 40%     |
| Qualcomm Atheros           | 3         | 5.45%   |
| ZTE WCDMA Technologies MSM | 1         | 1.82%   |
| VIA Technologies           | 1         | 1.82%   |
| TP-Link                    | 1         | 1.82%   |
| Samsung Electronics        | 1         | 1.82%   |
| JMicron Technology         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 29.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 12.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 10.91%  |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 5.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 3.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.64%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 1.82%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 1.82%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.82%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.82%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 50.46%  |
| Ethernet | 51        | 46.79%  |
| Modem    | 3         | 2.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 67.21%  |
| Ethernet | 20        | 32.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 49        | 85.96%  |
| 1     | 6         | 10.53%  |
| 0     | 2         | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 89.47%  |
| Yes  | 6         | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 31.43%  |
| Realtek Semiconductor           | 5         | 14.29%  |
| Qualcomm Atheros Communications | 4         | 11.43%  |
| Broadcom                        | 4         | 11.43%  |
| Lite-On Technology              | 2         | 5.71%   |
| Foxconn / Hon Hai               | 2         | 5.71%   |
| Dell                            | 2         | 5.71%   |
| Cambridge Silicon Radio         | 2         | 5.71%   |
| Ralink                          | 1         | 2.86%   |
| IMC Networks                    | 1         | 2.86%   |
| Foxconn International           | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 22.86%  |
| Realtek Bluetooth Radio                             | 5         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 5.71%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.86%   |
| Intel AX200 Bluetooth                               | 1         | 2.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.86%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2.86%   |
| Foxconn / Hon Hai BT                                | 1         | 2.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 69.12%  |
| AMD                   | 11        | 16.18%  |
| Nvidia                | 5         | 7.35%   |
| C-Media Electronics   | 2         | 2.94%   |
| Realtek Semiconductor | 1         | 1.47%   |
| GYROCOM C&C           | 1         | 1.47%   |
| Blue Microphones      | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 7.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 5.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.76%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.57%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.38%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.38%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.38%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.19%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.19%   |
| GYROCOM C&C Fiio E10                                                       | 1         | 1.19%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1.19%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.19%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.19%   |
| AMD High Definition Audio Controller                                       | 1         | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 32.69%  |
| Unknown             | 7         | 13.46%  |
| SK hynix            | 7         | 13.46%  |
| Kingston            | 4         | 7.69%   |
| Crucial             | 4         | 7.69%   |
| A-DATA Technology   | 4         | 7.69%   |
| Micron Technology   | 2         | 3.85%   |
| G.Skill             | 2         | 3.85%   |
| Unknown (ABCD)      | 1         | 1.92%   |
| Smart               | 1         | 1.92%   |
| Ramaxel Technology  | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| Apacer              | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 5%      |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 3.33%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 3.33%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.67%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.67%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.67%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.67%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.67%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.67%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s        | 1         | 1.67%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.67%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 47.83%  |
| DDR4    | 14        | 30.43%  |
| SDRAM   | 2         | 4.35%   |
| LPDDR3  | 2         | 4.35%   |
| DDR2    | 2         | 4.35%   |
| DDR     | 2         | 4.35%   |
| LPDDR4  | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 95.56%  |
| Row Of Chips | 2         | 4.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 41.82%  |
| 4096  | 14        | 25.45%  |
| 2048  | 9         | 16.36%  |
| 16384 | 4         | 7.27%   |
| 1024  | 3         | 5.45%   |
| 32768 | 1         | 1.82%   |
| 512   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 30%     |
| 2667    | 9         | 18%     |
| Unknown | 5         | 10%     |
| 2400    | 4         | 8%      |
| 3200    | 3         | 6%      |
| 1333    | 3         | 6%      |
| 1067    | 3         | 6%      |
| 4199    | 2         | 4%      |
| 2133    | 2         | 4%      |
| 3266    | 1         | 2%      |
| 1334    | 1         | 2%      |
| 1200    | 1         | 2%      |
| 800     | 1         | 2%      |

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
| Chicony Electronics                    | 21        | 45.65%  |
| Sunplus Innovation Technology          | 4         | 8.7%    |
| Microdia                               | 4         | 8.7%    |
| Acer                                   | 4         | 8.7%    |
| Realtek Semiconductor                  | 3         | 6.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.52%   |
| Suyin                                  | 2         | 4.35%   |
| Samsung Electronics                    | 1         | 2.17%   |
| Quanta                                 | 1         | 2.17%   |
| Mustek Systems                         | 1         | 2.17%   |
| Logitech                               | 1         | 2.17%   |
| IMC Networks                           | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 15.22%  |
| Chicony HP TrueVision HD Camera                                 | 2         | 4.35%   |
| Chicony HD Webcam                                               | 2         | 4.35%   |
| Chicony EasyCamera                                              | 2         | 4.35%   |
| Acer Integrated Camera                                          | 2         | 4.35%   |
| Acer BisonCam, NB Pro                                           | 2         | 4.35%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 2.17%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 1         | 2.17%   |
| Sunplus SPCA2650 AV Camera                                      | 1         | 2.17%   |
| Sunplus Laptop Integrated Webcam HD                             | 1         | 2.17%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 2.17%   |
| Sunplus Asus Webcam                                             | 1         | 2.17%   |
| Samsung Galaxy A5 (MTP)                                         | 1         | 2.17%   |
| Realtek Lenovo EasyCamera                                       | 1         | 2.17%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 2.17%   |
| Realtek Integrated Webcam_HD                                    | 1         | 2.17%   |
| Quanta Sony Visual Communication Camera                         | 1         | 2.17%   |
| Mustek Systems USB 2.0 PC Camera                                | 1         | 2.17%   |
| Microdia WebCam SC-13HDL12639P                                  | 1         | 2.17%   |
| Microdia Sonix USB 2.0 Camera                                   | 1         | 2.17%   |
| Microdia Dell Integrated HD Webcam                              | 1         | 2.17%   |
| Microdia 1.3 MPixel Integrated Webcam                           | 1         | 2.17%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.17%   |
| IMC Networks Integrated Webcam                                  | 1         | 2.17%   |
| Chicony WebCam                                                  | 1         | 2.17%   |
| Chicony VGA WebCam                                              | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 2.17%   |
| Chicony Thinkpad T430 camera                                    | 1         | 2.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 2.17%   |
| Chicony Lenovo EasyCamera                                       | 1         | 2.17%   |
| Chicony HP TrueVision HD                                        | 1         | 2.17%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-82                | 1         | 2.17%   |

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
| 0     | 38        | 64.41%  |
| 1     | 14        | 23.73%  |
| 2     | 5         | 8.47%   |
| 5     | 1         | 1.69%   |
| 3     | 1         | 1.69%   |

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

