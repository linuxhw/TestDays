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

Total: 85

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.3.18-59.27-default                | 8         | 13.79%  |
| 5.3.18-59.37-default                | 5         | 8.62%   |
| 5.3.18-59.19-default                | 5         | 8.62%   |
| 5.3.18-59.16-default                | 5         | 8.62%   |
| 5.3.18-57-default                   | 5         | 8.62%   |
| 5.3.18-150300.59.49-default         | 4         | 6.9%    |
| 5.3.18-59.5-default                 | 2         | 3.45%   |
| 5.3.18-59.34-default                | 2         | 3.45%   |
| 5.3.18-59.24-default                | 2         | 3.45%   |
| 5.3.18-59.10-default                | 2         | 3.45%   |
| 5.3.18-150300.59.63-default         | 2         | 3.45%   |
| 5.3.18-150300.59.54-default         | 2         | 3.45%   |
| 5.3.18-59.34-preempt                | 1         | 1.72%   |
| 5.3.18-59.19-preempt                | 1         | 1.72%   |
| 5.3.18-59.13-default                | 1         | 1.72%   |
| 5.3.18-57-preempt                   | 1         | 1.72%   |
| 5.3.18-56-default                   | 1         | 1.72%   |
| 5.3.18-52-default                   | 1         | 1.72%   |
| 5.3.18-46-default                   | 1         | 1.72%   |
| 5.3.18-150300.59.68-default         | 1         | 1.72%   |
| 5.3.18-150300.59.60-default         | 1         | 1.72%   |
| 5.3.18-150300.59.43-default         | 1         | 1.72%   |
| 5.17.2-1-default                    | 1         | 1.72%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 1.72%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 1.72%   |
| 4.12.14-197.105-vanilla             | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 50        | 92.59%  |
| 5.17.2  | 1         | 1.85%   |
| 5.16.0  | 1         | 1.85%   |
| 5.15.11 | 1         | 1.85%   |
| 4.12.14 | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 50        | 92.59%  |
| 5.17    | 1         | 1.85%   |
| 5.16    | 1         | 1.85%   |
| 5.15    | 1         | 1.85%   |
| 4.12    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 22        | 39.29%  |
| GNOME      | 10        | 17.86%  |
| XFCE       | 8         | 14.29%  |
| KDE        | 8         | 14.29%  |
| Unknown    | 3         | 5.36%   |
| X-Cinnamon | 2         | 3.57%   |
| plasma5    | 1         | 1.79%   |
| MATE       | 1         | 1.79%   |
| ICEWM      | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 45        | 83.33%  |
| Wayland | 9         | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 41.82%  |
| SDDM    | 15        | 27.27%  |
| LightDM | 14        | 25.45%  |
| XDM     | 2         | 3.64%   |
| GDM     | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 19        | 35.19%  |
| de_DE   | 13        | 24.07%  |
| POSIX   | 4         | 7.41%   |
| fr_FR   | 3         | 5.56%   |
| ru_RU   | 2         | 3.7%    |
| pt_BR   | 2         | 3.7%    |
| es_ES   | 2         | 3.7%    |
| zh_CN   | 1         | 1.85%   |
| sv_SE   | 1         | 1.85%   |
| pt_PT   | 1         | 1.85%   |
| it_IT   | 1         | 1.85%   |
| hu_HU   | 1         | 1.85%   |
| en_GB   | 1         | 1.85%   |
| en_DE   | 1         | 1.85%   |
| cs_CZ   | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 57.41%  |
| EFI  | 23        | 42.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 41        | 75.93%  |
| Ext4  | 12        | 22.22%  |
| Xfs   | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 27        | 49.09%  |
| Unknown | 23        | 41.82%  |
| MBR     | 5         | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 92.59%  |
| Yes       | 4         | 7.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 66.67%  |
| Yes       | 18        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 25.93%  |
| Dell                | 9         | 16.67%  |
| Hewlett-Packard     | 7         | 12.96%  |
| Acer                | 7         | 12.96%  |
| MSI                 | 4         | 7.41%   |
| ASUSTek Computer    | 3         | 5.56%   |
| TUXEDO              | 2         | 3.7%    |
| Sony                | 2         | 3.7%    |
| Fujitsu             | 2         | 3.7%    |
| Semp Toshiba        | 1         | 1.85%   |
| Samsung Electronics | 1         | 1.85%   |
| Medion              | 1         | 1.85%   |
| HUAWEI              | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                        | 1         | 1.85%   |
| TUXEDO Aura 15 Gen1                         | 1         | 1.85%   |
| Sony VPCSB15GB                              | 1         | 1.85%   |
| Sony VGN-Z570AN                             | 1         | 1.85%   |
| Semp Toshiba AS 1301                        | 1         | 1.85%   |
| Samsung 600B4B/600B5B                       | 1         | 1.85%   |
| MSI Modern 15 A4M                           | 1         | 1.85%   |
| MSI GS60 6QE                                | 1         | 1.85%   |
| MSI GP63 Leopard 8RD                        | 1         | 1.85%   |
| MSI CX600                                   | 1         | 1.85%   |
| Medion E6436 MD61150                        | 1         | 1.85%   |
| Lenovo V330-15IKB 81AX                      | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH  | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC    | 1         | 1.85%   |
| Lenovo ThinkPad T61 8895W9U                 | 1         | 1.85%   |
| Lenovo ThinkPad T490s 20NYS1XK00            | 1         | 1.85%   |
| Lenovo ThinkPad T470 20HES1RB06             | 1         | 1.85%   |
| Lenovo ThinkPad T460 20FMS75800             | 1         | 1.85%   |
| Lenovo ThinkPad T450s 20BWA06J00            | 1         | 1.85%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00        | 1         | 1.85%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000        | 1         | 1.85%   |
| Lenovo ThinkPad E580 20KS001RGE             | 1         | 1.85%   |
| Lenovo IdeaPad 330-15IKB 81DC               | 1         | 1.85%   |
| Lenovo G500 20236                           | 1         | 1.85%   |
| Lenovo G50-45 80E3                          | 1         | 1.85%   |
| HUAWEI KLVL-WXX9                            | 1         | 1.85%   |
| HP ZBook 17 G2                              | 1         | 1.85%   |
| HP Stream Notebook PC 11                    | 1         | 1.85%   |
| HP Pavilion dx6500                          | 1         | 1.85%   |
| HP OMEN by Laptop 15-dc1xxx                 | 1         | 1.85%   |
| HP Notebook                                 | 1         | 1.85%   |
| HP Laptop 17-ca1xxx                         | 1         | 1.85%   |
| HP Laptop 15s-eq0xxx                        | 1         | 1.85%   |
| Fujitsu LIFEBOOK S762                       | 1         | 1.85%   |
| Fujitsu LIFEBOOK E754                       | 1         | 1.85%   |
| Dell XPS 15 9510                            | 1         | 1.85%   |
| Dell System Inspiron N7110                  | 1         | 1.85%   |
| Dell Precision M6700                        | 1         | 1.85%   |
| Dell Latitude E7470                         | 1         | 1.85%   |
| Dell Latitude 5480                          | 1         | 1.85%   |
| Dell Inspiron N4030                         | 1         | 1.85%   |
| Dell Inspiron 7460                          | 1         | 1.85%   |
| Dell Inspiron 3521                          | 1         | 1.85%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 1.85%   |
| ASUS ZenBook UX325SA_UM325SA                | 1         | 1.85%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA | 1         | 1.85%   |
| ASUS G771JW                                 | 1         | 1.85%   |
| Acer Nitro AN515-54                         | 1         | 1.85%   |
| Acer Nitro AN515-52                         | 1         | 1.85%   |
| Acer Aspire VN7-792G                        | 1         | 1.85%   |
| Acer Aspire E1-772G                         | 1         | 1.85%   |
| Acer Aspire E1-571                          | 1         | 1.85%   |
| Acer Aspire 5820TG                          | 1         | 1.85%   |
| Acer Aspire 5560                            | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 18.52%  |
| Acer Aspire       | 5         | 9.26%   |
| Dell Inspiron     | 4         | 7.41%   |
| HP Laptop         | 2         | 3.7%    |
| Fujitsu LIFEBOOK  | 2         | 3.7%    |
| Dell Latitude     | 2         | 3.7%    |
| Acer Nitro        | 2         | 3.7%    |
| TUXEDO Pulse      | 1         | 1.85%   |
| TUXEDO Aura       | 1         | 1.85%   |
| Sony VPCSB15GB    | 1         | 1.85%   |
| Sony VGN-Z570AN   | 1         | 1.85%   |
| Semp Toshiba AS   | 1         | 1.85%   |
| Samsung 600B4B    | 1         | 1.85%   |
| MSI Modern        | 1         | 1.85%   |
| MSI GS60          | 1         | 1.85%   |
| MSI GP63          | 1         | 1.85%   |
| MSI CX600         | 1         | 1.85%   |
| Medion E6436      | 1         | 1.85%   |
| Lenovo V330-15IKB | 1         | 1.85%   |
| Lenovo IdeaPad    | 1         | 1.85%   |
| Lenovo G500       | 1         | 1.85%   |
| Lenovo G50-45     | 1         | 1.85%   |
| HUAWEI KLVL-WXX9  | 1         | 1.85%   |
| HP ZBook          | 1         | 1.85%   |
| HP Stream         | 1         | 1.85%   |
| HP Pavilion       | 1         | 1.85%   |
| HP OMEN           | 1         | 1.85%   |
| HP Notebook       | 1         | 1.85%   |
| Dell XPS          | 1         | 1.85%   |
| Dell System       | 1         | 1.85%   |
| Dell Precision    | 1         | 1.85%   |
| ASUS ZenBook      | 1         | 1.85%   |
| ASUS VivoBook     | 1         | 1.85%   |
| ASUS G771JW       | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 7         | 12.96%  |
| 2020 | 6         | 11.11%  |
| 2012 | 6         | 11.11%  |
| 2019 | 5         | 9.26%   |
| 2018 | 5         | 9.26%   |
| 2015 | 4         | 7.41%   |
| 2014 | 4         | 7.41%   |
| 2021 | 3         | 5.56%   |
| 2016 | 3         | 5.56%   |
| 2011 | 3         | 5.56%   |
| 2013 | 2         | 3.7%    |
| 2010 | 2         | 3.7%    |
| 2007 | 2         | 3.7%    |
| 2009 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |

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
| Disabled | 46        | 85.19%  |
| Enabled  | 8         | 14.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 27.78%  |
| 8.01-16.0   | 12        | 22.22%  |
| 3.01-4.0    | 10        | 18.52%  |
| 16.01-24.0  | 10        | 18.52%  |
| 32.01-64.0  | 3         | 5.56%   |
| 1.01-2.0    | 2         | 3.7%    |
| 2.01-3.0    | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 35.19%  |
| 1.01-2.0  | 16        | 29.63%  |
| 4.01-8.0  | 12        | 22.22%  |
| 3.01-4.0  | 5         | 9.26%   |
| 8.01-16.0 | 1         | 1.85%   |
| 0.51-1.0  | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 61.11%  |
| 2      | 21        | 38.89%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 59.26%  |
| Yes       | 22        | 40.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 87.04%  |
| No        | 7         | 12.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 74.55%  |
| No        | 14        | 25.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 13        | 24.07%  |
| Brazil      | 6         | 11.11%  |
| USA         | 4         | 7.41%   |
| France      | 4         | 7.41%   |
| Spain       | 2         | 3.7%    |
| Russia      | 2         | 3.7%    |
| Nicaragua   | 2         | 3.7%    |
| India       | 2         | 3.7%    |
| Greece      | 2         | 3.7%    |
| Czechia     | 2         | 3.7%    |
| UK          | 1         | 1.85%   |
| Thailand    | 1         | 1.85%   |
| Sweden      | 1         | 1.85%   |
| Sudan       | 1         | 1.85%   |
| Romania     | 1         | 1.85%   |
| Portugal    | 1         | 1.85%   |
| Netherlands | 1         | 1.85%   |
| Mexico      | 1         | 1.85%   |
| Italy       | 1         | 1.85%   |
| Hungary     | 1         | 1.85%   |
| China       | 1         | 1.85%   |
| Canada      | 1         | 1.85%   |
| Bulgaria    | 1         | 1.85%   |
| Belgium     | 1         | 1.85%   |
| Austria     | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sao Paulo           | 3         | 5.26%   |
| Managua             | 2         | 3.51%   |
| Lehrte              | 2         | 3.51%   |
| Berlin              | 2         | 3.51%   |
| Weilheim            | 1         | 1.75%   |
| Vienna              | 1         | 1.75%   |
| Vaennaes            | 1         | 1.75%   |
| The Hague           | 1         | 1.75%   |
| Teresina            | 1         | 1.75%   |
| Sofia               | 1         | 1.75%   |
| Saalfeld            | 1         | 1.75%   |
| Rockville           | 1         | 1.75%   |
| Prague              | 1         | 1.75%   |
| Phuket              | 1         | 1.75%   |
| Petrozavodsk        | 1         | 1.75%   |
| Peine               | 1         | 1.75%   |
| Paris               | 1         | 1.75%   |
| Palm Bay            | 1         | 1.75%   |
| Moscow              | 1         | 1.75%   |
| Montreal            | 1         | 1.75%   |
| Monterrey           | 1         | 1.75%   |
| Moelan-sur-Mer      | 1         | 1.75%   |
| León               | 1         | 1.75%   |
| Leiria              | 1         | 1.75%   |
| Kostelec nad Orlici | 1         | 1.75%   |
| Khartoum            | 1         | 1.75%   |
| Kesztolc            | 1         | 1.75%   |
| Islington           | 1         | 1.75%   |
| Irun                | 1         | 1.75%   |
| Ilsfeld             | 1         | 1.75%   |
| Houilles            | 1         | 1.75%   |
| Heraklion           | 1         | 1.75%   |
| Halle               | 1         | 1.75%   |
| Guangzhou           | 1         | 1.75%   |
| Gevelsberg          | 1         | 1.75%   |
| Frankfurt am Main   | 1         | 1.75%   |
| Dunkirk             | 1         | 1.75%   |
| Dornhan             | 1         | 1.75%   |
| Conroe              | 1         | 1.75%   |
| Concarneau          | 1         | 1.75%   |
| Cologne             | 1         | 1.75%   |
| Chapecó            | 1         | 1.75%   |
| Budapest            | 1         | 1.75%   |
| Bucharest           | 1         | 1.75%   |
| Bremen              | 1         | 1.75%   |
| Bologna             | 1         | 1.75%   |
| Bengaluru           | 1         | 1.75%   |
| Bebedouro           | 1         | 1.75%   |
| Atlanta             | 1         | 1.75%   |
| Athens              | 1         | 1.75%   |
| Antwerp             | 1         | 1.75%   |
| Ahmedabad           | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 16.44%  |
| WDC                 | 10        | 10     | 13.7%   |
| Seagate             | 8         | 11     | 10.96%  |
| Kingston            | 8         | 9      | 10.96%  |
| SanDisk             | 6         | 6      | 8.22%   |
| Toshiba             | 4         | 5      | 5.48%   |
| SK hynix            | 4         | 4      | 5.48%   |
| Unknown             | 3         | 3      | 4.11%   |
| Hitachi             | 3         | 4      | 4.11%   |
| HGST                | 3         | 4      | 4.11%   |
| Silicon Motion      | 2         | 2      | 2.74%   |
| Micron Technology   | 2         | 2      | 2.74%   |
| Crucial             | 2         | 2      | 2.74%   |
| Plextor             | 1         | 2      | 1.37%   |
| Phison              | 1         | 1      | 1.37%   |
| LITEON              | 1         | 1      | 1.37%   |
| Intenso             | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |
| China               | 1         | 1      | 1.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix HFS128G39TND-N210A 128GB SSD   | 2         | 2.74%   |
| Silicon Motion NVMe SSD Drive 512GB     | 2         | 2.74%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2.74%   |
| HGST HTS721010A9E630 1TB                | 2         | 2.74%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 1.37%   |
| WDC WD800BEVS-60RST0 80GB               | 1         | 1.37%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 1.37%   |
| WDC WD5000LPLX-66ZNTT1 500GB            | 1         | 1.37%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 1.37%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.37%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 1.37%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1.37%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 1.37%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 1.37%   |
| Unknown USD00  256GB                    | 1         | 1.37%   |
| Unknown SC16G  16GB                     | 1         | 1.37%   |
| Unknown DA4064  64GB                    | 1         | 1.37%   |
| Toshiba THNSNJ256G8NU 256GB SSD         | 1         | 1.37%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.37%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1.37%   |
| Toshiba MK3261GSYD 320GB                | 1         | 1.37%   |
| SK hynix HFM512GD3JX013N 512GB          | 1         | 1.37%   |
| SK hynix HBG4e  32GB                    | 1         | 1.37%   |
| Seagate ST9320325AS 320GB               | 1         | 1.37%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1.37%   |
| Seagate ST500LM000-SSHD-8GB             | 1         | 1.37%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 1         | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.37%   |
| SanDisk SSD U100 128GB                  | 1         | 1.37%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 1.37%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 1.37%   |
| SanDisk SD9SN8W256G 256GB SSD           | 1         | 1.37%   |
| SanDisk SD8TB8U512G1001 512GB SSD       | 1         | 1.37%   |
| SanDisk SD6SB1M128G1022I 128GB SSD      | 1         | 1.37%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 1.37%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.37%   |
| Samsung SSD 850 EVO 250GB               | 1         | 1.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB  | 1         | 1.37%   |
| Samsung PM9A1 NVMe 1024GB               | 1         | 1.37%   |
| Samsung NVMe SSD Drive 1TB              | 1         | 1.37%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 1         | 1.37%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 1.37%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 1         | 1.37%   |
| Samsung MZNLF128HCHP-00000 128GB SSD    | 1         | 1.37%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 1         | 1.37%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.37%   |
| Plextor PX-512M5Pro 512GB SSD           | 1         | 1.37%   |
| Phison 311CD0512GB                      | 1         | 1.37%   |
| Micron NVMe SSD Drive 512GB             | 1         | 1.37%   |
| Micron MTFDHBA512TDV 512GB              | 1         | 1.37%   |
| LITEON CX1-JB256-HP 256GB SSD           | 1         | 1.37%   |
| Kingston SNA-DC/U3 240GB SSD            | 1         | 1.37%   |
| Kingston SM2280S3G2480G 480GB SSD       | 1         | 1.37%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1.37%   |
| Kingston SA2000M81000G 1TB              | 1         | 1.37%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1.37%   |
| Kingston RBU-SC100S37128GD 128GB SSD    | 1         | 1.37%   |
| Kingston NVMe SSD Drive 512GB           | 1         | 1.37%   |
| Kingston NVMe SSD Drive 500GB           | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 30.77%  |
| Seagate | 8         | 11     | 30.77%  |
| Toshiba | 3         | 4      | 11.54%  |
| Hitachi | 3         | 4      | 11.54%  |
| HGST    | 3         | 4      | 11.54%  |
| Fujitsu | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 25%     |
| Kingston            | 5         | 6      | 20.83%  |
| Samsung Electronics | 4         | 4      | 16.67%  |
| SK hynix            | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Toshiba             | 1         | 1      | 4.17%   |
| Plextor             | 1         | 2      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 32     | 34.29%  |
| SSD  | 23        | 26     | 32.86%  |
| NVMe | 19        | 21     | 27.14%  |
| MMC  | 4         | 4      | 5.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 57     | 61.29%  |
| NVMe | 19        | 21     | 30.65%  |
| MMC  | 4         | 4      | 6.45%   |
| SAS  | 1         | 1      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 35     | 59.57%  |
| 0.51-1.0   | 18        | 22     | 38.3%   |
| 1.01-2.0   | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 14        | 25.93%  |
| More than 3000 | 11        | 20.37%  |
| 501-1000       | 9         | 16.67%  |
| 2001-3000      | 8         | 14.81%  |
| 251-500        | 6         | 11.11%  |
| 51-100         | 4         | 7.41%   |
| 101-250        | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 13        | 22.03%  |
| 51-100    | 11        | 18.64%  |
| 251-500   | 10        | 16.95%  |
| 501-1000  | 7         | 11.86%  |
| 1001-2000 | 6         | 10.17%  |
| 21-50     | 4         | 6.78%   |
| 1-20      | 4         | 6.78%   |
| 2001-3000 | 3         | 5.08%   |
| Unknown   | 1         | 1.69%   |

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
| Detected | 28        | 46     | 46.67%  |
| Works    | 27        | 32     | 45%     |
| Malfunc  | 5         | 5      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 58.06%  |
| Samsung Electronics              | 7         | 11.29%  |
| AMD                              | 6         | 9.68%   |
| Kingston Technology Company      | 3         | 4.84%   |
| Silicon Motion                   | 2         | 3.23%   |
| Micron Technology                | 2         | 3.23%   |
| SK hynix                         | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] | 1         | 1.61%   |
| SanDisk                          | 1         | 1.61%   |
| Phison Electronics               | 1         | 1.61%   |
| Micron/Crucial Technology        | 1         | 1.61%   |
| Lite-On Technology               | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 15.38%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 7.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 4.62%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 3.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.08%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.08%   |
| Micron Non-Volatile memory controller                                          | 2         | 3.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 3.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.08%   |
| SK hynix Gold P31 SSD                                                          | 1         | 1.54%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.54%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.54%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.54%   |
| Lite-On SATA controller                                                        | 1         | 1.54%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 39        | 61.9%   |
| NVMe | 18        | 28.57%  |
| RAID | 3         | 4.76%   |
| IDE  | 3         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 79.63%  |
| AMD    | 11        | 20.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 5.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 3.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 3.7%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.85%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 1.85%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.85%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.85%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.85%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD C-50 Processor                            | 1         | 1.85%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 1.85%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 35.19%  |
| Intel Core i7           | 12        | 22.22%  |
| Intel Core i3           | 4         | 7.41%   |
| AMD Ryzen 7             | 4         | 7.41%   |
| Intel Core 2 Duo        | 3         | 5.56%   |
| Other                   | 2         | 3.7%    |
| Intel Celeron           | 2         | 3.7%    |
| AMD Ryzen 5             | 2         | 3.7%    |
| AMD A6                  | 2         | 3.7%    |
| Intel Pentium Dual-Core | 1         | 1.85%   |
| AMD Ryzen 7 PRO         | 1         | 1.85%   |
| AMD Ryzen 3             | 1         | 1.85%   |
| AMD C-50                | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 53.7%   |
| 4      | 15        | 27.78%  |
| 8      | 6         | 11.11%  |
| 6      | 4         | 7.41%   |

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
| 2      | 40        | 74.07%  |
| 1      | 14        | 25.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 34.55%  |
| 0x806e9    | 4         | 7.27%   |
| 0x406e3    | 4         | 7.27%   |
| 0x906ea    | 3         | 5.45%   |
| 0x206a7    | 3         | 5.45%   |
| 0x08600106 | 3         | 5.45%   |
| 0x6fd      | 2         | 3.64%   |
| 0x506e3    | 2         | 3.64%   |
| 0x806ec    | 1         | 1.82%   |
| 0x806ea    | 1         | 1.82%   |
| 0x806d1    | 1         | 1.82%   |
| 0x806c1    | 1         | 1.82%   |
| 0x706a1    | 1         | 1.82%   |
| 0x306d4    | 1         | 1.82%   |
| 0x306c3    | 1         | 1.82%   |
| 0x306a9    | 1         | 1.82%   |
| 0x30678    | 1         | 1.82%   |
| 0x20655    | 1         | 1.82%   |
| 0x1067a    | 1         | 1.82%   |
| 0x10676    | 1         | 1.82%   |
| 0x0a50000c | 1         | 1.82%   |
| 0x08108109 | 1         | 1.82%   |
| 0x07030105 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 25.93%  |
| Skylake       | 6         | 11.11%  |
| Zen 2         | 5         | 9.26%   |
| SandyBridge   | 4         | 7.41%   |
| IvyBridge     | 4         | 7.41%   |
| Haswell       | 4         | 7.41%   |
| Zen+          | 2         | 3.7%    |
| Westmere      | 2         | 3.7%    |
| Penryn        | 2         | 3.7%    |
| Core          | 2         | 3.7%    |
| Zen 3         | 1         | 1.85%   |
| TigerLake     | 1         | 1.85%   |
| Silvermont    | 1         | 1.85%   |
| Puma          | 1         | 1.85%   |
| K10 Llano     | 1         | 1.85%   |
| Icelake       | 1         | 1.85%   |
| Goldmont plus | 1         | 1.85%   |
| Broadwell     | 1         | 1.85%   |
| Bobcat        | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 56.76%  |
| AMD    | 18        | 24.32%  |
| Nvidia | 14        | 18.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 5         | 6.58%   |
| AMD Renoir                                                                            | 5         | 6.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 5.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 5.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 5.26%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 3.95%   |
| Intel UHD Graphics 620                                                                | 2         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 2.63%   |
| Intel HD Graphics 530                                                                 | 2         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.32%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1.32%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 1.32%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.32%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 1.32%   |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.32%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.32%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.32%   |
| Intel HD Graphics 630                                                                 | 1         | 1.32%   |
| Intel HD Graphics 5500                                                                | 1         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.32%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.32%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1.32%   |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.32%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 1         | 1.32%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.32%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.32%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 1.32%   |
| AMD Cezanne                                                                           | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 42.59%  |
| Intel + Nvidia | 13        | 24.07%  |
| 1 x AMD        | 12        | 22.22%  |
| Intel + AMD    | 6         | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 48        | 88.89%  |
| Proprietary | 5         | 9.26%   |
| Unknown     | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 72.73%  |
| 0.01-0.5   | 6         | 10.91%  |
| 1.01-2.0   | 4         | 7.27%   |
| 3.01-4.0   | 3         | 5.45%   |
| 7.01-8.0   | 1         | 1.82%   |
| 0.51-1.0   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 15        | 23.81%  |
| Chimei Innolux      | 12        | 19.05%  |
| AU Optronics        | 11        | 17.46%  |
| Samsung Electronics | 5         | 7.94%   |
| Goldstar            | 4         | 6.35%   |
| BOE                 | 3         | 4.76%   |
| Lenovo              | 2         | 3.17%   |
| Hewlett-Packard     | 2         | 3.17%   |
| Sony                | 1         | 1.59%   |
| Sharp               | 1         | 1.59%   |
| Sceptre Tech        | 1         | 1.59%   |
| LG Philips          | 1         | 1.59%   |
| InfoVision          | 1         | 1.59%   |
| Iiyama              | 1         | 1.59%   |
| Dell                | 1         | 1.59%   |
| CSO                 | 1         | 1.59%   |
| CPT                 | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 3.13%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 3.13%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 3.13%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 1.56%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 1.56%   |
| Sceptre Tech Sceptre E19 SPT07A8 1366x768 575x323mm 26.0-inch         | 1         | 1.56%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 1.56%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch           | 1         | 1.56%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 1.56%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 1         | 1.56%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 1         | 1.56%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.56%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 1         | 1.56%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                      | 1         | 1.56%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 1.56%   |
| CPT LCD Monitor CPT17D8 1366x768 293x165mm 13.2-inch                  | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1136 1366x768 256x144mm 11.6-inch       | 1         | 1.56%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE06FF 1920x1080 344x194mm 15.5-inch                 | 1         | 1.56%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch        | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO225C 1366x768 256x144mm 11.6-inch         | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 28        | 48.28%  |
| 1366x768 (WXGA)   | 15        | 25.86%  |
| 1920x1200 (WUXGA) | 3         | 5.17%   |
| 1600x900 (HD+)    | 3         | 5.17%   |
| 3840x2160 (4K)    | 2         | 3.45%   |
| 2560x1080         | 2         | 3.45%   |
| 3840x2400         | 1         | 1.72%   |
| 2560x1440 (QHD)   | 1         | 1.72%   |
| 2160x1440         | 1         | 1.72%   |
| 1280x800 (WXGA)   | 1         | 1.72%   |
| 1024x768 (XGA)    | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 40.63%  |
| 14     | 10        | 15.63%  |
| 17     | 8         | 12.5%   |
| 13     | 6         | 9.38%   |
| 34     | 2         | 3.13%   |
| 27     | 2         | 3.13%   |
| 26     | 2         | 3.13%   |
| 18     | 2         | 3.13%   |
| 11     | 2         | 3.13%   |
| 84     | 1         | 1.56%   |
| 24     | 1         | 1.56%   |
| 23     | 1         | 1.56%   |
| 21     | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 57.81%  |
| 351-400     | 9         | 14.06%  |
| 201-300     | 6         | 9.38%   |
| 501-600     | 5         | 7.81%   |
| 401-500     | 3         | 4.69%   |
| 701-800     | 2         | 3.13%   |
| 601-700     | 1         | 1.56%   |
| 1501-2000   | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 85.71%  |
| 16/10 | 4         | 7.14%   |
| 21/9  | 2         | 3.57%   |
| 4/3   | 1         | 1.79%   |
| 3/2   | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 40.63%  |
| 81-90          | 13        | 20.31%  |
| 121-130        | 8         | 12.5%   |
| 301-350        | 3         | 4.69%   |
| 201-250        | 3         | 4.69%   |
| 71-80          | 2         | 3.13%   |
| 51-60          | 2         | 3.13%   |
| 351-500        | 2         | 3.13%   |
| 141-150        | 2         | 3.13%   |
| More than 1000 | 1         | 1.56%   |
| 251-300        | 1         | 1.56%   |
| 91-100         | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 29        | 46.03%  |
| 101-120       | 18        | 28.57%  |
| 51-100        | 12        | 19.05%  |
| More than 240 | 2         | 3.17%   |
| 161-240       | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 42        | 77.78%  |
| 2     | 11        | 20.37%  |
| 0     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 34        | 39.08%  |
| Realtek Semiconductor            | 27        | 31.03%  |
| Qualcomm Atheros                 | 11        | 12.64%  |
| Broadcom                         | 5         | 5.75%   |
| Broadcom Limited                 | 2         | 2.3%    |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |
| Sierra Wireless                  | 1         | 1.15%   |
| Samsung Electronics              | 1         | 1.15%   |
| Ralink                           | 1         | 1.15%   |
| Manta                            | 1         | 1.15%   |
| Lenovo                           | 1         | 1.15%   |
| Dell                             | 1         | 1.15%   |
| ASIX Electronics                 | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 16.82%  |
| Intel Wi-Fi 6 AX200                                               | 5         | 4.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.74%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.74%   |
| Intel Wireless 8260                                               | 3         | 2.8%    |
| Intel Wireless 3165                                               | 3         | 2.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.87%   |
| Intel Wireless 7260                                               | 2         | 1.87%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.87%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.93%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.93%   |
| Samsung Kiera                                                     | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Manta MM812                                                       | 1         | 0.93%   |
| Lenovo OneLink+ Giga                                              | 1         | 0.93%   |
| Intel Wireless 7265                                               | 1         | 0.93%   |
| Intel WiFi Link 5100                                              | 1         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.93%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 0.93%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.93%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 0.93%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 57.14%  |
| Realtek Semiconductor | 9         | 16.07%  |
| Qualcomm Atheros      | 7         | 12.5%   |
| Broadcom              | 5         | 8.93%   |
| Sierra Wireless       | 1         | 1.79%   |
| Ralink                | 1         | 1.79%   |
| Dell                  | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 5         | 8.93%   |
| Intel Wireless 8265 / 8275                                    | 4         | 7.14%   |
| Intel Wireless 8260                                           | 3         | 5.36%   |
| Intel Wireless 3165                                           | 3         | 5.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 3.57%   |
| Intel Wireless 7260                                           | 2         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 3.57%   |
| Sierra Wireless MC8305 Modem                                  | 1         | 1.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 1.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 1.79%   |
| Intel Wireless 7265                                           | 1         | 1.79%   |
| Intel WiFi Link 5100                                          | 1         | 1.79%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.79%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 1.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                 | 1         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 1.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 1.79%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 1         | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 1         | 1.79%   |
| Broadcom BCM43227 802.11b/g/n                                 | 1         | 1.79%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 22        | 44.9%   |
| Intel                            | 15        | 30.61%  |
| Qualcomm Atheros                 | 5         | 10.2%   |
| Broadcom Limited                 | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] | 1         | 2.04%   |
| Samsung Electronics              | 1         | 2.04%   |
| Lenovo                           | 1         | 2.04%   |
| Broadcom                         | 1         | 2.04%   |
| ASIX Electronics                 | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 36%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 4%      |
| Intel Ethernet Connection I219-LM                                 | 2         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2%      |
| Samsung Kiera                                                     | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2%      |
| Lenovo OneLink+ Giga                                              | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I217-V                                  | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2%      |
| Intel 82579V Gigabit Network Connection                           | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2%      |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 2%      |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 52.94%  |
| Ethernet | 47        | 46.08%  |
| Unknown  | 1         | 0.98%   |

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
| 2     | 45        | 83.33%  |
| 1     | 8         | 14.81%  |
| 3     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 69.09%  |
| Yes  | 17        | 30.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 42.86%  |
| Realtek Semiconductor           | 6         | 14.29%  |
| Qualcomm Atheros Communications | 4         | 9.52%   |
| IMC Networks                    | 3         | 7.14%   |
| Foxconn / Hon Hai               | 3         | 7.14%   |
| Lite-On Technology              | 2         | 4.76%   |
| Broadcom                        | 2         | 4.76%   |
| Realtek                         | 1         | 2.38%   |
| Dell                            | 1         | 2.38%   |
| Cambridge Silicon Radio         | 1         | 2.38%   |
| Alps Electric                   | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 19.05%  |
| Intel AX200 Bluetooth                                                               | 4         | 9.52%   |
| Realtek Bluetooth Radio                                                             | 3         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 4.76%   |
| Intel Bluetooth Device                                                              | 2         | 4.76%   |
| IMC Networks Bluetooth Device                                                       | 2         | 4.76%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 2.38%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.38%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.38%   |
| Lite-On Bluetooth Device                                                            | 1         | 2.38%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 2.38%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.38%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.38%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 2.38%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 2.38%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.38%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 2.38%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 42        | 63.64%  |
| AMD                              | 12        | 18.18%  |
| Nvidia                           | 4         | 6.06%   |
| Logitech                         | 2         | 3.03%   |
| Lenovo                           | 2         | 3.03%   |
| Silicon Integrated Systems [SiS] | 1         | 1.52%   |
| JMTek                            | 1         | 1.52%   |
| GN Netcom                        | 1         | 1.52%   |
| ESS Technology                   | 1         | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 13.75%  |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 8.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 7.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.5%    |
| Logitech Headset H390                                                      | 2         | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.5%    |
| AMD FCH Azalia Controller                                                  | 2         | 2.5%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.25%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.25%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 1.25%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 1.25%   |
| JMTek audio controller                                                     | 1         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.25%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 1.25%   |
| ESS Technology Asus USB DAC                                                | 1         | 1.25%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.25%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.25%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 12        | 30.77%  |
| Samsung Electronics | 12        | 30.77%  |
| Unknown             | 4         | 10.26%  |
| Micron Technology   | 3         | 7.69%   |
| Kingston            | 2         | 5.13%   |
| Smart               | 1         | 2.56%   |
| Ramaxel Technology  | 1         | 2.56%   |
| Goodram             | 1         | 2.56%   |
| Crucial             | 1         | 2.56%   |
| Corsair             | 1         | 2.56%   |
| A-DATA Technology   | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 4.65%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                      | 1         | 2.33%   |
| Smart RAM SH564568FH8NWPHSFG 2048MB SODIMM DDR3 1333MT/s       | 1         | 2.33%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.33%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s        | 1         | 2.33%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.33%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.33%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 2.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 2.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 2.33%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 2.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 2.33%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 2.33%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s      | 1         | 2.33%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.33%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4096MB SODIMM LPDDR4 3733MT/s      | 1         | 2.33%   |
| Samsung RAM K4E6E304EE-EGCF 4096MB SODIMM LPDDR3 1867MT/s      | 1         | 2.33%   |
| Samsung RAM K4E6E304EE-EGCF 4096MB Chip LPDDR3 1867MT/s        | 1         | 2.33%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Micron RAM 8ATF51264HZ-2G1B1 8GB SODIMM DDR4 2667MT/s          | 1         | 2.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.33%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 2.33%   |
| Kingston RAM MSI26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s          | 1         | 2.33%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Goodram RAM IR2400S464L15S/8G 8192MB SODIMM DDR4 2133MT/s      | 1         | 2.33%   |
| Crucial RAM BLS8G4S26BFSDK.8FD 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.33%   |
| Corsair RAM CMSX8GX4M1A2400C16 8192MB SODIMM DDR4 2400MT/s     | 1         | 2.33%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 17        | 47.22%  |
| DDR3    | 10        | 27.78%  |
| LPDDR4  | 4         | 11.11%  |
| DDR2    | 2         | 5.56%   |
| SDRAM   | 1         | 2.78%   |
| LPDDR3  | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 91.67%  |
| Row Of Chips | 2         | 5.56%   |
| Chip         | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 36.59%  |
| 4096  | 13        | 31.71%  |
| 2048  | 6         | 14.63%  |
| 16384 | 4         | 9.76%   |
| 1024  | 2         | 4.88%   |
| 32768 | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 10        | 26.32%  |
| 1600    | 7         | 18.42%  |
| 3200    | 5         | 13.16%  |
| 2133    | 3         | 7.89%   |
| 1333    | 2         | 5.26%   |
| 667     | 2         | 5.26%   |
| 4267    | 1         | 2.63%   |
| 4266    | 1         | 2.63%   |
| 3733    | 1         | 2.63%   |
| 2400    | 1         | 2.63%   |
| 2048    | 1         | 2.63%   |
| 1867    | 1         | 2.63%   |
| 1334    | 1         | 2.63%   |
| 1067    | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

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
| Chicony Electronics                    | 13        | 26%     |
| Acer                                   | 7         | 14%     |
| Sunplus Innovation Technology          | 5         | 10%     |
| Realtek Semiconductor                  | 5         | 10%     |
| Quanta                                 | 4         | 8%      |
| IMC Networks                           | 4         | 8%      |
| Microdia                               | 3         | 6%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6%      |
| Syntek                                 | 1         | 2%      |
| Silicon Motion                         | 1         | 2%      |
| Ricoh                                  | 1         | 2%      |
| Luxvisions Innotech Limited            | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| ALi                                    | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 4         | 7.84%   |
| Sunplus HD WebCam                                                        | 2         | 3.92%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 3.92%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 3.92%   |
| Chicony HD Webcam                                                        | 2         | 3.92%   |
| Acer HD Webcam                                                           | 2         | 3.92%   |
| Acer BisonCam, NB Pro                                                    | 2         | 3.92%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 1.96%   |
| Sunplus Laptop_Integrated_Webcam_HD                                      | 1         | 1.96%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 1.96%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 1.96%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 1.96%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 1.96%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 1.96%   |
| Realtek USB Camera                                                       | 1         | 1.96%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.96%   |
| Realtek Integrated Webcam HD                                             | 1         | 1.96%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 1.96%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 1.96%   |
| Quanta HD Webcam                                                         | 1         | 1.96%   |
| Quanta HD User Facing                                                    | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M    | 1         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.96%   |
| Lite-On Integrated Camera                                                | 1         | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.96%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 1.96%   |
| IMC Networks Integrated Camera                                           | 1         | 1.96%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 1.96%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.96%   |
| Chicony ThinkPad T490 Webcam                                             | 1         | 1.96%   |
| Chicony Integrated Camera (1280x720@30)                                  | 1         | 1.96%   |
| Chicony HP TrueVision HD                                                 | 1         | 1.96%   |
| Chicony FJ Camera                                                        | 1         | 1.96%   |
| Chicony EasyCamera                                                       | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.96%   |
| ALi Gateway Webcam                                                       | 1         | 1.96%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 1.96%   |
| Acer Integrated Camera                                                   | 1         | 1.96%   |
| Acer BisonCam,NB Pro                                                     | 1         | 1.96%   |

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
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics  WBDI                                        | 1         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 7.69%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 7.69%   |
| Unknown                                                | 1         | 7.69%   |

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
| 0     | 30        | 54.55%  |
| 1     | 20        | 36.36%  |
| 2     | 5         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 41.94%  |
| Chipcard              | 8         | 25.81%  |
| Graphics card         | 4         | 12.9%   |
| Net/wireless          | 2         | 6.45%   |
| Multimedia controller | 2         | 6.45%   |
| Camera                | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

