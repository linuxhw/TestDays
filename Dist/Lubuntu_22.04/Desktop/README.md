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

Total: 68

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic           | 9        | 15.52%  |
| 5.15.0-41-generic           | 5        | 8.62%   |
| 5.15.0-56-generic           | 4        | 6.9%    |
| 5.15.0-47-generic           | 4        | 6.9%    |
| 5.15.0-25-generic           | 4        | 6.9%    |
| 5.15.0-48-generic           | 3        | 5.17%   |
| 5.15.0-40-generic           | 3        | 5.17%   |
| 5.15.0-39-generic           | 3        | 5.17%   |
| 5.15.0-53-generic           | 2        | 3.45%   |
| 5.15.0-52-generic           | 2        | 3.45%   |
| 5.15.0-50-generic           | 2        | 3.45%   |
| 5.15.0-46-generic           | 2        | 3.45%   |
| 5.15.0-30-generic           | 2        | 3.45%   |
| 5.15.0-27-generic           | 2        | 3.45%   |
| 6.1.0-custom                | 1        | 1.72%   |
| 6.0.8-060008-generic        | 1        | 1.72%   |
| 5.19.0-16.2-liquorix-amd64  | 1        | 1.72%   |
| 5.15.0-59-lowlatency        | 1        | 1.72%   |
| 5.15.0-58-generic           | 1        | 1.72%   |
| 5.15.0-57-generic           | 1        | 1.72%   |
| 5.15.0-41-lowlatency        | 1        | 1.72%   |
| 5.15.0-362206031516-generic | 1        | 1.72%   |
| 5.15.0-35-generic           | 1        | 1.72%   |
| 5.15.0-23-generic           | 1        | 1.72%   |
| 5.15.0-18-generic           | 1        | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 53       | 94.64%  |
| 6.1.0   | 1        | 1.79%   |
| 6.0.8   | 1        | 1.79%   |
| 5.19.0  | 1        | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 53       | 94.64%  |
| 6.1     | 1        | 1.79%   |
| 6.0     | 1        | 1.79%   |
| 5.19    | 1        | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 52       | 94.55%  |
| LXDE | 2        | 3.64%   |
| XFCE | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 52       | 91.23%  |
| Tty         | 3        | 5.26%   |
| Wayland     | 1        | 1.75%   |
| Unspecified | 1        | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 47       | 85.45%  |
| LightDM | 3        | 5.45%   |
| Unknown | 2        | 3.64%   |
| XDM     | 1        | 1.82%   |
| SLiM    | 1        | 1.82%   |
| LXDM    | 1        | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 25.45%  |
| fr_FR | 9        | 16.36%  |
| de_DE | 5        | 9.09%   |
| es_ES | 4        | 7.27%   |
| en_GB | 4        | 7.27%   |
| it_IT | 3        | 5.45%   |
| es_CR | 2        | 3.64%   |
| es_AR | 2        | 3.64%   |
| C     | 2        | 3.64%   |
| sv_SE | 1        | 1.82%   |
| ru_UA | 1        | 1.82%   |
| pt_BR | 1        | 1.82%   |
| pl_PL | 1        | 1.82%   |
| nl_BE | 1        | 1.82%   |
| es_MX | 1        | 1.82%   |
| en_AU | 1        | 1.82%   |
| en_AG | 1        | 1.82%   |
| el_GR | 1        | 1.82%   |
| cv_RU | 1        | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 43       | 78.18%  |
| EFI  | 12       | 21.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 52       | 94.55%  |
| Overlay | 2        | 3.64%   |
| Btrfs   | 1        | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 38.18%  |
| MBR     | 17       | 30.91%  |
| Unknown | 17       | 30.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 81.82%  |
| Yes       | 10       | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 52.73%  |
| Yes       | 26       | 47.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 20%     |
| MSI                 | 9        | 16.36%  |
| Dell                | 8        | 14.55%  |
| ASRock              | 5        | 9.09%   |
| Hewlett-Packard     | 4        | 7.27%   |
| Gigabyte Technology | 3        | 5.45%   |
| Unknown             | 3        | 5.45%   |
| Lenovo              | 2        | 3.64%   |
| AMI                 | 2        | 3.64%   |
| Acer                | 2        | 3.64%   |
| ZOTAC               | 1        | 1.82%   |
| Positivo            | 1        | 1.82%   |
| Pegatron            | 1        | 1.82%   |
| NEC Computers       | 1        | 1.82%   |
| Intel               | 1        | 1.82%   |
| Fujitsu             | 1        | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 3        | 5.45%   |
| Dell Dimension 9100                    | 2        | 3.64%   |
| ZOTAC NM10                             | 1        | 1.82%   |
| Positivo POS-AG31AP                    | 1        | 1.82%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 1.82%   |
| NEC Computers ECS-945G                 | 1        | 1.82%   |
| MSI MS-7D09                            | 1        | 1.82%   |
| MSI MS-7C96                            | 1        | 1.82%   |
| MSI MS-7C51                            | 1        | 1.82%   |
| MSI MS-7C37                            | 1        | 1.82%   |
| MSI MS-7B86                            | 1        | 1.82%   |
| MSI MS-7978                            | 1        | 1.82%   |
| MSI MS-7641                            | 1        | 1.82%   |
| MSI MS-7501                            | 1        | 1.82%   |
| MSI MS-7032                            | 1        | 1.82%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1.82%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1.82%   |
| Intel BTC-T37                          | 1        | 1.82%   |
| HP Z400 Workstation                    | 1        | 1.82%   |
| HP t620 Quad Core TC                   | 1        | 1.82%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 1.82%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1.82%   |
| Gigabyte G31M-S2C                      | 1        | 1.82%   |
| Gigabyte G31M-ES2C                     | 1        | 1.82%   |
| Gigabyte F2A58M-HD2                    | 1        | 1.82%   |
| Fujitsu FUTRO S900                     | 1        | 1.82%   |
| Dell Vostro 410                        | 1        | 1.82%   |
| Dell Studio XPS 435MT                  | 1        | 1.82%   |
| Dell Precision T3610                   | 1        | 1.82%   |
| Dell OptiPlex 7020                     | 1        | 1.82%   |
| Dell OptiPlex 7010                     | 1        | 1.82%   |
| Dell OptiPlex 3020M                    | 1        | 1.82%   |
| ASUS TUF B450-PRO GAMING               | 1        | 1.82%   |
| ASUS ROG STRIX B450-F GAMING II        | 1        | 1.82%   |
| ASUS PRIME X370-A                      | 1        | 1.82%   |
| ASUS PRIME B350M-E                     | 1        | 1.82%   |
| ASUS M5A97 PRO                         | 1        | 1.82%   |
| ASUS M5A78L LE                         | 1        | 1.82%   |
| ASUS M4N78-AM                          | 1        | 1.82%   |
| ASUS M4A87TD/USB3                      | 1        | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 3        | 5.45%   |
| Unknown                | 3        | 5.45%   |
| Lenovo ThinkCentre     | 2        | 3.64%   |
| Dell Dimension         | 2        | 3.64%   |
| ASUS PRIME             | 2        | 3.64%   |
| ZOTAC NM10             | 1        | 1.82%   |
| Positivo POS-AG31AP    | 1        | 1.82%   |
| Pegatron AY748AA-ABA   | 1        | 1.82%   |
| NEC Computers ECS-945G | 1        | 1.82%   |
| MSI MS-7D09            | 1        | 1.82%   |
| MSI MS-7C96            | 1        | 1.82%   |
| MSI MS-7C51            | 1        | 1.82%   |
| MSI MS-7C37            | 1        | 1.82%   |
| MSI MS-7B86            | 1        | 1.82%   |
| MSI MS-7978            | 1        | 1.82%   |
| MSI MS-7641            | 1        | 1.82%   |
| MSI MS-7501            | 1        | 1.82%   |
| MSI MS-7032            | 1        | 1.82%   |
| Intel BTC-T37          | 1        | 1.82%   |
| HP Z400                | 1        | 1.82%   |
| HP t620                | 1        | 1.82%   |
| HP Slim                | 1        | 1.82%   |
| HP Compaq              | 1        | 1.82%   |
| Gigabyte G31M-S2C      | 1        | 1.82%   |
| Gigabyte G31M-ES2C     | 1        | 1.82%   |
| Gigabyte F2A58M-HD2    | 1        | 1.82%   |
| Fujitsu FUTRO          | 1        | 1.82%   |
| Dell Vostro            | 1        | 1.82%   |
| Dell Studio            | 1        | 1.82%   |
| Dell Precision         | 1        | 1.82%   |
| ASUS TUF               | 1        | 1.82%   |
| ASUS ROG               | 1        | 1.82%   |
| ASUS M5A97             | 1        | 1.82%   |
| ASUS M5A78L            | 1        | 1.82%   |
| ASUS M4N78-AM          | 1        | 1.82%   |
| ASUS M4A87TD           | 1        | 1.82%   |
| ASUS M4A785TD-V        | 1        | 1.82%   |
| ASUS IP4BL-ME          | 1        | 1.82%   |
| ASUS EB1501P           | 1        | 1.82%   |
| ASRock ION3D-HT        | 1        | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 6        | 10.91%  |
| 2008 | 6        | 10.91%  |
| 2017 | 5        | 9.09%   |
| 2020 | 4        | 7.27%   |
| 2015 | 4        | 7.27%   |
| 2014 | 4        | 7.27%   |
| 2011 | 4        | 7.27%   |
| 2009 | 4        | 7.27%   |
| 2021 | 3        | 5.45%   |
| 2019 | 3        | 5.45%   |
| 2007 | 3        | 5.45%   |
| 2016 | 2        | 3.64%   |
| 2013 | 2        | 3.64%   |
| 2006 | 2        | 3.64%   |
| 2022 | 1        | 1.82%   |
| 2018 | 1        | 1.82%   |
| 2001 | 1        | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 55       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 54       | 98.18%  |
| Enabled  | 1        | 1.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 12       | 21.82%  |
| 4.01-8.0    | 11       | 20%     |
| 16.01-24.0  | 10       | 18.18%  |
| 8.01-16.0   | 8        | 14.55%  |
| 32.01-64.0  | 5        | 9.09%   |
| 1.01-2.0    | 4        | 7.27%   |
| 0.51-1.0    | 3        | 5.45%   |
| 2.01-3.0    | 1        | 1.82%   |
| 64.01-256.0 | 1        | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 42.86%  |
| 0.51-1.0  | 13       | 23.21%  |
| 2.01-3.0  | 10       | 17.86%  |
| 4.01-8.0  | 5        | 8.93%   |
| 3.01-4.0  | 2        | 3.57%   |
| 8.01-16.0 | 1        | 1.79%   |
| 0.01-0.5  | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 47.27%  |
| 2      | 19       | 34.55%  |
| 3      | 3        | 5.45%   |
| 5      | 2        | 3.64%   |
| 4      | 2        | 3.64%   |
| 7      | 1        | 1.82%   |
| 6      | 1        | 1.82%   |
| 0      | 1        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 60%     |
| Yes       | 22       | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 98.18%  |
| No        | 1        | 1.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 58.18%  |
| Yes       | 23       | 41.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 83.93%  |
| Yes       | 9        | 16.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 12       | 21.82%  |
| France     | 9        | 16.36%  |
| Germany    | 5        | 9.09%   |
| Spain      | 4        | 7.27%   |
| UK         | 3        | 5.45%   |
| Poland     | 3        | 5.45%   |
| Italy      | 3        | 5.45%   |
| Costa Rica | 2        | 3.64%   |
| Brazil     | 2        | 3.64%   |
| Argentina  | 2        | 3.64%   |
| Ukraine    | 1        | 1.82%   |
| Sweden     | 1        | 1.82%   |
| Romania    | 1        | 1.82%   |
| Mexico     | 1        | 1.82%   |
| Latvia     | 1        | 1.82%   |
| Ireland    | 1        | 1.82%   |
| Greece     | 1        | 1.82%   |
| Bulgaria   | 1        | 1.82%   |
| Belgium    | 1        | 1.82%   |
| Australia  | 1        | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Largo                | 2        | 3.57%   |
| Heredia              | 2        | 3.57%   |
| Wetteren             | 1        | 1.79%   |
| Washington           | 1        | 1.79%   |
| Warsaw               | 1        | 1.79%   |
| Versailles           | 1        | 1.79%   |
| Varna                | 1        | 1.79%   |
| Valentigney          | 1        | 1.79%   |
| Tandil               | 1        | 1.79%   |
| Sonico               | 1        | 1.79%   |
| Riverenert           | 1        | 1.79%   |
| Rio Segundo          | 1        | 1.79%   |
| Richmond             | 1        | 1.79%   |
| Resistencia          | 1        | 1.79%   |
| Port Washington      | 1        | 1.79%   |
| Paris                | 1        | 1.79%   |
| Palencia             | 1        | 1.79%   |
| Ostrów Wielkopolski | 1        | 1.79%   |
| Oberkotzau           | 1        | 1.79%   |
| Novo Gama            | 1        | 1.79%   |
| Notting Hill Gate    | 1        | 1.79%   |
| Nederland            | 1        | 1.79%   |
| Mostoles             | 1        | 1.79%   |
| Mobile               | 1        | 1.79%   |
| Mexico City          | 1        | 1.79%   |
| Melbourne            | 1        | 1.79%   |
| Marseille            | 1        | 1.79%   |
| Madrid               | 1        | 1.79%   |
| Lebanon              | 1        | 1.79%   |
| Larissa              | 1        | 1.79%   |
| Kyiv                 | 1        | 1.79%   |
| Koblenz              | 1        | 1.79%   |
| Kielce               | 1        | 1.79%   |
| Karlstad             | 1        | 1.79%   |
| Huelva               | 1        | 1.79%   |
| Hemel Hempstead      | 1        | 1.79%   |
| Hayes                | 1        | 1.79%   |
| Frankfurt am Main    | 1        | 1.79%   |
| Enniscorthy          | 1        | 1.79%   |
| Denver               | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 21     | 19.78%  |
| WDC                 | 12       | 16     | 13.19%  |
| Samsung Electronics | 12       | 16     | 13.19%  |
| Kingston            | 7        | 8      | 7.69%   |
| Hitachi             | 6        | 7      | 6.59%   |
| SanDisk             | 4        | 4      | 4.4%    |
| Toshiba             | 3        | 3      | 3.3%    |
| Crucial             | 3        | 3      | 3.3%    |
| Maxtor              | 2        | 2      | 2.2%    |
| HGST                | 2        | 2      | 2.2%    |
| GOODRAM             | 2        | 2      | 2.2%    |
| WD MediaMax         | 1        | 1      | 1.1%    |
| Unknown             | 1        | 1      | 1.1%    |
| Transcend           | 1        | 1      | 1.1%    |
| TO Exter            | 1        | 1      | 1.1%    |
| Team                | 1        | 1      | 1.1%    |
| T-FORCE             | 1        | 1      | 1.1%    |
| RSH-319             | 1        | 1      | 1.1%    |
| PNY                 | 1        | 1      | 1.1%    |
| Patriot             | 1        | 1      | 1.1%    |
| LITEONIT            | 1        | 1      | 1.1%    |
| Kston               | 1        | 3      | 1.1%    |
| Intel               | 1        | 1      | 1.1%    |
| HGST HUS            | 1        | 2      | 1.1%    |
| Gigabyte Technology | 1        | 1      | 1.1%    |
| External            | 1        | 1      | 1.1%    |
| Emtec               | 1        | 1      | 1.1%    |
| Apricorn            | 1        | 1      | 1.1%    |
| Apacer              | 1        | 1      | 1.1%    |
| AMD                 | 1        | 1      | 1.1%    |
| A-DATA Technology   | 1        | 1      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 5        | 5%      |
| Toshiba DT01ACA100 1TB               | 2        | 2%      |
| Seagate ST3120213AS 120GB            | 2        | 2%      |
| Samsung HD502HJ 500GB                | 2        | 2%      |
| Kingston SA400S37240G 240GB SSD      | 2        | 2%      |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 1%      |
| WDC WDS100T1X0E-00AFY0 1TB           | 1        | 1%      |
| WDC WD800BB-00CAA1 80GB              | 1        | 1%      |
| WDC WD5000LUCT-63RC2Y0 500GB         | 1        | 1%      |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 1%      |
| WDC WD3200BPVT-80JJ5T0 320GB         | 1        | 1%      |
| WDC WD3200BPVT-00HXZT3 320GB         | 1        | 1%      |
| WDC WD30EZRZ-00GXCB0 3TB             | 1        | 1%      |
| WDC WD2500KS-00MJB0 250GB            | 1        | 1%      |
| WDC WD2500AAJS-07M0A0 250GB          | 1        | 1%      |
| WDC WD20EZRX-00D8PB0 2TB             | 1        | 1%      |
| WDC WD20EZBX-00AYRA0 2TB             | 1        | 1%      |
| WDC WD10EZRZ-00Z5HB0 1TB             | 1        | 1%      |
| WDC WD10EURX-63C57Y0 1TB             | 1        | 1%      |
| WDC WD10EACS-00D6B1 1TB              | 1        | 1%      |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1        | 1%      |
| WD MediaMax WL250GSA872 250GB        | 1        | 1%      |
| Unknown 032G72  32GB                 | 1        | 1%      |
| Transcend TS128GSSD340 128GB         | 1        | 1%      |
| Toshiba MK6465GSX 640GB              | 1        | 1%      |
| TO Exter nal USB 3.0 500GB           | 1        | 1%      |
| Team T253E2002T 2TB SSD              | 1        | 1%      |
| T-FORCE 1TB                          | 1        | 1%      |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 1%      |
| Seagate ST500LM000-1EJ162 500GB      | 1        | 1%      |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1%      |
| Seagate ST3500418AS 500GB            | 1        | 1%      |
| Seagate ST3250823AS 250GB            | 1        | 1%      |
| Seagate ST3200826AS 200GB            | 1        | 1%      |
| Seagate ST2000NE001-2M5101 2TB       | 1        | 1%      |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1%      |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1%      |
| Seagate ST2000DM001-1CH164 2TB       | 1        | 1%      |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 1%      |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 34.62%  |
| WDC                 | 11       | 13     | 21.15%  |
| Samsung Electronics | 6        | 7      | 11.54%  |
| Hitachi             | 6        | 7      | 11.54%  |
| Toshiba             | 3        | 3      | 5.77%   |
| Maxtor              | 2        | 2      | 3.85%   |
| HGST                | 2        | 2      | 3.85%   |
| WD MediaMax         | 1        | 1      | 1.92%   |
| RSH-319             | 1        | 1      | 1.92%   |
| External            | 1        | 1      | 1.92%   |
| Apricorn            | 1        | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 21.21%  |
| Kingston            | 6        | 7      | 18.18%  |
| SanDisk             | 3        | 3      | 9.09%   |
| GOODRAM             | 2        | 2      | 6.06%   |
| Crucial             | 2        | 2      | 6.06%   |
| WDC                 | 1        | 1      | 3.03%   |
| Transcend           | 1        | 1      | 3.03%   |
| TO Exter            | 1        | 1      | 3.03%   |
| Team                | 1        | 1      | 3.03%   |
| PNY                 | 1        | 1      | 3.03%   |
| Patriot             | 1        | 1      | 3.03%   |
| LITEONIT            | 1        | 1      | 3.03%   |
| Kston               | 1        | 3      | 3.03%   |
| Intel               | 1        | 1      | 3.03%   |
| Gigabyte Technology | 1        | 1      | 3.03%   |
| Emtec               | 1        | 1      | 3.03%   |
| Apacer              | 1        | 1      | 3.03%   |
| A-DATA Technology   | 1        | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 36       | 58     | 48%     |
| SSD     | 30       | 37     | 40%     |
| NVMe    | 6        | 7      | 8%      |
| MMC     | 2        | 2      | 2.67%   |
| Unknown | 1        | 3      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 50       | 91     | 80.65%  |
| NVMe | 6        | 7      | 9.68%   |
| SAS  | 4        | 7      | 6.45%   |
| MMC  | 2        | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 64     | 64.29%  |
| 0.51-1.0   | 12       | 14     | 17.14%  |
| 1.01-2.0   | 8        | 10     | 11.43%  |
| 2.01-3.0   | 3        | 4      | 4.29%   |
| 3.01-4.0   | 1        | 1      | 1.43%   |
| 4.01-10.0  | 1        | 2      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 25.45%  |
| 251-500        | 7        | 12.73%  |
| 21-50          | 7        | 12.73%  |
| 1001-2000      | 5        | 9.09%   |
| 501-1000       | 5        | 9.09%   |
| 51-100         | 5        | 9.09%   |
| More than 3000 | 4        | 7.27%   |
| 2001-3000      | 4        | 7.27%   |
| 1-20           | 4        | 7.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 42.86%  |
| 21-50          | 10       | 17.86%  |
| 101-250        | 6        | 10.71%  |
| 501-1000       | 5        | 8.93%   |
| More than 3000 | 3        | 5.36%   |
| 251-500        | 3        | 5.36%   |
| 1001-2000      | 2        | 3.57%   |
| 51-100         | 2        | 3.57%   |
| 2001-3000      | 1        | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 12.5%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 12.5%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 12.5%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 12.5%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 12.5%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 12.5%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 25%     |
| WDC                 | 1        | 1      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Maxtor              | 1        | 1      | 12.5%   |
| Apacer              | 1        | 1      | 12.5%   |
| A-DATA Technology   | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 33.33%  |
| WDC                 | 1        | 1      | 16.67%  |
| Toshiba             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Maxtor              | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 75%     |
| SSD  | 2        | 2      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB | 1        | 1      | 50%     |
| HGST HTS725025A7 250GB    | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| HGST    | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 28       | 56     | 45.9%   |
| Works    | 23       | 41     | 37.7%   |
| Malfunc  | 8        | 8      | 13.11%  |
| Failed   | 2        | 2      | 3.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 29       | 45.31%  |
| AMD                         | 20       | 31.25%  |
| Nvidia                      | 3        | 4.69%   |
| JMicron Technology          | 3        | 4.69%   |
| SanDisk                     | 2        | 3.13%   |
| VIA Technologies            | 1        | 1.56%   |
| Seagate Technology          | 1        | 1.56%   |
| Samsung Electronics         | 1        | 1.56%   |
| Micron/Crucial Technology   | 1        | 1.56%   |
| Marvell Technology Group    | 1        | 1.56%   |
| Kingston Technology Company | 1        | 1.56%   |
| ASMedia Technology          | 1        | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 10.99%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 8.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 7.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.49%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4        | 4.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 4.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.3%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.2%    |
| AMD FCH IDE Controller                                                                  | 2        | 2.2%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.1%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 1.1%    |
| Seagate FireCuda 520 SSD                                                                | 1        | 1.1%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.1%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 1.1%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.1%    |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.1%    |
| Nvidia MCP61 IDE                                                                        | 1        | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.1%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.1%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.1%    |
| JMicron JMB368 IDE controller                                                           | 1        | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.1%    |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.1%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 1        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 52.86%  |
| IDE  | 24       | 34.29%  |
| NVMe | 6        | 8.57%   |
| RAID | 3        | 4.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 56.36%  |
| AMD    | 24       | 43.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Atom CPU D525 @ 1.80GHz                  | 3        | 5.45%   |
| Intel Pentium D CPU 2.80GHz                    | 2        | 3.64%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 2        | 3.64%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 3.64%   |
| Intel Xeon CPU W3565 @ 3.20GHz                 | 1        | 1.82%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz            | 1        | 1.82%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 1        | 1.82%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz         | 1        | 1.82%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 1        | 1.82%   |
| Intel Core i7 CPU 920 @ 2.67GHz                | 1        | 1.82%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 1        | 1.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i5-4590T CPU @ 2.00GHz              | 1        | 1.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.82%   |
| Intel Core i3-4170 CPU @ 3.70GHz               | 1        | 1.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.82%   |
| Intel Core i3-10105 CPU @ 3.70GHz              | 1        | 1.82%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 1        | 1.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 1.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 1.82%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz           | 1        | 1.82%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 1.82%   |
| Intel Celeron CPU N3010 @ 1.04GHz              | 1        | 1.82%   |
| Intel Celeron CPU E3300 @ 2.50GHz              | 1        | 1.82%   |
| Intel Celeron CPU 847 @ 1.10GHz                | 1        | 1.82%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1        | 1.82%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz              | 1        | 1.82%   |
| AMD Unknown Processor                          | 1        | 1.82%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1        | 1.82%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 1        | 1.82%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 1.82%   |
| AMD Ryzen 5 PRO 2400GE w/ Radeon Vega Graphics | 1        | 1.82%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 1        | 1.82%   |
| AMD Ryzen 5 3500X 6-Core Processor             | 1        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 1.82%   |
| AMD Phenom II X6 1090T Processor               | 1        | 1.82%   |
| AMD Phenom II X4 945 Processor                 | 1        | 1.82%   |
| AMD Phenom II X4 820 Processor                 | 1        | 1.82%   |
| AMD GX-415GA SOC with Radeon HD Graphics       | 1        | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 5        | 9.09%   |
| Intel Celeron      | 5        | 9.09%   |
| Intel Atom         | 5        | 9.09%   |
| AMD Ryzen 5        | 5        | 9.09%   |
| Intel Core i3      | 3        | 5.45%   |
| Intel Core 2 Duo   | 3        | 5.45%   |
| AMD FX             | 3        | 5.45%   |
| Intel Xeon         | 2        | 3.64%   |
| Intel Pentium Dual | 2        | 3.64%   |
| Intel Pentium D    | 2        | 3.64%   |
| Intel Core 2 Quad  | 2        | 3.64%   |
| AMD Ryzen 7        | 2        | 3.64%   |
| AMD Phenom II X4   | 2        | 3.64%   |
| AMD Athlon 64 X2   | 2        | 3.64%   |
| Other              | 1        | 1.82%   |
| Intel Core i9      | 1        | 1.82%   |
| Intel Core i7      | 1        | 1.82%   |
| AMD Ryzen 9        | 1        | 1.82%   |
| AMD Ryzen 5 PRO    | 1        | 1.82%   |
| AMD Phenom II X6   | 1        | 1.82%   |
| AMD GX             | 1        | 1.82%   |
| AMD G              | 1        | 1.82%   |
| AMD Athlon II X2   | 1        | 1.82%   |
| AMD A8             | 1        | 1.82%   |
| AMD A4             | 1        | 1.82%   |
| AMD A10            | 1        | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 38.18%  |
| 2      | 20       | 36.36%  |
| 6      | 5        | 9.09%   |
| 8      | 3        | 5.45%   |
| 1      | 3        | 5.45%   |
| 3      | 2        | 3.64%   |
| 10     | 1        | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 63.64%  |
| 2      | 20       | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 55       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 52.73%  |
| 0x6fb      | 2        | 3.64%   |
| 0x406c4    | 2        | 3.64%   |
| 0x306c3    | 2        | 3.64%   |
| 0x106ca    | 2        | 3.64%   |
| 0x1067a    | 2        | 3.64%   |
| 0xa0653    | 1        | 1.82%   |
| 0x706a8    | 1        | 1.82%   |
| 0x506e3    | 1        | 1.82%   |
| 0x206a7    | 1        | 1.82%   |
| 0x106a5    | 1        | 1.82%   |
| 0x0a50000c | 1        | 1.82%   |
| 0x0a50000b | 1        | 1.82%   |
| 0x0a201009 | 1        | 1.82%   |
| 0x08701021 | 1        | 1.82%   |
| 0x08001138 | 1        | 1.82%   |
| 0x0700010f | 1        | 1.82%   |
| 0x06003106 | 1        | 1.82%   |
| 0x06001119 | 1        | 1.82%   |
| 0x06000852 | 1        | 1.82%   |
| 0x010000db | 1        | 1.82%   |
| 0x010000c7 | 1        | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 4        | 7.27%   |
| K10           | 4        | 7.27%   |
| Core          | 4        | 7.27%   |
| Zen+          | 3        | 5.45%   |
| Zen 3         | 3        | 5.45%   |
| Silvermont    | 3        | 5.45%   |
| Piledriver    | 3        | 5.45%   |
| K8 Hammer     | 3        | 5.45%   |
| Haswell       | 3        | 5.45%   |
| Bonnell       | 3        | 5.45%   |
| Zen           | 2        | 3.64%   |
| Skylake       | 2        | 3.64%   |
| SandyBridge   | 2        | 3.64%   |
| NetBurst      | 2        | 3.64%   |
| Nehalem       | 2        | 3.64%   |
| IvyBridge     | 2        | 3.64%   |
| Goldmont plus | 2        | 3.64%   |
| CometLake     | 2        | 3.64%   |
| Zen 2         | 1        | 1.82%   |
| Steamroller   | 1        | 1.82%   |
| K10 Llano     | 1        | 1.82%   |
| Jaguar        | 1        | 1.82%   |
| Bulldozer     | 1        | 1.82%   |
| Bobcat        | 1        | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 24       | 41.38%  |
| Nvidia | 21       | 36.21%  |
| Intel  | 13       | 22.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [ION]                                                                       | 3        | 4.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 4.76%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 3.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 3.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.17%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 3.17%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 3.17%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 3.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 3.17%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 1.59%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.59%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 1.59%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 1.59%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 1.59%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 1.59%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 1.59%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 1.59%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.59%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.59%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 1.59%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.59%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.59%   |
| Nvidia C78 [GeForce 9100]                                                                | 1        | 1.59%   |
| Nvidia C77 [GeForce 8200]                                                                | 1        | 1.59%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.59%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1        | 1.59%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.59%   |
| AMD RV350 [Radeon 9550] (Secondary)                                                      | 1        | 1.59%   |
| AMD RV350 [Radeon 9550]                                                                  | 1        | 1.59%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 1.59%   |
| AMD RS780C [Radeon 3100]                                                                 | 1        | 1.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.59%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1        | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 19       | 34.55%  |
| 1 x AMD            | 19       | 34.55%  |
| 1 x Intel          | 11       | 20%     |
| 2 x AMD            | 3        | 5.45%   |
| Intel + 2 x Nvidia | 1        | 1.82%   |
| Intel + 2 x AMD    | 1        | 1.82%   |
| AMD + Nvidia       | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 81.82%  |
| Proprietary | 7        | 12.73%  |
| Unknown     | 3        | 5.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 60%     |
| 0.01-0.5   | 9        | 16.36%  |
| 7.01-8.0   | 4        | 7.27%   |
| 0.51-1.0   | 4        | 7.27%   |
| 8.01-16.0  | 2        | 3.64%   |
| 3.01-4.0   | 1        | 1.82%   |
| 2.01-3.0   | 1        | 1.82%   |
| 1.01-2.0   | 1        | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 17.65%  |
| Dell                 | 7        | 13.73%  |
| Hewlett-Packard      | 6        | 11.76%  |
| Goldstar             | 5        | 9.8%    |
| Philips              | 4        | 7.84%   |
| Ancor Communications | 3        | 5.88%   |
| Eizo                 | 2        | 3.92%   |
| Acer                 | 2        | 3.92%   |
| Vizio                | 1        | 1.96%   |
| VHT                  | 1        | 1.96%   |
| Unknown              | 1        | 1.96%   |
| Sony                 | 1        | 1.96%   |
| SNC                  | 1        | 1.96%   |
| Sharp                | 1        | 1.96%   |
| Sampo                | 1        | 1.96%   |
| Positivo             | 1        | 1.96%   |
| MSI                  | 1        | 1.96%   |
| LG Electronics       | 1        | 1.96%   |
| HannStar             | 1        | 1.96%   |
| Daewoo               | 1        | 1.96%   |
| BenQ                 | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 3.85%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                   | 1        | 1.92%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.92%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.92%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.92%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.92%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.92%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.92%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.92%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.92%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.92%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.92%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.92%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch            | 1        | 1.92%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.92%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.92%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.92%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.92%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 509x286mm 23.0-inch         | 1        | 1.92%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch          | 1        | 1.92%   |
| Hewlett-Packard E201 HWP305E 1600x900 443x249mm 20.0-inch            | 1        | 1.92%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch           | 1        | 1.92%   |
| Hewlett-Packard 2310 HWP2890 1920x1080 510x287mm 23.0-inch           | 1        | 1.92%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch            | 1        | 1.92%   |
| HannStar HL190APB HSD62C3 1366x768 410x230mm 18.5-inch               | 1        | 1.92%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.92%   |
| Goldstar M2394D GSM56C4 1920x1080 509x286mm 23.0-inch                | 1        | 1.92%   |
| Goldstar M197WD GSM4BA2 1360x768 410x230mm 18.5-inch                 | 1        | 1.92%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 1        | 1.92%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.92%   |
| Eizo M1700 ENC1789 1280x1024 338x271mm 17.1-inch                     | 1        | 1.92%   |
| Eizo L565 ENC1651 1280x1024 337x270mm 17.0-inch                      | 1        | 1.92%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                   | 1        | 1.92%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 1        | 1.92%   |
| Dell LCD Monitor U2412M 1920x1200                                    | 1        | 1.92%   |
| Dell LCD Monitor E196FP 1280x1024                                    | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 34.69%  |
| 1680x1050 (WSXGA+) | 5        | 10.2%   |
| 1600x900 (HD+)     | 5        | 10.2%   |
| 1280x1024 (SXGA)   | 5        | 10.2%   |
| 1366x768 (WXGA)    | 4        | 8.16%   |
| 2560x1440 (QHD)    | 2        | 4.08%   |
| 1440x900 (WXGA+)   | 2        | 4.08%   |
| 1360x768           | 2        | 4.08%   |
| 800x600            | 1        | 2.04%   |
| 3840x2160 (4K)     | 1        | 2.04%   |
| 2560x1600          | 1        | 2.04%   |
| 1920x1200 (WUXGA)  | 1        | 2.04%   |
| 1280x768           | 1        | 2.04%   |
| 1280x720 (HD)      | 1        | 2.04%   |
| 1024x768 (XGA)     | 1        | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 6        | 12%     |
| 23      | 5        | 10%     |
| 22      | 5        | 10%     |
| Unknown | 5        | 10%     |
| 27      | 4        | 8%      |
| 24      | 4        | 8%      |
| 21      | 4        | 8%      |
| 20      | 4        | 8%      |
| 19      | 3        | 6%      |
| 17      | 2        | 4%      |
| 72      | 1        | 2%      |
| 49      | 1        | 2%      |
| 47      | 1        | 2%      |
| 43      | 1        | 2%      |
| 34      | 1        | 2%      |
| 15      | 1        | 2%      |
| 14      | 1        | 2%      |
| 8       | 1        | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 21       | 42%     |
| 501-600     | 13       | 26%     |
| Unknown     | 5        | 10%     |
| 301-350     | 4        | 8%      |
| 1001-1500   | 2        | 4%      |
| 701-800     | 1        | 2%      |
| 351-400     | 1        | 2%      |
| 1501-2000   | 1        | 2%      |
| 101-200     | 1        | 2%      |
| 901-1000    | 1        | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 62.5%   |
| 16/10   | 8        | 16.67%  |
| Unknown | 4        | 8.33%   |
| 5/4     | 3        | 6.25%   |
| 4/3     | 3        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 30.61%  |
| 151-200        | 9        | 18.37%  |
| 141-150        | 7        | 14.29%  |
| Unknown        | 5        | 10.2%   |
| 301-350        | 4        | 8.16%   |
| 501-1000       | 3        | 6.12%   |
| More than 1000 | 2        | 4.08%   |
| 81-90          | 1        | 2.04%   |
| 1-40           | 1        | 2.04%   |
| 251-300        | 1        | 2.04%   |
| 111-120        | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 60.42%  |
| 101-120 | 8        | 16.67%  |
| 1-50    | 5        | 10.42%  |
| Unknown | 5        | 10.42%  |
| 161-240 | 1        | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 89.09%  |
| 2     | 4        | 7.27%   |
| 0     | 2        | 3.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 34       | 44.74%  |
| Intel                           | 15       | 19.74%  |
| Qualcomm Atheros                | 6        | 7.89%   |
| TP-Link                         | 4        | 5.26%   |
| Broadcom                        | 3        | 3.95%   |
| Samsung Electronics             | 2        | 2.63%   |
| Qualcomm Atheros Communications | 2        | 2.63%   |
| Nvidia                          | 2        | 2.63%   |
| MediaTek                        | 2        | 2.63%   |
| VIA Technologies                | 1        | 1.32%   |
| Trident Microsystems            | 1        | 1.32%   |
| NetGear                         | 1        | 1.32%   |
| Marvell Technology Group        | 1        | 1.32%   |
| Broadcom Limited                | 1        | 1.32%   |
| ASUSTek Computer                | 1        | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 30       | 36.14%  |
| Intel Ethernet Controller I225-V                                    | 3        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 3.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 2.41%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 2.41%   |
| Nvidia MCP77 Ethernet                                               | 2        | 2.41%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 2.41%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 2.41%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 2.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 1        | 1.2%    |
| Trident Microsystems 4DWave DX                                      | 1        | 1.2%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 1.2%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 1.2%    |
| TP-Link 802.11ac NIC                                                | 1        | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.2%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 1.2%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 1.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 1.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 1.2%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 1        | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 1.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 1.2%    |
| NetGear A6210                                                       | 1        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 1.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 1        | 1.2%    |
| Intel Wi-Fi 6 AX200                                                 | 1        | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 1.2%    |
| Intel I211 Gigabit Network Connection                               | 1        | 1.2%    |
| Intel Centrino Advanced-N 6235                                      | 1        | 1.2%    |
| Intel 82567LF-2 Gigabit Network Connection                          | 1        | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 26.92%  |
| TP-Link                         | 4        | 15.38%  |
| Qualcomm Atheros                | 3        | 11.54%  |
| Intel                           | 3        | 11.54%  |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| MediaTek                        | 2        | 7.69%   |
| Broadcom                        | 2        | 7.69%   |
| NetGear                         | 1        | 3.85%   |
| Broadcom Limited                | 1        | 3.85%   |
| ASUSTek Computer                | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 7.69%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 7.69%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 7.69%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 3.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 3.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 3.85%   |
| TP-Link 802.11ac NIC                                                | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 3.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 3.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 3.85%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 3.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 3.85%   |
| NetGear A6210                                                       | 1        | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                                 | 1        | 3.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 3.85%   |
| Intel Centrino Advanced-N 6235                                      | 1        | 3.85%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 3.85%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]      | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 33       | 57.89%  |
| Intel                    | 12       | 21.05%  |
| Qualcomm Atheros         | 4        | 7.02%   |
| Samsung Electronics      | 2        | 3.51%   |
| Nvidia                   | 2        | 3.51%   |
| VIA Technologies         | 1        | 1.75%   |
| Trident Microsystems     | 1        | 1.75%   |
| Marvell Technology Group | 1        | 1.75%   |
| Broadcom                 | 1        | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 52.63%  |
| Intel Ethernet Controller I225-V                                  | 3        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.51%   |
| Nvidia MCP77 Ethernet                                             | 2        | 3.51%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 3.51%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.75%   |
| Trident Microsystems 4DWave DX                                    | 1        | 1.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.75%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.75%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 70.13%  |
| WiFi     | 23       | 29.87%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 69.64%  |
| WiFi     | 17       | 30.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 72.73%  |
| 2     | 12       | 21.82%  |
| 4     | 1        | 1.82%   |
| 3     | 1        | 1.82%   |
| 0     | 1        | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 72.73%  |
| Yes  | 15       | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| MediaTek                | 2        | 22.22%  |
| Intel                   | 2        | 22.22%  |
| Realtek Semiconductor   | 1        | 11.11%  |
| Logitech                | 1        | 11.11%  |
| Foxconn / Hon Hai       | 1        | 11.11%  |
| Cambridge Silicon Radio | 1        | 11.11%  |
| Broadcom                | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                            | 2        | 22.22%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 11.11%  |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 11.11%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 11.11%  |
| Intel AX200 Bluetooth                               | 1        | 11.11%  |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 29       | 35.37%  |
| AMD                                          | 25       | 30.49%  |
| Nvidia                                       | 19       | 23.17%  |
| C-Media Electronics                          | 2        | 2.44%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.22%   |
| VIA Technologies                             | 1        | 1.22%   |
| Sony                                         | 1        | 1.22%   |
| Razer USA                                    | 1        | 1.22%   |
| Ensoniq                                      | 1        | 1.22%   |
| Creative Labs                                | 1        | 1.22%   |
| ASUSTek Computer                             | 1        | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11       | 11.11%  |
| Nvidia High Definition Audio Controller                                                           | 7        | 7.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6        | 6.06%   |
| AMD FCH Azalia Controller                                                                         | 4        | 4.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 4.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.03%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 3        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 3.03%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2        | 2.02%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 2.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 2.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 2.02%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2        | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 2.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 2.02%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 1.01%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 1.01%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1        | 1.01%   |
| Razer USA Razer Kraken X USB                                                                      | 1        | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 1.01%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.01%   |
| Nvidia GM200 High Definition Audio                                                                | 1        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.01%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 1.01%   |
| Intel Audio device                                                                                | 1        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 1.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.01%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                                      | 1        | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 25.81%  |
| Kingston            | 5        | 16.13%  |
| Micron Technology   | 4        | 12.9%   |
| SK hynix            | 3        | 9.68%   |
| G.Skill             | 3        | 9.68%   |
| Samsung Electronics | 2        | 6.45%   |
| Corsair             | 2        | 6.45%   |
| Nanya Technology    | 1        | 3.23%   |
| GOODRAM             | 1        | 3.23%   |
| Elpida              | 1        | 3.23%   |
| Unknown             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 1        | 2.78%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 2.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 2.78%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s | 1        | 2.78%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s               | 1        | 2.78%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 2.78%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.78%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 2.78%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s       | 1        | 2.78%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 2.78%   |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s   | 1        | 2.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 1        | 2.78%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 2.78%   |
| Kingston RAM KN2M64-ETB 8GB DIMM DDR3 1600MT/s           | 1        | 2.78%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 2.78%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s    | 1        | 2.78%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s  | 1        | 2.78%   |
| Kingston RAM 99U5474-028.A 4GB DIMM DDR3 1333MT/s        | 1        | 2.78%   |
| GOODRAM RAM IRX3200D464L16S/8G 8GB DIMM DDR4 3200MT/s    | 1        | 2.78%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 3666MT/s      | 1        | 2.78%   |
| G.Skill RAM F4-3000C15-8GVKB 8GB DIMM DDR4 3066MT/s      | 1        | 2.78%   |
| G.Skill RAM F3-2400C11-4GXM 4GB DIMM DDR3 1600MT/s       | 1        | 2.78%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4GB DIMM DDR3 1333MT/s      | 1        | 2.78%   |
| Elpida RAM EBJ21EE8BDFA-DJ-F 2048MB DIMM DDR3 1333MT/s   | 1        | 2.78%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s   | 1        | 2.78%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 2.78%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.78%   |
| Unknown                                                  | 1        | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 11       | 37.93%  |
| DDR3    | 9        | 31.03%  |
| DDR2    | 5        | 17.24%  |
| SDRAM   | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 72.41%  |
| SODIMM | 8        | 27.59%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 30.3%   |
| 4096  | 9        | 27.27%  |
| 2048  | 9        | 27.27%  |
| 16384 | 3        | 9.09%   |
| 32768 | 1        | 3.03%   |
| 1024  | 1        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 7        | 24.14%  |
| 3200    | 5        | 17.24%  |
| 1333    | 3        | 10.34%  |
| 800     | 2        | 6.9%    |
| 667     | 2        | 6.9%    |
| 3666    | 1        | 3.45%   |
| 3400    | 1        | 3.45%   |
| 3066    | 1        | 3.45%   |
| 2800    | 1        | 3.45%   |
| 2400    | 1        | 3.45%   |
| 2133    | 1        | 3.45%   |
| 2048    | 1        | 3.45%   |
| 1066    | 1        | 3.45%   |
| 333     | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon PIXMA MP250       | 1        | 33.33%  |
| Canon CanoScan LiDE 300 | 1        | 33.33%  |
| Brother DCP-7055W       | 1        | 33.33%  |

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
| 0     | 50       | 89.29%  |
| 1     | 6        | 10.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 50%     |
| Graphics card | 3        | 50%     |

