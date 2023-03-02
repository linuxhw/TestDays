Lubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

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

Total: 76

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron      | 2AD5                        | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| MSI           | MS-7267                     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| ECS           | G41T-M7                     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Dell          | 0FPP7F A00                  | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| MSI           | MS-7032                     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| NEC Comput... | ECS-945G                    | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| ASRock        | ION3D-HT                    | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| ASUSTek       | M5A97 PRO                   | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Positivo      | POS-AG31AP                  | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Intel         | BTC-T37                     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| ASUSTek       | EB1501P                     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| ASRock        | H110M-HDV                   | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Gigabyte      | F2A58M-HD2                  | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| HP            | 0B4Ch D                     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Dell          | 0R849J A00                  | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Dell          | 09M8Y8 A01                  | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| MSI           | B450-A PRO MAX              | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Dell          | 0J584C A00                  | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| MSI           | Z590-A PRO                  | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| MSI           | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| ASRock        | G41M-VS3                    | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| HP            | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| HP            | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| MSI           | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.15.0-43-generic           | 11       | 16.92%  |
| 5.15.0-41-generic           | 5        | 7.69%   |
| 5.15.0-56-generic           | 4        | 6.15%   |
| 5.15.0-47-generic           | 4        | 6.15%   |
| 5.15.0-25-generic           | 4        | 6.15%   |
| 5.15.0-60-generic           | 3        | 4.62%   |
| 5.15.0-48-generic           | 3        | 4.62%   |
| 5.15.0-40-generic           | 3        | 4.62%   |
| 5.15.0-39-generic           | 3        | 4.62%   |
| 5.15.0-53-generic           | 2        | 3.08%   |
| 5.15.0-52-generic           | 2        | 3.08%   |
| 5.15.0-50-generic           | 2        | 3.08%   |
| 5.15.0-46-generic           | 2        | 3.08%   |
| 5.15.0-30-generic           | 2        | 3.08%   |
| 5.15.0-27-generic           | 2        | 3.08%   |
| 6.1.0-custom                | 1        | 1.54%   |
| 6.0.8-060008-generic        | 1        | 1.54%   |
| 5.19.0-32-generic           | 1        | 1.54%   |
| 5.19.0-16.2-liquorix-amd64  | 1        | 1.54%   |
| 5.15.0-59-lowlatency        | 1        | 1.54%   |
| 5.15.0-58-lowlatency        | 1        | 1.54%   |
| 5.15.0-58-generic           | 1        | 1.54%   |
| 5.15.0-57-generic           | 1        | 1.54%   |
| 5.15.0-41-lowlatency        | 1        | 1.54%   |
| 5.15.0-362206031516-generic | 1        | 1.54%   |
| 5.15.0-35-generic           | 1        | 1.54%   |
| 5.15.0-23-generic           | 1        | 1.54%   |
| 5.15.0-18-generic           | 1        | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 59       | 93.65%  |
| 5.19.0  | 2        | 3.17%   |
| 6.1.0   | 1        | 1.59%   |
| 6.0.8   | 1        | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 59       | 93.65%  |
| 5.19    | 2        | 3.17%   |
| 6.1     | 1        | 1.59%   |
| 6.0     | 1        | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 62       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 59       | 95.16%  |
| LXDE | 2        | 3.23%   |
| XFCE | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 59       | 92.19%  |
| Tty         | 3        | 4.69%   |
| Wayland     | 1        | 1.56%   |
| Unspecified | 1        | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 52       | 83.87%  |
| LightDM | 4        | 6.45%   |
| Unknown | 3        | 4.84%   |
| XDM     | 1        | 1.61%   |
| SLiM    | 1        | 1.61%   |
| LXDM    | 1        | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 15       | 24.19%  |
| fr_FR | 11       | 17.74%  |
| de_DE | 6        | 9.68%   |
| it_IT | 5        | 8.06%   |
| es_ES | 4        | 6.45%   |
| en_GB | 4        | 6.45%   |
| es_CR | 2        | 3.23%   |
| es_AR | 2        | 3.23%   |
| C     | 2        | 3.23%   |
| tr_TR | 1        | 1.61%   |
| sv_SE | 1        | 1.61%   |
| ru_UA | 1        | 1.61%   |
| pt_BR | 1        | 1.61%   |
| pl_PL | 1        | 1.61%   |
| nl_BE | 1        | 1.61%   |
| es_MX | 1        | 1.61%   |
| en_AU | 1        | 1.61%   |
| en_AG | 1        | 1.61%   |
| el_GR | 1        | 1.61%   |
| cv_RU | 1        | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 48       | 77.42%  |
| EFI  | 14       | 22.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 58       | 93.55%  |
| Overlay | 2        | 3.23%   |
| XXX4    | 1        | 1.61%   |
| Btrfs   | 1        | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 24       | 38.71%  |
| MBR     | 20       | 32.26%  |
| Unknown | 18       | 29.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 83.87%  |
| Yes       | 10       | 16.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 54.84%  |
| Yes       | 28       | 45.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 12       | 19.35%  |
| ASUSTek Computer    | 12       | 19.35%  |
| Dell                | 9        | 14.52%  |
| ASRock              | 5        | 8.06%   |
| Hewlett-Packard     | 4        | 6.45%   |
| Gigabyte Technology | 3        | 4.84%   |
| Unknown             | 3        | 4.84%   |
| Pegatron            | 2        | 3.23%   |
| Lenovo              | 2        | 3.23%   |
| AMI                 | 2        | 3.23%   |
| Acer                | 2        | 3.23%   |
| ZOTAC               | 1        | 1.61%   |
| Positivo            | 1        | 1.61%   |
| NEC Computers       | 1        | 1.61%   |
| Intel               | 1        | 1.61%   |
| Fujitsu             | 1        | 1.61%   |
| ECS                 | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 3        | 4.84%   |
| MSI MS-7C37                            | 2        | 3.23%   |
| Dell Dimension 9100                    | 2        | 3.23%   |
| ZOTAC NM10                             | 1        | 1.61%   |
| Positivo POS-AG31AP                    | 1        | 1.61%   |
| Pegatron h8-1350ef                     | 1        | 1.61%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 1.61%   |
| NEC Computers ECS-945G                 | 1        | 1.61%   |
| MSI MS-7D09                            | 1        | 1.61%   |
| MSI MS-7C96                            | 1        | 1.61%   |
| MSI MS-7C56                            | 1        | 1.61%   |
| MSI MS-7C51                            | 1        | 1.61%   |
| MSI MS-7B86                            | 1        | 1.61%   |
| MSI MS-7978                            | 1        | 1.61%   |
| MSI MS-7641                            | 1        | 1.61%   |
| MSI MS-7501                            | 1        | 1.61%   |
| MSI MS-7267                            | 1        | 1.61%   |
| MSI MS-7032                            | 1        | 1.61%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1.61%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1.61%   |
| Intel BTC-T37                          | 1        | 1.61%   |
| HP Z400 Workstation                    | 1        | 1.61%   |
| HP t620 Quad Core TC                   | 1        | 1.61%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 1.61%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1.61%   |
| Gigabyte G31M-S2C                      | 1        | 1.61%   |
| Gigabyte G31M-ES2C                     | 1        | 1.61%   |
| Gigabyte F2A58M-HD2                    | 1        | 1.61%   |
| Fujitsu FUTRO S900                     | 1        | 1.61%   |
| ECS G41T-M7                            | 1        | 1.61%   |
| Dell Vostro 410                        | 1        | 1.61%   |
| Dell Vostro 3670                       | 1        | 1.61%   |
| Dell Studio XPS 435MT                  | 1        | 1.61%   |
| Dell Precision T3610                   | 1        | 1.61%   |
| Dell OptiPlex 7020                     | 1        | 1.61%   |
| Dell OptiPlex 7010                     | 1        | 1.61%   |
| Dell OptiPlex 3020M                    | 1        | 1.61%   |
| ASUS TUF B450-PRO GAMING               | 1        | 1.61%   |
| ASUS ROG STRIX B450-F GAMING II        | 1        | 1.61%   |
| ASUS PRIME X370-A                      | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 3        | 4.84%   |
| Unknown                | 3        | 4.84%   |
| MSI MS-7C37            | 2        | 3.23%   |
| Lenovo ThinkCentre     | 2        | 3.23%   |
| Dell Vostro            | 2        | 3.23%   |
| Dell Dimension         | 2        | 3.23%   |
| ASUS PRIME             | 2        | 3.23%   |
| ZOTAC NM10             | 1        | 1.61%   |
| Positivo POS-AG31AP    | 1        | 1.61%   |
| Pegatron h8-1350ef     | 1        | 1.61%   |
| Pegatron AY748AA-ABA   | 1        | 1.61%   |
| NEC Computers ECS-945G | 1        | 1.61%   |
| MSI MS-7D09            | 1        | 1.61%   |
| MSI MS-7C96            | 1        | 1.61%   |
| MSI MS-7C56            | 1        | 1.61%   |
| MSI MS-7C51            | 1        | 1.61%   |
| MSI MS-7B86            | 1        | 1.61%   |
| MSI MS-7978            | 1        | 1.61%   |
| MSI MS-7641            | 1        | 1.61%   |
| MSI MS-7501            | 1        | 1.61%   |
| MSI MS-7267            | 1        | 1.61%   |
| MSI MS-7032            | 1        | 1.61%   |
| Intel BTC-T37          | 1        | 1.61%   |
| HP Z400                | 1        | 1.61%   |
| HP t620                | 1        | 1.61%   |
| HP Slim                | 1        | 1.61%   |
| HP Compaq              | 1        | 1.61%   |
| Gigabyte G31M-S2C      | 1        | 1.61%   |
| Gigabyte G31M-ES2C     | 1        | 1.61%   |
| Gigabyte F2A58M-HD2    | 1        | 1.61%   |
| Fujitsu FUTRO          | 1        | 1.61%   |
| ECS G41T-M7            | 1        | 1.61%   |
| Dell Studio            | 1        | 1.61%   |
| Dell Precision         | 1        | 1.61%   |
| ASUS TUF               | 1        | 1.61%   |
| ASUS ROG               | 1        | 1.61%   |
| ASUS M5A97             | 1        | 1.61%   |
| ASUS M5A78L-M          | 1        | 1.61%   |
| ASUS M5A78L            | 1        | 1.61%   |
| ASUS M4N78-AM          | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 6        | 9.68%   |
| 2008 | 6        | 9.68%   |
| 2020 | 5        | 8.06%   |
| 2019 | 5        | 8.06%   |
| 2017 | 5        | 8.06%   |
| 2011 | 5        | 8.06%   |
| 2015 | 4        | 6.45%   |
| 2014 | 4        | 6.45%   |
| 2009 | 4        | 6.45%   |
| 2007 | 4        | 6.45%   |
| 2021 | 3        | 4.84%   |
| 2016 | 2        | 3.23%   |
| 2013 | 2        | 3.23%   |
| 2012 | 2        | 3.23%   |
| 2006 | 2        | 3.23%   |
| 2022 | 1        | 1.61%   |
| 2018 | 1        | 1.61%   |
| 2001 | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 61       | 98.39%  |
| Enabled  | 1        | 1.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 12       | 19.35%  |
| 3.01-4.0    | 12       | 19.35%  |
| 16.01-24.0  | 10       | 16.13%  |
| 8.01-16.0   | 10       | 16.13%  |
| 32.01-64.0  | 7        | 11.29%  |
| 1.01-2.0    | 6        | 9.68%   |
| 0.51-1.0    | 3        | 4.84%   |
| 2.01-3.0    | 1        | 1.61%   |
| 64.01-256.0 | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 26       | 41.27%  |
| 0.51-1.0  | 15       | 23.81%  |
| 2.01-3.0  | 12       | 19.05%  |
| 4.01-8.0  | 6        | 9.52%   |
| 3.01-4.0  | 2        | 3.17%   |
| 8.01-16.0 | 1        | 1.59%   |
| 0.01-0.5  | 1        | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 48.39%  |
| 2      | 22       | 35.48%  |
| 3      | 3        | 4.84%   |
| 5      | 2        | 3.23%   |
| 4      | 2        | 3.23%   |
| 7      | 1        | 1.61%   |
| 6      | 1        | 1.61%   |
| 0      | 1        | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 58.06%  |
| Yes       | 26       | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 98.39%  |
| No        | 1        | 1.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 56.45%  |
| Yes       | 27       | 43.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 79.37%  |
| Yes       | 13       | 20.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 13       | 20.97%  |
| France     | 11       | 17.74%  |
| Germany    | 6        | 9.68%   |
| Italy      | 5        | 8.06%   |
| Spain      | 4        | 6.45%   |
| UK         | 3        | 4.84%   |
| Poland     | 3        | 4.84%   |
| Costa Rica | 2        | 3.23%   |
| Brazil     | 2        | 3.23%   |
| Argentina  | 2        | 3.23%   |
| Ukraine    | 1        | 1.61%   |
| Turkey     | 1        | 1.61%   |
| Sweden     | 1        | 1.61%   |
| Romania    | 1        | 1.61%   |
| Mexico     | 1        | 1.61%   |
| Latvia     | 1        | 1.61%   |
| Ireland    | 1        | 1.61%   |
| Greece     | 1        | 1.61%   |
| Bulgaria   | 1        | 1.61%   |
| Belgium    | 1        | 1.61%   |
| Australia  | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 3        | 4.76%   |
| Largo                | 2        | 3.17%   |
| Heredia              | 2        | 3.17%   |
| Wetteren             | 1        | 1.59%   |
| Washington           | 1        | 1.59%   |
| Warsaw               | 1        | 1.59%   |
| Versailles           | 1        | 1.59%   |
| Varna                | 1        | 1.59%   |
| Valentigney          | 1        | 1.59%   |
| Tyler                | 1        | 1.59%   |
| Turin                | 1        | 1.59%   |
| Tandil               | 1        | 1.59%   |
| Sonico               | 1        | 1.59%   |
| Riverenert           | 1        | 1.59%   |
| Rio Segundo          | 1        | 1.59%   |
| Richmond             | 1        | 1.59%   |
| Resistencia          | 1        | 1.59%   |
| Port Washington      | 1        | 1.59%   |
| Palencia             | 1        | 1.59%   |
| Ostrów Wielkopolski | 1        | 1.59%   |
| Oberkotzau           | 1        | 1.59%   |
| Novo Gama            | 1        | 1.59%   |
| Notting Hill Gate    | 1        | 1.59%   |
| Nederland            | 1        | 1.59%   |
| Mostoles             | 1        | 1.59%   |
| Mobile               | 1        | 1.59%   |
| Mexico City          | 1        | 1.59%   |
| Melbourne            | 1        | 1.59%   |
| Marseille            | 1        | 1.59%   |
| Madrid               | 1        | 1.59%   |
| Lebanon              | 1        | 1.59%   |
| Larissa              | 1        | 1.59%   |
| Kyiv                 | 1        | 1.59%   |
| Koblenz              | 1        | 1.59%   |
| Kielce               | 1        | 1.59%   |
| Karlstad             | 1        | 1.59%   |
| Imola                | 1        | 1.59%   |
| Huelva               | 1        | 1.59%   |
| Hemel Hempstead      | 1        | 1.59%   |
| Hayes                | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 19       | 23     | 19%     |
| Samsung Electronics       | 15       | 19     | 15%     |
| WDC                       | 14       | 18     | 14%     |
| Kingston                  | 7        | 8      | 7%      |
| Hitachi                   | 7        | 8      | 7%      |
| SanDisk                   | 4        | 4      | 4%      |
| Toshiba                   | 3        | 3      | 3%      |
| Crucial                   | 3        | 3      | 3%      |
| Maxtor                    | 2        | 2      | 2%      |
| HGST                      | 2        | 2      | 2%      |
| GOODRAM                   | 2        | 2      | 2%      |
| A-DATA Technology         | 2        | 2      | 2%      |
| WD MediaMax               | 1        | 1      | 1%      |
| Unknown                   | 1        | 1      | 1%      |
| Transcend                 | 1        | 1      | 1%      |
| TO Exter                  | 1        | 1      | 1%      |
| Team                      | 1        | 1      | 1%      |
| T-FORCE                   | 1        | 1      | 1%      |
| RSH-319                   | 1        | 1      | 1%      |
| PNY                       | 1        | 1      | 1%      |
| Patriot                   | 1        | 1      | 1%      |
| Micron/Crucial Technology | 1        | 1      | 1%      |
| LITEONIT                  | 1        | 1      | 1%      |
| Kston                     | 1        | 3      | 1%      |
| Intel                     | 1        | 1      | 1%      |
| HGST HUS                  | 1        | 2      | 1%      |
| Gigabyte Technology       | 1        | 1      | 1%      |
| External                  | 1        | 1      | 1%      |
| Emtec                     | 1        | 1      | 1%      |
| Apricorn                  | 1        | 1      | 1%      |
| Apacer                    | 1        | 1      | 1%      |
| AMD                       | 1        | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 6        | 5.45%   |
| Toshiba DT01ACA100 1TB               | 2        | 1.82%   |
| Seagate ST3120213AS 120GB            | 2        | 1.82%   |
| Samsung SSD 870 EVO 500GB            | 2        | 1.82%   |
| Samsung HD502HJ 500GB                | 2        | 1.82%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 1.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.91%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1        | 0.91%   |
| WDC WD800BB-00CAA1 80GB              | 1        | 0.91%   |
| WDC WD5000LUCT-63RC2Y0 500GB         | 1        | 0.91%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.91%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 1        | 0.91%   |
| WDC WD3200BPVT-00HXZT3 320GB         | 1        | 0.91%   |
| WDC WD3200AACS-00M6B0 320GB          | 1        | 0.91%   |
| WDC WD30EZRZ-00GXCB0 3TB             | 1        | 0.91%   |
| WDC WD2500KS-00MJB0 250GB            | 1        | 0.91%   |
| WDC WD2500AAJS-07M0A0 250GB          | 1        | 0.91%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1        | 0.91%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1        | 0.91%   |
| WDC WD10EZRZ-00Z5HB0 1TB             | 1        | 0.91%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1        | 0.91%   |
| WDC WD10EURX-63C57Y0 1TB             | 1        | 0.91%   |
| WDC WD10EACS-00D6B1 1TB              | 1        | 0.91%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1        | 0.91%   |
| WD MediaMax WL250GSA872 250GB        | 1        | 0.91%   |
| Unknown 032G72  32GB                 | 1        | 0.91%   |
| Transcend TS128GSSD340 128GB         | 1        | 0.91%   |
| Toshiba MK6465GSX 640GB              | 1        | 0.91%   |
| TO Exter nal USB 3.0 240GB           | 1        | 0.91%   |
| Team T253E2002T 2TB SSD              | 1        | 0.91%   |
| T-FORCE 1TB                          | 1        | 0.91%   |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 0.91%   |
| Seagate ST500LM000-1EJ162 500GB      | 1        | 0.91%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 0.91%   |
| Seagate ST3500418AS 500GB            | 1        | 0.91%   |
| Seagate ST3250823AS 250GB            | 1        | 0.91%   |
| Seagate ST3200826AS 200GB            | 1        | 0.91%   |
| Seagate ST2000NE001-2M5101 2TB       | 1        | 0.91%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 0.91%   |
| Seagate ST2000DM008-2UB102 2TB       | 1        | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 22     | 33.93%  |
| WDC                 | 13       | 15     | 23.21%  |
| Hitachi             | 7        | 8      | 12.5%   |
| Samsung Electronics | 6        | 7      | 10.71%  |
| Toshiba             | 3        | 3      | 5.36%   |
| Maxtor              | 2        | 2      | 3.57%   |
| HGST                | 2        | 2      | 3.57%   |
| WD MediaMax         | 1        | 1      | 1.79%   |
| RSH-319             | 1        | 1      | 1.79%   |
| External            | 1        | 1      | 1.79%   |
| Apricorn            | 1        | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 10     | 25%     |
| Kingston            | 6        | 7      | 16.67%  |
| SanDisk             | 3        | 3      | 8.33%   |
| GOODRAM             | 2        | 2      | 5.56%   |
| Crucial             | 2        | 2      | 5.56%   |
| A-DATA Technology   | 2        | 2      | 5.56%   |
| WDC                 | 1        | 1      | 2.78%   |
| Transcend           | 1        | 1      | 2.78%   |
| TO Exter            | 1        | 1      | 2.78%   |
| Team                | 1        | 1      | 2.78%   |
| PNY                 | 1        | 1      | 2.78%   |
| Patriot             | 1        | 1      | 2.78%   |
| LITEONIT            | 1        | 1      | 2.78%   |
| Kston               | 1        | 3      | 2.78%   |
| Intel               | 1        | 1      | 2.78%   |
| Gigabyte Technology | 1        | 1      | 2.78%   |
| Emtec               | 1        | 1      | 2.78%   |
| Apacer              | 1        | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 40       | 63     | 47.62%  |
| SSD     | 33       | 40     | 39.29%  |
| NVMe    | 8        | 9      | 9.52%   |
| MMC     | 2        | 2      | 2.38%   |
| Unknown | 1        | 3      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 57       | 99     | 80.28%  |
| NVMe | 8        | 9      | 11.27%  |
| SAS  | 4        | 7      | 5.63%   |
| MMC  | 2        | 2      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 69     | 64.1%   |
| 0.51-1.0   | 13       | 15     | 16.67%  |
| 1.01-2.0   | 10       | 12     | 12.82%  |
| 2.01-3.0   | 3        | 4      | 3.85%   |
| 3.01-4.0   | 1        | 1      | 1.28%   |
| 4.01-10.0  | 1        | 2      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 17       | 27.42%  |
| 251-500        | 9        | 14.52%  |
| 21-50          | 7        | 11.29%  |
| 1001-2000      | 7        | 11.29%  |
| 501-1000       | 5        | 8.06%   |
| 51-100         | 5        | 8.06%   |
| More than 3000 | 4        | 6.45%   |
| 2001-3000      | 4        | 6.45%   |
| 1-20           | 4        | 6.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26       | 41.27%  |
| 21-50          | 10       | 15.87%  |
| 101-250        | 6        | 9.52%   |
| 501-1000       | 6        | 9.52%   |
| 51-100         | 6        | 9.52%   |
| More than 3000 | 3        | 4.76%   |
| 251-500        | 3        | 4.76%   |
| 1001-2000      | 2        | 3.17%   |
| 2001-3000      | 1        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 10%     |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 10%     |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 10%     |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 10%     |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 10%     |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 10%     |
| Maxtor 6L200M0 208GB                | 1        | 1      | 10%     |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 10%     |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 30%     |
| Seagate             | 2        | 2      | 20%     |
| Toshiba             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |
| Apacer              | 1        | 1      | 10%     |
| A-DATA Technology   | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 37.5%   |
| Seagate             | 2        | 2      | 25%     |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Maxtor              | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 80%     |
| SSD  | 2        | 2      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1        | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1        | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |
| HGST                | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 31       | 60     | 44.93%  |
| Works    | 25       | 44     | 36.23%  |
| Malfunc  | 10       | 10     | 14.49%  |
| Failed   | 3        | 3      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 33       | 44.59%  |
| AMD                         | 23       | 31.08%  |
| Nvidia                      | 3        | 4.05%   |
| JMicron Technology          | 3        | 4.05%   |
| SanDisk                     | 2        | 2.7%    |
| Samsung Electronics         | 2        | 2.7%    |
| Micron/Crucial Technology   | 2        | 2.7%    |
| ASMedia Technology          | 2        | 2.7%    |
| VIA Technologies            | 1        | 1.35%   |
| Seagate Technology          | 1        | 1.35%   |
| Marvell Technology Group    | 1        | 1.35%   |
| Kingston Technology Company | 1        | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 11       | 10.58%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10       | 9.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9        | 8.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5        | 4.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5        | 4.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4        | 3.85%   |
| Intel SATA Controller [RAID mode]                                                | 3        | 2.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3        | 2.88%   |
| AMD 400 Series Chipset SATA Controller                                           | 3        | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2        | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2        | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 1.92%   |
| AMD FCH IDE Controller                                                           | 2        | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                           | 2        | 1.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.96%   |
| VIA VIA VT6420 SATA RAID Controller                                              | 1        | 0.96%   |
| Seagate FireCuda 520 SSD                                                         | 1        | 0.96%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.96%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.96%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1        | 0.96%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1        | 0.96%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                     | 1        | 0.96%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.96%   |
| Nvidia MCP61 IDE                                                                 | 1        | 0.96%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1        | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 0.96%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 0.96%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1        | 0.96%   |
| JMicron JMB368 IDE controller                                                    | 1        | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1        | 0.96%   |
| JMicron JMB362 SATA Controller                                                   | 1        | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 0.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 0.96%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1        | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 51.25%  |
| IDE  | 27       | 33.75%  |
| NVMe | 8        | 10%     |
| RAID | 4        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 56.45%  |
| AMD    | 27       | 43.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Atom CPU D525 @ 1.80GHz                  | 3        | 4.84%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz         | 2        | 3.23%   |
| Intel Pentium D CPU 2.80GHz                    | 2        | 3.23%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 2        | 3.23%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.23%   |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1        | 1.61%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz            | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz    | 1        | 1.61%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 1        | 1.61%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 1        | 1.61%   |
| Intel Core i7 CPU 920 @ 2.67GHz                | 1        | 1.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.61%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 1        | 1.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.61%   |
| Intel Core i3-4170 CPU @ 3.70GHz               | 1        | 1.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.61%   |
| Intel Core i3-10105 CPU @ 3.70GHz              | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 1.61%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz           | 1        | 1.61%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 1.61%   |
| Intel Celeron CPU N3010 @ 1.04GHz              | 1        | 1.61%   |
| Intel Celeron CPU E3300 @ 2.50GHz              | 1        | 1.61%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 1        | 1.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1        | 1.61%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz              | 1        | 1.61%   |
| AMD Unknown Processor                          | 1        | 1.61%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1        | 1.61%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.61%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 1.61%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 1        | 1.61%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.61%   |
| AMD Ryzen 5 PRO 2400GE w/ Radeon Vega Graphics | 1        | 1.61%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 1        | 1.61%   |
| AMD Ryzen 5 3500X 6-Core Processor             | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 11.29%  |
| Intel Celeron           | 5        | 8.06%   |
| Intel Atom              | 5        | 8.06%   |
| AMD Ryzen 5             | 5        | 8.06%   |
| AMD Ryzen 7             | 4        | 6.45%   |
| Intel Pentium Dual      | 3        | 4.84%   |
| Intel Core i3           | 3        | 4.84%   |
| Intel Core 2 Duo        | 3        | 4.84%   |
| AMD FX                  | 3        | 4.84%   |
| Intel Xeon              | 2        | 3.23%   |
| Intel Pentium D         | 2        | 3.23%   |
| Intel Core 2 Quad       | 2        | 3.23%   |
| AMD Phenom II X4        | 2        | 3.23%   |
| AMD Athlon 64 X2        | 2        | 3.23%   |
| Other                   | 1        | 1.61%   |
| Intel Pentium Dual-Core | 1        | 1.61%   |
| Intel Core i9           | 1        | 1.61%   |
| Intel Core i7           | 1        | 1.61%   |
| AMD Ryzen 9             | 1        | 1.61%   |
| AMD Ryzen 5 PRO         | 1        | 1.61%   |
| AMD Phenom II X6        | 1        | 1.61%   |
| AMD GX                  | 1        | 1.61%   |
| AMD G                   | 1        | 1.61%   |
| AMD Athlon II X3        | 1        | 1.61%   |
| AMD Athlon II X2        | 1        | 1.61%   |
| AMD A8                  | 1        | 1.61%   |
| AMD A4                  | 1        | 1.61%   |
| AMD A10                 | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 22       | 35.48%  |
| 2      | 22       | 35.48%  |
| 6      | 6        | 9.68%   |
| 8      | 5        | 8.06%   |
| 3      | 3        | 4.84%   |
| 1      | 3        | 4.84%   |
| 10     | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 64.52%  |
| 2      | 22       | 35.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 62       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 51.61%  |
| 0x1067a    | 3        | 4.84%   |
| 0x6fb      | 2        | 3.23%   |
| 0x406c4    | 2        | 3.23%   |
| 0x306c3    | 2        | 3.23%   |
| 0x106ca    | 2        | 3.23%   |
| 0x010000db | 2        | 3.23%   |
| 0xa0653    | 1        | 1.61%   |
| 0x906ea    | 1        | 1.61%   |
| 0x706a8    | 1        | 1.61%   |
| 0x506e3    | 1        | 1.61%   |
| 0x206a7    | 1        | 1.61%   |
| 0x106a5    | 1        | 1.61%   |
| 0x0a50000c | 1        | 1.61%   |
| 0x0a50000b | 1        | 1.61%   |
| 0x0a201009 | 1        | 1.61%   |
| 0x08701021 | 1        | 1.61%   |
| 0x08701013 | 1        | 1.61%   |
| 0x08001138 | 1        | 1.61%   |
| 0x0700010f | 1        | 1.61%   |
| 0x06003106 | 1        | 1.61%   |
| 0x06001119 | 1        | 1.61%   |
| 0x06000852 | 1        | 1.61%   |
| 0x010000c7 | 1        | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 5        | 8.06%   |
| K10           | 5        | 8.06%   |
| Core          | 5        | 8.06%   |
| Zen 3         | 4        | 6.45%   |
| Zen+          | 3        | 4.84%   |
| Silvermont    | 3        | 4.84%   |
| SandyBridge   | 3        | 4.84%   |
| Piledriver    | 3        | 4.84%   |
| K8 Hammer     | 3        | 4.84%   |
| Haswell       | 3        | 4.84%   |
| Bonnell       | 3        | 4.84%   |
| Zen 2         | 2        | 3.23%   |
| Zen           | 2        | 3.23%   |
| Skylake       | 2        | 3.23%   |
| NetBurst      | 2        | 3.23%   |
| Nehalem       | 2        | 3.23%   |
| IvyBridge     | 2        | 3.23%   |
| Goldmont plus | 2        | 3.23%   |
| CometLake     | 2        | 3.23%   |
| Steamroller   | 1        | 1.61%   |
| KabyLake      | 1        | 1.61%   |
| K10 Llano     | 1        | 1.61%   |
| Jaguar        | 1        | 1.61%   |
| Bulldozer     | 1        | 1.61%   |
| Bobcat        | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 27       | 40.91%  |
| Nvidia | 24       | 36.36%  |
| Intel  | 15       | 22.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [ION]                                                                       | 3        | 4.23%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 4.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 4.23%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 4.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.82%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 2.82%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 2.82%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 2.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.82%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 1.41%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.41%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.41%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 1.41%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 1.41%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 1.41%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 1.41%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 1.41%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.41%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.41%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 1.41%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 1.41%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.41%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.41%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1        | 1.41%   |
| Nvidia C78 [GeForce 9100]                                                                | 1        | 1.41%   |
| Nvidia C77 [GeForce 8200]                                                                | 1        | 1.41%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 1.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.41%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.41%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.41%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1        | 1.41%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.41%   |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1        | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 21       | 33.87%  |
| 1 x AMD            | 21       | 33.87%  |
| 1 x Intel          | 13       | 20.97%  |
| 2 x AMD            | 3        | 4.84%   |
| AMD + Nvidia       | 2        | 3.23%   |
| Intel + 2 x Nvidia | 1        | 1.61%   |
| Intel + 2 x AMD    | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 50       | 80.65%  |
| Proprietary | 9        | 14.52%  |
| Unknown     | 3        | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 59.68%  |
| 0.01-0.5   | 9        | 14.52%  |
| 7.01-8.0   | 5        | 8.06%   |
| 0.51-1.0   | 5        | 8.06%   |
| 3.01-4.0   | 2        | 3.23%   |
| 8.01-16.0  | 2        | 3.23%   |
| 2.01-3.0   | 1        | 1.61%   |
| 1.01-2.0   | 1        | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 20.34%  |
| Dell                 | 8        | 13.56%  |
| Hewlett-Packard      | 6        | 10.17%  |
| Goldstar             | 5        | 8.47%   |
| Philips              | 4        | 6.78%   |
| Eizo                 | 3        | 5.08%   |
| Ancor Communications | 3        | 5.08%   |
| Acer                 | 3        | 5.08%   |
| Vizio                | 1        | 1.69%   |
| VHT                  | 1        | 1.69%   |
| Unknown              | 1        | 1.69%   |
| Sony                 | 1        | 1.69%   |
| SNC                  | 1        | 1.69%   |
| Sharp                | 1        | 1.69%   |
| Sampo                | 1        | 1.69%   |
| Positivo             | 1        | 1.69%   |
| MSI                  | 1        | 1.69%   |
| LG Electronics       | 1        | 1.69%   |
| Iiyama               | 1        | 1.69%   |
| HannStar             | 1        | 1.69%   |
| Daewoo               | 1        | 1.69%   |
| Compal               | 1        | 1.69%   |
| BenQ                 | 1        | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 3.33%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                   | 1        | 1.67%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.67%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.67%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.67%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.67%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.67%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.67%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 1.67%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 1.67%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.67%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.67%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch    | 1        | 1.67%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.67%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.67%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.67%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch            | 1        | 1.67%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.67%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.67%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.67%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.67%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.67%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 509x286mm 23.0-inch         | 1        | 1.67%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch          | 1        | 1.67%   |
| Hewlett-Packard E201 HWP305E 1600x900 443x249mm 20.0-inch            | 1        | 1.67%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch           | 1        | 1.67%   |
| Hewlett-Packard 2310 HWP2890 1920x1080 510x287mm 23.0-inch           | 1        | 1.67%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 1.67%   |
| HannStar HL190APB HSD62C3 1366x768 410x230mm 18.5-inch               | 1        | 1.67%   |
| Goldstar Ultra HD GSM5B08 3780x2160 600x340mm 27.2-inch              | 1        | 1.67%   |
| Goldstar M2394D GSM56C4 1920x1080 509x286mm 23.0-inch                | 1        | 1.67%   |
| Goldstar M197WD GSM4BA2 1360x768 410x230mm 18.5-inch                 | 1        | 1.67%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 1        | 1.67%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.67%   |
| Eizo S1932 ENC1940 1280x1024 376x301mm 19.0-inch                     | 1        | 1.67%   |
| Eizo M1700 ENC1789 1280x1024 338x271mm 17.1-inch                     | 1        | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 22       | 38.6%   |
| 1280x1024 (SXGA)   | 6        | 10.53%  |
| 1680x1050 (WSXGA+) | 5        | 8.77%   |
| 1600x900 (HD+)     | 5        | 8.77%   |
| 1366x768 (WXGA)    | 5        | 8.77%   |
| 1440x900 (WXGA+)   | 3        | 5.26%   |
| 2560x1440 (QHD)    | 2        | 3.51%   |
| 1360x768           | 2        | 3.51%   |
| 800x600            | 1        | 1.75%   |
| 3840x2160 (4K)     | 1        | 1.75%   |
| 2560x1600          | 1        | 1.75%   |
| 1920x1200 (WUXGA)  | 1        | 1.75%   |
| 1280x768           | 1        | 1.75%   |
| 1280x720 (HD)      | 1        | 1.75%   |
| 1024x768 (XGA)     | 1        | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 12.07%  |
| 18      | 7        | 12.07%  |
| 23      | 6        | 10.34%  |
| Unknown | 6        | 10.34%  |
| 22      | 5        | 8.62%   |
| 24      | 4        | 6.9%    |
| 21      | 4        | 6.9%    |
| 20      | 4        | 6.9%    |
| 19      | 4        | 6.9%    |
| 17      | 3        | 5.17%   |
| 72      | 1        | 1.72%   |
| 49      | 1        | 1.72%   |
| 47      | 1        | 1.72%   |
| 43      | 1        | 1.72%   |
| 34      | 1        | 1.72%   |
| 15      | 1        | 1.72%   |
| 14      | 1        | 1.72%   |
| 8       | 1        | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 22       | 37.93%  |
| 501-600     | 17       | 29.31%  |
| Unknown     | 6        | 10.34%  |
| 301-350     | 4        | 6.9%    |
| 351-400     | 3        | 5.17%   |
| 1001-1500   | 2        | 3.45%   |
| 701-800     | 1        | 1.72%   |
| 1501-2000   | 1        | 1.72%   |
| 101-200     | 1        | 1.72%   |
| 901-1000    | 1        | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 62.5%   |
| 16/10   | 9        | 16.07%  |
| Unknown | 5        | 8.93%   |
| 5/4     | 4        | 7.14%   |
| 4/3     | 3        | 5.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 28.07%  |
| 151-200        | 10       | 17.54%  |
| 141-150        | 8        | 14.04%  |
| 301-350        | 7        | 12.28%  |
| Unknown        | 6        | 10.53%  |
| 501-1000       | 3        | 5.26%   |
| More than 1000 | 2        | 3.51%   |
| 81-90          | 1        | 1.75%   |
| 1-40           | 1        | 1.75%   |
| 251-300        | 1        | 1.75%   |
| 131-140        | 1        | 1.75%   |
| 111-120        | 1        | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 63.64%  |
| 101-120 | 8        | 14.55%  |
| Unknown | 6        | 10.91%  |
| 1-50    | 5        | 9.09%   |
| 161-240 | 1        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 88.71%  |
| 2     | 5        | 8.06%   |
| 0     | 2        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 44.32%  |
| Intel                           | 17       | 19.32%  |
| Qualcomm Atheros                | 9        | 10.23%  |
| TP-Link                         | 4        | 4.55%   |
| Broadcom                        | 3        | 3.41%   |
| Samsung Electronics             | 2        | 2.27%   |
| Qualcomm Atheros Communications | 2        | 2.27%   |
| Nvidia                          | 2        | 2.27%   |
| MediaTek                        | 2        | 2.27%   |
| VIA Technologies                | 1        | 1.14%   |
| Trident Microsystems            | 1        | 1.14%   |
| Ralink                          | 1        | 1.14%   |
| NetGear                         | 1        | 1.14%   |
| Marvell Technology Group        | 1        | 1.14%   |
| Broadcom Limited                | 1        | 1.14%   |
| ASUSTek Computer                | 1        | 1.14%   |
| Accton Technology               | 1        | 1.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 34       | 35.79%  |
| Intel Ethernet Controller I225-V                                    | 3        | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 3.16%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 2.11%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 2.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 2.11%   |
| Nvidia MCP77 Ethernet                                               | 2        | 2.11%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 2.11%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 2.11%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 2.11%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 1        | 1.05%   |
| Trident Microsystems 4DWave DX                                      | 1        | 1.05%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 1.05%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 1.05%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 1.05%   |
| TP-Link 802.11ac NIC                                                | 1        | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.05%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 1.05%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 1.05%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 1.05%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 1.05%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 1        | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 1.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 1.05%   |
| NetGear A6210                                                       | 1        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 1.05%   |
| Intel Wireless 7265                                                 | 1        | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 23.33%  |
| Intel                           | 5        | 16.67%  |
| TP-Link                         | 4        | 13.33%  |
| Qualcomm Atheros                | 4        | 13.33%  |
| Qualcomm Atheros Communications | 2        | 6.67%   |
| MediaTek                        | 2        | 6.67%   |
| Broadcom                        | 2        | 6.67%   |
| Ralink                          | 1        | 3.33%   |
| NetGear                         | 1        | 3.33%   |
| Broadcom Limited                | 1        | 3.33%   |
| ASUSTek Computer                | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 6.67%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 6.67%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 6.67%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 3.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 3.33%   |
| TP-Link 802.11ac NIC                                                | 1        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 3.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 3.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 3.33%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 3.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 3.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 3.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 3.33%   |
| NetGear A6210                                                       | 1        | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 3.33%   |
| Intel Wireless 7265                                                 | 1        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                 | 1        | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 3.33%   |
| Intel Centrino Advanced-N 6235                                      | 1        | 3.33%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 3.33%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]      | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 38       | 58.46%  |
| Intel                    | 12       | 18.46%  |
| Qualcomm Atheros         | 6        | 9.23%   |
| Samsung Electronics      | 2        | 3.08%   |
| Nvidia                   | 2        | 3.08%   |
| VIA Technologies         | 1        | 1.54%   |
| Trident Microsystems     | 1        | 1.54%   |
| Marvell Technology Group | 1        | 1.54%   |
| Broadcom                 | 1        | 1.54%   |
| Accton Technology        | 1        | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34       | 52.31%  |
| Intel Ethernet Controller I225-V                                  | 3        | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 3.08%   |
| Nvidia MCP77 Ethernet                                             | 2        | 3.08%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.54%   |
| Trident Microsystems 4DWave DX                                    | 1        | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.54%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.54%   |
| Accton SMC2-1211TX                                                | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 69.32%  |
| WiFi     | 27       | 30.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 69.84%  |
| WiFi     | 19       | 30.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 67.74%  |
| 2     | 17       | 27.42%  |
| 4     | 1        | 1.61%   |
| 3     | 1        | 1.61%   |
| 0     | 1        | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 72.58%  |
| Yes  | 17       | 27.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 30.77%  |
| MediaTek                        | 2        | 15.38%  |
| Cambridge Silicon Radio         | 2        | 15.38%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| Qualcomm Atheros Communications | 1        | 7.69%   |
| Logitech                        | 1        | 7.69%   |
| Foxconn / Hon Hai               | 1        | 7.69%   |
| Broadcom                        | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                            | 2        | 15.38%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 15.38%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 7.69%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 33       | 35.48%  |
| AMD                                          | 29       | 31.18%  |
| Nvidia                                       | 21       | 22.58%  |
| C-Media Electronics                          | 2        | 2.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.08%   |
| VIA Technologies                             | 1        | 1.08%   |
| Sony                                         | 1        | 1.08%   |
| Razer USA                                    | 1        | 1.08%   |
| Focusrite-Novation                           | 1        | 1.08%   |
| Ensoniq                                      | 1        | 1.08%   |
| Creative Labs                                | 1        | 1.08%   |
| ASUSTek Computer                             | 1        | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13       | 11.61%  |
| Nvidia High Definition Audio Controller                                    | 7        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 4.46%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 2.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.68%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3        | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.68%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 1.79%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.79%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.79%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.89%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.89%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.89%   |
| Razer USA Razer Kraken X USB                                               | 1        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.89%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.89%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.89%   |
| Intel Audio device                                                         | 1        | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10       | 28.57%  |
| Micron Technology   | 5        | 14.29%  |
| Kingston            | 5        | 14.29%  |
| G.Skill             | 4        | 11.43%  |
| SK hynix            | 3        | 8.57%   |
| Samsung Electronics | 2        | 5.71%   |
| Corsair             | 2        | 5.71%   |
| Nanya Technology    | 1        | 2.86%   |
| GOODRAM             | 1        | 2.86%   |
| Elpida              | 1        | 2.86%   |
| Unknown             | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 1        | 2.5%    |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 2.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 2.5%    |
| Unknown RAM Module 2GB DIMM                              | 1        | 2.5%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 2.5%    |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s | 1        | 2.5%    |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s               | 1        | 2.5%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 2.5%    |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 2.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 2.5%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s       | 1        | 2.5%    |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 2.5%    |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s   | 1        | 2.5%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 1        | 2.5%    |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s       | 1        | 2.5%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 2.5%    |
| Kingston RAM KN2M64-ETB 8GB DIMM DDR3 1600MT/s           | 1        | 2.5%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 2.5%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3266MT/s    | 1        | 2.5%    |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s  | 1        | 2.5%    |
| Kingston RAM 99U5474-028.A 4GB DIMM DDR3 1333MT/s        | 1        | 2.5%    |
| GOODRAM RAM IRX3200D464L16S/8G 8GB DIMM DDR4 3200MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3666MT/s      | 1        | 2.5%    |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s    | 1        | 2.5%    |
| G.Skill RAM F4-3000C15-8GVKB 8GB DIMM DDR4 3066MT/s      | 1        | 2.5%    |
| G.Skill RAM F3-2400C11-4GXM 4GB DIMM DDR3 1600MT/s       | 1        | 2.5%    |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4GB DIMM DDR3 1333MT/s      | 1        | 2.5%    |
| Elpida RAM EBJ21EE8BDFA-DJ-F 2048MB DIMM DDR3 1333MT/s   | 1        | 2.5%    |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 1        | 2.5%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 2.5%    |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.5%    |
| Unknown                                                  | 1        | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 13       | 39.39%  |
| DDR3    | 9        | 27.27%  |
| DDR2    | 5        | 15.15%  |
| Unknown | 4        | 12.12%  |
| SDRAM   | 2        | 6.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 25       | 75.76%  |
| SODIMM | 8        | 24.24%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 32.43%  |
| 2048  | 10       | 27.03%  |
| 4096  | 9        | 24.32%  |
| 16384 | 4        | 10.81%  |
| 32768 | 1        | 2.7%    |
| 1024  | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 24.24%  |
| 3200    | 4        | 12.12%  |
| 1333    | 3        | 9.09%   |
| 800     | 2        | 6.06%   |
| 667     | 2        | 6.06%   |
| Unknown | 2        | 6.06%   |
| 3666    | 1        | 3.03%   |
| 3400    | 1        | 3.03%   |
| 3266    | 1        | 3.03%   |
| 3066    | 1        | 3.03%   |
| 3000    | 1        | 3.03%   |
| 2800    | 1        | 3.03%   |
| 2667    | 1        | 3.03%   |
| 2400    | 1        | 3.03%   |
| 2133    | 1        | 3.03%   |
| 2048    | 1        | 3.03%   |
| 1066    | 1        | 3.03%   |
| 333     | 1        | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Brother Industries  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 25%     |
| Canon PIXMA MP250       | 1        | 25%     |
| Canon CanoScan LiDE 300 | 1        | 25%     |
| Brother DCP-7055W       | 1        | 25%     |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 3        | 42.86%  |
| WaveRider Communications | 1        | 14.29%  |
| Pixart Imaging           | 1        | 14.29%  |
| Microsoft                | 1        | 14.29%  |
| AVerMedia Technologies   | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Webcam C270                 | 2        | 28.57%  |
| WaveRider USB 2.0 Camera             | 1        | 14.29%  |
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 14.29%  |
| Microsoft LifeCam VX-800             | 1        | 14.29%  |
| Logitech HD Webcam C615              | 1        | 14.29%  |
| AVerMedia Live Streamer CAM 313      | 1        | 14.29%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Cherry | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 56       | 88.89%  |
| 1     | 7        | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 4        | 57.14%  |
| Net/wireless  | 3        | 42.86%  |

