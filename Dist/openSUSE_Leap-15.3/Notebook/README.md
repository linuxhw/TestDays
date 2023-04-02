openSUSE Leap-15.3 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

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

Total: 93

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | PCx0Dx                      | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| ASUSTek       | G771JW                      | [e5b5f4792c](https://linux-hardware.org/?probe=e5b5f4792c) | Feb 19, 2023 |
| ASUSTek       | G771JW                      | [c73a9b9ee2](https://linux-hardware.org/?probe=c73a9b9ee2) | Feb 19, 2023 |
| HP            | ZBook 15 G6                 | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| Gateway       | NV54 Series                 | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| HP            | Mini 210-1000               | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | G771JW                      | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| HP            | 250 G3                      | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Fujitsu       | LIFEBOOK S762               | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| HP            | Notebook                    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Dell          | System Inspiron N7110       | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Acer          | Aspire E1-571               | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Dell          | Latitude E7470              | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| MSI           | CX600                       | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| LG Electro... | C400-G.BC22P1               | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Acer          | Nitro AN515-52              | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Toshiba       | AS 1301                     | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | XPS 15 9510                 | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Dell          | Inspiron N4030              | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Acer          | Aspire E1-571               | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo        | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer          | Aspire E1-772G              | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Lenovo        | G50-45 80E3                 | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Acer          | Aspire E1-772G              | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer          | Aspire 5820TG               | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Acer          | Aspire E1-772G              | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Medion        | E6436 MD61150               | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| Dell          | Precision M6700             | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| Dell          | Precision M6700             | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo        | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell          | Latitude 5480               | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell          | Inspiron 3521               | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| HP            | Stream Notebook PC 11       | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu       | LIFEBOOK E754               | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| ASUSTek       | G771JW                      | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony          | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| Sony          | VGN-Z570AN                  | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI           | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP            | Pavilion dx6500             | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP            | Pavilion dx6500             | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.27-default                | 8         | 12.5%   |
| 5.3.18-59.37-default                | 5         | 7.81%   |
| 5.3.18-59.19-default                | 5         | 7.81%   |
| 5.3.18-59.16-default                | 5         | 7.81%   |
| 5.3.18-57-default                   | 5         | 7.81%   |
| 5.3.18-150300.59.49-default         | 5         | 7.81%   |
| 5.3.18-59.5-default                 | 2         | 3.13%   |
| 5.3.18-59.34-default                | 2         | 3.13%   |
| 5.3.18-59.24-default                | 2         | 3.13%   |
| 5.3.18-59.10-default                | 2         | 3.13%   |
| 5.3.18-150300.59.68-default         | 2         | 3.13%   |
| 5.3.18-150300.59.63-default         | 2         | 3.13%   |
| 5.3.18-150300.59.54-default         | 2         | 3.13%   |
| 5.3.18-59.34-preempt                | 1         | 1.56%   |
| 5.3.18-59.19-preempt                | 1         | 1.56%   |
| 5.3.18-59.13-default                | 1         | 1.56%   |
| 5.3.18-57-preempt                   | 1         | 1.56%   |
| 5.3.18-56-default                   | 1         | 1.56%   |
| 5.3.18-52-default                   | 1         | 1.56%   |
| 5.3.18-46-default                   | 1         | 1.56%   |
| 5.3.18-150300.59.93-default         | 1         | 1.56%   |
| 5.3.18-150300.59.87-default         | 1         | 1.56%   |
| 5.3.18-150300.59.60-default         | 1         | 1.56%   |
| 5.3.18-150300.59.43-default         | 1         | 1.56%   |
| 5.3.18-150300.59.106-default        | 1         | 1.56%   |
| 5.3.18-150300.59.101-default        | 1         | 1.56%   |
| 5.17.2-1-default                    | 1         | 1.56%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 1.56%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 1.56%   |
| 4.12.14-197.105-vanilla             | 1         | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 55        | 93.22%  |
| 5.17.2  | 1         | 1.69%   |
| 5.16.0  | 1         | 1.69%   |
| 5.15.11 | 1         | 1.69%   |
| 4.12.14 | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 55        | 93.22%  |
| 5.17    | 1         | 1.69%   |
| 5.16    | 1         | 1.69%   |
| 5.15    | 1         | 1.69%   |
| 4.12    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 25        | 40.98%  |
| GNOME      | 11        | 18.03%  |
| XFCE       | 8         | 13.11%  |
| KDE        | 8         | 13.11%  |
| X-Cinnamon | 3         | 4.92%   |
| Unknown    | 3         | 4.92%   |
| plasma5    | 1         | 1.64%   |
| MATE       | 1         | 1.64%   |
| ICEWM      | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 84.75%  |
| Wayland | 9         | 15.25%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 45%     |
| SDDM    | 15        | 25%     |
| LightDM | 14        | 23.33%  |
| XDM     | 3         | 5%      |
| GDM     | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 21        | 35.59%  |
| de_DE   | 14        | 23.73%  |
| POSIX   | 4         | 6.78%   |
| fr_FR   | 3         | 5.08%   |
| es_ES   | 3         | 5.08%   |
| ru_RU   | 2         | 3.39%   |
| pt_BR   | 2         | 3.39%   |
| it_IT   | 2         | 3.39%   |
| zh_CN   | 1         | 1.69%   |
| sv_SE   | 1         | 1.69%   |
| pt_PT   | 1         | 1.69%   |
| hu_HU   | 1         | 1.69%   |
| en_GB   | 1         | 1.69%   |
| en_DE   | 1         | 1.69%   |
| cs_CZ   | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 35        | 59.32%  |
| EFI  | 24        | 40.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 46        | 77.97%  |
| Ext4  | 12        | 20.34%  |
| Xfs   | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 46.67%  |
| Unknown | 27        | 45%     |
| MBR     | 5         | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 93.22%  |
| Yes       | 4         | 6.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 69.49%  |
| Yes       | 18        | 30.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 25.42%  |
| Dell                | 9         | 15.25%  |
| Hewlett-Packard     | 8         | 13.56%  |
| Acer                | 7         | 11.86%  |
| MSI                 | 4         | 6.78%   |
| TUXEDO              | 3         | 5.08%   |
| ASUSTek Computer    | 3         | 5.08%   |
| Sony                | 2         | 3.39%   |
| Fujitsu             | 2         | 3.39%   |
| Semp Toshiba        | 1         | 1.69%   |
| Samsung Electronics | 1         | 1.69%   |
| Notebook            | 1         | 1.69%   |
| Medion              | 1         | 1.69%   |
| HUAWEI              | 1         | 1.69%   |
| Gateway             | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                       | 2         | 3.39%   |
| TUXEDO Aura 15 Gen1                        | 1         | 1.69%   |
| Sony VPCSB15GB                             | 1         | 1.69%   |
| Sony VGN-Z570AN                            | 1         | 1.69%   |
| Semp Toshiba AS 1301                       | 1         | 1.69%   |
| Samsung 600B4B/600B5B                      | 1         | 1.69%   |
| Notebook PCx0Dx                            | 1         | 1.69%   |
| MSI Modern 15 A4M                          | 1         | 1.69%   |
| MSI GS60 6QE                               | 1         | 1.69%   |
| MSI GP63 Leopard 8RD                       | 1         | 1.69%   |
| MSI CX600                                  | 1         | 1.69%   |
| Medion E6436 MD61150                       | 1         | 1.69%   |
| Lenovo V330-15IKB 81AX                     | 1         | 1.69%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH | 1         | 1.69%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC   | 1         | 1.69%   |
| Lenovo ThinkPad T61 8895W9U                | 1         | 1.69%   |
| Lenovo ThinkPad T490s 20NYS1XK00           | 1         | 1.69%   |
| Lenovo ThinkPad T470 20HES1RB06            | 1         | 1.69%   |
| Lenovo ThinkPad T460 20FMS75800            | 1         | 1.69%   |
| Lenovo ThinkPad T450s 20BWA06J00           | 1         | 1.69%   |
| Lenovo ThinkPad T450 20BUS0EW1F            | 1         | 1.69%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00       | 1         | 1.69%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000       | 1         | 1.69%   |
| Lenovo ThinkPad E580 20KS001RGE            | 1         | 1.69%   |
| Lenovo IdeaPad 330-15IKB 81DC              | 1         | 1.69%   |
| Lenovo G500 20236                          | 1         | 1.69%   |
| Lenovo G50-45 80E3                         | 1         | 1.69%   |
| HUAWEI KLVL-WXX9                           | 1         | 1.69%   |
| HP ZBook 17 G2                             | 1         | 1.69%   |
| HP ZBook 15 G6                             | 1         | 1.69%   |
| HP Stream Notebook PC 11                   | 1         | 1.69%   |
| HP Pavilion dx6500                         | 1         | 1.69%   |
| HP OMEN by Laptop 15-dc1xxx                | 1         | 1.69%   |
| HP Notebook                                | 1         | 1.69%   |
| HP Laptop 17-ca1xxx                        | 1         | 1.69%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.69%   |
| Gateway NV54 Series                        | 1         | 1.69%   |
| Fujitsu LIFEBOOK S762                      | 1         | 1.69%   |
| Fujitsu LIFEBOOK E754                      | 1         | 1.69%   |
| Dell XPS 15 9510                           | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 11        | 18.64%  |
| Acer Aspire       | 5         | 8.47%   |
| Dell Inspiron     | 4         | 6.78%   |
| TUXEDO Pulse      | 2         | 3.39%   |
| HP ZBook          | 2         | 3.39%   |
| HP Laptop         | 2         | 3.39%   |
| Fujitsu LIFEBOOK  | 2         | 3.39%   |
| Dell Latitude     | 2         | 3.39%   |
| Acer Nitro        | 2         | 3.39%   |
| TUXEDO Aura       | 1         | 1.69%   |
| Sony VPCSB15GB    | 1         | 1.69%   |
| Sony VGN-Z570AN   | 1         | 1.69%   |
| Semp Toshiba AS   | 1         | 1.69%   |
| Samsung 600B4B    | 1         | 1.69%   |
| Notebook PCx0Dx   | 1         | 1.69%   |
| MSI Modern        | 1         | 1.69%   |
| MSI GS60          | 1         | 1.69%   |
| MSI GP63          | 1         | 1.69%   |
| MSI CX600         | 1         | 1.69%   |
| Medion E6436      | 1         | 1.69%   |
| Lenovo V330-15IKB | 1         | 1.69%   |
| Lenovo IdeaPad    | 1         | 1.69%   |
| Lenovo G500       | 1         | 1.69%   |
| Lenovo G50-45     | 1         | 1.69%   |
| HUAWEI KLVL-WXX9  | 1         | 1.69%   |
| HP Stream         | 1         | 1.69%   |
| HP Pavilion       | 1         | 1.69%   |
| HP OMEN           | 1         | 1.69%   |
| HP Notebook       | 1         | 1.69%   |
| Gateway NV54      | 1         | 1.69%   |
| Dell XPS          | 1         | 1.69%   |
| Dell System       | 1         | 1.69%   |
| Dell Precision    | 1         | 1.69%   |
| ASUS ZenBook      | 1         | 1.69%   |
| ASUS VivoBook     | 1         | 1.69%   |
| ASUS G771JW       | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 13.56%  |
| 2017 | 7         | 11.86%  |
| 2019 | 6         | 10.17%  |
| 2012 | 6         | 10.17%  |
| 2018 | 5         | 8.47%   |
| 2015 | 5         | 8.47%   |
| 2014 | 4         | 6.78%   |
| 2021 | 3         | 5.08%   |
| 2016 | 3         | 5.08%   |
| 2011 | 3         | 5.08%   |
| 2013 | 2         | 3.39%   |
| 2010 | 2         | 3.39%   |
| 2009 | 2         | 3.39%   |
| 2007 | 2         | 3.39%   |
| 2008 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 59        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 51        | 86.44%  |
| Enabled  | 8         | 13.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 25.42%  |
| 8.01-16.0   | 13        | 22.03%  |
| 16.01-24.0  | 12        | 20.34%  |
| 3.01-4.0    | 11        | 18.64%  |
| 32.01-64.0  | 4         | 6.78%   |
| 1.01-2.0    | 2         | 3.39%   |
| 2.01-3.0    | 1         | 1.69%   |
| 64.01-256.0 | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 38.33%  |
| 1.01-2.0  | 17        | 28.33%  |
| 4.01-8.0  | 13        | 21.67%  |
| 3.01-4.0  | 5         | 8.33%   |
| 8.01-16.0 | 1         | 1.67%   |
| 0.51-1.0  | 1         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 62.71%  |
| 2      | 22        | 37.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 61.02%  |
| Yes       | 23        | 38.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 88.14%  |
| No        | 7         | 11.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 98.31%  |
| No        | 1         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 73.33%  |
| No        | 16        | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 14        | 23.73%  |
| Brazil      | 6         | 10.17%  |
| USA         | 5         | 8.47%   |
| France      | 5         | 8.47%   |
| Spain       | 2         | 3.39%   |
| Russia      | 2         | 3.39%   |
| Nicaragua   | 2         | 3.39%   |
| Italy       | 2         | 3.39%   |
| India       | 2         | 3.39%   |
| Greece      | 2         | 3.39%   |
| Czechia     | 2         | 3.39%   |
| UK          | 1         | 1.69%   |
| Thailand    | 1         | 1.69%   |
| Switzerland | 1         | 1.69%   |
| Sweden      | 1         | 1.69%   |
| Sudan       | 1         | 1.69%   |
| Romania     | 1         | 1.69%   |
| Portugal    | 1         | 1.69%   |
| Netherlands | 1         | 1.69%   |
| Mexico      | 1         | 1.69%   |
| Hungary     | 1         | 1.69%   |
| China       | 1         | 1.69%   |
| Canada      | 1         | 1.69%   |
| Bulgaria    | 1         | 1.69%   |
| Belgium     | 1         | 1.69%   |
| Austria     | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sao Paulo           | 3         | 4.76%   |
| Managua             | 2         | 3.17%   |
| Lehrte              | 2         | 3.17%   |
| Halle               | 2         | 3.17%   |
| Berlin              | 2         | 3.17%   |
| Zurich              | 1         | 1.59%   |
| Weilheim            | 1         | 1.59%   |
| Vienna              | 1         | 1.59%   |
| Vaennaes            | 1         | 1.59%   |
| Udine               | 1         | 1.59%   |
| The Hague           | 1         | 1.59%   |
| Teresina            | 1         | 1.59%   |
| Sofia               | 1         | 1.59%   |
| Seclin              | 1         | 1.59%   |
| Saalfeld            | 1         | 1.59%   |
| Rockville           | 1         | 1.59%   |
| Prague              | 1         | 1.59%   |
| Phuket              | 1         | 1.59%   |
| Petrozavodsk        | 1         | 1.59%   |
| Peine               | 1         | 1.59%   |
| Paris               | 1         | 1.59%   |
| Palm Bay            | 1         | 1.59%   |
| Moscow              | 1         | 1.59%   |
| Montreal            | 1         | 1.59%   |
| Monterrey           | 1         | 1.59%   |
| Moelan-sur-Mer      | 1         | 1.59%   |
| León               | 1         | 1.59%   |
| Leiria              | 1         | 1.59%   |
| Kostelec nad Orlici | 1         | 1.59%   |
| Khartoum            | 1         | 1.59%   |
| Kesztolc            | 1         | 1.59%   |
| Islington           | 1         | 1.59%   |
| Irun                | 1         | 1.59%   |
| Ilsfeld             | 1         | 1.59%   |
| Houilles            | 1         | 1.59%   |
| Heraklion           | 1         | 1.59%   |
| Guangzhou           | 1         | 1.59%   |
| Gevelsberg          | 1         | 1.59%   |
| Garden Grove        | 1         | 1.59%   |
| Frankfurt am Main   | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 16.88%  |
| WDC                 | 10        | 10     | 12.99%  |
| Kingston            | 10        | 12     | 12.99%  |
| Seagate             | 8         | 11     | 10.39%  |
| SanDisk             | 6         | 6      | 7.79%   |
| Toshiba             | 4         | 5      | 5.19%   |
| SK hynix            | 4         | 4      | 5.19%   |
| Hitachi             | 4         | 5      | 5.19%   |
| Unknown             | 3         | 3      | 3.9%    |
| HGST                | 3         | 5      | 3.9%    |
| Silicon Motion      | 2         | 2      | 2.6%    |
| Micron Technology   | 2         | 2      | 2.6%    |
| Crucial             | 2         | 2      | 2.6%    |
| Plextor             | 1         | 2      | 1.3%    |
| Phison              | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Intenso             | 1         | 1      | 1.3%    |
| Fujitsu             | 1         | 1      | 1.3%    |
| China               | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2.6%    |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2.6%    |
| Kingston NVMe SSD Drive 500GB         | 2         | 2.6%    |
| HGST HTS721010A9E630 1TB              | 2         | 2.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1.3%    |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1.3%    |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1.3%    |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1         | 1.3%    |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1.3%    |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1.3%    |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1.3%    |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.3%    |
| WDC WD10SPZX-17Z10T0 1TB              | 1         | 1.3%    |
| WDC PC SN730 SDBPNTY-512G-1006 512GB  | 1         | 1.3%    |
| Unknown USD00  256GB                  | 1         | 1.3%    |
| Unknown SC16G  16GB                   | 1         | 1.3%    |
| Unknown DA4064  64GB                  | 1         | 1.3%    |
| Toshiba THNSNJ256G8NU 256GB SSD       | 1         | 1.3%    |
| Toshiba MQ04ABF100 1TB                | 1         | 1.3%    |
| Toshiba MQ01ABD075 752GB              | 1         | 1.3%    |
| Toshiba MK3261GSYD 320GB              | 1         | 1.3%    |
| SK hynix HFM512GD3JX013N 512GB        | 1         | 1.3%    |
| SK hynix HBG4e  32GB                  | 1         | 1.3%    |
| Seagate ST9320325AS 320GB             | 1         | 1.3%    |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1.3%    |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1.3%    |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1.3%    |
| SanDisk SSD U100 128GB                | 1         | 1.3%    |
| SanDisk SSD PLUS 1000GB               | 1         | 1.3%    |
| SanDisk SDSSDH3 1T00 1TB              | 1         | 1.3%    |
| SanDisk SD9SN8W256G 256GB SSD         | 1         | 1.3%    |
| SanDisk SD8TB8U512G1001 512GB SSD     | 1         | 1.3%    |
| SanDisk SD6SB1M128G1022I 128GB SSD    | 1         | 1.3%    |
| Samsung SSD 970 EVO 1TB               | 1         | 1.3%    |
| Samsung SSD 860 EVO 1TB               | 1         | 1.3%    |
| Samsung SSD 850 EVO 250GB             | 1         | 1.3%    |
| Samsung PM9A1 NVMe 1024GB             | 1         | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 29.63%  |
| Seagate | 8         | 11     | 29.63%  |
| Hitachi | 4         | 5      | 14.81%  |
| Toshiba | 3         | 4      | 11.11%  |
| HGST    | 3         | 5      | 11.11%  |
| Fujitsu | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 24%     |
| Kingston            | 6         | 8      | 24%     |
| Samsung Electronics | 4         | 4      | 16%     |
| SK hynix            | 2         | 2      | 8%      |
| WDC                 | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| Plextor             | 1         | 2      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Intenso             | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| China               | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 34     | 33.78%  |
| SSD  | 24        | 28     | 32.43%  |
| NVMe | 21        | 25     | 28.38%  |
| MMC  | 4         | 4      | 5.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 61     | 60.61%  |
| NVMe | 21        | 25     | 31.82%  |
| MMC  | 4         | 4      | 6.06%   |
| SAS  | 1         | 1      | 1.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 38     | 61.22%  |
| 0.51-1.0   | 18        | 23     | 36.73%  |
| 1.01-2.0   | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 15        | 25%     |
| More than 3000 | 13        | 21.67%  |
| 2001-3000      | 11        | 18.33%  |
| 501-1000       | 9         | 15%     |
| 251-500        | 6         | 10%     |
| 51-100         | 4         | 6.67%   |
| 101-250        | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 20%     |
| 251-500        | 11        | 16.92%  |
| 51-100         | 11        | 16.92%  |
| 501-1000       | 9         | 13.85%  |
| 1001-2000      | 7         | 10.77%  |
| 21-50          | 4         | 6.15%   |
| 2001-3000      | 4         | 6.15%   |
| 1-20           | 4         | 6.15%   |
| More than 3000 | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 20%     |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 20%     |
| Seagate ST9320325AS 320GB             | 1         | 1      | 20%     |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 20%     |
| Phison 311CD0512GB                    | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 40%     |
| WDC      | 1         | 1      | 20%     |
| SK hynix | 1         | 1      | 20%     |
| Phison   | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 31        | 53     | 48.44%  |
| Works    | 28        | 33     | 43.75%  |
| Malfunc  | 5         | 5      | 7.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 57.14%  |
| Samsung Electronics              | 9         | 12.86%  |
| AMD                              | 7         | 10%     |
| Kingston Technology Company      | 4         | 5.71%   |
| Silicon Motion                   | 2         | 2.86%   |
| Micron Technology                | 2         | 2.86%   |
| SK hynix                         | 1         | 1.43%   |
| Silicon Integrated Systems [SiS] | 1         | 1.43%   |
| SanDisk                          | 1         | 1.43%   |
| Phison Electronics               | 1         | 1.43%   |
| Micron/Crucial Technology        | 1         | 1.43%   |
| Lite-On Technology               | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 13.7%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 8.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 4.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 4.11%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.74%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.74%   |
| Micron NVMe Storage Controller                                                 | 2         | 2.74%   |
| Kingston Company NVMe Controller                                               | 2         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.37%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.37%   |
| Lite-On SATA controller                                                        | 1         | 1.37%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.37%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 60.56%  |
| NVMe | 21        | 29.58%  |
| IDE  | 4         | 5.63%   |
| RAID | 3         | 4.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 79.66%  |
| AMD    | 12        | 20.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 5.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 5.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 3.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 3.39%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 3.39%   |
| Intel Xeon E-2286M CPU @ 2.40GHz            | 1         | 1.69%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.69%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.69%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.69%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.69%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.69%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.69%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.69%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.69%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.69%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.69%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 33.9%   |
| Intel Core i7           | 13        | 22.03%  |
| AMD Ryzen 7             | 5         | 8.47%   |
| Intel Core i3           | 4         | 6.78%   |
| Intel Core 2 Duo        | 3         | 5.08%   |
| Other                   | 2         | 3.39%   |
| Intel Pentium Dual-Core | 2         | 3.39%   |
| Intel Celeron           | 2         | 3.39%   |
| AMD Ryzen 5             | 2         | 3.39%   |
| AMD A6                  | 2         | 3.39%   |
| Intel Xeon              | 1         | 1.69%   |
| AMD Ryzen 7 PRO         | 1         | 1.69%   |
| AMD Ryzen 3             | 1         | 1.69%   |
| AMD C-50                | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 52.54%  |
| 4      | 15        | 25.42%  |
| 8      | 9         | 15.25%  |
| 6      | 4         | 6.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 74.58%  |
| 1      | 15        | 25.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 36.67%  |
| 0x806e9    | 4         | 6.67%   |
| 0x406e3    | 4         | 6.67%   |
| 0x906ea    | 3         | 5%      |
| 0x206a7    | 3         | 5%      |
| 0x08600106 | 3         | 5%      |
| 0x6fd      | 2         | 3.33%   |
| 0x506e3    | 2         | 3.33%   |
| 0x306d4    | 2         | 3.33%   |
| 0x906ed    | 1         | 1.67%   |
| 0x806ec    | 1         | 1.67%   |
| 0x806ea    | 1         | 1.67%   |
| 0x806d1    | 1         | 1.67%   |
| 0x806c1    | 1         | 1.67%   |
| 0x706a1    | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x306a9    | 1         | 1.67%   |
| 0x30678    | 1         | 1.67%   |
| 0x20655    | 1         | 1.67%   |
| 0x1067a    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x0a50000c | 1         | 1.67%   |
| 0x08108109 | 1         | 1.67%   |
| 0x07030105 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 25.42%  |
| Zen 2         | 6         | 10.17%  |
| Skylake       | 6         | 10.17%  |
| SandyBridge   | 4         | 6.78%   |
| IvyBridge     | 4         | 6.78%   |
| Haswell       | 4         | 6.78%   |
| Penryn        | 3         | 5.08%   |
| Zen+          | 2         | 3.39%   |
| Westmere      | 2         | 3.39%   |
| Core          | 2         | 3.39%   |
| Broadwell     | 2         | 3.39%   |
| Zen 3         | 1         | 1.69%   |
| TigerLake     | 1         | 1.69%   |
| Silvermont    | 1         | 1.69%   |
| Puma          | 1         | 1.69%   |
| K10 Llano     | 1         | 1.69%   |
| Icelake       | 1         | 1.69%   |
| Goldmont plus | 1         | 1.69%   |
| CometLake     | 1         | 1.69%   |
| Bobcat        | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 56.79%  |
| AMD    | 19        | 23.46%  |
| Nvidia | 16        | 19.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                            | 6         | 7.23%   |
| Intel HD Graphics 620                                                                 | 5         | 6.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 6.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 4.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 4.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 3.61%   |
| Intel UHD Graphics 620                                                                | 2         | 2.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 2.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 2.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 2         | 2.41%   |
| Intel HD Graphics 5500                                                                | 2         | 2.41%   |
| Intel HD Graphics 530                                                                 | 2         | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 2.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.2%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.2%    |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1.2%    |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                            | 1         | 1.2%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.2%    |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 1.2%    |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.2%    |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.2%    |
| Intel HD Graphics 630                                                                 | 1         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.2%    |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.2%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 42.37%  |
| Intel + Nvidia | 15        | 25.42%  |
| 1 x AMD        | 13        | 22.03%  |
| Intel + AMD    | 6         | 10.17%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 88.14%  |
| Proprietary | 6         | 10.17%  |
| Unknown     | 1         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 73.33%  |
| 0.01-0.5   | 6         | 10%     |
| 3.01-4.0   | 4         | 6.67%   |
| 1.01-2.0   | 4         | 6.67%   |
| 7.01-8.0   | 1         | 1.67%   |
| 0.51-1.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 16        | 23.19%  |
| Chimei Innolux      | 13        | 18.84%  |
| AU Optronics        | 11        | 15.94%  |
| Samsung Electronics | 6         | 8.7%    |
| Goldstar            | 4         | 5.8%    |
| BOE                 | 4         | 5.8%    |
| Philips             | 2         | 2.9%    |
| Lenovo              | 2         | 2.9%    |
| Hewlett-Packard     | 2         | 2.9%    |
| Sony                | 1         | 1.45%   |
| Sharp               | 1         | 1.45%   |
| Sceptre Tech        | 1         | 1.45%   |
| LG Philips          | 1         | 1.45%   |
| InfoVision          | 1         | 1.45%   |
| Iiyama              | 1         | 1.45%   |
| Dell                | 1         | 1.45%   |
| CSO                 | 1         | 1.45%   |
| CPT                 | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 2.86%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch            | 2         | 2.86%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2         | 2.86%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 2         | 2.86%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch   | 1         | 1.43%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 1.43%   |
| Sceptre Tech Sceptre E19 SPT07A8 1366x768 575x323mm 26.0-inch          | 1         | 1.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC324E 1600x900 309x174mm 14.0-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 1.43%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch                | 1         | 1.43%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1         | 1.43%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch            | 1         | 1.43%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch            | 1         | 1.43%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch               | 1         | 1.43%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                | 1         | 1.43%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch           | 1         | 1.43%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                   | 1         | 1.43%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 1         | 1.43%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch               | 1         | 1.43%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                       | 1         | 1.43%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                  | 1         | 1.43%   |
| CPT LCD Monitor CPT17D8 1366x768 293x165mm 13.2-inch                   | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 31        | 49.21%  |
| 1366x768 (WXGA)   | 16        | 25.4%   |
| 1600x900 (HD+)    | 4         | 6.35%   |
| 1920x1200 (WUXGA) | 3         | 4.76%   |
| 3840x2160 (4K)    | 2         | 3.17%   |
| 2560x1080         | 2         | 3.17%   |
| 3840x2400         | 1         | 1.59%   |
| 2560x1440 (QHD)   | 1         | 1.59%   |
| 2160x1440         | 1         | 1.59%   |
| 1280x800 (WXGA)   | 1         | 1.59%   |
| 1024x768 (XGA)    | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 28        | 40%     |
| 14     | 11        | 15.71%  |
| 17     | 9         | 12.86%  |
| 13     | 6         | 8.57%   |
| 27     | 3         | 4.29%   |
| 34     | 2         | 2.86%   |
| 26     | 2         | 2.86%   |
| 24     | 2         | 2.86%   |
| 18     | 2         | 2.86%   |
| 11     | 2         | 2.86%   |
| 84     | 1         | 1.43%   |
| 23     | 1         | 1.43%   |
| 21     | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 57.14%  |
| 351-400     | 10        | 14.29%  |
| 501-600     | 7         | 10%     |
| 201-300     | 6         | 8.57%   |
| 401-500     | 3         | 4.29%   |
| 701-800     | 2         | 2.86%   |
| 601-700     | 1         | 1.43%   |
| 1501-2000   | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 52        | 86.67%  |
| 16/10 | 4         | 6.67%   |
| 21/9  | 2         | 3.33%   |
| 4/3   | 1         | 1.67%   |
| 3/2   | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 40%     |
| 81-90          | 14        | 20%     |
| 121-130        | 9         | 12.86%  |
| 301-350        | 4         | 5.71%   |
| 201-250        | 4         | 5.71%   |
| 71-80          | 2         | 2.86%   |
| 51-60          | 2         | 2.86%   |
| 351-500        | 2         | 2.86%   |
| 141-150        | 2         | 2.86%   |
| More than 1000 | 1         | 1.43%   |
| 251-300        | 1         | 1.43%   |
| 91-100         | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 46.38%  |
| 101-120       | 19        | 27.54%  |
| 51-100        | 14        | 20.29%  |
| More than 240 | 2         | 2.9%    |
| 161-240       | 2         | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 76.67%  |
| 2     | 13        | 21.67%  |
| 0     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 39.58%  |
| Realtek Semiconductor            | 29        | 30.21%  |
| Qualcomm Atheros                 | 12        | 12.5%   |
| Broadcom                         | 6         | 6.25%   |
| Broadcom Limited                 | 2         | 2.08%   |
| Silicon Integrated Systems [SiS] | 1         | 1.04%   |
| Sierra Wireless                  | 1         | 1.04%   |
| Samsung Electronics              | 1         | 1.04%   |
| Ralink                           | 1         | 1.04%   |
| Manta                            | 1         | 1.04%   |
| Lenovo                           | 1         | 1.04%   |
| DisplayLink                      | 1         | 1.04%   |
| Dell                             | 1         | 1.04%   |
| ASIX Electronics                 | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 17.09%  |
| Intel Wi-Fi 6 AX200                                               | 7         | 5.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.42%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.42%   |
| Intel Wireless 8260                                               | 3         | 2.56%   |
| Intel Wireless 3165                                               | 3         | 2.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.71%   |
| Intel Wireless 7265                                               | 2         | 1.71%   |
| Intel Wireless 7260                                               | 2         | 1.71%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.85%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.85%   |
| Samsung Kiera                                                     | 1         | 0.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.85%   |
| Manta MM812                                                       | 1         | 0.85%   |
| Lenovo OneLink+ Giga                                              | 1         | 0.85%   |
| Intel WiFi Link 5100                                              | 1         | 0.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 58.33%  |
| Realtek Semiconductor | 9         | 15%     |
| Qualcomm Atheros      | 8         | 13.33%  |
| Broadcom              | 5         | 8.33%   |
| Sierra Wireless       | 1         | 1.67%   |
| Ralink                | 1         | 1.67%   |
| Dell                  | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 7         | 11.67%  |
| Intel Wireless 8265 / 8275                                     | 4         | 6.67%   |
| Intel Wireless 8260                                            | 3         | 5%      |
| Intel Wireless 3165                                            | 3         | 5%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.33%   |
| Intel Wireless 7265                                            | 2         | 3.33%   |
| Intel Wireless 7260                                            | 2         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.33%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| Intel WiFi Link 5100                                           | 1         | 1.67%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.67%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.67%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.67%   |
| Broadcom BCM43227 802.11b/g/n                                  | 1         | 1.67%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 43.64%  |
| Intel                            | 17        | 30.91%  |
| Qualcomm Atheros                 | 5         | 9.09%   |
| Broadcom Limited                 | 2         | 3.64%   |
| Broadcom                         | 2         | 3.64%   |
| Silicon Integrated Systems [SiS] | 1         | 1.82%   |
| Samsung Electronics              | 1         | 1.82%   |
| Lenovo                           | 1         | 1.82%   |
| DisplayLink                      | 1         | 1.82%   |
| ASIX Electronics                 | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 3.57%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.79%   |
| Samsung Kiera                                                     | 1         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.79%   |
| Lenovo OneLink+ Giga                                              | 1         | 1.79%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.79%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1         | 1.79%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 52.25%  |
| Ethernet | 52        | 46.85%  |
| Unknown  | 1         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 71.43%  |
| Ethernet | 18        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 49        | 83.05%  |
| 1     | 9         | 15.25%  |
| 3     | 1         | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 70%     |
| Yes  | 18        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 46.67%  |
| Realtek Semiconductor           | 6         | 13.33%  |
| Qualcomm Atheros Communications | 4         | 8.89%   |
| IMC Networks                    | 3         | 6.67%   |
| Foxconn / Hon Hai               | 3         | 6.67%   |
| Lite-On Technology              | 2         | 4.44%   |
| Broadcom                        | 2         | 4.44%   |
| Realtek                         | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| Alps Electric                   | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 9         | 20%     |
| Intel AX200 Bluetooth                                                               | 6         | 13.33%  |
| Realtek Bluetooth Radio                                                             | 3         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 4.44%   |
| Intel AX201 Bluetooth                                                               | 2         | 4.44%   |
| IMC Networks Bluetooth Device                                                       | 2         | 4.44%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 2.22%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.22%   |
| Lite-On Bluetooth Device                                                            | 1         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.22%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 2.22%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 2.22%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.22%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 2.22%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 2.22%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 63.89%  |
| AMD                              | 13        | 18.06%  |
| Nvidia                           | 5         | 6.94%   |
| Logitech                         | 2         | 2.78%   |
| Lenovo                           | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] | 1         | 1.39%   |
| JMTek                            | 1         | 1.39%   |
| GN Netcom                        | 1         | 1.39%   |
| ESS Technology                   | 1         | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 12.5%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 9.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 7.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 5.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.27%   |
| Logitech Headset H390                                                      | 2         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.27%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.27%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.27%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 1.14%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.14%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 1.14%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 1.14%   |
| JMTek audio controller                                                     | 1         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.14%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 1.14%   |
| ESS Technology Asus USB DAC                                                | 1         | 1.14%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.14%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.14%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 31.71%  |
| Samsung Electronics | 13        | 31.71%  |
| Unknown             | 4         | 9.76%   |
| Micron Technology   | 3         | 7.32%   |
| Kingston            | 2         | 4.88%   |
| Smart               | 1         | 2.44%   |
| Ramaxel Technology  | 1         | 2.44%   |
| Goodram             | 1         | 2.44%   |
| Crucial             | 1         | 2.44%   |
| Corsair             | 1         | 2.44%   |
| A-DATA Technology   | 1         | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 2         | 4.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 4.44%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                  | 1         | 2.22%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                   | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 2.22%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                   | 1         | 2.22%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s       | 1         | 2.22%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 2.22%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM 2048MT/s  | 1         | 2.22%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 2.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s   | 1         | 2.22%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 2.22%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 1         | 2.22%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 1         | 2.22%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s  | 1         | 2.22%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s    | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 2.22%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s      | 1         | 2.22%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 2.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.22%   |
| Samsung RAM K4F6E3S4HM-MGCJ 2GB SODIMM LPDDR4 3733MT/s      | 1         | 2.22%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s      | 1         | 2.22%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s        | 1         | 2.22%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Micron RAM 8ATF51264HZ-2G1B1 8GB SODIMM DDR4 2667MT/s       | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 1         | 2.22%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 2.22%   |
| Kingston RAM MSI26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s       | 1         | 2.22%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 2.22%   |
| Goodram RAM IR2400S464L15S/8G 8192MB SODIMM DDR4 2133MT/s   | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 18        | 47.37%  |
| DDR3    | 11        | 28.95%  |
| LPDDR4  | 4         | 10.53%  |
| DDR2    | 2         | 5.26%   |
| SDRAM   | 1         | 2.63%   |
| LPDDR3  | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 92.11%  |
| Row Of Chips | 2         | 5.26%   |
| Chip         | 1         | 2.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 38.1%   |
| 4096  | 12        | 28.57%  |
| 2048  | 6         | 14.29%  |
| 16384 | 5         | 11.9%   |
| 1024  | 2         | 4.76%   |
| 32768 | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 11        | 27.5%   |
| 1600    | 8         | 20%     |
| 3200    | 5         | 12.5%   |
| 2133    | 3         | 7.5%    |
| 1333    | 2         | 5%      |
| 667     | 2         | 5%      |
| 4267    | 1         | 2.5%    |
| 4266    | 1         | 2.5%    |
| 3733    | 1         | 2.5%    |
| 2400    | 1         | 2.5%    |
| 2048    | 1         | 2.5%    |
| 1867    | 1         | 2.5%    |
| 1334    | 1         | 2.5%    |
| 1067    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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
| Chicony Electronics                    | 15        | 27.78%  |
| Acer                                   | 7         | 12.96%  |
| Sunplus Innovation Technology          | 5         | 9.26%   |
| Realtek Semiconductor                  | 5         | 9.26%   |
| Quanta                                 | 4         | 7.41%   |
| IMC Networks                           | 4         | 7.41%   |
| Microdia                               | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Syntek                                 | 1         | 1.85%   |
| Suyin                                  | 1         | 1.85%   |
| Silicon Motion                         | 1         | 1.85%   |
| Ricoh                                  | 1         | 1.85%   |
| Luxvisions Innotech Limited            | 1         | 1.85%   |
| Lite-On Technology                     | 1         | 1.85%   |
| Bison Electronics                      | 1         | 1.85%   |
| ALi                                    | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 6         | 10.91%  |
| Realtek Integrated_Webcam_HD                                             | 3         | 5.45%   |
| Sunplus HD WebCam                                                        | 2         | 3.64%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 3.64%   |
| Chicony Integrated IR Camera                                             | 2         | 3.64%   |
| Acer HD Webcam                                                           | 2         | 3.64%   |
| Acer BisonCam,NB Pro                                                     | 2         | 3.64%   |
| Acer BisonCam, NB Pro                                                    | 2         | 3.64%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_HD                                      | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 1.82%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 1.82%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 1.82%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 1.82%   |
| Realtek USB Camera                                                       | 1         | 1.82%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.82%   |
| Realtek Laptop_Integrated_Webcam_HD                                      | 1         | 1.82%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 1.82%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 1.82%   |
| Quanta HD Webcam                                                         | 1         | 1.82%   |
| Quanta HD User Facing                                                    | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                   | 1         | 1.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.82%   |
| Lite-On Integrated Camera                                                | 1         | 1.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.82%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 1.82%   |
| IMC Networks Integrated Camera                                           | 1         | 1.82%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 1.82%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.82%   |
| Chicony Integrated Camera (1280x720@30)                                  | 1         | 1.82%   |
| Chicony HP TrueVision HD                                                 | 1         | 1.82%   |
| Chicony HD WebCam                                                        | 1         | 1.82%   |
| Chicony FJ Camera                                                        | 1         | 1.82%   |
| Chicony EasyCamera                                                       | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.82%   |
| Bison Integrated Camera                                                  | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 42.86%  |
| Validity Sensors           | 5         | 35.71%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics WBDI                                         | 1         | 7.14%   |
| Synaptics  WBDI                                        | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 7.14%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 2         | 28.57%  |
| Broadcom              | 2         | 28.57%  |
| Alcor Micro           | 2         | 28.57%  |
| Gemalto (was Gemplus) | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader               | 2         | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 14.29%  |
| Broadcom 5880                                     | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 33        | 55%     |
| 1     | 21        | 35%     |
| 2     | 6         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 41.18%  |
| Chipcard              | 8         | 23.53%  |
| Graphics card         | 4         | 11.76%  |
| Multimedia controller | 3         | 8.82%   |
| Net/wireless          | 2         | 5.88%   |
| Net/ethernet          | 1         | 2.94%   |
| Camera                | 1         | 2.94%   |
| Bluetooth             | 1         | 2.94%   |

