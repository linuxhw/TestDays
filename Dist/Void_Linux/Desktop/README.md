Void Linux - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | B550M PRO                   | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| MSI      | B550M PRO                   | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| Unknown  | Unknown                     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Dell     | 0WR7PY A03                  | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| ASUSTek  | TUF B450M-PRO GAMING        | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP       | 3397                        | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek  | TUF Gaming B560-PLUS WIF... | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek  | PRIME Z690-P                | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| ASUSTek  | PRIME Z690-P                | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek  | PRIME Z690-P                | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI      | B450M-A PRO MAX             | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| Dell     | 0WR7PY A01                  | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI      | Z87-G43                     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| ASRock   | X570 Pro4                   | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| ASRock   | TRX40 Taichi                | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| MSI      | B550M PRO                   | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| Gigabyte | B450M DS3H-CF               | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Gigabyte | B550M AORUS PRO-P           | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| ASUSTek  | PRIME X470-PRO              | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| MSI      | B450M-A PRO MAX             | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI      | B450M-A PRO MAX             | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Gigabyte | B450M DS3H-CF               | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Gigabyte | B450M DS3H-CF               | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Gigabyte | H310M M.2 x.x               | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| MSI      | B450 TOMAHAWK MAX II        | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek  | M4A89GTD-PRO/USB3           | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek  | ROG CROSSHAIR VII HERO      | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Dell     | 03NVJ6 A02                  | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| ASRock   | J4005B-ITX                  | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| ASRock   | H61M-VG4                    | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock   | H61M-VG4                    | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| ASUSTek  | M5A78L-M LX                 | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek  | M5A78L-M LX                 | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock   | B450 Pro4                   | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| Unknown  | Unknown                     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASRock   | B450 Pro4                   | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek  | PRIME Z390-P                | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| MSI      | MPG B550I GAMING EDGE WI... | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek  | PRIME Z390-P                | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek  | PRIME Z270-AR               | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI      | MPG B550I GAMING EDGE WI... | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| ASUSTek  | B150M PRO GAMING            | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek  | B150M PRO GAMING            | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| ASUSTek  | H110M-PLUS                  | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| ASUSTek  | PRIME B360M-A               | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek  | PRIME B360M-A               | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock   | 970 Pro3 R2.0               | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| MSI      | Z270 TOMAHAWK               | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| ASUSTek  | P8Z77-V LX2                 | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| ASUSTek  | P8H67-V                     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Gigabyte | GA-78LMT-S2                 | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Dell     | 0H8052                      | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown  | Unknown                     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown  | Unknown                     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek  | H110M-PLUS                  | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASRock   | AB350M                      | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock   | N68-S3 FX                   | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock   | N68-S3 FX                   | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek  | Z97-A                       | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| MSI      | B350M GAMING PRO            | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| ASUSTek  | PRIME A320M-K/BR            | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Void Linux Rolling | 26       | 57.78%  |
| Void Linux         | 19       | 42.22%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Void Linux | 43       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Desktops | Percent |
|-----------|----------|---------|
| 6.0.13_1  | 2        | 4%      |
| 5.8.18_1  | 2        | 4%      |
| 5.18.9_1  | 2        | 4%      |
| 5.16.20_1 | 2        | 4%      |
| 5.13.19_1 | 2        | 4%      |
| 5.11.9_1  | 2        | 4%      |
| 5.10.14_1 | 2        | 4%      |
| 5.9.14_1  | 1        | 2%      |
| 5.8.5_1   | 1        | 2%      |
| 5.8.16_1  | 1        | 2%      |
| 5.8.11_1  | 1        | 2%      |
| 5.8.10_1  | 1        | 2%      |
| 5.6.14_1  | 1        | 2%      |
| 5.4.15_1  | 1        | 2%      |
| 5.4.13_2  | 1        | 2%      |
| 5.3.16_1  | 1        | 2%      |
| 5.18.1_1  | 1        | 2%      |
| 5.18.16_1 | 1        | 2%      |
| 5.18.14_1 | 1        | 2%      |
| 5.15.50_1 | 1        | 2%      |
| 5.15.41_1 | 1        | 2%      |
| 5.15.34_1 | 1        | 2%      |
| 5.15.32_1 | 1        | 2%      |
| 5.15.30_1 | 1        | 2%      |
| 5.15.22_1 | 1        | 2%      |
| 5.15.19_1 | 1        | 2%      |
| 5.15.16_1 | 1        | 2%      |
| 5.15.11_1 | 1        | 2%      |
| 5.13.15_1 | 1        | 2%      |
| 5.13.13_1 | 1        | 2%      |
| 5.13.10_1 | 1        | 2%      |
| 5.12.14_1 | 1        | 2%      |
| 5.12.10_1 | 1        | 2%      |
| 5.11.18_1 | 1        | 2%      |
| 5.10.8_1  | 1        | 2%      |
| 5.10.7_1  | 1        | 2%      |
| 5.10.67_1 | 1        | 2%      |
| 5.10.3_1  | 1        | 2%      |
| 5.10.17_1 | 1        | 2%      |
| 4.19.67_1 | 1        | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.13  | 2        | 4%      |
| 5.8.18  | 2        | 4%      |
| 5.18.9  | 2        | 4%      |
| 5.16.20 | 2        | 4%      |
| 5.13.19 | 2        | 4%      |
| 5.11.9  | 2        | 4%      |
| 5.10.14 | 2        | 4%      |
| 5.9.14  | 1        | 2%      |
| 5.8.5   | 1        | 2%      |
| 5.8.16  | 1        | 2%      |
| 5.8.11  | 1        | 2%      |
| 5.8.10  | 1        | 2%      |
| 5.6.14  | 1        | 2%      |
| 5.4.15  | 1        | 2%      |
| 5.4.13  | 1        | 2%      |
| 5.3.16  | 1        | 2%      |
| 5.18.16 | 1        | 2%      |
| 5.18.14 | 1        | 2%      |
| 5.18.1  | 1        | 2%      |
| 5.15.50 | 1        | 2%      |
| 5.15.41 | 1        | 2%      |
| 5.15.34 | 1        | 2%      |
| 5.15.32 | 1        | 2%      |
| 5.15.30 | 1        | 2%      |
| 5.15.22 | 1        | 2%      |
| 5.15.19 | 1        | 2%      |
| 5.15.16 | 1        | 2%      |
| 5.15.11 | 1        | 2%      |
| 5.13.15 | 1        | 2%      |
| 5.13.13 | 1        | 2%      |
| 5.13.10 | 1        | 2%      |
| 5.12.14 | 1        | 2%      |
| 5.12.10 | 1        | 2%      |
| 5.11.18 | 1        | 2%      |
| 5.10.8  | 1        | 2%      |
| 5.10.7  | 1        | 2%      |
| 5.10.67 | 1        | 2%      |
| 5.10.3  | 1        | 2%      |
| 5.10.17 | 1        | 2%      |
| 4.19.67 | 1        | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 9        | 18%     |
| 5.10    | 7        | 14%     |
| 5.8     | 6        | 12%     |
| 5.18    | 5        | 10%     |
| 5.13    | 5        | 10%     |
| 4.19    | 4        | 8%      |
| 5.11    | 3        | 6%      |
| 6.0     | 2        | 4%      |
| 5.4     | 2        | 4%      |
| 5.16    | 2        | 4%      |
| 5.12    | 2        | 4%      |
| 5.9     | 1        | 2%      |
| 5.6     | 1        | 2%      |
| 5.3     | 1        | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 40       | 93.02%  |
| ppc64le | 1        | 2.33%   |
| ppc64   | 1        | 2.33%   |
| i686    | 1        | 2.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 54.35%  |
| XFCE       | 5        | 10.87%  |
| KDE5       | 4        | 8.7%    |
| GNOME      | 3        | 6.52%   |
| X-Cinnamon | 2        | 4.35%   |
| KDE        | 2        | 4.35%   |
| sway       | 1        | 2.17%   |
| openbox    | 1        | 2.17%   |
| Lumina     | 1        | 2.17%   |
| bspwm      | 1        | 2.17%   |
| awesome    | 1        | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 33       | 73.33%  |
| Wayland | 5        | 11.11%  |
| Unknown | 4        | 8.89%   |
| Tty     | 3        | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 84.44%  |
| SDDM    | 3        | 6.67%   |
| LightDM | 2        | 4.44%   |
| LXDM    | 1        | 2.22%   |
| GDM     | 1        | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 38.3%   |
| Unknown | 11       | 23.4%   |
| ru_RU   | 4        | 8.51%   |
| pl_PL   | 2        | 4.26%   |
| fr_FR   | 2        | 4.26%   |
| cs_CZ   | 2        | 4.26%   |
| pt_BR   | 1        | 2.13%   |
| en_IE   | 1        | 2.13%   |
| en_GB   | 1        | 2.13%   |
| en_DK   | 1        | 2.13%   |
| en_AU   | 1        | 2.13%   |
| el_GR   | 1        | 2.13%   |
| de_DE   | 1        | 2.13%   |
| bg_BG   | 1        | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 27       | 58.7%   |
| EFI  | 19       | 41.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 27       | 58.7%   |
| Btrfs   | 9        | 19.57%  |
| Zfs     | 5        | 10.87%  |
| Xfs     | 4        | 8.7%    |
| Unknown | 1        | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 22       | 48.89%  |
| Unknown | 15       | 33.33%  |
| MBR     | 8        | 17.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 83.72%  |
| Yes       | 7        | 16.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 77.78%  |
| Yes       | 10       | 22.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 37.21%  |
| ASRock              | 8        | 18.6%   |
| MSI                 | 7        | 16.28%  |
| Gigabyte Technology | 4        | 9.3%    |
| Dell                | 4        | 9.3%    |
| Unknown             | 3        | 6.98%   |
| Hewlett-Packard     | 1        | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 3        | 6.98%   |
| Dell OptiPlex 7010           | 2        | 4.65%   |
| ASUS PRIME Z390-P            | 2        | 4.65%   |
| MSI MS-7D14                  | 1        | 2.33%   |
| MSI MS-7C92                  | 1        | 2.33%   |
| MSI MS-7C52                  | 1        | 2.33%   |
| MSI MS-7C02                  | 1        | 2.33%   |
| MSI MS-7A68                  | 1        | 2.33%   |
| MSI MS-7A39                  | 1        | 2.33%   |
| MSI MS-7816                  | 1        | 2.33%   |
| HP Compaq Elite 8300 SFF     | 1        | 2.33%   |
| Gigabyte H310M M.2 2.0       | 1        | 2.33%   |
| Gigabyte GA-78LMT-S2         | 1        | 2.33%   |
| Gigabyte B550M AORUS PRO-P   | 1        | 2.33%   |
| Gigabyte B450M DS3H          | 1        | 2.33%   |
| Dell OptiPlex GX520          | 1        | 2.33%   |
| Dell OptiPlex 780            | 1        | 2.33%   |
| ASUS TUF B450M-PRO GAMING    | 1        | 2.33%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 2.33%   |
| ASUS ROG CROSSHAIR VII HERO  | 1        | 2.33%   |
| ASUS PRIME Z690-P            | 1        | 2.33%   |
| ASUS PRIME Z270-AR           | 1        | 2.33%   |
| ASUS PRIME X470-PRO          | 1        | 2.33%   |
| ASUS PRIME A320M-K/BR        | 1        | 2.33%   |
| ASUS P8Z77-V LX2             | 1        | 2.33%   |
| ASUS P8H67-V                 | 1        | 2.33%   |
| ASUS M5A78L-M LX             | 1        | 2.33%   |
| ASUS M4A89GTD-PRO/USB3       | 1        | 2.33%   |
| ASUS H110M-PLUS              | 1        | 2.33%   |
| ASUS CUSTOM                  | 1        | 2.33%   |
| ASUS B150M PRO GAMING        | 1        | 2.33%   |
| ASRock X570 Pro4             | 1        | 2.33%   |
| ASRock TRX40 Taichi          | 1        | 2.33%   |
| ASRock N68-S3 FX             | 1        | 2.33%   |
| ASRock J4005B-ITX            | 1        | 2.33%   |
| ASRock H61M-VG4              | 1        | 2.33%   |
| ASRock B450 Pro4             | 1        | 2.33%   |
| ASRock AB350M                | 1        | 2.33%   |
| ASRock 970 Pro3 R2.0         | 1        | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 6        | 13.95%  |
| Dell OptiPlex        | 4        | 9.3%    |
| Unknown              | 3        | 6.98%   |
| ASUS ROG             | 2        | 4.65%   |
| MSI MS-7D14          | 1        | 2.33%   |
| MSI MS-7C92          | 1        | 2.33%   |
| MSI MS-7C52          | 1        | 2.33%   |
| MSI MS-7C02          | 1        | 2.33%   |
| MSI MS-7A68          | 1        | 2.33%   |
| MSI MS-7A39          | 1        | 2.33%   |
| MSI MS-7816          | 1        | 2.33%   |
| HP Compaq            | 1        | 2.33%   |
| Gigabyte H310M       | 1        | 2.33%   |
| Gigabyte GA-78LMT-S2 | 1        | 2.33%   |
| Gigabyte B550M       | 1        | 2.33%   |
| Gigabyte B450M       | 1        | 2.33%   |
| ASUS TUF             | 1        | 2.33%   |
| ASUS P8Z77-V         | 1        | 2.33%   |
| ASUS P8H67-V         | 1        | 2.33%   |
| ASUS M5A78L-M        | 1        | 2.33%   |
| ASUS M4A89GTD-PRO    | 1        | 2.33%   |
| ASUS H110M-PLUS      | 1        | 2.33%   |
| ASUS CUSTOM          | 1        | 2.33%   |
| ASUS B150M           | 1        | 2.33%   |
| ASRock X570          | 1        | 2.33%   |
| ASRock TRX40         | 1        | 2.33%   |
| ASRock N68-S3        | 1        | 2.33%   |
| ASRock J4005B-ITX    | 1        | 2.33%   |
| ASRock H61M-VG4      | 1        | 2.33%   |
| ASRock B450          | 1        | 2.33%   |
| ASRock AB350M        | 1        | 2.33%   |
| ASRock 970           | 1        | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 9        | 20.93%  |
| 2020    | 5        | 11.63%  |
| 2019    | 5        | 11.63%  |
| 2017    | 4        | 9.3%    |
| 2013    | 4        | 9.3%    |
| 2012    | 4        | 9.3%    |
| 2010    | 3        | 6.98%   |
| 2016    | 2        | 4.65%   |
| 2011    | 2        | 4.65%   |
| Unknown | 2        | 4.65%   |
| 2022    | 1        | 2.33%   |
| 2021    | 1        | 2.33%   |
| 2005    | 1        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 43       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 43       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 16       | 36.36%  |
| 8.01-16.0       | 11       | 25%     |
| 32.01-64.0      | 6        | 13.64%  |
| 4.01-8.0        | 5        | 11.36%  |
| 3.01-4.0        | 3        | 6.82%   |
| More than 256.0 | 1        | 2.27%   |
| 2.01-3.0        | 1        | 2.27%   |
| 64.01-256.0     | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 13       | 27.08%  |
| 3.01-4.0    | 7        | 14.58%  |
| 1.01-2.0    | 7        | 14.58%  |
| 0.51-1.0    | 7        | 14.58%  |
| 8.01-16.0   | 6        | 12.5%   |
| 4.01-8.0    | 5        | 10.42%  |
| 64.01-256.0 | 1        | 2.08%   |
| 16.01-24.0  | 1        | 2.08%   |
| 0.01-0.5    | 1        | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 31.11%  |
| 3      | 13       | 28.89%  |
| 1      | 13       | 28.89%  |
| 4      | 3        | 6.67%   |
| 9      | 1        | 2.22%   |
| 5      | 1        | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 79.07%  |
| Yes       | 9        | 20.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 67.44%  |
| Yes       | 14       | 32.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 77.27%  |
| Yes       | 10       | 22.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 27.91%  |
| Russia      | 4        | 9.3%    |
| Poland      | 4        | 9.3%    |
| Germany     | 3        | 6.98%   |
| Czechia     | 3        | 6.98%   |
| Brazil      | 3        | 6.98%   |
| France      | 2        | 4.65%   |
| UK          | 1        | 2.33%   |
| Turkey      | 1        | 2.33%   |
| Sweden      | 1        | 2.33%   |
| Spain       | 1        | 2.33%   |
| Netherlands | 1        | 2.33%   |
| India       | 1        | 2.33%   |
| Greece      | 1        | 2.33%   |
| Bulgaria    | 1        | 2.33%   |
| Belgium     | 1        | 2.33%   |
| Bangladesh  | 1        | 2.33%   |
| Australia   | 1        | 2.33%   |
| Argentina   | 1        | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Denver             | 3        | 6.67%   |
| Prague             | 2        | 4.44%   |
| Munich             | 2        | 4.44%   |
| Lublin             | 2        | 4.44%   |
| Amsterdam          | 2        | 4.44%   |
| Zagnansk           | 1        | 2.22%   |
| Yekaterinburg      | 1        | 2.22%   |
| Varna              | 1        | 2.22%   |
| South Shields      | 1        | 2.22%   |
| Sofia              | 1        | 2.22%   |
| Saint-Paul-les-Dax | 1        | 2.22%   |
| Saint Paul         | 1        | 2.22%   |
| Rosario            | 1        | 2.22%   |
| Rio de Janeiro     | 1        | 2.22%   |
| Richmond           | 1        | 2.22%   |
| Pyatigorsk         | 1        | 2.22%   |
| Pelabravo          | 1        | 2.22%   |
| Pardubice          | 1        | 2.22%   |
| Orlando            | 1        | 2.22%   |
| Nizhniy Novgorod   | 1        | 2.22%   |
| New York           | 1        | 2.22%   |
| Monaca             | 1        | 2.22%   |
| Miedziana Gora     | 1        | 2.22%   |
| Mer                | 1        | 2.22%   |
| Kolkata            | 1        | 2.22%   |
| Iwkowa             | 1        | 2.22%   |
| Ioannina           | 1        | 2.22%   |
| Gothenburg         | 1        | 2.22%   |
| Glasgow            | 1        | 2.22%   |
| Epping             | 1        | 2.22%   |
| Elgin              | 1        | 2.22%   |
| Eden               | 1        | 2.22%   |
| Dhaka              | 1        | 2.22%   |
| Contagem           | 1        | 2.22%   |
| Burgau             | 1        | 2.22%   |
| Brussels           | 1        | 2.22%   |
| Blumenau           | 1        | 2.22%   |
| Arkhangelsk        | 1        | 2.22%   |
| Antalya            | 1        | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 19       | 26     | 21.59%  |
| Samsung Electronics       | 19       | 32     | 21.59%  |
| Seagate                   | 13       | 19     | 14.77%  |
| Kingston                  | 9        | 9      | 10.23%  |
| Toshiba                   | 4        | 5      | 4.55%   |
| Crucial                   | 3        | 4      | 3.41%   |
| SanDisk                   | 2        | 2      | 2.27%   |
| Intel                     | 2        | 3      | 2.27%   |
| Hitachi                   | 2        | 2      | 2.27%   |
| HGST                      | 2        | 2      | 2.27%   |
| Corsair                   | 2        | 2      | 2.27%   |
| A-DATA Technology         | 2        | 3      | 2.27%   |
| XPG                       | 1        | 4      | 1.14%   |
| SPCC                      | 1        | 1      | 1.14%   |
| Phison                    | 1        | 1      | 1.14%   |
| Patriot                   | 1        | 1      | 1.14%   |
| OCZ                       | 1        | 1      | 1.14%   |
| Micron/Crucial Technology | 1        | 1      | 1.14%   |
| Maxtor                    | 1        | 1      | 1.14%   |
| LITEONIT                  | 1        | 1      | 1.14%   |
| Gigabyte Technology       | 1        | 2      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 4        | 3.92%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.96%   |
| Samsung SSD 980 PRO 500GB        | 2        | 1.96%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.96%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.96%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 1.96%   |
| Kingston SHFS37A120G 120GB SSD   | 2        | 1.96%   |
| XPG NVMe SSD Drive 2TB           | 1        | 0.98%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.98%   |
| WDC WD7500AYYS-01RCA0 752GB      | 1        | 0.98%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.98%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.98%   |
| WDC WD20EZBX-00AYRA0 2TB         | 1        | 0.98%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 0.98%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.98%   |
| WDC WD1600AAJS-60PSA0 160GB      | 1        | 0.98%   |
| WDC WD15EARS-00MVWB0 1TB         | 1        | 0.98%   |
| WDC WD10JPVX-08JC3T6 1TB         | 1        | 0.98%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1        | 0.98%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1        | 0.98%   |
| WDC WD10EZEX-00BBHA0 1TB         | 1        | 0.98%   |
| WDC WD10EFRX-68PJCN0 1TB         | 1        | 0.98%   |
| WDC WD10EFRX-68FYTN0 1TB         | 1        | 0.98%   |
| WDC WD10EARX-00PASB0 1TB         | 1        | 0.98%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 0.98%   |
| WDC WD1001FALS-00K1B0 1TB        | 1        | 0.98%   |
| Toshiba MQ04ABF100 1TB           | 1        | 0.98%   |
| Toshiba HDWD110 1TB              | 1        | 0.98%   |
| Toshiba DT01ACA200 2TB           | 1        | 0.98%   |
| Toshiba DT01ACA050 500GB         | 1        | 0.98%   |
| SPCC Solid State Disk 128GB      | 1        | 0.98%   |
| Seagate ST9500325AS 500GB        | 1        | 0.98%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 0.98%   |
| Seagate ST3750330AS 752GB        | 1        | 0.98%   |
| Seagate ST3500413AS 500GB        | 1        | 0.98%   |
| Seagate ST3360320AS 360GB        | 1        | 0.98%   |
| Seagate ST2000VX000-1CU164 2TB   | 1        | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 24     | 40.48%  |
| Seagate             | 13       | 19     | 30.95%  |
| Toshiba             | 4        | 5      | 9.52%   |
| Samsung Electronics | 3        | 3      | 7.14%   |
| Hitachi             | 2        | 2      | 4.76%   |
| HGST                | 2        | 2      | 4.76%   |
| Maxtor              | 1        | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 13     | 32.26%  |
| Kingston            | 9        | 9      | 29.03%  |
| WDC                 | 2        | 2      | 6.45%   |
| SPCC                | 1        | 1      | 3.23%   |
| SanDisk             | 1        | 1      | 3.23%   |
| Patriot             | 1        | 1      | 3.23%   |
| OCZ                 | 1        | 1      | 3.23%   |
| LITEONIT            | 1        | 1      | 3.23%   |
| Intel               | 1        | 1      | 3.23%   |
| Gigabyte Technology | 1        | 2      | 3.23%   |
| Crucial             | 1        | 2      | 3.23%   |
| Corsair             | 1        | 1      | 3.23%   |
| A-DATA Technology   | 1        | 2      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 56     | 43.24%  |
| SSD  | 27       | 37     | 36.49%  |
| NVMe | 15       | 29     | 20.27%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 41       | 93     | 73.21%  |
| NVMe | 15       | 29     | 26.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 42     | 48.48%  |
| 0.51-1.0   | 20       | 29     | 30.3%   |
| 1.01-2.0   | 12       | 19     | 18.18%  |
| 3.01-4.0   | 1        | 2      | 1.52%   |
| 4.01-10.0  | 1        | 1      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 9        | 20%     |
| 101-250        | 8        | 17.78%  |
| 1001-2000      | 7        | 15.56%  |
| 501-1000       | 7        | 15.56%  |
| Unknown        | 5        | 11.11%  |
| More than 3000 | 4        | 8.89%   |
| 2001-3000      | 4        | 8.89%   |
| 1-20           | 1        | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 20%     |
| 1-20           | 10       | 20%     |
| 251-500        | 7        | 14%     |
| 51-100         | 5        | 10%     |
| Unknown        | 5        | 10%     |
| 1001-2000      | 4        | 8%      |
| 501-1000       | 4        | 8%      |
| More than 3000 | 2        | 4%      |
| 21-50          | 2        | 4%      |
| 2001-3000      | 1        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB       | 1        | 2      | 7.14%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1        | 1      | 7.14%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 1      | 7.14%   |
| Toshiba MQ04ABF100 1TB            | 1        | 2      | 7.14%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 7.14%   |
| Seagate ST3750330AS 752GB         | 1        | 1      | 7.14%   |
| Seagate ST2000VX000-1CU164 2TB    | 1        | 2      | 7.14%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 7.14%   |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 7.14%   |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 7.14%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 7.14%   |
| Hitachi HTS545050B9A300 500GB     | 1        | 1      | 7.14%   |
| A-DATA Technology SU700 120GB SSD | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 35.71%  |
| WDC                 | 3        | 4      | 21.43%  |
| Samsung Electronics | 3        | 3      | 21.43%  |
| Toshiba             | 1        | 2      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| A-DATA Technology   | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 38.46%  |
| WDC                 | 3        | 4      | 23.08%  |
| Samsung Electronics | 3        | 3      | 23.08%  |
| Toshiba             | 1        | 2      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 16     | 92.31%  |
| SSD  | 1        | 1      | 7.69%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 29       | 61     | 49.15%  |
| Detected | 18       | 44     | 30.51%  |
| Malfunc  | 12       | 17     | 20.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 21       | 33.87%  |
| AMD                       | 20       | 32.26%  |
| Samsung Electronics       | 9        | 14.52%  |
| Phison Electronics        | 2        | 3.23%   |
| Micron/Crucial Technology | 2        | 3.23%   |
| ADATA Technology          | 2        | 3.23%   |
| SanDisk                   | 1        | 1.61%   |
| Nvidia                    | 1        | 1.61%   |
| Marvell Technology Group  | 1        | 1.61%   |
| JMicron Technology        | 1        | 1.61%   |
| Broadcom                  | 1        | 1.61%   |
| ASMedia Technology        | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 14.1%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 10.26%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 8.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.56%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 2.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 2.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.28%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.28%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.28%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.28%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.28%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.28%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.28%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1        | 1.28%   |
| JMicron JMB361 AHCI/IDE                                                        | 1        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.28%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.28%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.28%   |
| Broadcom K2 SATA                                                               | 1        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.28%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 39       | 62.9%   |
| NVMe | 15       | 24.19%  |
| IDE  | 7        | 11.29%  |
| RAID | 1        | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 21       | 48.84%  |
| Intel                    | 20       | 46.51%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 2.33%   |
| PowerMac11,2             | 1        | 2.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4        | 9.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2        | 4.65%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2        | 4.65%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2        | 4.65%   |
| AMD FX-4300 Quad-Core Processor                    | 2        | 4.65%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1        | 2.33%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1        | 2.33%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1        | 2.33%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1        | 2.33%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1        | 2.33%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1        | 2.33%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1        | 2.33%   |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1        | 2.33%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1        | 2.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz                   | 1        | 2.33%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1        | 2.33%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1        | 2.33%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1        | 2.33%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1        | 2.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1        | 2.33%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1        | 2.33%   |
| Intel 12th Gen Core i7-12700K                      | 1        | 2.33%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz             | 1        | 2.33%   |
| AMD Ryzen Threadripper 3990X 64-Core Processor     | 1        | 2.33%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 1        | 2.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1        | 2.33%   |
| AMD Ryzen 7 1700X Eight-Core Processor             | 1        | 2.33%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1        | 2.33%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1        | 2.33%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 1        | 2.33%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1        | 2.33%   |
| AMD Ryzen 5 1600 Six-Core Processor                | 1        | 2.33%   |
| AMD Ryzen 3 3100 4-Core Processor                  | 1        | 2.33%   |
| AMD Phenom II X4 980 Processor                     | 1        | 2.33%   |
| AMD Athlon II X3 455 Processor                     | 1        | 2.33%   |
| AMD Athlon II X2 280 Processor                     | 1        | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 10       | 23.26%  |
| Intel Core i5          | 7        | 16.28%  |
| Other                  | 4        | 9.3%    |
| AMD Ryzen 7            | 4        | 9.3%    |
| Intel Core i3          | 3        | 6.98%   |
| Intel Core i7          | 2        | 4.65%   |
| AMD FX                 | 2        | 4.65%   |
| Intel Pentium Gold     | 1        | 2.33%   |
| Intel Pentium 4        | 1        | 2.33%   |
| Intel Pentium          | 1        | 2.33%   |
| Intel Core i9          | 1        | 2.33%   |
| Intel Core 2 Duo       | 1        | 2.33%   |
| Intel Celeron          | 1        | 2.33%   |
| AMD Ryzen Threadripper | 1        | 2.33%   |
| AMD Ryzen 3            | 1        | 2.33%   |
| AMD Phenom II X4       | 1        | 2.33%   |
| AMD Athlon II X3       | 1        | 2.33%   |
| AMD Athlon II X2       | 1        | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 27.91%  |
| 6      | 11       | 25.58%  |
| 2      | 10       | 23.26%  |
| 8      | 6        | 13.95%  |
| 64     | 1        | 2.33%   |
| 12     | 1        | 2.33%   |
| 3      | 1        | 2.33%   |
| 1      | 1        | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 60.47%  |
| 1      | 16       | 37.21%  |
| 4      | 1        | 2.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 39       | 90.7%   |
| Unknown        | 3        | 6.98%   |
| 32-bit         | 1        | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 35.56%  |
| 0x306a9    | 3        | 6.67%   |
| 0x906e9    | 2        | 4.44%   |
| 0x0a201009 | 2        | 4.44%   |
| 0x08701021 | 2        | 4.44%   |
| 0x0800820d | 2        | 4.44%   |
| 0x06000852 | 2        | 4.44%   |
| 0x010000c8 | 2        | 4.44%   |
| 0xa0671    | 1        | 2.22%   |
| 0x906ed    | 1        | 2.22%   |
| 0x906ea    | 1        | 2.22%   |
| 0x90672    | 1        | 2.22%   |
| 0x706a1    | 1        | 2.22%   |
| 0x506e3    | 1        | 2.22%   |
| 0x306c3    | 1        | 2.22%   |
| 0x1067a    | 1        | 2.22%   |
| 0x0a50000c | 1        | 2.22%   |
| 0x0a201205 | 1        | 2.22%   |
| 0x08701013 | 1        | 2.22%   |
| 0x08001138 | 1        | 2.22%   |
| 0x08001136 | 1        | 2.22%   |
| 0x08001129 | 1        | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 6        | 13.95%  |
| KabyLake         | 6        | 13.95%  |
| IvyBridge        | 6        | 13.95%  |
| Zen 2            | 4        | 9.3%    |
| Zen+             | 3        | 6.98%   |
| Zen              | 3        | 6.98%   |
| K10              | 3        | 6.98%   |
| Piledriver       | 2        | 4.65%   |
| Haswell          | 2        | 4.65%   |
| Unknown          | 2        | 4.65%   |
| Skylake          | 1        | 2.33%   |
| Penryn           | 1        | 2.33%   |
| NetBurst         | 1        | 2.33%   |
| Icelake          | 1        | 2.33%   |
| Goldmont plus    | 1        | 2.33%   |
| Alderlake Hybrid | 1        | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 22       | 45.83%  |
| AMD               | 18       | 37.5%   |
| Intel             | 7        | 14.58%  |
| ASPEED Technology | 1        | 2.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                               | 4        | 8%      |
| Nvidia TU117 [GeForce GTX 1650]                                  | 2        | 4%      |
| Nvidia GM204 [GeForce GTX 970]                                   | 2        | 4%      |
| Nvidia GK208B [GeForce GT 710]                                   | 2        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 2        | 4%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 2        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2        | 4%      |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]               | 2        | 4%      |
| Nvidia TU106 [GeForce RTX 2070]                                  | 1        | 2%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                           | 1        | 2%      |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                            | 1        | 2%      |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                        | 1        | 2%      |
| Nvidia NV43 [GeForce 6600]                                       | 1        | 2%      |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 2%      |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 2%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 2%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                | 1        | 2%      |
| Nvidia GK110 [GeForce GTX 780]                                   | 1        | 2%      |
| Nvidia GF108 [GeForce GT 420]                                    | 1        | 2%      |
| Nvidia GA102 [GeForce RTX 3090]                                  | 1        | 2%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                          | 1        | 2%      |
| Intel RocketLake-S GT1 [UHD Graphics 750]                        | 1        | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1        | 2%      |
| Intel GeminiLake [UHD Graphics 600]                              | 1        | 2%      |
| Intel 82945G/GZ Integrated Graphics Controller                   | 1        | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller            | 1        | 2%      |
| ASPEED Technology ASPEED Graphics Family                         | 1        | 2%      |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                         | 1        | 2%      |
| AMD Tonga PRO [Radeon R9 285/380]                                | 1        | 2%      |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                | 1        | 2%      |
| AMD RS880 [Radeon HD 4290]                                       | 1        | 2%      |
| AMD RS780L [Radeon 3000]                                         | 1        | 2%      |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                   | 1        | 2%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]             | 1        | 2%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 1        | 2%      |
| AMD Lexa XT [Radeon PRO WX 2100]                                 | 1        | 2%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]       | 1        | 2%      |
| AMD Juniper XT [Radeon HD 6770]                                  | 1        | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]     | 1        | 2%      |
| AMD Bonaire [FirePro W5100]                                      | 1        | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 21       | 45.65%  |
| 1 x AMD      | 17       | 36.96%  |
| 1 x Intel    | 6        | 13.04%  |
| 2 x Nvidia   | 1        | 2.17%   |
| AMD + ASPEED | 1        | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 56.52%  |
| Proprietary | 20       | 43.48%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 31.91%  |
| 3.01-4.0   | 9        | 19.15%  |
| 1.01-2.0   | 9        | 19.15%  |
| 5.01-6.0   | 3        | 6.38%   |
| 8.01-16.0  | 3        | 6.38%   |
| 7.01-8.0   | 2        | 4.26%   |
| 2.01-3.0   | 2        | 4.26%   |
| 0.01-0.5   | 2        | 4.26%   |
| 16.01-24.0 | 1        | 2.13%   |
| 0.51-1.0   | 1        | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 8        | 16.33%  |
| Samsung Electronics  | 6        | 12.24%  |
| Hewlett-Packard      | 6        | 12.24%  |
| Acer                 | 5        | 10.2%   |
| Philips              | 3        | 6.12%   |
| Goldstar             | 3        | 6.12%   |
| BenQ                 | 3        | 6.12%   |
| Iiyama               | 2        | 4.08%   |
| Fujitsu Siemens      | 2        | 4.08%   |
| ASUSTek Computer     | 2        | 4.08%   |
| Ancor Communications | 2        | 4.08%   |
| Unknown              | 1        | 2.04%   |
| Sceptre Tech         | 1        | 2.04%   |
| Sceptre              | 1        | 2.04%   |
| ONN                  | 1        | 2.04%   |
| MSI                  | 1        | 2.04%   |
| Lenovo               | 1        | 2.04%   |
| FUN                  | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1        | 1.85%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1        | 1.85%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1        | 1.85%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1        | 1.85%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1        | 1.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1        | 1.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1        | 1.85%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1        | 1.85%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1        | 1.85%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 1.85%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1        | 1.85%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1        | 1.85%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1        | 1.85%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 1        | 1.85%   |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1        | 1.85%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1        | 1.85%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1        | 1.85%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 1        | 1.85%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1        | 1.85%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1        | 1.85%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1        | 1.85%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1        | 1.85%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 1.85%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1        | 1.85%   |
| Goldstar LG 32 FHD GSM7701 1920x1080 600x340mm 27.2-inch              | 1        | 1.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.85%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1        | 1.85%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1        | 1.85%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1        | 1.85%   |
| Fujitsu Siemens E19-06SA FUS0742 1280x1024 376x301mm 19.0-inch        | 1        | 1.85%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1        | 1.85%   |
| Dell U2913WM DEL4089 2560x1080 673x284mm 28.8-inch                    | 1        | 1.85%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1        | 1.85%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 1.85%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1        | 1.85%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1        | 1.85%   |
| Dell P2418HZ DELD0AF 1920x1080 530x300mm 24.0-inch                    | 1        | 1.85%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 1        | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 52.08%  |
| 1680x1050 (WSXGA+) | 4        | 8.33%   |
| 3840x2160 (4K)     | 3        | 6.25%   |
| 1920x1200 (WUXGA)  | 3        | 6.25%   |
| 3440x1440          | 2        | 4.17%   |
| 2560x1440 (QHD)    | 2        | 4.17%   |
| 1366x768 (WXGA)    | 2        | 4.17%   |
| 1280x1024 (SXGA)   | 2        | 4.17%   |
| Unknown            | 2        | 4.17%   |
| 7680x1080          | 1        | 2.08%   |
| 3840x1600          | 1        | 2.08%   |
| 2560x1080          | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 13       | 25.49%  |
| Unknown | 9        | 17.65%  |
| 21      | 6        | 11.76%  |
| 27      | 5        | 9.8%    |
| 23      | 4        | 7.84%   |
| 22      | 4        | 7.84%   |
| 34      | 2        | 3.92%   |
| 40      | 1        | 1.96%   |
| 37      | 1        | 1.96%   |
| 31      | 1        | 1.96%   |
| 28      | 1        | 1.96%   |
| 25      | 1        | 1.96%   |
| 20      | 1        | 1.96%   |
| 19      | 1        | 1.96%   |
| 17      | 1        | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 21       | 42%     |
| 401-500     | 11       | 22%     |
| Unknown     | 9        | 18%     |
| 601-700     | 3        | 6%      |
| 801-900     | 2        | 4%      |
| 701-800     | 2        | 4%      |
| 351-400     | 1        | 2%      |
| 301-350     | 1        | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 54.17%  |
| Unknown | 9        | 18.75%  |
| 16/10   | 7        | 14.58%  |
| 21/9    | 4        | 8.33%   |
| 5/4     | 2        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 38.78%  |
| Unknown        | 9        | 18.37%  |
| 251-300        | 8        | 16.33%  |
| 301-350        | 5        | 10.2%   |
| 351-500        | 3        | 6.12%   |
| 151-200        | 2        | 4.08%   |
| 501-1000       | 2        | 4.08%   |
| 141-150        | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 56.86%  |
| 101-120 | 11       | 21.57%  |
| Unknown | 9        | 17.65%  |
| 161-240 | 1        | 1.96%   |
| 121-160 | 1        | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 80%     |
| 2     | 9        | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 29       | 43.28%  |
| Intel                           | 18       | 26.87%  |
| Broadcom                        | 3        | 4.48%   |
| TP-Link                         | 2        | 2.99%   |
| Ralink Technology               | 2        | 2.99%   |
| Qualcomm Atheros Communications | 2        | 2.99%   |
| Qualcomm Atheros                | 2        | 2.99%   |
| Xiaomi                          | 1        | 1.49%   |
| Tenda                           | 1        | 1.49%   |
| STMicroelectronics              | 1        | 1.49%   |
| OnePlus Technology (Shenzhen)   | 1        | 1.49%   |
| Nvidia                          | 1        | 1.49%   |
| MediaTek                        | 1        | 1.49%   |
| ASIX Electronics                | 1        | 1.49%   |
| Arduino SA                      | 1        | 1.49%   |
| Apple                           | 1        | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 21       | 30.88%  |
| Realtek RTL8125 2.5GbE Controller                                       | 5        | 7.35%   |
| Intel I211 Gigabit Network Connection                                   | 5        | 7.35%   |
| Intel Wi-Fi 6 AX200                                                     | 3        | 4.41%   |
| Intel Ethernet Connection (2) I219-V                                    | 3        | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3        | 4.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2        | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1        | 1.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 1.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1        | 1.47%   |
| Tenda U12                                                               | 1        | 1.47%   |
| STMicroelectronics Virtual COM Port                                     | 1        | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.47%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1        | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.47%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:3BB6B401                              | 1        | 1.47%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.47%   |
| MediaTek Infinix NOTE 11                                                | 1        | 1.47%   |
| Intel Wireless 7265                                                     | 1        | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 1.47%   |
| Intel Ethernet Connection I218-V                                        | 1        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 1        | 1.47%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                             | 1        | 1.47%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                 | 1        | 1.47%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                        | 1        | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1        | 1.47%   |
| Arduino SA Uno R3 (CDC ACM)                                             | 1        | 1.47%   |
| Apple iPad 4/Mini1                                                      | 1        | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 40%     |
| TP-Link                         | 2        | 13.33%  |
| Ralink Technology               | 2        | 13.33%  |
| Qualcomm Atheros Communications | 2        | 13.33%  |
| Tenda                           | 1        | 6.67%   |
| Realtek Semiconductor           | 1        | 6.67%   |
| Qualcomm Atheros                | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 3        | 20%     |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 13.33%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1        | 6.67%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1        | 6.67%   |
| Tenda U12                                                               | 1        | 6.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 6.67%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 6.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 6.67%   |
| Intel Wireless 7265                                                     | 1        | 6.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1        | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 56%     |
| Intel                 | 13       | 26%     |
| Broadcom              | 3        | 6%      |
| Xiaomi                | 1        | 2%      |
| Qualcomm Atheros      | 1        | 2%      |
| Nvidia                | 1        | 2%      |
| MediaTek              | 1        | 2%      |
| ASIX Electronics      | 1        | 2%      |
| Apple                 | 1        | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 42%     |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 10%     |
| Intel I211 Gigabit Network Connection                             | 5        | 10%     |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 4%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2%      |
| Nvidia MCP61 Ethernet                                             | 1        | 2%      |
| MediaTek Infinix NOTE 11                                          | 1        | 2%      |
| Intel Ethernet Connection I218-V                                  | 1        | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2%      |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1        | 2%      |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 2%      |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 2%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 2%      |
| Apple iPad 4/Mini1                                                | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 71.67%  |
| WiFi     | 14       | 23.33%  |
| Modem    | 2        | 3.33%   |
| Unknown  | 1        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 36       | 81.82%  |
| WiFi     | 8        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 81.4%   |
| 2     | 5        | 11.63%  |
| 3     | 3        | 6.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 86.05%  |
| Yes  | 6        | 13.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 45.45%  |
| Cambridge Silicon Radio | 4        | 36.36%  |
| Broadcom                | 2        | 18.18%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 36.36%  |
| Intel AX200 Bluetooth                               | 3        | 27.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 9.09%   |
| Intel AX201 Bluetooth                               | 1        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 9.09%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 24       | 27.91%  |
| Nvidia              | 21       | 24.42%  |
| Intel               | 19       | 22.09%  |
| C-Media Electronics | 5        | 5.81%   |
| JMTek               | 4        | 4.65%   |
| Logitech            | 3        | 3.49%   |
| VIA Technologies    | 1        | 1.16%   |
| Unknown             | 1        | 1.16%   |
| SteelSeries ApS     | 1        | 1.16%   |
| SAVITECH            | 1        | 1.16%   |
| Fry's Electronics   | 1        | 1.16%   |
| Focusrite-Novation  | 1        | 1.16%   |
| Elgato Systems      | 1        | 1.16%   |
| Creative Technology | 1        | 1.16%   |
| Corsair             | 1        | 1.16%   |
| Cambridge Audio     | 1        | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 8.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 5.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 4.9%    |
| JMTek USB PnP Audio Device                                                 | 4        | 3.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.94%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.96%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 0.98%   |
| Unknown USB Audio                                                          | 1        | 0.98%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.98%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.98%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.98%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.98%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.98%   |
| Logitech PRO X                                                             | 1        | 0.98%   |
| Logitech G633 Gaming Headset                                               | 1        | 0.98%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 0.98%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.98%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 0.98%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 20.69%  |
| G.Skill             | 6        | 20.69%  |
| Corsair             | 4        | 13.79%  |
| Unknown             | 3        | 10.34%  |
| Crucial             | 3        | 10.34%  |
| Samsung Electronics | 2        | 6.9%    |
| A-DATA Technology   | 2        | 6.9%    |
| SK hynix            | 1        | 3.45%   |
| Patriot             | 1        | 3.45%   |
| Avant               | 1        | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 5.88%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 2.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 2.94%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2.94%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.94%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s      | 1        | 2.94%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s        | 1        | 2.94%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s      | 1        | 2.94%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s        | 1        | 2.94%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s  | 1        | 2.94%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2.94%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.94%   |
| Kingston RAM 99U5471-025.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 2.94%   |
| Kingston RAM 9905701-017.A00G 16384MB DIMM DDR4 2666MT/s | 1        | 2.94%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 1        | 2.94%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 2.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 2.94%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s    | 1        | 2.94%   |
| G.Skill RAM F4-2666C18-4GRS 4GB SODIMM DDR4 2400MT/s     | 1        | 2.94%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s  | 1        | 2.94%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s     | 1        | 2.94%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s     | 1        | 2.94%   |
| Crucial RAM CT16G4DFD824A.M16FJ 16GB DIMM DDR4 2400MT/s  | 1        | 2.94%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s  | 1        | 2.94%   |
| Crucial RAM CT16G48C40U5.M8A1 16GB DIMM DDR5 4800MT/s    | 1        | 2.94%   |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s | 1        | 2.94%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s      | 1        | 2.94%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s     | 1        | 2.94%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s     | 1        | 2.94%   |
| Avant RAM W641GU42J7240NC 8192MB DIMM DDR4 2400MT/s      | 1        | 2.94%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 2.94%   |
| A-DATA RAM DDR4 2666 2OZ 8192MB DIMM DDR4 3200MT/s       | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 62.07%  |
| DDR3    | 8        | 27.59%  |
| Unknown | 2        | 6.9%    |
| DDR5    | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 96.55%  |
| SODIMM | 1        | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 46.67%  |
| 4096  | 7        | 23.33%  |
| 16384 | 6        | 20%     |
| 2048  | 2        | 6.67%   |
| 1024  | 1        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 6        | 18.18%  |
| 1333  | 5        | 15.15%  |
| 3600  | 4        | 12.12%  |
| 3200  | 4        | 12.12%  |
| 1600  | 4        | 12.12%  |
| 3000  | 2        | 6.06%   |
| 4800  | 1        | 3.03%   |
| 3866  | 1        | 3.03%   |
| 3333  | 1        | 3.03%   |
| 2933  | 1        | 3.03%   |
| 2800  | 1        | 3.03%   |
| 2666  | 1        | 3.03%   |
| 1867  | 1        | 3.03%   |
| 1067  | 1        | 3.03%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 6        | 42.86%  |
| Microdia              | 2        | 14.29%  |
| MacroSilicon          | 2        | 14.29%  |
| Realtek Semiconductor | 1        | 7.14%   |
| Microsoft             | 1        | 7.14%   |
| GEMBIRD               | 1        | 7.14%   |
| Chicony Electronics   | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 21.43%  |
| Realtek USB Camera                                | 1        | 7.14%   |
| Microsoft LifeCam HD-3000                         | 1        | 7.14%   |
| Microdia USB 2.0 Camera                           | 1        | 7.14%   |
| Microdia Camera                                   | 1        | 7.14%   |
| MacroSilicon USB Video                            | 1        | 7.14%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1        | 7.14%   |
| Logitech Webcam C930e                             | 1        | 7.14%   |
| Logitech HD Webcam C615                           | 1        | 7.14%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 7.14%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 7.14%   |
| Chicony HP 720p HD Monitor Webcam                 | 1        | 7.14%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 38       | 88.37%  |
| 1     | 3        | 6.98%   |
| 2     | 2        | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Sound         | 2        | 28.57%  |
| Net/wireless  | 2        | 28.57%  |
| Graphics card | 2        | 28.57%  |
| Camera        | 1        | 14.29%  |

