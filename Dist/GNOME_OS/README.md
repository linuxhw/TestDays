GNOME OS - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GNOME OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GNOME_OS/Desktop/README.md) and [notebooks](/Dist/GNOME_OS/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| GPU Compan... | GWNR71517                   | Notebook    | [89dbdfd53e](https://linux-hardware.org/?probe=89dbdfd53e) | Apr 13, 2024 |
| Lenovo        | ThinkPad X280 20KF001RMX    | Notebook    | [0caddb11a4](https://linux-hardware.org/?probe=0caddb11a4) | Apr 02, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [261726d643](https://linux-hardware.org/?probe=261726d643) | Mar 25, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c21a61a96d](https://linux-hardware.org/?probe=c21a61a96d) | Mar 23, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6P20... | Notebook    | [4f3a1c8208](https://linux-hardware.org/?probe=4f3a1c8208) | Sep 24, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2bd22135e0](https://linux-hardware.org/?probe=2bd22135e0) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [074de9621d](https://linux-hardware.org/?probe=074de9621d) | Mar 21, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0a83a62b1c](https://linux-hardware.org/?probe=0a83a62b1c) | Mar 13, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 82F2 A01                    | Desktop     | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| Unknown       | 1.0                         | Desktop     | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1b5ab725ab](https://linux-hardware.org/?probe=1b5ab725ab) | Nov 09, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [abbb3295c8](https://linux-hardware.org/?probe=abbb3295c8) | Oct 14, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [f19e981e03](https://linux-hardware.org/?probe=f19e981e03) | Oct 14, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c2f80d89da](https://linux-hardware.org/?probe=c2f80d89da) | Sep 26, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [8d0067a198](https://linux-hardware.org/?probe=8d0067a198) | Sep 26, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [56a10ce74c](https://linux-hardware.org/?probe=56a10ce74c) | Sep 21, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1bbdbe7117](https://linux-hardware.org/?probe=1bbdbe7117) | Apr 04, 2022 |
| Acer          | Iconia W700                 | Notebook    | [604cdabab4](https://linux-hardware.org/?probe=604cdabab4) | Mar 23, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | Notebook    | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| Gateway       | NE71B                       | Notebook    | [ac3dc96ccf](https://linux-hardware.org/?probe=ac3dc96ccf) | Feb 02, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [c604eec754](https://linux-hardware.org/?probe=c604eec754) | Jan 27, 2022 |
| Chuwi         | HeroBook                    | Notebook    | [67990dbe7f](https://linux-hardware.org/?probe=67990dbe7f) | Jan 19, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [2560d8b5a0](https://linux-hardware.org/?probe=2560d8b5a0) | Sep 27, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5a54384297](https://linux-hardware.org/?probe=5a54384297) | Aug 11, 2021 |
| HP            | 8767 A                      | Desktop     | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel         | X79                         | Desktop     | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [35876a09ad](https://linux-hardware.org/?probe=35876a09ad) | May 09, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Lenovo        | 317E NOK                    | Desktop     | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| HP            | Pavilion 17                 | Notebook    | [220bf859f8](https://linux-hardware.org/?probe=220bf859f8) | Mar 28, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a5a6941b23](https://linux-hardware.org/?probe=a5a6941b23) | Mar 28, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ce86510d2b](https://linux-hardware.org/?probe=ce86510d2b) | Mar 28, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [1c5ed732c5](https://linux-hardware.org/?probe=1c5ed732c5) | Mar 01, 2021 |
| Dell          | Precision M6800             | Notebook    | [95fa029c09](https://linux-hardware.org/?probe=95fa029c09) | Jan 14, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [a3fd17119a](https://linux-hardware.org/?probe=a3fd17119a) | Nov 03, 2020 |
| Chuwi         | LarkBox                     | Mini pc     | [c7f6fd9a66](https://linux-hardware.org/?probe=c7f6fd9a66) | Oct 21, 2020 |
| HP            | Pavilion 17                 | Notebook    | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| Acer          | Aspire GX-781               | Desktop     | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |
| ASUSTek       | E202SA                      | Notebook    | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME OS Nightly | 42        | 72.41%  |
| GNOME OS 3.38    | 7         | 12.07%  |
| GNOME OS 43      | 3         | 5.17%   |
| GNOME OS 46      | 2         | 3.45%   |
| GNOME OS 41      | 2         | 3.45%   |
| GNOME OS 42      | 1         | 1.72%   |
| GNOME OS 40      | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME OS | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 13.33%  |
| 5.11.10 | 8         | 13.33%  |
| 5.14.18 | 7         | 11.67%  |
| 5.19.17 | 6         | 10%     |
| 5.13.9  | 5         | 8.33%   |
| 5.19.16 | 3         | 5%      |
| 5.18.19 | 3         | 5%      |
| 5.11.2  | 3         | 5%      |
| 6.7.9   | 2         | 3.33%   |
| 5.18.16 | 2         | 3.33%   |
| 5.14.4  | 2         | 3.33%   |
| 5.13.8  | 2         | 3.33%   |
| 6.7.8   | 1         | 1.67%   |
| 6.6.10  | 1         | 1.67%   |
| 6.5.5   | 1         | 1.67%   |
| 6.5.0   | 1         | 1.67%   |
| 6.4.0   | 1         | 1.67%   |
| 5.18.10 | 1         | 1.67%   |
| 5.14.11 | 1         | 1.67%   |
| 5.12.12 | 1         | 1.67%   |
| 5.11.0  | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 13.33%  |
| 5.11.10 | 8         | 13.33%  |
| 5.14.18 | 7         | 11.67%  |
| 5.19.17 | 6         | 10%     |
| 5.13.9  | 5         | 8.33%   |
| 5.19.16 | 3         | 5%      |
| 5.18.19 | 3         | 5%      |
| 5.11.2  | 3         | 5%      |
| 6.7.9   | 2         | 3.33%   |
| 5.18.16 | 2         | 3.33%   |
| 5.14.4  | 2         | 3.33%   |
| 5.13.8  | 2         | 3.33%   |
| 6.7.8   | 1         | 1.67%   |
| 6.6.10  | 1         | 1.67%   |
| 6.5.5   | 1         | 1.67%   |
| 6.5.0   | 1         | 1.67%   |
| 6.4.0   | 1         | 1.67%   |
| 5.18.10 | 1         | 1.67%   |
| 5.14.11 | 1         | 1.67%   |
| 5.12.12 | 1         | 1.67%   |
| 5.11.0  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 20.34%  |
| 5.19    | 9         | 15.25%  |
| 5.14    | 9         | 15.25%  |
| 5.7     | 8         | 13.56%  |
| 5.13    | 7         | 11.86%  |
| 5.18    | 6         | 10.17%  |
| 6.7     | 3         | 5.08%   |
| 6.5     | 2         | 3.39%   |
| 6.6     | 1         | 1.69%   |
| 6.4     | 1         | 1.69%   |
| 5.12    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 58        | 98.31%  |
| Unknown | 1         | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 58        | 98.31%  |
| Unknown | 1         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 26        | 44.83%  |
| pt_BR | 5         | 8.62%   |
| ru_RU | 4         | 6.9%    |
| it_IT | 3         | 5.17%   |
| fr_FR | 3         | 5.17%   |
| es_ES | 3         | 5.17%   |
| de_DE | 3         | 5.17%   |
| hu_HU | 2         | 3.45%   |
| cs_CZ | 2         | 3.45%   |
| sv_SE | 1         | 1.72%   |
| sk_SK | 1         | 1.72%   |
| ru_UA | 1         | 1.72%   |
| nl_NL | 1         | 1.72%   |
| es_CL | 1         | 1.72%   |
| en_IN | 1         | 1.72%   |
| en_GB | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 57        | 98.28%  |
| BIOS | 1         | 1.72%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 58        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 98.31%  |
| GPT     | 1         | 1.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 15.52%  |
| ASUSTek Computer    | 9         | 15.52%  |
| Lenovo              | 8         | 13.79%  |
| Apple               | 8         | 13.79%  |
| Dell                | 5         | 8.62%   |
| Gigabyte Technology | 4         | 6.9%    |
| Acer                | 4         | 6.9%    |
| Intel               | 2         | 3.45%   |
| Chuwi               | 2         | 3.45%   |
| Toshiba             | 1         | 1.72%   |
| MSI                 | 1         | 1.72%   |
| Microsoft           | 1         | 1.72%   |
| GPU Company         | 1         | 1.72%   |
| Gateway             | 1         | 1.72%   |
| Colorful Technology | 1         | 1.72%   |
| Unknown             | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 3.45%   |
| Apple iMac8,1                          | 2         | 3.45%   |
| Toshiba Satellite C55-A-1F5            | 1         | 1.72%   |
| MSI MS-7918                            | 1         | 1.72%   |
| Microsoft Surface Pro                  | 1         | 1.72%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 1.72%   |
| Lenovo ThinkPad X280 20KF001RMX        | 1         | 1.72%   |
| Lenovo ThinkPad T480s 20L8S6P200       | 1         | 1.72%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 1.72%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1      | 1         | 1.72%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 1.72%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 1.72%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 1.72%   |
| Intel X79                              | 1         | 1.72%   |
| Intel H61                              | 1         | 1.72%   |
| HP ProBook 430 G3                      | 1         | 1.72%   |
| HP Pavilion Notebook                   | 1         | 1.72%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 1.72%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 1.72%   |
| HP Pavilion Desktop PC 570-p0xx        | 1         | 1.72%   |
| HP Pavilion 15                         | 1         | 1.72%   |
| HP Laptop 14-dk1xxx                    | 1         | 1.72%   |
| GPU Company GWNR71517                  | 1         | 1.72%   |
| Gigabyte Z97X-Gaming 7                 | 1         | 1.72%   |
| Gigabyte X570 GAMING X                 | 1         | 1.72%   |
| Gigabyte B450M S2H V2                  | 1         | 1.72%   |
| Gigabyte B450M DS3H                    | 1         | 1.72%   |
| Gateway NE71B                          | 1         | 1.72%   |
| Dell Precision M6800                   | 1         | 1.72%   |
| Dell Latitude 7490                     | 1         | 1.72%   |
| Dell Inspiron 5566                     | 1         | 1.72%   |
| Dell Inspiron 3584                     | 1         | 1.72%   |
| Dell Inspiron 3542                     | 1         | 1.72%   |
| Colorful BATTLE-AX B660M-HD DELUXE     | 1         | 1.72%   |
| Chuwi LarkBox                          | 1         | 1.72%   |
| Chuwi HeroBook                         | 1         | 1.72%   |
| ASUS X555LD                            | 1         | 1.72%   |
| ASUS X550LC                            | 1         | 1.72%   |
| ASUS SABERTOOTH X79                    | 1         | 1.72%   |
| ASUS PRIME H410M-K                     | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 7         | 12.07%  |
| Lenovo ThinkPad       | 3         | 5.17%   |
| Dell Inspiron         | 3         | 5.17%   |
| Lenovo IdeaPad        | 2         | 3.45%   |
| Gigabyte B450M        | 2         | 3.45%   |
| ASUS PRIME            | 2         | 3.45%   |
| Apple iMac8           | 2         | 3.45%   |
| Acer Aspire           | 2         | 3.45%   |
| Toshiba Satellite     | 1         | 1.72%   |
| MSI MS-7918           | 1         | 1.72%   |
| Microsoft Surface     | 1         | 1.72%   |
| Lenovo Yoga           | 1         | 1.72%   |
| Lenovo IdeaPadFlex    | 1         | 1.72%   |
| Lenovo IdeaCentre     | 1         | 1.72%   |
| Intel X79             | 1         | 1.72%   |
| Intel H61             | 1         | 1.72%   |
| HP ProBook            | 1         | 1.72%   |
| HP Laptop             | 1         | 1.72%   |
| GPU Company GWNR71517 | 1         | 1.72%   |
| Gigabyte Z97X-Gaming  | 1         | 1.72%   |
| Gigabyte X570         | 1         | 1.72%   |
| Gateway NE71B         | 1         | 1.72%   |
| Dell Precision        | 1         | 1.72%   |
| Dell Latitude         | 1         | 1.72%   |
| Colorful BATTLE-AX    | 1         | 1.72%   |
| Chuwi LarkBox         | 1         | 1.72%   |
| Chuwi HeroBook        | 1         | 1.72%   |
| ASUS X555LD           | 1         | 1.72%   |
| ASUS X550LC           | 1         | 1.72%   |
| ASUS SABERTOOTH       | 1         | 1.72%   |
| ASUS M5A97            | 1         | 1.72%   |
| ASUS H61M-A           | 1         | 1.72%   |
| ASUS GL553VE          | 1         | 1.72%   |
| ASUS E202SA           | 1         | 1.72%   |
| Apple Macmini5        | 1         | 1.72%   |
| Apple MacBookPro8     | 1         | 1.72%   |
| Apple MacBookPro10    | 1         | 1.72%   |
| Apple MacBook4        | 1         | 1.72%   |
| Apple iMac7           | 1         | 1.72%   |
| Apple iMac16          | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 13.79%  |
| 2020 | 7         | 12.07%  |
| 2019 | 7         | 12.07%  |
| 2017 | 7         | 12.07%  |
| 2014 | 6         | 10.34%  |
| 2012 | 6         | 10.34%  |
| 2018 | 5         | 8.62%   |
| 2008 | 3         | 5.17%   |
| 2021 | 2         | 3.45%   |
| 2016 | 2         | 3.45%   |
| 2015 | 2         | 3.45%   |
| 2022 | 1         | 1.72%   |
| 2011 | 1         | 1.72%   |
| 2007 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 55.17%  |
| Desktop     | 18        | 31.03%  |
| All in one  | 4         | 6.9%    |
| Mini pc     | 2         | 3.45%   |
| Tablet      | 1         | 1.72%   |
| Convertible | 1         | 1.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 21        | 36.21%  |
| 3.01-4.0   | 13        | 22.41%  |
| 8.01-16.0  | 12        | 20.69%  |
| 16.01-24.0 | 8         | 13.79%  |
| 32.01-64.0 | 3         | 5.17%   |
| 1.01-2.0   | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 36        | 61.02%  |
| 2.01-3.0 | 9         | 15.25%  |
| 3.01-4.0 | 6         | 10.17%  |
| 4.01-8.0 | 4         | 6.78%   |
| 0.51-1.0 | 4         | 6.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 68.97%  |
| 2      | 13        | 22.41%  |
| 4      | 3         | 5.17%   |
| 3      | 2         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 72.41%  |
| Yes       | 16        | 27.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 87.93%  |
| No        | 7         | 12.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 87.93%  |
| No        | 7         | 12.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 75.86%  |
| No        | 14        | 24.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 18.97%  |
| Brazil      | 7         | 12.07%  |
| Ukraine     | 3         | 5.17%   |
| Sweden      | 3         | 5.17%   |
| Italy       | 3         | 5.17%   |
| Germany     | 3         | 5.17%   |
| France      | 3         | 5.17%   |
| Spain       | 2         | 3.45%   |
| Russia      | 2         | 3.45%   |
| India       | 2         | 3.45%   |
| Czechia     | 2         | 3.45%   |
| Chile       | 2         | 3.45%   |
| Canada      | 2         | 3.45%   |
| UK          | 1         | 1.72%   |
| UAE         | 1         | 1.72%   |
| Thailand    | 1         | 1.72%   |
| Slovakia    | 1         | 1.72%   |
| Serbia      | 1         | 1.72%   |
| Netherlands | 1         | 1.72%   |
| Latvia      | 1         | 1.72%   |
| Iraq        | 1         | 1.72%   |
| Iran        | 1         | 1.72%   |
| Hungary     | 1         | 1.72%   |
| Greece      | 1         | 1.72%   |
| Finland     | 1         | 1.72%   |
| El Salvador | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Vancouver             | 2         | 3.45%   |
| Santiago              | 2         | 3.45%   |
| Waldachtal            | 1         | 1.72%   |
| Verden an der Aller   | 1         | 1.72%   |
| Västerås            | 1         | 1.72%   |
| Uruguaiana            | 1         | 1.72%   |
| Tyumen                | 1         | 1.72%   |
| Tehran                | 1         | 1.72%   |
| Talence               | 1         | 1.72%   |
| Stockholm             | 1         | 1.72%   |
| St. Ingbert           | 1         | 1.72%   |
| Skydra                | 1         | 1.72%   |
| Si Racha              | 1         | 1.72%   |
| Shreveport            | 1         | 1.72%   |
| Sesto Fiorentino      | 1         | 1.72%   |
| Sao Luís             | 1         | 1.72%   |
| Sao Bernardo do Campo | 1         | 1.72%   |
| San Salvador          | 1         | 1.72%   |
| Rio de Janeiro        | 1         | 1.72%   |
| Riga                  | 1         | 1.72%   |
| Ramsgate              | 1         | 1.72%   |
| Prague                | 1         | 1.72%   |
| Pori                  | 1         | 1.72%   |
| Parempuyre            | 1         | 1.72%   |
| Ottawa                | 1         | 1.72%   |
| Novoyavorovske        | 1         | 1.72%   |
| Novi Sad              | 1         | 1.72%   |
| Millers Creek         | 1         | 1.72%   |
| Milan                 | 1         | 1.72%   |
| Mariupol              | 1         | 1.72%   |
| Madrid                | 1         | 1.72%   |
| Levis                 | 1         | 1.72%   |
| Lelystad              | 1         | 1.72%   |
| Lehighton             | 1         | 1.72%   |
| Kyiv                  | 1         | 1.72%   |
| Krasnoyarsk           | 1         | 1.72%   |
| Kolkata               | 1         | 1.72%   |
| Kearney               | 1         | 1.72%   |
| Kalispell             | 1         | 1.72%   |
| Juazeiro do Norte     | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 16        | 16     | 19.75%  |
| WDC                       | 11        | 11     | 13.58%  |
| Kingston                  | 10        | 11     | 12.35%  |
| Samsung Electronics       | 8         | 10     | 9.88%   |
| SanDisk                   | 6         | 7      | 7.41%   |
| Toshiba                   | 5         | 5      | 6.17%   |
| SK hynix                  | 3         | 4      | 3.7%    |
| HGST                      | 3         | 3      | 3.7%    |
| PNY                       | 2         | 2      | 2.47%   |
| Micron Technology         | 2         | 2      | 2.47%   |
| Apple                     | 2         | 2      | 2.47%   |
| Wibtek                    | 1         | 1      | 1.23%   |
| Transcend                 | 1         | 1      | 1.23%   |
| Team                      | 1         | 1      | 1.23%   |
| SSSTC                     | 1         | 1      | 1.23%   |
| Phison Electronics        | 1         | 1      | 1.23%   |
| Patriot                   | 1         | 1      | 1.23%   |
| Micron/Crucial Technology | 1         | 1      | 1.23%   |
| Intel                     | 1         | 1      | 1.23%   |
| HECTRON                   | 1         | 1      | 1.23%   |
| Fanxiang                  | 1         | 1      | 1.23%   |
| Crucial                   | 1         | 1      | 1.23%   |
| Apacer                    | 1         | 1      | 1.23%   |
| AirDisk                   | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB             | 2         | 2.38%   |
| Seagate ST9500325AS 500GB                 | 2         | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 2         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 2.38%   |
| Seagate ST1000DM003-1SB102 1TB            | 2         | 2.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB    | 2         | 2.38%   |
| PNY CS900 240GB SSD                       | 2         | 2.38%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 2.38%   |
| HGST HTS541010A9E680 1TB                  | 2         | 2.38%   |
| Wibtek W800S 256GB SSD                    | 1         | 1.19%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 1.19%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.19%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 1.19%   |
| WDC WD5000AAKX-003CA0 500GB               | 1         | 1.19%   |
| WDC WD40EZRZ-00GXCB0 4TB                  | 1         | 1.19%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 1.19%   |
| WDC WD20SPZX-11UA7T0 2TB                  | 1         | 1.19%   |
| WDC WD1600AAJS-22L7A0 160GB               | 1         | 1.19%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.19%   |
| WDC WD10SPZX-22Z10T0 1TB                  | 1         | 1.19%   |
| WDC WD10EALX-009BA0 1TB                   | 1         | 1.19%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 1.19%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.19%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 1.19%   |
| Toshiba HDWD120 2TB                       | 1         | 1.19%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1.19%   |
| Toshiba DT01ACA050 500GB                  | 1         | 1.19%   |
| Team TM8PS7512G 512GB SSD                 | 1         | 1.19%   |
| SSSTC CVB-8D128-HP 128GB SSD              | 1         | 1.19%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 1.19%   |
| SK hynix HFS128G39TND-N210A 128GB SSD     | 1         | 1.19%   |
| Seagate ST9500420AS 500GB                 | 1         | 1.19%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.19%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.19%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 1.19%   |
| Seagate ST3500312CS 500GB                 | 1         | 1.19%   |
| Seagate ST2000DM001-1ER164 2TB            | 1         | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 1.19%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1.19%   |
| SanDisk X300 MSATA 128GB SSD              | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 45.71%  |
| WDC     | 10        | 10     | 28.57%  |
| Toshiba | 5         | 5      | 14.29%  |
| HGST    | 3         | 3      | 8.57%   |
| Apple   | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 27.78%  |
| SanDisk             | 4         | 4      | 11.11%  |
| Samsung Electronics | 4         | 5      | 11.11%  |
| PNY                 | 2         | 2      | 5.56%   |
| Micron Technology   | 2         | 2      | 5.56%   |
| Wibtek              | 1         | 1      | 2.78%   |
| WDC                 | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| Team                | 1         | 1      | 2.78%   |
| SSSTC               | 1         | 1      | 2.78%   |
| SK hynix            | 1         | 1      | 2.78%   |
| Patriot             | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| HECTRON             | 1         | 1      | 2.78%   |
| Fanxiang            | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |
| Apacer              | 1         | 1      | 2.78%   |
| AirDisk             | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 37     | 42.11%  |
| HDD  | 32        | 35     | 42.11%  |
| NVMe | 12        | 14     | 15.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 72     | 81.25%  |
| NVMe | 12        | 14     | 18.75%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 45     | 59.38%  |
| 0.51-1.0   | 20        | 21     | 31.25%  |
| 1.01-2.0   | 3         | 3      | 4.69%   |
| 3.01-4.0   | 2         | 2      | 3.13%   |
| 4.01-10.0  | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 25        | 43.1%   |
| 251-500    | 15        | 25.86%  |
| 501-1000   | 13        | 22.41%  |
| 51-100     | 3         | 5.17%   |
| 1001-2000  | 2         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 47        | 79.66%  |
| 21-50    | 6         | 10.17%  |
| 101-250  | 3         | 5.08%   |
| 251-500  | 1         | 1.69%   |
| 501-1000 | 1         | 1.69%   |
| 51-100   | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 58        | 85     | 98.31%  |
| Works    | 1         | 1      | 1.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 60.29%  |
| AMD                         | 12        | 17.65%  |
| Samsung Electronics         | 5         | 7.35%   |
| SK hynix                    | 2         | 2.94%   |
| SanDisk                     | 2         | 2.94%   |
| Marvell Technology Group    | 2         | 2.94%   |
| Phison Electronics          | 1         | 1.47%   |
| Micron/Crucial Technology   | 1         | 1.47%   |
| Kingston Technology Company | 1         | 1.47%   |
| ASMedia Technology          | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 7.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 6.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 5.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 5.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 5.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 3.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.6%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 2.6%    |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 1.3%    |
| SK hynix BC511 NVMe SSD                                                                 | 1         | 1.3%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1         | 1.3%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1         | 1.3%    |
| Samsung NVMe SSD SM0032L                                                                | 1         | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1         | 1.3%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1         | 1.3%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1         | 1.3%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 1.3%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 1.3%    |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                          | 1         | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.3%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.3%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.3%    |
| AMD FCH SATA Controller D                                                               | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 72.86%  |
| NVMe | 12        | 17.14%  |
| IDE  | 6         | 8.57%   |
| RAID | 1         | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 75.86%  |
| AMD    | 14        | 24.14%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-2415M CPU @ 2.30GHz    | 2         | 3.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 2         | 3.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 2         | 3.45%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz | 2         | 3.45%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz   | 1         | 1.72%   |
| Intel Pentium CPU J4205 @ 1.50GHz    | 1         | 1.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz    | 1         | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 1         | 1.72%   |
| Intel Core i7-4930K CPU @ 3.40GHz    | 1         | 1.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz    | 1         | 1.72%   |
| Intel Core i7-3820QM CPU @ 2.70GHz   | 1         | 1.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz    | 1         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz     | 1         | 1.72%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 1         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i5-5675R CPU @ 3.10GHz    | 1         | 1.72%   |
| Intel Core i5-4690K CPU @ 3.50GHz    | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 1         | 1.72%   |
| Intel Core i5-4200M CPU @ 2.50GHz    | 1         | 1.72%   |
| Intel Core i5-3337U CPU @ 1.80GHz    | 1         | 1.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz    | 1         | 1.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz   | 1         | 1.72%   |
| Intel Core i3-7100 CPU @ 3.90GHz     | 1         | 1.72%   |
| Intel Core i3-7020U CPU @ 2.30GHz    | 1         | 1.72%   |
| Intel Core i3-4030U CPU @ 1.90GHz    | 1         | 1.72%   |
| Intel Core i3-3240 CPU @ 3.40GHz     | 1         | 1.72%   |
| Intel Core i3-2375M CPU @ 1.50GHz    | 1         | 1.72%   |
| Intel Core i3-10100F CPU @ 3.60GHz   | 1         | 1.72%   |
| Intel Core i3-10100 CPU @ 3.60GHz    | 1         | 1.72%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz | 1         | 1.72%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz | 1         | 1.72%   |
| Intel Celeron J4115 CPU @ 1.80GHz    | 1         | 1.72%   |
| Intel Celeron CPU N3050 @ 1.60GHz    | 1         | 1.72%   |
| Intel Celeron CPU G530 @ 2.40GHz     | 1         | 1.72%   |
| Intel Celeron 2957U @ 1.40GHz        | 1         | 1.72%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz    | 1         | 1.72%   |
| Intel 12th Gen Core i3-12100         | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 16        | 27.59%  |
| Intel Core i3    | 11        | 18.97%  |
| AMD Ryzen 5      | 6         | 10.34%  |
| Intel Core i7    | 5         | 8.62%   |
| Intel Core 2 Duo | 4         | 6.9%    |
| Intel Celeron    | 4         | 6.9%    |
| AMD Ryzen 7      | 2         | 3.45%   |
| AMD A8           | 2         | 3.45%   |
| Other            | 1         | 1.72%   |
| Intel Xeon       | 1         | 1.72%   |
| Intel Pentium    | 1         | 1.72%   |
| Intel Atom       | 1         | 1.72%   |
| AMD FX           | 1         | 1.72%   |
| AMD E1           | 1         | 1.72%   |
| AMD Athlon       | 1         | 1.72%   |
| AMD A10          | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 48.28%  |
| 4      | 22        | 37.93%  |
| 6      | 5         | 8.62%   |
| 8      | 2         | 3.45%   |
| 3      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 70.69%  |
| 1      | 17        | 29.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 12.07%  |
| 0x306a9    | 5         | 8.62%   |
| 0x40651    | 4         | 6.9%    |
| 0x206a7    | 4         | 6.9%    |
| 0x08108109 | 4         | 6.9%    |
| 0xa0653    | 3         | 5.17%   |
| 0x406e3    | 3         | 5.17%   |
| 0x906e9    | 2         | 3.45%   |
| 0x306c3    | 2         | 3.45%   |
| 0x10676    | 2         | 3.45%   |
| 0x06001119 | 2         | 3.45%   |
| 0x90675    | 1         | 1.72%   |
| 0x806ec    | 1         | 1.72%   |
| 0x806ea    | 1         | 1.72%   |
| 0x806e9    | 1         | 1.72%   |
| 0x706e5    | 1         | 1.72%   |
| 0x706a1    | 1         | 1.72%   |
| 0x6fb      | 1         | 1.72%   |
| 0x506c9    | 1         | 1.72%   |
| 0x406c4    | 1         | 1.72%   |
| 0x406c3    | 1         | 1.72%   |
| 0x40671    | 1         | 1.72%   |
| 0x306e4    | 1         | 1.72%   |
| 0x206d7    | 1         | 1.72%   |
| 0x0a201009 | 1         | 1.72%   |
| 0x08701021 | 1         | 1.72%   |
| 0x08600106 | 1         | 1.72%   |
| 0x0800820d | 1         | 1.72%   |
| 0x07030105 | 1         | 1.72%   |
| 0x06000822 | 1         | 1.72%   |
| 0x0500010d | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 15.52%  |
| Haswell          | 7         | 12.07%  |
| Zen+             | 6         | 10.34%  |
| IvyBridge        | 6         | 10.34%  |
| SandyBridge      | 5         | 8.62%   |
| Skylake          | 3         | 5.17%   |
| Piledriver       | 3         | 5.17%   |
| Penryn           | 3         | 5.17%   |
| CometLake        | 3         | 5.17%   |
| Zen 2            | 2         | 3.45%   |
| Silvermont       | 2         | 3.45%   |
| Zen 3            | 1         | 1.72%   |
| Puma             | 1         | 1.72%   |
| IceLake          | 1         | 1.72%   |
| Goldmont plus    | 1         | 1.72%   |
| Goldmont         | 1         | 1.72%   |
| Core             | 1         | 1.72%   |
| Broadwell        | 1         | 1.72%   |
| Bobcat           | 1         | 1.72%   |
| Alderlake Hybrid | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 47.06%  |
| Nvidia | 19        | 27.94%  |
| AMD    | 17        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 7.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 4.23%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 2.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.82%   |
| Intel HD Graphics 630                                                                    | 2         | 2.82%   |
| Intel HD Graphics 620                                                                    | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 2.82%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 2         | 2.82%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.41%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.41%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.41%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.41%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.41%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.41%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.41%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.41%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.41%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 1.41%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.41%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 1.41%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 39.66%  |
| 1 x AMD        | 13        | 22.41%  |
| 1 x Nvidia     | 10        | 17.24%  |
| Intel + Nvidia | 8         | 13.79%  |
| 2 x AMD        | 2         | 3.45%   |
| Intel + AMD    | 1         | 1.72%   |
| AMD + Nvidia   | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 58        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 41.38%  |
| 1.01-2.0   | 9         | 15.52%  |
| 0.01-0.5   | 7         | 12.07%  |
| 0.51-1.0   | 6         | 10.34%  |
| 2.01-3.0   | 4         | 6.9%    |
| 7.01-8.0   | 3         | 5.17%   |
| 3.01-4.0   | 3         | 5.17%   |
| 5.01-6.0   | 2         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 13.56%  |
| LG Display          | 7         | 11.86%  |
| Chimei Innolux      | 7         | 11.86%  |
| AU Optronics        | 7         | 11.86%  |
| Apple               | 7         | 11.86%  |
| BOE                 | 5         | 8.47%   |
| Goldstar            | 4         | 6.78%   |
| AOC                 | 3         | 5.08%   |
| Acer                | 2         | 3.39%   |
| Viotek              | 1         | 1.69%   |
| Sony                | 1         | 1.69%   |
| Philips             | 1         | 1.69%   |
| PANDA               | 1         | 1.69%   |
| Insignia            | 1         | 1.69%   |
| InfoVision          | 1         | 1.69%   |
| Iiyama              | 1         | 1.69%   |
| Dell                | 1         | 1.69%   |
| BenQ                | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 3.33%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 2         | 3.33%   |
| Viotek GNV34DBE VTK3400 3440x1440 797x334mm 34.0-inch                | 1         | 1.67%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                        | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 1.67%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 1.67%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 1.67%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1         | 1.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.67%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 1.67%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch         | 1         | 1.67%   |
| Insignia DX-15E220A12 BBY0032 1360x768 544x326mm 25.0-inch           | 1         | 1.67%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 1.67%   |
| Iiyama X2485 IVM6122 1920x1200 518x324mm 24.1-inch                   | 1         | 1.67%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 1.67%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                  | 1         | 1.67%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch             | 1         | 1.67%   |
| Goldstar 24GL600F GSM5B73 1920x1080 530x300mm 24.0-inch              | 1         | 1.67%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 1.67%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 1         | 1.67%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 1.67%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 1.67%   |
| BOE LCD Monitor BOE065F 1920x1080 344x194mm 15.5-inch                | 1         | 1.67%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 27        | 47.37%  |
| 1366x768 (WXGA)    | 12        | 21.05%  |
| 1680x1050 (WSXGA+) | 3         | 5.26%   |
| 1600x900 (HD+)     | 3         | 5.26%   |
| 3840x2160 (4K)     | 2         | 3.51%   |
| 2560x1440 (QHD)    | 2         | 3.51%   |
| 1280x800 (WXGA)    | 2         | 3.51%   |
| 3440x1440          | 1         | 1.75%   |
| 2880x1800          | 1         | 1.75%   |
| 2736x1824          | 1         | 1.75%   |
| 1920x540           | 1         | 1.75%   |
| 1920x1200 (WUXGA)  | 1         | 1.75%   |
| 1440x900 (WXGA+)   | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 13        | 22.03%  |
| 13     | 7         | 11.86%  |
| 21     | 5         | 8.47%   |
| 17     | 5         | 8.47%   |
| 14     | 5         | 8.47%   |
| 24     | 4         | 6.78%   |
| 23     | 3         | 5.08%   |
| 20     | 3         | 5.08%   |
| 40     | 2         | 3.39%   |
| 12     | 2         | 3.39%   |
| 11     | 2         | 3.39%   |
| 72     | 1         | 1.69%   |
| 60     | 1         | 1.69%   |
| 48     | 1         | 1.69%   |
| 34     | 1         | 1.69%   |
| 31     | 1         | 1.69%   |
| 27     | 1         | 1.69%   |
| 22     | 1         | 1.69%   |
| 18     | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 37.93%  |
| 401-500     | 10        | 17.24%  |
| 501-600     | 7         | 12.07%  |
| 201-300     | 7         | 12.07%  |
| 351-400     | 5         | 8.62%   |
| 801-900     | 2         | 3.45%   |
| 1001-1500   | 2         | 3.45%   |
| 701-800     | 1         | 1.72%   |
| 601-700     | 1         | 1.72%   |
| 1501-2000   | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 45        | 78.95%  |
| 16/10 | 9         | 15.79%  |
| 3/2   | 1         | 1.75%   |
| 21/9  | 1         | 1.75%   |
| 1.96  | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 22.41%  |
| 81-90          | 11        | 18.97%  |
| 201-250        | 10        | 17.24%  |
| 151-200        | 4         | 6.9%    |
| 121-130        | 4         | 6.9%    |
| 501-1000       | 3         | 5.17%   |
| More than 1000 | 2         | 3.45%   |
| 71-80          | 2         | 3.45%   |
| 51-60          | 2         | 3.45%   |
| 351-500        | 2         | 3.45%   |
| 61-70          | 1         | 1.72%   |
| 301-350        | 1         | 1.72%   |
| 251-300        | 1         | 1.72%   |
| 141-150        | 1         | 1.72%   |
| 131-140        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 19        | 32.76%  |
| 51-100  | 17        | 29.31%  |
| 121-160 | 16        | 27.59%  |
| 161-240 | 4         | 6.9%    |
| 1-50    | 2         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 93.1%   |
| 2     | 4         | 6.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 33        | 35.87%  |
| Intel                           | 18        | 19.57%  |
| Qualcomm Atheros                | 12        | 13.04%  |
| Broadcom                        | 10        | 10.87%  |
| Marvell Technology Group        | 5         | 5.43%   |
| Broadcom Limited                | 4         | 4.35%   |
| Google                          | 2         | 2.17%   |
| Xiaomi                          | 1         | 1.09%   |
| TP-Link                         | 1         | 1.09%   |
| Samsung Electronics             | 1         | 1.09%   |
| Ralink Technology               | 1         | 1.09%   |
| Ralink                          | 1         | 1.09%   |
| Qualcomm Atheros Communications | 1         | 1.09%   |
| Motorola PCS                    | 1         | 1.09%   |
| ASIX Electronics                | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 21        | 19.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 3.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 4         | 3.7%    |
| Broadcom BCM4321 802.11a/b/g/n                                         | 4         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.85%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.93%   |
| Realtek 802.11ac NIC                                                   | 1         | 0.93%   |
| Ralink RT2770 Wireless Adapter                                         | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.93%   |
| Motorola PCS moto g82 5G                                               | 1         | 0.93%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                      | 1         | 0.93%   |
| Intel Wireless 8260                                                    | 1         | 0.93%   |
| Intel Wireless 7265                                                    | 1         | 0.93%   |
| Intel Wireless 3165                                                    | 1         | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 25.49%  |
| Realtek Semiconductor           | 12        | 23.53%  |
| Qualcomm Atheros                | 9         | 17.65%  |
| Broadcom                        | 9         | 17.65%  |
| Broadcom Limited                | 4         | 7.84%   |
| Ralink Technology               | 1         | 1.96%   |
| Ralink                          | 1         | 1.96%   |
| Qualcomm Atheros Communications | 1         | 1.96%   |
| Marvell Technology Group        | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 7.84%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 4         | 7.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 5.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 3.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 3.92%   |
| Intel Wireless 8265 / 8275                                           | 2         | 3.92%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 3.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 3.92%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.96%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 1.96%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.96%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.96%   |
| Ralink RT2770 Wireless Adapter                                       | 1         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.96%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 1.96%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 1         | 1.96%   |
| Intel Wireless 8260                                                  | 1         | 1.96%   |
| Intel Wireless 7265                                                  | 1         | 1.96%   |
| Intel Wireless 3165                                                  | 1         | 1.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.96%   |
| Intel Centrino Wireless-N 105                                        | 1         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1         | 1.96%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 1         | 1.96%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                               | 1         | 1.96%   |
| Broadcom Limited BCM43142 802.11b/g/n                                | 1         | 1.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 54.55%  |
| Intel                    | 7         | 12.73%  |
| Qualcomm Atheros         | 4         | 7.27%   |
| Marvell Technology Group | 4         | 7.27%   |
| Broadcom                 | 4         | 7.27%   |
| Google                   | 2         | 3.64%   |
| Xiaomi                   | 1         | 1.82%   |
| TP-Link                  | 1         | 1.82%   |
| Samsung Electronics      | 1         | 1.82%   |
| ASIX Electronics         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 21        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 14.29%  |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 4         | 7.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 3.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.79%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.79%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.79%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.79%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 1.79%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.79%   |
| Google Pixel 7 Pro                                                     | 1         | 1.79%   |
| Google Nexus/Pixel Device (tether)                                     | 1         | 1.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.79%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 49.51%  |
| Ethernet | 51        | 49.51%  |
| Unknown  | 1         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 58.18%  |
| WiFi     | 23        | 41.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 65.52%  |
| 1     | 17        | 29.31%  |
| 0     | 2         | 3.45%   |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 76.27%  |
| Yes  | 14        | 23.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 24.44%  |
| Apple                           | 9         | 20%     |
| Realtek Semiconductor           | 8         | 17.78%  |
| Qualcomm Atheros Communications | 5         | 11.11%  |
| Lite-On Technology              | 4         | 8.89%   |
| Broadcom                        | 2         | 4.44%   |
| Toshiba                         | 1         | 2.22%   |
| Ralink                          | 1         | 2.22%   |
| Marvell Semiconductor           | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| ASUSTek Computer                | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.67%   |
| Realtek Bluetooth Radio                             | 3         | 6.67%   |
| Intel Bluetooth wireless interface                  | 3         | 6.67%   |
| Intel Bluetooth Device                              | 3         | 6.67%   |
| Apple Bluetooth Host Controller                     | 3         | 6.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 4.44%   |
| Apple Bluetooth USB Host Controller                 | 2         | 4.44%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 4.44%   |
| Apple Bluetooth HCI                                 | 2         | 4.44%   |
| Toshiba Bluetooth Device                            | 1         | 2.22%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.22%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2.22%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.22%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.22%   |
| Lite-On Bluetooth Device                            | 1         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.22%   |
| Intel AX201 Bluetooth                               | 1         | 2.22%   |
| Intel AX200 Bluetooth                               | 1         | 2.22%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.22%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 44        | 56.41%  |
| AMD                 | 16        | 20.51%  |
| Nvidia              | 13        | 16.67%  |
| C-Media Electronics | 2         | 2.56%   |
| Huawei Technologies | 1         | 1.28%   |
| Guillemot           | 1         | 1.28%   |
| Creative Labs       | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 8.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 6.32%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 4.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 4.21%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 4.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 4.21%   |
| AMD FCH Azalia Controller                                                                         | 4         | 4.21%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.11%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.11%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.05%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.05%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.05%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.05%   |
| Huawei Technologies HUAWEI USB-C HEADSET                                                          | 1         | 1.05%   |
| Guillemot Hercules DJ Console 4-Mx                                                                | 1         | 1.05%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.05%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 21.05%  |
| Apple                                  | 6         | 15.79%  |
| Realtek Semiconductor                  | 5         | 13.16%  |
| Suyin                                  | 3         | 7.89%   |
| Syntek                                 | 2         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Microdia                               | 2         | 5.26%   |
| Logitech                               | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.26%   |
| Quanta                                 | 1         | 2.63%   |
| Microsoft                              | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| IMC Networks                           | 1         | 2.63%   |
| HRY                                    | 1         | 2.63%   |
| 2M UVC CAMERA                          | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 7.69%   |
| Apple Built-in iSight                            | 3         | 7.69%   |
| Syntek Integrated Camera                         | 2         | 5.13%   |
| Realtek USB Camera                               | 2         | 5.13%   |
| Chicony Integrated Camera                        | 2         | 5.13%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 5.13%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 2.56%   |
| Sunplus HD WebCam                                | 1         | 2.56%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 2.56%   |
| Realtek Integrated_Webcam_HD                     | 1         | 2.56%   |
| Realtek Integrated Camera                        | 1         | 2.56%   |
| Quanta HD Webcam                                 | 1         | 2.56%   |
| Microsoft LifeCam Cinema                         | 1         | 2.56%   |
| Microdia Integrated_Webcam_HD                    | 1         | 2.56%   |
| Microdia Integrated Webcam HD                    | 1         | 2.56%   |
| Logitech Webcam C270                             | 1         | 2.56%   |
| Logitech HD Pro Webcam C920                      | 1         | 2.56%   |
| Lite-On Integrated Camera                        | 1         | 2.56%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 2.56%   |
| HRY USB Camera                                   | 1         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 2.56%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)          | 1         | 2.56%   |
| Chicony HP HD Camera                             | 1         | 2.56%   |
| Chicony HD WebCam                                | 1         | 2.56%   |
| Chicony 5M Cam                                   | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.56%   |
| Apple FaceTime HD Camera                         | 1         | 2.56%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam              | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Synaptics          | 3         | 60%     |
| Validity Sensors   | 1         | 20%     |
| Focal-systems.Corp | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader | 2         | 40%     |
| Validity Sensors VFS5011 Fingerprint Reader      | 1         | 20%     |
| Synaptics WBDI                                   | 1         | 20%     |
| Focal-systems.Corp FT9201Fingerprint.            | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 34.48%  |
| 2     | 17        | 29.31%  |
| 0     | 11        | 18.97%  |
| 3     | 7         | 12.07%  |
| 4     | 3         | 5.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 39.77%  |
| Net/wireless             | 19        | 21.59%  |
| Graphics card            | 6         | 6.82%   |
| Bluetooth                | 6         | 6.82%   |
| Fingerprint reader       | 5         | 5.68%   |
| Card reader              | 5         | 5.68%   |
| Net/ethernet             | 4         | 4.55%   |
| Multimedia controller    | 4         | 4.55%   |
| Firewire controller      | 2         | 2.27%   |
| Storage/ide              | 1         | 1.14%   |
| Chipcard                 | 1         | 1.14%   |

