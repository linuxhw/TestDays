RHEL 9 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_9/Desktop/README.md) and [notebooks](/Dist/RHEL_9/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | Notebook    | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Intel         | NUC12WSBi7 M63355-302       | Mini pc     | [043bac31d2](https://linux-hardware.org/?probe=043bac31d2) | Sep 28, 2023 |
| Dell          | G16 7620                    | Notebook    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| Acer          | Aspire C24-865              | All in one  | [de824a4f4e](https://linux-hardware.org/?probe=de824a4f4e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | Desktop     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Lenovo        | STA7B38870 02               | Server      | [80a2f3d367](https://linux-hardware.org/?probe=80a2f3d367) | Jun 18, 2023 |
| Dell          | 07T4MC A02                  | Desktop     | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 13.43%  |
| 5.14.0-284.30.1.el9_2.x86_64 | 8         | 11.94%  |
| 5.14.0-284.25.1.el9_2.x86_64 | 7         | 10.45%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 8.96%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 5         | 7.46%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 5         | 7.46%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 5.97%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 5.97%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 5.97%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 4.48%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 4.48%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 2.99%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 2.99%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 1.49%   |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 1.49%   |
| 5.14.0-39.el9.x86_64         | 1         | 1.49%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1         | 1.49%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 63        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 63        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 62        | 98.41%  |
| aarch64 | 1         | 1.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 59        | 92.19%  |
| GNOME Classic   | 2         | 3.13%   |
| KDE5            | 1         | 1.56%   |
| GNOME Flashback | 1         | 1.56%   |
| Unknown         | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 44        | 69.84%  |
| X11     | 17        | 26.98%  |
| Tty     | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 58.73%  |
| GDM     | 25        | 39.68%  |
| SDDM    | 1         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 43        | 68.25%  |
| en_GB | 5         | 7.94%   |
| pt_BR | 4         | 6.35%   |
| en_IN | 3         | 4.76%   |
| en_NZ | 2         | 3.17%   |
| ru_RU | 1         | 1.59%   |
| ja_JP | 1         | 1.59%   |
| es_ES | 1         | 1.59%   |
| en_ZA | 1         | 1.59%   |
| en_CA | 1         | 1.59%   |
| cs_CZ | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 56        | 88.89%  |
| BIOS | 7         | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 61        | 96.83%  |
| Ext4 | 2         | 3.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 55.56%  |
| GPT     | 25        | 39.68%  |
| MBR     | 3         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 87.3%   |
| Yes       | 8         | 12.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 88.89%  |
| Yes       | 7         | 11.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 12        | 19.05%  |
| Lenovo                  | 9         | 14.29%  |
| ASUSTek Computer        | 9         | 14.29%  |
| MSI                     | 7         | 11.11%  |
| Hewlett-Packard         | 7         | 11.11%  |
| Gigabyte Technology     | 5         | 7.94%   |
| Unknown                 | 3         | 4.76%   |
| Intel                   | 2         | 3.17%   |
| ASRock                  | 2         | 3.17%   |
| Acer                    | 2         | 3.17%   |
| System76                | 1         | 1.59%   |
| Samsung Electronics     | 1         | 1.59%   |
| Razer                   | 1         | 1.59%   |
| Raspberry Pi Foundation | 1         | 1.59%   |
| Hardkernel              | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 4.76%   |
| System76 Galago Pro                      | 1         | 1.59%   |
| Samsung 730QCJ/730QCR                    | 1         | 1.59%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 1.59%   |
| RPi Raspberry Pi 4 Model B               | 1         | 1.59%   |
| MSI MS-7D54                              | 1         | 1.59%   |
| MSI MS-7C95                              | 1         | 1.59%   |
| MSI MS-7B89                              | 1         | 1.59%   |
| MSI MS-7A71                              | 1         | 1.59%   |
| MSI Katana GF66 12UC                     | 1         | 1.59%   |
| MSI GP75 Leopard 9SD                     | 1         | 1.59%   |
| MSI GE72VR 7RF                           | 1         | 1.59%   |
| Lenovo ThinkSystem SR950 V3              | 1         | 1.59%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 1.59%   |
| Lenovo ThinkPad T490 20N3S77601          | 1         | 1.59%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 1.59%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 1.59%   |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 1.59%   |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 1.59%   |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 1.59%   |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 1.59%   |
| Intel NUC12WSHi7                         | 1         | 1.59%   |
| Intel H81                                | 1         | 1.59%   |
| HP Z800 Workstation                      | 1         | 1.59%   |
| HP ProLiant ML310e Gen8                  | 1         | 1.59%   |
| HP ProBook 640 G2                        | 1         | 1.59%   |
| HP Laptop 14s-dk0xxx                     | 1         | 1.59%   |
| HP EliteBook 855 G7 Notebook PC          | 1         | 1.59%   |
| HP EliteBook 2570p                       | 1         | 1.59%   |
| HP 340S G7                               | 1         | 1.59%   |
| Hardkernel ODROID-H3                     | 1         | 1.59%   |
| Gigabyte X670E AORUS MASTER              | 1         | 1.59%   |
| Gigabyte MU72-SU0-00                     | 1         | 1.59%   |
| Gigabyte H510M H                         | 1         | 1.59%   |
| Gigabyte B550M AORUS PRO-P               | 1         | 1.59%   |
| Gigabyte AERO 15 KD                      | 1         | 1.59%   |
| Dell XPS 17 9710                         | 1         | 1.59%   |
| Dell Precision Tower 5810                | 1         | 1.59%   |
| Dell Precision 7920 Tower                | 1         | 1.59%   |
| Dell Precision 7720                      | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 6         | 9.52%   |
| Dell Precision       | 5         | 7.94%   |
| ASUS PRIME           | 3         | 4.76%   |
| Unknown              | 3         | 4.76%   |
| Lenovo ThinkBook     | 2         | 3.17%   |
| HP EliteBook         | 2         | 3.17%   |
| Dell Latitude        | 2         | 3.17%   |
| Dell Inspiron        | 2         | 3.17%   |
| ASUS TUF             | 2         | 3.17%   |
| ASUS ROG             | 2         | 3.17%   |
| Acer Aspire          | 2         | 3.17%   |
| System76 Galago      | 1         | 1.59%   |
| Samsung 730QCJ       | 1         | 1.59%   |
| Razer Blade          | 1         | 1.59%   |
| RPi Raspberry        | 1         | 1.59%   |
| MSI MS-7D54          | 1         | 1.59%   |
| MSI MS-7C95          | 1         | 1.59%   |
| MSI MS-7B89          | 1         | 1.59%   |
| MSI MS-7A71          | 1         | 1.59%   |
| MSI Katana           | 1         | 1.59%   |
| MSI GP75             | 1         | 1.59%   |
| MSI GE72VR           | 1         | 1.59%   |
| Lenovo ThinkSystem   | 1         | 1.59%   |
| Intel NUC12WSHi7     | 1         | 1.59%   |
| Intel H81            | 1         | 1.59%   |
| HP Z800              | 1         | 1.59%   |
| HP ProLiant          | 1         | 1.59%   |
| HP ProBook           | 1         | 1.59%   |
| HP Laptop            | 1         | 1.59%   |
| HP 340S              | 1         | 1.59%   |
| Hardkernel ODROID-H3 | 1         | 1.59%   |
| Gigabyte X670E       | 1         | 1.59%   |
| Gigabyte MU72-SU0-00 | 1         | 1.59%   |
| Gigabyte H510M       | 1         | 1.59%   |
| Gigabyte B550M       | 1         | 1.59%   |
| Gigabyte AERO        | 1         | 1.59%   |
| Dell XPS             | 1         | 1.59%   |
| Dell PowerEdge       | 1         | 1.59%   |
| Dell G16             | 1         | 1.59%   |
| ASUS Z450LA          | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 12        | 19.05%  |
| 2019 | 10        | 15.87%  |
| 2022 | 8         | 12.7%   |
| 2020 | 8         | 12.7%   |
| 2017 | 5         | 7.94%   |
| 2023 | 4         | 6.35%   |
| 2018 | 3         | 4.76%   |
| 2016 | 3         | 4.76%   |
| 2015 | 3         | 4.76%   |
| 2014 | 2         | 3.17%   |
| 2012 | 2         | 3.17%   |
| 2010 | 2         | 3.17%   |
| 2013 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 32        | 50.79%  |
| Desktop        | 25        | 39.68%  |
| Server         | 3         | 4.76%   |
| System on chip | 1         | 1.59%   |
| Mini pc        | 1         | 1.59%   |
| All in one     | 1         | 1.59%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 84.38%  |
| Enabled  | 10        | 15.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 98.41%  |
| Yes  | 1         | 1.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 24        | 38.1%   |
| 32.01-64.0      | 13        | 20.63%  |
| 4.01-8.0        | 10        | 15.87%  |
| 64.01-256.0     | 6         | 9.52%   |
| 3.01-4.0        | 5         | 7.94%   |
| More than 256.0 | 2         | 3.17%   |
| 16.01-24.0      | 2         | 3.17%   |
| 24.01-32.0      | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 35.29%  |
| 4.01-8.0   | 15        | 22.06%  |
| 3.01-4.0   | 14        | 20.59%  |
| 8.01-16.0  | 8         | 11.76%  |
| 1.01-2.0   | 6         | 8.82%   |
| 32.01-64.0 | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 44.62%  |
| 2      | 17        | 26.15%  |
| 3      | 9         | 13.85%  |
| 5      | 4         | 6.15%   |
| 4      | 3         | 4.62%   |
| 14     | 1         | 1.54%   |
| 6      | 1         | 1.54%   |
| 0      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 80.95%  |
| Yes       | 12        | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 88.89%  |
| No        | 7         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 75%     |
| No        | 16        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 66.15%  |
| No        | 22        | 33.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 31.75%  |
| India        | 7         | 11.11%  |
| UK           | 4         | 6.35%   |
| Brazil       | 4         | 6.35%   |
| Guatemala    | 3         | 4.76%   |
| Canada       | 3         | 4.76%   |
| Turkey       | 2         | 3.17%   |
| New Zealand  | 2         | 3.17%   |
| Chile        | 2         | 3.17%   |
| Switzerland  | 1         | 1.59%   |
| Sri Lanka    | 1         | 1.59%   |
| Spain        | 1         | 1.59%   |
| South Africa | 1         | 1.59%   |
| Saint Lucia  | 1         | 1.59%   |
| Russia       | 1         | 1.59%   |
| Norway       | 1         | 1.59%   |
| Kenya        | 1         | 1.59%   |
| Jordan       | 1         | 1.59%   |
| Japan        | 1         | 1.59%   |
| Italy        | 1         | 1.59%   |
| Indonesia    | 1         | 1.59%   |
| Germany      | 1         | 1.59%   |
| Finland      | 1         | 1.59%   |
| Egypt        | 1         | 1.59%   |
| Czechia      | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Guatemala City | 3         | 4.55%   |
| Wellington     | 2         | 3.03%   |
| Santiago       | 2         | 3.03%   |
| Wildomar       | 1         | 1.52%   |
| Whiteley       | 1         | 1.52%   |
| Wake Forest    | 1         | 1.52%   |
| Valencia       | 1         | 1.52%   |
| Tokyo          | 1         | 1.52%   |
| Sutton         | 1         | 1.52%   |
| Stratham       | 1         | 1.52%   |
| Stavropol      | 1         | 1.52%   |
| Skien          | 1         | 1.52%   |
| Sao Paulo      | 1         | 1.52%   |
| Sainte-Marie   | 1         | 1.52%   |
| Saint Paul     | 1         | 1.52%   |
| Rio de Janeiro | 1         | 1.52%   |
| Ribeirao Preto | 1         | 1.52%   |
| Providence     | 1         | 1.52%   |
| Prairieville   | 1         | 1.52%   |
| Piracicaba     | 1         | 1.52%   |
| Pforzheim      | 1         | 1.52%   |
| Parker         | 1         | 1.52%   |
| Oldham         | 1         | 1.52%   |
| Newham         | 1         | 1.52%   |
| New Delhi      | 1         | 1.52%   |
| Nairobi        | 1         | 1.52%   |
| Montgomery     | 1         | 1.52%   |
| Mohegan Lake   | 1         | 1.52%   |
| Milano         | 1         | 1.52%   |
| Mattapoisett   | 1         | 1.52%   |
| Maltepe        | 1         | 1.52%   |
| Liberec        | 1         | 1.52%   |
| Lansing        | 1         | 1.52%   |
| Kolkata        | 1         | 1.52%   |
| Kochi          | 1         | 1.52%   |
| Johannesburg   | 1         | 1.52%   |
| Houston        | 1         | 1.52%   |
| Helsinki       | 1         | 1.52%   |
| Ghaziabad      | 1         | 1.52%   |
| Fort Collins   | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 20        | 25     | 17.54%  |
| Seagate                     | 13        | 21     | 11.4%   |
| WDC                         | 12        | 19     | 10.53%  |
| Sandisk                     | 9         | 13     | 7.89%   |
| Unknown                     | 6         | 8      | 5.26%   |
| Toshiba                     | 5         | 5      | 4.39%   |
| Micron Technology           | 4         | 4      | 3.51%   |
| Kingston                    | 4         | 4      | 3.51%   |
| Intel                       | 4         | 9      | 3.51%   |
| SK hynix                    | 3         | 3      | 2.63%   |
| Phison                      | 3         | 3      | 2.63%   |
| KIOXIA                      | 3         | 4      | 2.63%   |
| HGST                        | 3         | 3      | 2.63%   |
| China                       | 3         | 3      | 2.63%   |
| SABRENT                     | 2         | 2      | 1.75%   |
| Micron/Crucial Technology   | 2         | 3      | 1.75%   |
| Kingston Technology Company | 2         | 2      | 1.75%   |
| KingSpec                    | 2         | 2      | 1.75%   |
| Crucial                     | 2         | 3      | 1.75%   |
| ADATA Technology            | 2         | 2      | 1.75%   |
| XUM                         | 1         | 1      | 0.88%   |
| SSSTC                       | 1         | 1      | 0.88%   |
| PNY                         | 1         | 1      | 0.88%   |
| Plextor                     | 1         | 1      | 0.88%   |
| Phison Electronics          | 1         | 2      | 0.88%   |
| Hitachi                     | 1         | 1      | 0.88%   |
| Golden                      | 1         | 1      | 0.88%   |
| Gigabyte Technology         | 1         | 1      | 0.88%   |
| Fantom                      | 1         | 1      | 0.88%   |
| A-DATA Technology           | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 2.27%   |
| Unknown MMC Card  256GB                            | 2         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 1.52%   |
| Sandisk WD Blue SN570 500GB                        | 2         | 1.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 1.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 2         | 1.52%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 1.52%   |
| SABRENT Disk 240GB SSD                             | 2         | 1.52%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB              | 2         | 1.52%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 1.52%   |
| Kingston Company SNV2S250G 250GB                   | 2         | 1.52%   |
| Intel SSD 660P Series 1024GB                       | 2         | 1.52%   |
| HGST HTS721010A9E630 1TB                           | 2         | 1.52%   |
| XUM HX256GSSDSATA3 256GB                           | 1         | 0.76%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1         | 0.76%   |
| WDC WD80EFAX-68KNBN0 8TB                           | 1         | 0.76%   |
| WDC WD5000AVDS-63U7B0 500GB                        | 1         | 0.76%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1         | 0.76%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 1         | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1         | 0.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1         | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1         | 0.76%   |
| WDC WD20EARX-008FB0 2TB                            | 1         | 0.76%   |
| WDC WD141KFGX-68FH9N0 14TB                         | 1         | 0.76%   |
| WDC WD140EFGX-68B0GN0 14TB                         | 1         | 0.76%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.76%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.76%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1         | 0.76%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1         | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.76%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1         | 0.76%   |
| WDC WD100EFAX-68LHPN0 10TB                         | 1         | 0.76%   |
| Unknown SDU1  64GB                                 | 1         | 0.76%   |
| Unknown SD/MMC/MS PRO 16GB                         | 1         | 0.76%   |
| Unknown SD/MMC/M.S.PRO 32GB                        | 1         | 0.76%   |
| Unknown SD/MMC 2GB                                 | 1         | 0.76%   |
| Unknown MMC Card  512GB                            | 1         | 0.76%   |
| Unknown M.S./M.S.Pro/HG 16GB                       | 1         | 0.76%   |
| Toshiba MQ01ACF050 500GB                           | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 21     | 37.14%  |
| WDC     | 11        | 18     | 31.43%  |
| Toshiba | 5         | 5      | 14.29%  |
| HGST    | 3         | 3      | 8.57%   |
| Unknown | 1         | 1      | 2.86%   |
| Hitachi | 1         | 1      | 2.86%   |
| Fantom  | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 31.03%  |
| China               | 3         | 3      | 10.34%  |
| SanDisk             | 2         | 2      | 6.9%    |
| SABRENT             | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| KingSpec            | 2         | 2      | 6.9%    |
| Intel               | 2         | 4      | 6.9%    |
| Crucial             | 2         | 2      | 6.9%    |
| XUM                 | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| PNY                 | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| Gigabyte Technology | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 59     | 42.72%  |
| HDD     | 28        | 50     | 27.18%  |
| SSD     | 25        | 32     | 24.27%  |
| MMC     | 4         | 4      | 3.88%   |
| Unknown | 2         | 4      | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 59     | 47.31%  |
| SATA | 39        | 76     | 41.94%  |
| SAS  | 6         | 10     | 6.45%   |
| MMC  | 4         | 4      | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 32     | 40.74%  |
| 0.51-1.0   | 18        | 24     | 33.33%  |
| 1.01-2.0   | 4         | 5      | 7.41%   |
| 3.01-4.0   | 3         | 7      | 5.56%   |
| 4.01-10.0  | 3         | 7      | 5.56%   |
| 2.01-3.0   | 2         | 3      | 3.7%    |
| 10.01-20.0 | 2         | 4      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 36.92%  |
| 251-500        | 15        | 23.08%  |
| 501-1000       | 10        | 15.38%  |
| 1001-2000      | 7         | 10.77%  |
| More than 3000 | 4         | 6.15%   |
| 51-100         | 3         | 4.62%   |
| 21-50          | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 38.46%  |
| 21-50          | 16        | 24.62%  |
| 51-100         | 10        | 15.38%  |
| 251-500        | 5         | 7.69%   |
| 101-250        | 3         | 4.62%   |
| More than 3000 | 2         | 3.08%   |
| 1001-2000      | 2         | 3.08%   |
| 2001-3000      | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB   | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 20%     |
| Seagate ST1000DM010-2EP102 1TB  | 1         | 1      | 20%     |
| Intel SSDSC2BA800G4R 800GB      | 1         | 2      | 20%     |
| Crucial CT1000BX500SSD1 1TB     | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Intel   | 1         | 2      | 20%     |
| Crucial | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 50%     |
| HDD  | 2         | 3      | 50%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 41        | 93     | 60.29%  |
| Works    | 23        | 50     | 33.82%  |
| Malfunc  | 4         | 6      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 44%     |
| Samsung Electronics         | 12        | 12%     |
| AMD                         | 10        | 10%     |
| SanDisk                     | 8         | 8%      |
| Phison Electronics          | 4         | 4%      |
| Micron Technology           | 4         | 4%      |
| Kingston Technology Company | 4         | 4%      |
| Micron/Crucial Technology   | 3         | 3%      |
| KIOXIA                      | 3         | 3%      |
| ADATA Technology            | 3         | 3%      |
| SK hynix                    | 2         | 2%      |
| Broadcom / LSI              | 2         | 2%      |
| ASMedia Technology          | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 7         | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 4.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 4         | 3.57%   |
| Intel Volume Management Device NVMe RAID Controller                           | 4         | 3.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 3         | 2.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 2.68%   |
| Intel SSD 660P Series                                                         | 3         | 2.68%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 2.68%   |
| Intel Comet Lake SATA AHCI Controller                                         | 3         | 2.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 2.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 1.79%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 2         | 1.79%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 2         | 1.79%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2         | 1.79%   |
| Phison E16 PCIe4 NVMe Controller                                              | 2         | 1.79%   |
| Phison E12 NVMe Controller                                                    | 2         | 1.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 2         | 1.79%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 2         | 1.79%   |
| Kingston Company NV2 NVMe SSD E21T                                            | 2         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.79%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 2         | 1.79%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 2         | 1.79%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 1.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 2         | 1.79%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 2         | 1.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 1.79%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1         | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 1         | 0.89%   |
| Phison E7 NVMe Controller                                                     | 1         | 0.89%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 0.89%   |
| Micron 7450 PRO NVMe SSD                                                      | 1         | 0.89%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.89%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 1         | 0.89%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 43        | 42.57%  |
| SATA | 42        | 41.58%  |
| RAID | 14        | 13.86%  |
| SAS  | 1         | 0.99%   |
| IDE  | 1         | 0.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 80.95%  |
| AMD    | 11        | 17.46%  |
| ARM    | 1         | 1.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 4.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 3.17%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 3.17%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 3.17%   |
| Intel 12th Gen Core i9-12900K           | 2         | 3.17%   |
| Intel 12th Gen Core i7-12700H           | 2         | 3.17%   |
| Intel 12th Gen Core i7-1260P            | 2         | 3.17%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2         | 3.17%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 3.17%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 1.59%   |
| Intel Xeon Silver 4310 CPU @ 2.10GHz    | 1         | 1.59%   |
| Intel Xeon Platinum 8468H               | 1         | 1.59%   |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz  | 1         | 1.59%   |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1         | 1.59%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1         | 1.59%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1         | 1.59%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1         | 1.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.59%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.59%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.59%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.59%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 1.59%   |
| Intel Core i5-3470S CPU @ 2.90GHz       | 1         | 1.59%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1         | 1.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 1         | 1.59%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 1         | 1.59%   |
| Intel Celeron N5105 @ 2.00GHz           | 1         | 1.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 1         | 1.59%   |
| Intel 13th Gen Core i5-13600K           | 1         | 1.59%   |
| Intel 12th Gen Core i5-1235U            | 1         | 1.59%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 15        | 23.81%  |
| Intel Core i5        | 12        | 19.05%  |
| Intel Core i7        | 11        | 17.46%  |
| Intel Xeon           | 4         | 6.35%   |
| Intel Core i3        | 4         | 6.35%   |
| AMD Ryzen 9          | 4         | 6.35%   |
| AMD Ryzen 5          | 4         | 6.35%   |
| Intel Xeon Platinum  | 2         | 3.17%   |
| Intel Celeron        | 2         | 3.17%   |
| Intel Xeon Silver    | 1         | 1.59%   |
| Intel Pentium Silver | 1         | 1.59%   |
| AMD Ryzen 7 PRO      | 1         | 1.59%   |
| AMD Athlon X4        | 1         | 1.59%   |
| AMD A4               | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 21        | 33.33%  |
| 2      | 11        | 17.46%  |
| 8      | 9         | 14.29%  |
| 6      | 7         | 11.11%  |
| 12     | 6         | 9.52%   |
| 14     | 3         | 4.76%   |
| 16     | 2         | 3.17%   |
| 384    | 1         | 1.59%   |
| 48     | 1         | 1.59%   |
| 10     | 1         | 1.59%   |
| 1      | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 95.24%  |
| 2      | 2         | 3.17%   |
| 8      | 1         | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 82.54%  |
| 1      | 11        | 17.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 6         | 9.52%   |
| 0x306a9    | 5         | 7.94%   |
| 0x906a3    | 4         | 6.35%   |
| 0x806d1    | 4         | 6.35%   |
| 0xa0671    | 3         | 4.76%   |
| 0x506e3    | 3         | 4.76%   |
| 0x08701021 | 3         | 4.76%   |
| 0x906ea    | 2         | 3.17%   |
| 0x906e9    | 2         | 3.17%   |
| 0x906c0    | 2         | 3.17%   |
| 0x90672    | 2         | 3.17%   |
| 0x706e5    | 2         | 3.17%   |
| 0x406e3    | 2         | 3.17%   |
| 0x0a20120a | 2         | 3.17%   |
| 0xb0671    | 1         | 1.59%   |
| 0x906ed    | 1         | 1.59%   |
| 0x906a4    | 1         | 1.59%   |
| 0x806f6    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x706a8    | 1         | 1.59%   |
| 0x606a6    | 1         | 1.59%   |
| 0x50654    | 1         | 1.59%   |
| 0x406f1    | 1         | 1.59%   |
| 0x40651    | 1         | 1.59%   |
| 0x306d4    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x106a5    | 1         | 1.59%   |
| 0x0a601203 | 1         | 1.59%   |
| 0x0a50000c | 1         | 1.59%   |
| 0x08600106 | 1         | 1.59%   |
| 0x08108109 | 1         | 1.59%   |
| 0x06006705 | 1         | 1.59%   |
| 0x0600611a | 1         | 1.59%   |
| Unknown    | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 19.05%  |
| Icelake          | 10        | 15.87%  |
| Alderlake Hybrid | 8         | 12.7%   |
| Skylake          | 6         | 9.52%   |
| IvyBridge        | 5         | 7.94%   |
| Zen 2            | 4         | 6.35%   |
| Zen 3            | 3         | 4.76%   |
| Tremont          | 2         | 3.17%   |
| Haswell          | 2         | 3.17%   |
| Excavator        | 2         | 3.17%   |
| Broadwell        | 2         | 3.17%   |
| Unknown          | 2         | 3.17%   |
| Zen+             | 1         | 1.59%   |
| Westmere         | 1         | 1.59%   |
| Sapphire Rapids  | 1         | 1.59%   |
| Nehalem          | 1         | 1.59%   |
| Goldmont plus    | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 37        | 49.33%  |
| Nvidia                     | 22        | 29.33%  |
| AMD                        | 13        | 17.33%  |
| ASPEED Technology          | 2         | 2.67%   |
| Matrox Electronics Systems | 1         | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                             | 4         | 5.19%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                        | 4         | 5.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                  | 3         | 3.9%    |
| Nvidia TU117GL [T400 4GB]                                        | 2         | 2.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                       | 2         | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                       | 2         | 2.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                             | 2         | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                              | 2         | 2.6%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                        | 2         | 2.6%    |
| Intel JasperLake [UHD Graphics]                                  | 2         | 2.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                           | 2         | 2.6%    |
| Intel HD Graphics 630                                            | 2         | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                        | 2         | 2.6%    |
| Intel 3rd Gen Core processor Graphics Controller                 | 2         | 2.6%    |
| ASPEED Technology ASPEED Graphics Family                         | 2         | 2.6%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                   | 2         | 2.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 2         | 2.6%    |
| Nvidia TU117GLM [T1200 Laptop GPU]                               | 1         | 1.3%    |
| Nvidia GT218 [GeForce G210]                                      | 1         | 1.3%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                          | 1         | 1.3%    |
| Nvidia GP104GLM [Quadro P3000 Mobile]                            | 1         | 1.3%    |
| Nvidia GP104GL [Quadro P4000]                                    | 1         | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                  | 1         | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                               | 1         | 1.3%    |
| Nvidia GM206GL [Quadro M2000]                                    | 1         | 1.3%    |
| Nvidia GK208B [GeForce GT 730]                                   | 1         | 1.3%    |
| Nvidia GK106 [GeForce GTX 660]                                   | 1         | 1.3%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                          | 1         | 1.3%    |
| Nvidia GA106 [Geforce RTX 3050]                                  | 1         | 1.3%    |
| Nvidia GA104GLM [RTX A5000 Mobile]                               | 1         | 1.3%    |
| Nvidia GA102 [GeForce RTX 3090]                                  | 1         | 1.3%    |
| Nvidia GA102 [GeForce RTX 3090 Ti]                               | 1         | 1.3%    |
| Nvidia G92 [GeForce 9800 GT]                                     | 1         | 1.3%    |
| Matrox Electronics Systems MGA G200EH                            | 1         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1         | 1.3%    |
| Intel UHD Graphics 620                                           | 1         | 1.3%    |
| Intel HD Graphics P530                                           | 1         | 1.3%    |
| Intel HD Graphics 5500                                           | 1         | 1.3%    |
| Intel HD Graphics 530                                            | 1         | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                 | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 39.68%  |
| 1 x Nvidia     | 13        | 20.63%  |
| Intel + Nvidia | 8         | 12.7%   |
| 1 x AMD        | 8         | 12.7%   |
| Intel + AMD    | 3         | 4.76%   |
| Other          | 1         | 1.59%   |
| 2 x Nvidia     | 1         | 1.59%   |
| 2 x AMD        | 1         | 1.59%   |
| 1 x Matrox     | 1         | 1.59%   |
| 1 x ASPEED     | 1         | 1.59%   |
| AMD + ASPEED   | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 80.95%  |
| Proprietary | 9         | 14.29%  |
| Unknown     | 3         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 47.62%  |
| 7.01-8.0   | 7         | 11.11%  |
| 3.01-4.0   | 6         | 9.52%   |
| 1.01-2.0   | 6         | 9.52%   |
| 5.01-6.0   | 5         | 7.94%   |
| 0.01-0.5   | 3         | 4.76%   |
| 16.01-24.0 | 2         | 3.17%   |
| 8.01-16.0  | 2         | 3.17%   |
| 2.01-3.0   | 1         | 1.59%   |
| 0.51-1.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 10        | 14.49%  |
| BOE                  | 10        | 14.49%  |
| Dell                 | 7         | 10.14%  |
| Chimei Innolux       | 5         | 7.25%   |
| LG Display           | 4         | 5.8%    |
| AU Optronics         | 4         | 5.8%    |
| Goldstar             | 3         | 4.35%   |
| Acer                 | 3         | 4.35%   |
| Sharp                | 2         | 2.9%    |
| Lenovo               | 2         | 2.9%    |
| AOC                  | 2         | 2.9%    |
| Vizio                | 1         | 1.45%   |
| Unknown              | 1         | 1.45%   |
| STD                  | 1         | 1.45%   |
| Sony                 | 1         | 1.45%   |
| Philips              | 1         | 1.45%   |
| Panasonic            | 1         | 1.45%   |
| OUT                  | 1         | 1.45%   |
| InfoVision           | 1         | 1.45%   |
| Hewlett-Packard      | 1         | 1.45%   |
| Haier                | 1         | 1.45%   |
| Gigabyte Technology  | 1         | 1.45%   |
| Deco Gear            | 1         | 1.45%   |
| CSO                  | 1         | 1.45%   |
| BOE Technology Group | 1         | 1.45%   |
| BenQ                 | 1         | 1.45%   |
| ASUSTek Computer     | 1         | 1.45%   |
| Unknown              | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2         | 2.78%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                   | 1         | 1.39%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 1.39%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1         | 1.39%   |
| Sony TV SNYD703 1360x768                                               | 1         | 1.39%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                | 1         | 1.39%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1         | 1.39%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1         | 1.39%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1         | 1.39%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                      | 1         | 1.39%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                | 1         | 1.39%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1         | 1.39%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1         | 1.39%   |
| LG Display LCD Monitor LGD0625 1920x1080 340x190mm 15.3-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch            | 1         | 1.39%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch               | 1         | 1.39%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch             | 1         | 1.39%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch             | 1         | 1.39%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 1         | 1.39%   |
| Hewlett-Packard LCD Monitor Pavilion32                                 | 1         | 1.39%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1         | 1.39%   |
| Goldstar UltraFine GSM5B11 2560x2880 600x340mm 27.2-inch               | 1         | 1.39%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 1         | 1.39%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1         | 1.39%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 1         | 1.39%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1         | 1.39%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                  | 1         | 1.39%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1         | 1.39%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                     | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 46.97%  |
| 3840x2160 (4K)     | 8         | 12.12%  |
| 1366x768 (WXGA)    | 7         | 10.61%  |
| 2560x1440 (QHD)    | 5         | 7.58%   |
| Unknown            | 3         | 4.55%   |
| 1680x1050 (WSXGA+) | 2         | 3.03%   |
| 1280x1024 (SXGA)   | 2         | 3.03%   |
| 7280x2160          | 1         | 1.52%   |
| 5120x1440          | 1         | 1.52%   |
| 3440x1440          | 1         | 1.52%   |
| 2560x1600          | 1         | 1.52%   |
| 2160x1350          | 1         | 1.52%   |
| 1920x1200 (WUXGA)  | 1         | 1.52%   |
| 1600x900 (HD+)     | 1         | 1.52%   |
| 1280x768           | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 12        | 17.65%  |
| 23      | 7         | 10.29%  |
| 15      | 7         | 10.29%  |
| 21      | 5         | 7.35%   |
| 14      | 5         | 7.35%   |
| 27      | 4         | 5.88%   |
| 17      | 4         | 5.88%   |
| Unknown | 4         | 5.88%   |
| 31      | 3         | 4.41%   |
| 24      | 3         | 4.41%   |
| 84      | 2         | 2.94%   |
| 72      | 2         | 2.94%   |
| 16      | 2         | 2.94%   |
| 64      | 1         | 1.47%   |
| 54      | 1         | 1.47%   |
| 52      | 1         | 1.47%   |
| 43      | 1         | 1.47%   |
| 35      | 1         | 1.47%   |
| 33      | 1         | 1.47%   |
| 20      | 1         | 1.47%   |
| 19      | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 34.33%  |
| 501-600     | 13        | 19.4%   |
| 401-500     | 6         | 8.96%   |
| 351-400     | 4         | 5.97%   |
| 201-300     | 4         | 5.97%   |
| 1501-2000   | 4         | 5.97%   |
| Unknown     | 4         | 5.97%   |
| 601-700     | 3         | 4.48%   |
| 1001-1500   | 3         | 4.48%   |
| 801-900     | 1         | 1.49%   |
| 701-800     | 1         | 1.49%   |
| 901-1000    | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 45        | 77.59%  |
| 16/10   | 5         | 8.62%   |
| Unknown | 4         | 6.9%    |
| 5/4     | 2         | 3.45%   |
| 4/3     | 1         | 1.72%   |
| 21/9    | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 19.4%   |
| 201-250        | 12        | 17.91%  |
| More than 1000 | 7         | 10.45%  |
| 101-110        | 7         | 10.45%  |
| 351-500        | 5         | 7.46%   |
| 71-80          | 4         | 5.97%   |
| 301-350        | 4         | 5.97%   |
| Unknown        | 4         | 5.97%   |
| 151-200        | 3         | 4.48%   |
| 121-130        | 3         | 4.48%   |
| 251-300        | 1         | 1.49%   |
| 141-150        | 1         | 1.49%   |
| 131-140        | 1         | 1.49%   |
| 111-120        | 1         | 1.49%   |
| 501-1000       | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 19        | 30.16%  |
| 121-160       | 15        | 23.81%  |
| 101-120       | 14        | 22.22%  |
| 161-240       | 6         | 9.52%   |
| Unknown       | 4         | 6.35%   |
| 1-50          | 3         | 4.76%   |
| More than 240 | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 70.31%  |
| 2     | 11        | 17.19%  |
| 0     | 5         | 7.81%   |
| 5     | 1         | 1.56%   |
| 4     | 1         | 1.56%   |
| 3     | 1         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 51.09%  |
| Realtek Semiconductor | 32        | 34.78%  |
| Broadcom              | 4         | 4.35%   |
| Qualcomm Atheros      | 3         | 3.26%   |
| Tehuti Networks       | 1         | 1.09%   |
| Ralink Technology     | 1         | 1.09%   |
| IBM                   | 1         | 1.09%   |
| DisplayLink           | 1         | 1.09%   |
| ASUSTek Computer      | 1         | 1.09%   |
| Aquantia              | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 13.33%  |
| Intel Ethernet Controller I225-V                                  | 7         | 5.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 4.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 4.17%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.5%    |
| Intel Wireless 8260                                               | 2         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.67%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.67%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.67%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2         | 1.67%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.67%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.83%   |
| Intel Wireless 7265                                               | 1         | 0.83%   |
| Intel Wireless 3160                                               | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.83%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.83%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.83%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 78%     |
| Realtek Semiconductor | 6         | 12%     |
| Broadcom              | 2         | 4%      |
| Ralink Technology     | 1         | 2%      |
| Qualcomm Atheros      | 1         | 2%      |
| ASUSTek Computer      | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 6         | 12%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 5         | 10%     |
| Intel Wi-Fi 6 AX200                                        | 4         | 8%      |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 4         | 8%      |
| Intel Alder Lake-P PCH CNVi WiFi                           | 4         | 8%      |
| Intel Wireless 8260                                        | 2         | 4%      |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 4%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 4%      |
| Intel Alder Lake-S PCH CNVi WiFi                           | 2         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2%      |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1         | 2%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 2%      |
| Realtek 802.11n WLAN Adapter                               | 1         | 2%      |
| Ralink MT7601U Wireless Adapter                            | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2%      |
| Intel Wireless 8265 / 8275                                 | 1         | 2%      |
| Intel Wireless 7265                                        | 1         | 2%      |
| Intel Wireless 3160                                        | 1         | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                 | 1         | 2%      |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 2%      |
| Intel Centrino Wireless-N 2230                             | 1         | 2%      |
| Broadcom BCM4321 802.11b/g/n                               | 1         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2%      |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]        | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 31        | 47.69%  |
| Intel                 | 25        | 38.46%  |
| Broadcom              | 3         | 4.62%   |
| Qualcomm Atheros      | 2         | 3.08%   |
| Tehuti Networks       | 1         | 1.54%   |
| IBM                   | 1         | 1.54%   |
| DisplayLink           | 1         | 1.54%   |
| Aquantia              | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 22.86%  |
| Intel Ethernet Controller I225-V                                  | 7         | 10%     |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 8.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 8.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.29%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.86%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.86%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.86%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter        | 1         | 1.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.43%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 1.43%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.43%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 1.43%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.43%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.43%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.43%   |
| IBM RNDIS/Ethernet Gadget                                         | 1         | 1.43%   |
| DisplayLink Dell D3100 Docking Station                            | 1         | 1.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.43%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                  | 1         | 1.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56        | 53.85%  |
| WiFi     | 48        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 50.77%  |
| WiFi     | 32        | 49.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 54.69%  |
| 1     | 18        | 28.13%  |
| 4     | 5         | 7.81%   |
| 3     | 5         | 7.81%   |
| 0     | 1         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 73.44%  |
| Yes  | 17        | 26.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 36        | 80%     |
| Realtek Semiconductor      | 2         | 4.44%   |
| Cambridge Silicon Radio    | 2         | 4.44%   |
| Broadcom                   | 2         | 4.44%   |
| Integrated System Solution | 1         | 2.22%   |
| IMC Networks               | 1         | 2.22%   |
| ASUSTek Computer           | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 9         | 20%     |
| Intel AX210 Bluetooth                                 | 6         | 13.33%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5         | 11.11%  |
| Intel Bluetooth wireless interface                    | 4         | 8.89%   |
| Intel AX200 Bluetooth                                 | 4         | 8.89%   |
| Intel Bluetooth Device                                | 2         | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 4.44%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 2.22%   |
| Realtek Bluetooth Radio                               | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 2.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                          | 1         | 2.22%   |
| Broadcom HP Portable SoftSailing                      | 1         | 2.22%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 2.22%   |
| ASUS ASUS USB-BT500                                   | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 48        | 48%     |
| Nvidia                                       | 20        | 20%     |
| AMD                                          | 14        | 14%     |
| Texas Instruments                            | 5         | 5%      |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1%      |
| Sony                                         | 1         | 1%      |
| Realtek Semiconductor                        | 1         | 1%      |
| Micro Star International                     | 1         | 1%      |
| Logitech                                     | 1         | 1%      |
| LG Electronics                               | 1         | 1%      |
| Hewlett-Packard                              | 1         | 1%      |
| Creative Labs                                | 1         | 1%      |
| Corsair                                      | 1         | 1%      |
| Blue Microphones                             | 1         | 1%      |
| BEHRINGER International                      | 1         | 1%      |
| ASUSTek Computer                             | 1         | 1%      |
| Astro Gaming                                 | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 6.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 4.42%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4         | 3.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 3.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 3.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 3.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 3.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 2.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 1.77%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.77%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.77%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.77%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 0.88%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.88%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.88%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.88%   |
| Micro Star International USB Audio                                         | 1         | 0.88%   |
| Logitech Headset H340                                                      | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 25.93%  |
| Samsung Electronics | 4         | 14.81%  |
| Kingston            | 3         | 11.11%  |
| G.Skill             | 3         | 11.11%  |
| Unknown             | 2         | 7.41%   |
| Corsair             | 2         | 7.41%   |
| Team                | 1         | 3.7%    |
| Smart               | 1         | 3.7%    |
| Micron Technology   | 1         | 3.7%    |
| Hewlett-Packard     | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2         | 6.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 3.33%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                    | 1         | 3.33%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s          | 1         | 3.33%   |
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.33%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s        | 1         | 3.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.33%   |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s         | 1         | 3.33%   |
| SK hynix RAM HMCG94MEBRA121N 64GB DIMM DDR5 4800MT/s         | 1         | 3.33%   |
| SK hynix RAM HMCG94MEBRA109N 64GB DIMM DDR5 4800MT/s         | 1         | 3.33%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s        | 1         | 3.33%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.33%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 3.33%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 3.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 3.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.33%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s          | 1         | 3.33%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.33%   |
| Micron RAM Module 8GB Chip LPDDR4                            | 1         | 3.33%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 3.33%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 1         | 3.33%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 3.33%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                     | 1         | 3.33%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s         | 1         | 3.33%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 1         | 3.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 1         | 3.33%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 3.33%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s         | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 58.33%  |
| DDR3   | 5         | 20.83%  |
| LPDDR4 | 2         | 8.33%   |
| DDR5   | 2         | 8.33%   |
| LPDDR5 | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 12        | 50%     |
| SODIMM       | 9         | 37.5%   |
| Row Of Chips | 2         | 8.33%   |
| Chip         | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 42.31%  |
| 16384 | 8         | 30.77%  |
| 4096  | 3         | 11.54%  |
| 65536 | 2         | 7.69%   |
| 2048  | 2         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3600    | 5         | 20%     |
| 2667    | 3         | 12%     |
| 1600    | 3         | 12%     |
| 6400    | 2         | 8%      |
| 3200    | 2         | 8%      |
| 2400    | 2         | 8%      |
| 2133    | 2         | 8%      |
| 4800    | 1         | 4%      |
| 2933    | 1         | 4%      |
| 2666    | 1         | 4%      |
| 1867    | 1         | 4%      |
| 1333    | 1         | 4%      |
| Unknown | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 75%     |
| Canon       | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-4100 Series | 1         | 25%     |
| Seiko Epson WF-3520 Series | 1         | 25%     |
| Seiko Epson L3210 Series   | 1         | 25%     |
| Canon PIXMA MG2500 Series  | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 16.67%  |
| Microdia                               | 4         | 9.52%   |
| IMC Networks                           | 4         | 9.52%   |
| Realtek Semiconductor                  | 3         | 7.14%   |
| Sunplus Innovation Technology          | 2         | 4.76%   |
| Logitech                               | 2         | 4.76%   |
| Bison Electronics                      | 2         | 4.76%   |
| Apple                                  | 2         | 4.76%   |
| vivo                                   | 1         | 2.38%   |
| Syntek                                 | 1         | 2.38%   |
| Suyin                                  | 1         | 2.38%   |
| Sonix Technology                       | 1         | 2.38%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 2.38%   |
| Samsung Electronics                    | 1         | 2.38%   |
| Remo Tech                              | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Owon                                   | 1         | 2.38%   |
| Microsoft                              | 1         | 2.38%   |
| Luxvisions Innotech Limited            | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| LG Electronics                         | 1         | 2.38%   |
| Generalplus Technology                 | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |
| 8SSC21D67422V1SR28902JL                | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 4.76%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.76%   |
| Chicony Integrated Camera                                      | 2         | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 4.76%   |
| vivo V2023                                                     | 1         | 2.38%   |
| Syntek Integrated Camera                                       | 1         | 2.38%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 2.38%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 2.38%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 2.38%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.38%   |
| Remo Tech OBSBOT Tiny 4K                                       | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.38%   |
| Realtek Integrated Webcam_HD                                   | 1         | 2.38%   |
| Realtek Full HD webcam                                         | 1         | 2.38%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 2.38%   |
| Owon USB CAMERA                                                | 1         | 2.38%   |
| Microsoft LifeCam VX-2000                                      | 1         | 2.38%   |
| Microdia USB 2.0 Camera                                        | 1         | 2.38%   |
| Microdia 1.3 MPixel Integrated Webcam                          | 1         | 2.38%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 2.38%   |
| Logitech Webcam C250                                           | 1         | 2.38%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 2.38%   |
| Lite-On HP HD Camera                                           | 1         | 2.38%   |
| LG LG UltraFine Display Camera                                 | 1         | 2.38%   |
| IMC Networks XHC Camera                                        | 1         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 2.38%   |
| IMC Networks USB Camera                                        | 1         | 2.38%   |
| IMC Networks Integrated Camera                                 | 1         | 2.38%   |
| Generalplus WEB CAM                                            | 1         | 2.38%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 2.38%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 2.38%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.38%   |
| Chicony HP HD Camera                                           | 1         | 2.38%   |
| Chicony HD Webcam                                              | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.38%   |
| Bison Integrated Camera                                        | 1         | 2.38%   |
| Bison BisonCam, NB Pro                                         | 1         | 2.38%   |
| 8SSC21D67422V1SR28902JL Integrated RGB Camera                  | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Samsung Electronics        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS491                                   | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 64.06%  |
| 1     | 18        | 28.13%  |
| 2     | 3         | 4.69%   |
| 4     | 1         | 1.56%   |
| 3     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 30%     |
| Net/wireless             | 4         | 13.33%  |
| Graphics card            | 4         | 13.33%  |
| Unassigned class         | 3         | 10%     |
| Multimedia controller    | 3         | 10%     |
| Communication controller | 2         | 6.67%   |
| Storage/ide              | 1         | 3.33%   |
| Net/ethernet             | 1         | 3.33%   |
| Chipcard                 | 1         | 3.33%   |
| Card reader              | 1         | 3.33%   |
| Camera                   | 1         | 3.33%   |

