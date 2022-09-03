Red OS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 53

| Vendor        | Model            | Probe                                                      | Date         |
|---------------|------------------|------------------------------------------------------------|--------------|
| ASRock        | N68-VS3 FX       | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F     | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3         | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| ASRock        | H110M-DVS R2.0   | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H       | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00       | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T          | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3          | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus    | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K           | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D          | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F     | [3a12e41029](https://linux-hardware.org/?probe=3a12e41029) | Jun 01, 2022 |
| MSI           | A520M PRO        | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO        | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01       | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H          | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K           | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4        | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V         | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V         | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3       | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V         | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS        | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T          | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M          | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H       | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K    | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V         | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H       | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M          | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M          | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V         | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H       | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV        | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF      | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS        | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H       | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS       | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0  | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H       | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K           | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K          | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K          | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K           | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H       | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H       | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K           | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 21       | 46.67%  |
| Red OS 7.3.1 | 19       | 42.22%  |
| Red OS 7.2   | 5        | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 41       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.29-1.el7.x86_64   | 12       | 25.53%  |
| 5.15.10-1.el7.x86_64   | 9        | 19.15%  |
| 5.15.35-1.el7.3.x86_64 | 7        | 14.89%  |
| 5.15.35-4.el7.3.x86_64 | 4        | 8.51%   |
| 5.15.10-3.el7.x86_64   | 3        | 6.38%   |
| 5.15.10-2.el7.x86_64   | 3        | 6.38%   |
| 4.19.79-1.el7.x86_64   | 3        | 6.38%   |
| 5.14.9-1.el7.x86_64    | 1        | 2.13%   |
| 5.10.24-3.el7.x86_64   | 1        | 2.13%   |
| 5.10.24-2.el7.x86_64   | 1        | 2.13%   |
| 5.10.1-1.el7.x86_64    | 1        | 2.13%   |
| 4.19.56-2.el7.x86_64   | 1        | 2.13%   |
| 4.19.204-1.el7.x86_64  | 1        | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.10  | 15       | 32.61%  |
| 5.10.29  | 12       | 26.09%  |
| 5.15.35  | 10       | 21.74%  |
| 4.19.79  | 3        | 6.52%   |
| 5.10.24  | 2        | 4.35%   |
| 5.14.9   | 1        | 2.17%   |
| 5.10.1   | 1        | 2.17%   |
| 4.19.56  | 1        | 2.17%   |
| 4.19.204 | 1        | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 25       | 54.35%  |
| 5.10    | 15       | 32.61%  |
| 4.19    | 5        | 10.87%  |
| 5.14    | 1        | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 33       | 73.33%  |
| Cinnamon   | 10       | 22.22%  |
| X-Cinnamon | 1        | 2.22%   |
| Unknown    | 1        | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 86.05%  |
| Wayland | 5        | 11.63%  |
| Unknown | 1        | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 39       | 92.86%  |
| SDDM    | 2        | 4.76%   |
| Unknown | 1        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 39       | 92.86%  |
| ru_RU   | 3        | 7.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 64.29%  |
| BIOS | 15       | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 38       | 92.68%  |
| Btrfs   | 2        | 4.88%   |
| Unknown | 1        | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 28       | 66.67%  |
| MBR     | 13       | 30.95%  |
| Unknown | 1        | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 83.33%  |
| Yes       | 7        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 80.95%  |
| Yes       | 8        | 19.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 14       | 34.15%  |
| ASUSTek Computer    | 9        | 21.95%  |
| ASRock              | 5        | 12.2%   |
| DEPO Computers      | 4        | 9.76%   |
| Aquarius            | 4        | 9.76%   |
| MSI                 | 3        | 7.32%   |
| Hewlett-Packard     | 1        | 2.44%   |
| Dell                | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B365M DS3H    | 4        | 9.76%   |
| DEPO Computers DPH310T | 4        | 9.76%   |
| MSI MS-7D14            | 2        | 4.88%   |
| Gigabyte B560M DS3H    | 2        | 4.88%   |
| MSI MS-7D35            | 1        | 2.44%   |
| HP Z400 Workstation    | 1        | 2.44%   |
| Gigabyte X58-USB3      | 1        | 2.44%   |
| Gigabyte H410M H V3    | 1        | 2.44%   |
| Gigabyte H110M-M.2     | 1        | 2.44%   |
| Gigabyte B75M-D3V      | 1        | 2.44%   |
| Gigabyte B75M-D2V      | 1        | 2.44%   |
| Gigabyte B365M H       | 1        | 2.44%   |
| Gigabyte B360M-DS3H    | 1        | 2.44%   |
| Gigabyte 970A-D3       | 1        | 2.44%   |
| Dell OptiPlex 3020     | 1        | 2.44%   |
| ASUS PRIME H510T2/CSM  | 1        | 2.44%   |
| ASUS PRIME H510M-K     | 1        | 2.44%   |
| ASUS PC                | 1        | 2.44%   |
| ASUS P8H61-I LX R2.0   | 1        | 2.44%   |
| ASUS M2N68-AM Plus     | 1        | 2.44%   |
| ASUS H110M-PLUS        | 1        | 2.44%   |
| ASUS H110M-K           | 1        | 2.44%   |
| ASUS H110-PLUS         | 1        | 2.44%   |
| ASUS All Series        | 1        | 2.44%   |
| ASRock N68-VS3 FX      | 1        | 2.44%   |
| ASRock H470M-HDV       | 1        | 2.44%   |
| ASRock H110M-DVS R2.0  | 1        | 2.44%   |
| ASRock B560 Pro4       | 1        | 2.44%   |
| ASRock B365M Pro4-F    | 1        | 2.44%   |
| Aquarius Pro T584      | 1        | 2.44%   |
| Aquarius P30 K44 R53   | 1        | 2.44%   |
| Aquarius AQH410T       | 1        | 2.44%   |
| Aquarius AQB560M       | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B365M         | 5        | 12.2%   |
| DEPO Computers DPH310T | 4        | 9.76%   |
| MSI MS-7D14            | 2        | 4.88%   |
| Gigabyte B560M         | 2        | 4.88%   |
| ASUS PRIME             | 2        | 4.88%   |
| MSI MS-7D35            | 1        | 2.44%   |
| HP Z400                | 1        | 2.44%   |
| Gigabyte X58-USB3      | 1        | 2.44%   |
| Gigabyte H410M         | 1        | 2.44%   |
| Gigabyte H110M-M.2     | 1        | 2.44%   |
| Gigabyte B75M-D3V      | 1        | 2.44%   |
| Gigabyte B75M-D2V      | 1        | 2.44%   |
| Gigabyte B360M-DS3H    | 1        | 2.44%   |
| Gigabyte 970A-D3       | 1        | 2.44%   |
| Dell OptiPlex          | 1        | 2.44%   |
| ASUS PC                | 1        | 2.44%   |
| ASUS P8H61-I           | 1        | 2.44%   |
| ASUS M2N68-AM          | 1        | 2.44%   |
| ASUS H110M-PLUS        | 1        | 2.44%   |
| ASUS H110M-K           | 1        | 2.44%   |
| ASUS H110-PLUS         | 1        | 2.44%   |
| ASUS All               | 1        | 2.44%   |
| ASRock N68-VS3         | 1        | 2.44%   |
| ASRock H470M-HDV       | 1        | 2.44%   |
| ASRock H110M-DVS       | 1        | 2.44%   |
| ASRock B560            | 1        | 2.44%   |
| ASRock B365M           | 1        | 2.44%   |
| Aquarius Pro           | 1        | 2.44%   |
| Aquarius P30           | 1        | 2.44%   |
| Aquarius AQH410T       | 1        | 2.44%   |
| Aquarius AQB560M       | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 26.83%  |
| 2020 | 6        | 14.63%  |
| 2019 | 6        | 14.63%  |
| 2016 | 4        | 9.76%   |
| 2012 | 4        | 9.76%   |
| 2022 | 2        | 4.88%   |
| 2010 | 2        | 4.88%   |
| 2018 | 1        | 2.44%   |
| 2017 | 1        | 2.44%   |
| 2014 | 1        | 2.44%   |
| 2013 | 1        | 2.44%   |
| 2011 | 1        | 2.44%   |
| 2009 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 41       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 16       | 39.02%  |
| 4.01-8.0   | 9        | 21.95%  |
| 8.01-16.0  | 8        | 19.51%  |
| 3.01-4.0   | 6        | 14.63%  |
| 24.01-32.0 | 1        | 2.44%   |
| Unknown    | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 15       | 31.91%  |
| 4.01-8.0  | 11       | 23.4%   |
| 3.01-4.0  | 8        | 17.02%  |
| 0.51-1.0  | 6        | 12.77%  |
| 2.01-3.0  | 4        | 8.51%   |
| 8.01-16.0 | 2        | 4.26%   |
| Unknown   | 1        | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 59.52%  |
| 2      | 15       | 35.71%  |
| 4      | 1        | 2.38%   |
| 3      | 1        | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 70.73%  |
| Yes       | 12       | 29.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 41       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 79.07%  |
| Yes       | 9        | 20.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 85.37%  |
| Yes       | 6        | 14.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 41       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Murom         | 13       | 31.71%  |
| Salekhard     | 9        | 21.95%  |
| Moscow        | 4        | 9.76%   |
| Yekaterinburg | 1        | 2.44%   |
| Ulyanovsk     | 1        | 2.44%   |
| Surgut        | 1        | 2.44%   |
| Stavropol     | 1        | 2.44%   |
| Rostov-on-Don | 1        | 2.44%   |
| Penza         | 1        | 2.44%   |
| Novosibirsk   | 1        | 2.44%   |
| Kursk         | 1        | 2.44%   |
| Krasnodar     | 1        | 2.44%   |
| Kovrov        | 1        | 2.44%   |
| Kirov         | 1        | 2.44%   |
| Kholmsk       | 1        | 2.44%   |
| Kaluga        | 1        | 2.44%   |
| Bryansk       | 1        | 2.44%   |
| Arzamas       | 1        | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 30     | 32.76%  |
| Toshiba             | 6        | 6      | 10.34%  |
| WDC                 | 5        | 7      | 8.62%   |
| Apacer              | 4        | 4      | 6.9%    |
| A-DATA Technology   | 4        | 4      | 6.9%    |
| SanDisk             | 3        | 4      | 5.17%   |
| Foxline             | 3        | 3      | 5.17%   |
| Samsung Electronics | 2        | 2      | 3.45%   |
| KIOXIA-EXCERIA      | 2        | 2      | 3.45%   |
| Kingston            | 2        | 2      | 3.45%   |
| Crucial             | 2        | 5      | 3.45%   |
| Smartbuy            | 1        | 1      | 1.72%   |
| Patriot             | 1        | 1      | 1.72%   |
| GOODRAM             | 1        | 1      | 1.72%   |
| ExeGate             | 1        | 1      | 1.72%   |
| China               | 1        | 1      | 1.72%   |
| AMD                 | 1        | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000LM049-2GH172 1TB     | 4        | 6.67%   |
| Seagate ST1000DM010-2EP102 1TB     | 4        | 6.67%   |
| Apacer AS2280P4 256GB              | 4        | 6.67%   |
| Toshiba HDWD110 1TB                | 2        | 3.33%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 3.33%   |
| Seagate ST1000DM010-2DM162 1TB     | 2        | 3.33%   |
| Seagate ST1000DM003-1SB10C 1TB     | 2        | 3.33%   |
| SanDisk SD8SBAT256G1122 256GB SSD  | 2        | 3.33%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 2        | 3.33%   |
| Foxline FLSSD240X5SE 240GB         | 2        | 3.33%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 3.33%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 1.67%   |
| WDC WD3200AAKX-001CA0 320GB        | 1        | 1.67%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 1.67%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1.67%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1.67%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 1        | 1.67%   |
| Toshiba MK5075GSX 500GB            | 1        | 1.67%   |
| Toshiba KHK61VSE960G 960GB SSD     | 1        | 1.67%   |
| Toshiba HDWD105 500GB              | 1        | 1.67%   |
| Toshiba DT01ACA200 2TB             | 1        | 1.67%   |
| Smartbuy SSD 240GB                 | 1        | 1.67%   |
| Seagate ST3400620AS 400GB          | 1        | 1.67%   |
| Seagate ST3320620AS 320GB          | 1        | 1.67%   |
| Seagate ST3250823AS 250GB          | 1        | 1.67%   |
| Seagate ST31000528AS 1TB           | 1        | 1.67%   |
| Seagate ST2000DM008-2UB102 2TB     | 1        | 1.67%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1.67%   |
| SanDisk SSD PLUS 240GB             | 1        | 1.67%   |
| Samsung SSD 870 EVO 250GB          | 1        | 1.67%   |
| Samsung SSD 860 EVO 250GB          | 1        | 1.67%   |
| Patriot P210 128GB SSD             | 1        | 1.67%   |
| Kingston SA400S37120G 120GB SSD    | 1        | 1.67%   |
| Kingston OM8PCP3512F-A02 512GB     | 1        | 1.67%   |
| GOODRAM SSDPR-CX400-512-G2 512GB   | 1        | 1.67%   |
| Foxline FLSSD120SM5 120GB          | 1        | 1.67%   |
| ExeGate EX276690RUS(960G 960GB SSD | 1        | 1.67%   |
| China SSD 256GB                    | 1        | 1.67%   |
| AMD R5MP120G8 120GB                | 1        | 1.67%   |
| A-DATA SX6000PNP 256GB             | 1        | 1.67%   |
| A-DATA SU800 256GB SSD             | 1        | 1.67%   |
| A-DATA SU630 960GB SSD             | 1        | 1.67%   |
| A-DATA FALCON 512GB                | 1        | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 19       | 30     | 65.52%  |
| WDC     | 5        | 7      | 17.24%  |
| Toshiba | 5        | 5      | 17.24%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 3        | 4      | 14.29%  |
| Foxline             | 3        | 3      | 14.29%  |
| Samsung Electronics | 2        | 2      | 9.52%   |
| KIOXIA-EXCERIA      | 2        | 2      | 9.52%   |
| Crucial             | 2        | 5      | 9.52%   |
| A-DATA Technology   | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Smartbuy            | 1        | 1      | 4.76%   |
| Patriot             | 1        | 1      | 4.76%   |
| Kingston            | 1        | 1      | 4.76%   |
| GOODRAM             | 1        | 1      | 4.76%   |
| ExeGate             | 1        | 1      | 4.76%   |
| China               | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 42     | 48.21%  |
| SSD  | 21       | 25     | 37.5%   |
| NVMe | 8        | 8      | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 39       | 67     | 82.98%  |
| NVMe | 8        | 8      | 17.02%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 30     | 48.98%  |
| 0.51-1.0   | 21       | 32     | 42.86%  |
| 1.01-2.0   | 4        | 5      | 8.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 501-1000   | 12       | 28.57%  |
| 101-250    | 11       | 26.19%  |
| 251-500    | 9        | 21.43%  |
| 2001-3000  | 3        | 7.14%   |
| 1001-2000  | 3        | 7.14%   |
| 51-100     | 3        | 7.14%   |
| Unknown    | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 24       | 52.17%  |
| 501-1000  | 7        | 15.22%  |
| 21-50     | 4        | 8.7%    |
| 251-500   | 3        | 6.52%   |
| 51-100    | 3        | 6.52%   |
| 101-250   | 2        | 4.35%   |
| 1001-2000 | 2        | 4.35%   |
| Unknown   | 1        | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB    | 1        | 1      | 25%     |
| WDC WD10EARS-00Y5B1 1TB        | 1        | 1      | 25%     |
| Seagate ST3250823AS 250GB      | 1        | 1      | 25%     |
| Seagate ST1000DM010-2EP102 1TB | 1        | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 2        | 3      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 2        | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 100%    |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 39       | 70     | 92.86%  |
| Malfunc | 3        | 5      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 36       | 73.47%  |
| Phison Electronics          | 4        | 8.16%   |
| AMD                         | 3        | 6.12%   |
| Realtek Semiconductor       | 2        | 4.08%   |
| Nvidia                      | 2        | 4.08%   |
| Silicon Motion              | 1        | 2.04%   |
| Kingston Technology Company | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 20.37%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 18.52%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 9.26%   |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 7.41%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 3.7%    |
| Nvidia MCP61 SATA Controller                                                            | 2        | 3.7%    |
| Nvidia MCP61 IDE                                                                        | 2        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.85%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.85%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 71.43%  |
| NVMe | 8        | 16.33%  |
| IDE  | 5        | 10.2%   |
| RAID | 1        | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 87.8%   |
| AMD    | 5        | 12.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz           | 10       | 24.39%  |
| Intel Core i3-10100 CPU @ 3.60GHz          | 7        | 17.07%  |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3        | 7.32%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2        | 4.88%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 2        | 4.88%   |
| Intel Xeon CPU W3670 @ 3.20GHz             | 1        | 2.44%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz     | 1        | 2.44%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 2.44%   |
| Intel Pentium CPU G4500 @ 3.50GHz          | 1        | 2.44%   |
| Intel Core i7 CPU 950 @ 3.07GHz            | 1        | 2.44%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 2.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 1        | 2.44%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 1        | 2.44%   |
| Intel Core i5-10500 CPU @ 3.10GHz          | 1        | 2.44%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1        | 2.44%   |
| Intel Core i3-10105 CPU @ 3.70GHz          | 1        | 2.44%   |
| Intel Celeron G5925 CPU @ 3.60GHz          | 1        | 2.44%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 1        | 2.44%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz     | 1        | 2.44%   |
| AMD FX-6300 Six-Core Processor             | 1        | 2.44%   |
| AMD FX-4100 Quad-Core Processor            | 1        | 2.44%   |
| AMD Athlon II X2 240 Processor             | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 17       | 41.46%  |
| Intel Core i3      | 11       | 26.83%  |
| Intel Pentium      | 2        | 4.88%   |
| Intel Celeron      | 2        | 4.88%   |
| AMD Ryzen 7 PRO    | 2        | 4.88%   |
| AMD FX             | 2        | 4.88%   |
| Other              | 1        | 2.44%   |
| Intel Xeon         | 1        | 2.44%   |
| Intel Pentium Gold | 1        | 2.44%   |
| Intel Core i7      | 1        | 2.44%   |
| AMD Athlon II X2   | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 15       | 36.59%  |
| 4      | 13       | 31.71%  |
| 2      | 10       | 24.39%  |
| 8      | 2        | 4.88%   |
| 3      | 1        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 51.22%  |
| 1      | 20       | 48.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 40       | 97.56%  |
| Unknown        | 1        | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 11       | 26.19%  |
| 0x906ed    | 8        | 19.05%  |
| 0x506e3    | 4        | 9.52%   |
| 0x906ea    | 3        | 7.14%   |
| 0x306a9    | 3        | 7.14%   |
| 0x306c3    | 2        | 4.76%   |
| 0x08600106 | 2        | 4.76%   |
| 0xa0671    | 1        | 2.38%   |
| 0xa0654    | 1        | 2.38%   |
| 0x906e9    | 1        | 2.38%   |
| 0x206c2    | 1        | 2.38%   |
| 0x106a5    | 1        | 2.38%   |
| 0x06000852 | 1        | 2.38%   |
| 0x0600063e | 1        | 2.38%   |
| 0x010000c7 | 1        | 2.38%   |
| Unknown    | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KabyLake   | 12       | 29.27%  |
| CometLake  | 12       | 29.27%  |
| Skylake    | 4        | 9.76%   |
| IvyBridge  | 3        | 7.32%   |
| Zen 2      | 2        | 4.88%   |
| Haswell    | 2        | 4.88%   |
| Westmere   | 1        | 2.44%   |
| Piledriver | 1        | 2.44%   |
| Nehalem    | 1        | 2.44%   |
| K10        | 1        | 2.44%   |
| Bulldozer  | 1        | 2.44%   |
| Unknown    | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 75.61%  |
| Nvidia | 5        | 12.2%   |
| AMD    | 5        | 12.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 23.81%  |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 9        | 21.43%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 7.14%   |
| Intel HD Graphics 530                                                       | 3        | 7.14%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 4.76%   |
| AMD Renoir                                                                  | 2        | 4.76%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 2.38%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.38%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 2.38%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 2.38%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.38%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 2.38%   |
| Intel HD Graphics 610                                                       | 1        | 2.38%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.38%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 2.38%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                       | 1        | 2.38%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                   | 1        | 2.38%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 31       | 75.61%  |
| 1 x Nvidia | 5        | 12.2%   |
| 1 x AMD    | 4        | 9.76%   |
| 2 x AMD    | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 80.49%  |
| Unknown     | 7        | 17.07%  |
| Proprietary | 1        | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 78.05%  |
| 1.01-2.0   | 3        | 7.32%   |
| 0.01-0.5   | 3        | 7.32%   |
| 0.51-1.0   | 2        | 4.88%   |
| 3.01-4.0   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 10       | 25%     |
| ViewSonic           | 7        | 17.5%   |
| Samsung Electronics | 6        | 15%     |
| Acer                | 5        | 12.5%   |
| BenQ                | 4        | 10%     |
| AOC                 | 3        | 7.5%    |
| SGT                 | 2        | 5%      |
| DOY                 | 1        | 2.5%    |
| Dell                | 1        | 2.5%    |
| CHR                 | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 14.29%  |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 4        | 9.52%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 2        | 4.76%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 4.76%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 4.76%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 4.76%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 2.38%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 2.38%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 1        | 2.38%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 2.38%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 2.38%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 2.38%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 1        | 2.38%   |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch             | 1        | 2.38%   |
| Philips 190VL PHLC080 1440x900 408x255mm 18.9-inch                    | 1        | 2.38%   |
| DOY LCD Monitor DOY2760 1920x1080 598x336mm 27.0-inch                 | 1        | 2.38%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1        | 2.38%   |
| CHR CH7511B CHR7511 800x600 519x324mm 24.1-inch                       | 1        | 2.38%   |
| BenQ V2420H BNQ7B14 1920x1080 531x299mm 24.0-inch                     | 1        | 2.38%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 1        | 2.38%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 1        | 2.38%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 1        | 2.38%   |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                       | 1        | 2.38%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 1        | 2.38%   |
| AOC 2250W AOC2250 1920x1080 480x270mm 21.7-inch                       | 1        | 2.38%   |
| Acer VG272U ACR0778 2560x1440 597x336mm 27.0-inch                     | 1        | 2.38%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 1        | 2.38%   |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 1        | 2.38%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 1        | 2.38%   |
| Acer H226HQL ACR0319 1920x1080 476x268mm 21.5-inch                    | 1        | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 25       | 69.44%  |
| 2560x1440 (QHD)   | 5        | 13.89%  |
| 3840x2160 (4K)    | 1        | 2.78%   |
| 1920x1200 (WUXGA) | 1        | 2.78%   |
| 1600x900 (HD+)    | 1        | 2.78%   |
| 1440x900 (WXGA+)  | 1        | 2.78%   |
| 1280x1024 (SXGA)  | 1        | 2.78%   |
| 1024x768 (XGA)    | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 13       | 32.5%   |
| 23     | 9        | 22.5%   |
| 27     | 8        | 20%     |
| 21     | 4        | 10%     |
| 19     | 2        | 5%      |
| 32     | 1        | 2.5%    |
| 31     | 1        | 2.5%    |
| 20     | 1        | 2.5%    |
| 15     | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 26       | 72.22%  |
| 401-500     | 6        | 16.67%  |
| 701-800     | 1        | 2.78%   |
| 601-700     | 1        | 2.78%   |
| 351-400     | 1        | 2.78%   |
| 301-350     | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 31       | 86.11%  |
| 16/10 | 3        | 8.33%   |
| 5/4   | 1        | 2.78%   |
| 4/3   | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 57.89%  |
| 301-350        | 8        | 21.05%  |
| 151-200        | 3        | 7.89%   |
| 351-500        | 2        | 5.26%   |
| 251-300        | 2        | 5.26%   |
| 101-110        | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 73.53%  |
| 101-120 | 9        | 26.47%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 72.73%  |
| 2     | 6        | 13.64%  |
| 0     | 6        | 13.64%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 68.75%  |
| Intel                 | 8        | 16.67%  |
| Nvidia                | 2        | 4.17%   |
| TP-Link               | 1        | 2.08%   |
| Ralink Technology     | 1        | 2.08%   |
| Mercucys              | 1        | 2.08%   |
| Edimax Technology     | 1        | 2.08%   |
| Broadcom              | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 60.78%  |
| Intel Ethernet Controller I225-V                                  | 3        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 3.92%   |
| Nvidia MCP61 Ethernet                                             | 2        | 3.92%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.92%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 3.92%   |
| TP-Link USB 10/100 LAN                                            | 1        | 1.96%   |
| Realtek 802.11ac NIC                                              | 1        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.96%   |
| Mercucys 802.11n NIC                                              | 1        | 1.96%   |
| Intel Wireless 3165                                               | 1        | 1.96%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU]   | 1        | 1.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 55.56%  |
| Ralink Technology     | 1        | 11.11%  |
| Mercucys              | 1        | 11.11%  |
| Intel                 | 1        | 11.11%  |
| Edimax Technology     | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2        | 22.22%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2        | 22.22%  |
| Realtek 802.11ac NIC                                            | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                                 | 1        | 11.11%  |
| Mercucys 802.11n NIC                                            | 1        | 11.11%  |
| Intel Wireless 3165                                             | 1        | 11.11%  |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 73.81%  |
| Intel                 | 7        | 16.67%  |
| Nvidia                | 2        | 4.76%   |
| TP-Link               | 1        | 2.38%   |
| Broadcom              | 1        | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 73.81%  |
| Intel Ethernet Controller I225-V                                  | 3        | 7.14%   |
| Nvidia MCP61 Ethernet                                             | 2        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.76%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 4.76%   |
| TP-Link USB 10/100 LAN                                            | 1        | 2.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 82%     |
| WiFi     | 9        | 18%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 95.35%  |
| WiFi     | 2        | 4.65%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 82.93%  |
| 2     | 7        | 17.07%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 66.67%  |
| Intel                 | 1        | 16.67%  |
| Broadcom              | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                          | 4        | 66.67%  |
| Intel Bluetooth wireless interface               | 1        | 16.67%  |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 80%     |
| AMD    | 5        | 11.11%  |
| Nvidia | 4        | 8.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 10       | 20%     |
| Intel 200 Series PCH HD Audio                                              | 10       | 20%     |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 10%     |
| Nvidia MCP61 High Definition Audio                                         | 2        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 4%      |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 4%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2%      |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 2%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2%      |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2%      |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2%      |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2%      |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 8        | 18.6%   |
| Foxline             | 7        | 16.28%  |
| Kingston            | 6        | 13.95%  |
| Unknown             | 4        | 9.3%    |
| SK hynix            | 3        | 6.98%   |
| AMD                 | 3        | 6.98%   |
| Samsung Electronics | 2        | 4.65%   |
| Corsair             | 2        | 4.65%   |
| Unknown             | 2        | 4.65%   |
| Qumo                | 1        | 2.33%   |
| Patriot             | 1        | 2.33%   |
| Neo Forza           | 1        | 2.33%   |
| ChangXin Memory     | 1        | 2.33%   |
| Apacer              | 1        | 2.33%   |
| A-DATA Technology   | 1        | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s          | 4        | 9.09%   |
| Foxline RAM FL2666D4U19-8G 8192MB DIMM DDR4 2667MT/s         | 3        | 6.82%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 4.55%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 4.55%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 2        | 4.55%   |
| Unknown                                                      | 2        | 4.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 2.27%   |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 1        | 2.27%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 2.27%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                  | 1        | 2.27%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 2.27%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 1        | 2.27%   |
| Samsung RAM M378B5273DH0 4GB DIMM DDR3 1333MT/s              | 1        | 2.27%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s             | 1        | 2.27%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s              | 1        | 2.27%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 1        | 2.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 1        | 2.27%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 2.27%   |
| Kingston RAM 99U5471-060.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 2.27%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 2.27%   |
| Kingston RAM 99P5663-010.A00G 16GB SODIMM DDR4 2667MT/s      | 1        | 2.27%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s       | 1        | 2.27%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s         | 1        | 2.27%   |
| Crucial RAM CT8G4DFS824A.M8FH3 8GB DIMM DDR4 2400MT/s        | 1        | 2.27%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s         | 1        | 2.27%   |
| Crucial RAM CT8G4DFRA266.C16FG 8GB DIMM DDR4 2667MT/s        | 1        | 2.27%   |
| Crucial RAM CT8G4DFD8213.M16FA 8192MB DIMM DDR4 2133MT/s     | 1        | 2.27%   |
| Crucial RAM CT4G4DFS824A.C8FE 4GB DIMM DDR4 2400MT/s         | 1        | 2.27%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s       | 1        | 2.27%   |
| Corsair RAM CMX4GX3M2A160 2GB DIMM DDR3 1333MT/s             | 1        | 2.27%   |
| Corsair RAM CMK8GX4M1A2666C16 8192MB DIMM DDR4 3000MT/s      | 1        | 2.27%   |
| ChangXin Memory RAM QUM4S-8G2666P19 8GB SODIMM DDR4 2667MT/s | 1        | 2.27%   |
| Apacer RAM D22.22242S.001 8GB SODIMM DDR4 2667MT/s           | 1        | 2.27%   |
| AMD RAM R744G2606U1S 4GB DIMM DDR4 2866MT/s                  | 1        | 2.27%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1        | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 76.32%  |
| DDR3    | 6        | 15.79%  |
| Unknown | 2        | 5.26%   |
| DDR2    | 1        | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 78.95%  |
| SODIMM | 8        | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 58.14%  |
| 4096  | 11       | 25.58%  |
| 2048  | 4        | 9.3%    |
| 16384 | 3        | 6.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 16       | 38.1%   |
| 3200  | 4        | 9.52%   |
| 1333  | 4        | 9.52%   |
| 2400  | 3        | 7.14%   |
| 2133  | 3        | 7.14%   |
| 1600  | 2        | 4.76%   |
| 3466  | 1        | 2.38%   |
| 3000  | 1        | 2.38%   |
| 2934  | 1        | 2.38%   |
| 2866  | 1        | 2.38%   |
| 2800  | 1        | 2.38%   |
| 2666  | 1        | 2.38%   |
| 1800  | 1        | 2.38%   |
| 800   | 1        | 2.38%   |
| 400   | 1        | 2.38%   |
| 333   | 1        | 2.38%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SunplusIT             | 3        | 27.27%  |
| Alcor Micro           | 3        | 27.27%  |
| Realtek Semiconductor | 1        | 9.09%   |
| Logitech              | 1        | 9.09%   |
| Creative Technology   | 1        | 9.09%   |
| Arkmicro Technologies | 1        | 9.09%   |
| Apple                 | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SunplusIT USB Camera              | 3        | 27.27%  |
| Alcor Micro USB 2.0 PC Camera     | 3        | 27.27%  |
| Realtek 1080p Camera              | 1        | 9.09%   |
| Logitech HD Webcam C615           | 1        | 9.09%   |
| Creative VF0530 Live! Cam Chat IM | 1        | 9.09%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 9.09%   |
| Apple iPhone 5/5C/5S/6/SE         | 1        | 9.09%   |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Aladdin R.D. | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Aladdin R.D. JaCarta | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 33       | 76.74%  |
| 1     | 10       | 23.26%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 7        | 70%     |
| Net/wireless  | 2        | 20%     |
| Chipcard      | 1        | 10%     |

