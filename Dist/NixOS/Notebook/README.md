NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 58

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | XPS 13 9310                 | [b9c698a94c](https://linux-hardware.org/?probe=b9c698a94c) | Sep 21, 2022 |
| Dell          | Precision M4800             | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Apple         | MacBookPro11,5              | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| Apple         | MacBookPro11,5              | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Dell          | XPS 13 9310                 | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 22.05                      | 17        | 38.64%  |
| NixOS 21.11                      | 9         | 20.45%  |
| NixOS 22.11                      | 4         | 9.09%   |
| NixOS                            | 2         | 4.55%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 2.27%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 2.27%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 2.27%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 2.27%   |
| NixOS 21.05.2132.733682c3292     | 1         | 2.27%   |
| NixOS 21.05.20210423.c21475e     | 1         | 2.27%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 2.27%   |
| NixOS 20.09pre-git               | 1         | 2.27%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 2.27%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 2.27%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 2.27%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.15.43         | 3         | 6.38%   |
| 5.16.15         | 2         | 4.26%   |
| 5.15.68         | 2         | 4.26%   |
| 5.15.64         | 2         | 4.26%   |
| 5.15.26         | 2         | 4.26%   |
| 5.13.7          | 2         | 4.26%   |
| 5.8.4           | 1         | 2.13%   |
| 5.8.16-hardened | 1         | 2.13%   |
| 5.8.11          | 1         | 2.13%   |
| 5.7.4           | 1         | 2.13%   |
| 5.7.17          | 1         | 2.13%   |
| 5.4.24          | 1         | 2.13%   |
| 5.4.209         | 1         | 2.13%   |
| 5.4.187         | 1         | 2.13%   |
| 5.19.0          | 1         | 2.13%   |
| 5.18.7-zen1     | 1         | 2.13%   |
| 5.18.0          | 1         | 2.13%   |
| 5.17.1          | 1         | 2.13%   |
| 5.17.0          | 1         | 2.13%   |
| 5.16.8-zen1     | 1         | 2.13%   |
| 5.16.7          | 1         | 2.13%   |
| 5.16.3          | 1         | 2.13%   |
| 5.16.10         | 1         | 2.13%   |
| 5.15.62         | 1         | 2.13%   |
| 5.15.59         | 1         | 2.13%   |
| 5.15.55         | 1         | 2.13%   |
| 5.15.4          | 1         | 2.13%   |
| 5.15.32         | 1         | 2.13%   |
| 5.15.3          | 1         | 2.13%   |
| 5.15.25         | 1         | 2.13%   |
| 5.15.22         | 1         | 2.13%   |
| 5.15.12         | 1         | 2.13%   |
| 5.15.0          | 1         | 2.13%   |
| 5.13.2          | 1         | 2.13%   |
| 5.12.7          | 1         | 2.13%   |
| 5.10.69         | 1         | 2.13%   |
| 5.10.30         | 1         | 2.13%   |
| 5.10.109        | 1         | 2.13%   |
| 4.19.57         | 1         | 2.13%   |
| 4.19.116        | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.43  | 3         | 6.38%   |
| 5.16.15  | 2         | 4.26%   |
| 5.15.68  | 2         | 4.26%   |
| 5.15.64  | 2         | 4.26%   |
| 5.15.26  | 2         | 4.26%   |
| 5.13.7   | 2         | 4.26%   |
| 5.8.4    | 1         | 2.13%   |
| 5.8.16   | 1         | 2.13%   |
| 5.8.11   | 1         | 2.13%   |
| 5.7.4    | 1         | 2.13%   |
| 5.7.17   | 1         | 2.13%   |
| 5.4.24   | 1         | 2.13%   |
| 5.4.209  | 1         | 2.13%   |
| 5.4.187  | 1         | 2.13%   |
| 5.19.0   | 1         | 2.13%   |
| 5.18.7   | 1         | 2.13%   |
| 5.18.0   | 1         | 2.13%   |
| 5.17.1   | 1         | 2.13%   |
| 5.17.0   | 1         | 2.13%   |
| 5.16.8   | 1         | 2.13%   |
| 5.16.7   | 1         | 2.13%   |
| 5.16.3   | 1         | 2.13%   |
| 5.16.10  | 1         | 2.13%   |
| 5.15.62  | 1         | 2.13%   |
| 5.15.59  | 1         | 2.13%   |
| 5.15.55  | 1         | 2.13%   |
| 5.15.4   | 1         | 2.13%   |
| 5.15.32  | 1         | 2.13%   |
| 5.15.3   | 1         | 2.13%   |
| 5.15.25  | 1         | 2.13%   |
| 5.15.22  | 1         | 2.13%   |
| 5.15.12  | 1         | 2.13%   |
| 5.15.0   | 1         | 2.13%   |
| 5.13.2   | 1         | 2.13%   |
| 5.12.7   | 1         | 2.13%   |
| 5.10.69  | 1         | 2.13%   |
| 5.10.30  | 1         | 2.13%   |
| 5.10.109 | 1         | 2.13%   |
| 4.19.57  | 1         | 2.13%   |
| 4.19.116 | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 18        | 40%     |
| 5.16    | 6         | 13.33%  |
| 5.8     | 3         | 6.67%   |
| 5.13    | 3         | 6.67%   |
| 5.10    | 3         | 6.67%   |
| 5.7     | 2         | 4.44%   |
| 5.4     | 2         | 4.44%   |
| 5.18    | 2         | 4.44%   |
| 5.17    | 2         | 4.44%   |
| 4.19    | 2         | 4.44%   |
| 5.19    | 1         | 2.22%   |
| 5.12    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 34        | 80.95%  |
| GNOME       | 3         | 7.14%   |
| XFCE        | 2         | 4.76%   |
| sway        | 1         | 2.38%   |
| none+xmonad | 1         | 2.38%   |
| KDE         | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 76.74%  |
| Wayland | 5         | 11.63%  |
| X11     | 4         | 9.3%    |
| Tty     | 1         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 87.8%   |
| LightDM | 3         | 7.32%   |
| GDM     | 2         | 4.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 70%     |
| en_US   | 9         | 22.5%   |
| ru_RU   | 1         | 2.5%    |
| ro_RO   | 1         | 2.5%    |
| en_DK   | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 33        | 82.5%   |
| BIOS | 7         | 17.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 24        | 57.14%  |
| Btrfs   | 7         | 16.67%  |
| Tmpfs   | 5         | 11.9%   |
| Unknown | 3         | 7.14%   |
| Zfs     | 2         | 4.76%   |
| Xfs     | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 37        | 88.1%   |
| Unknown | 5         | 11.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 73.17%  |
| Yes       | 11        | 26.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 75%     |
| Yes       | 10        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 40%     |
| Dell                | 8         | 20%     |
| ASUSTek Computer    | 5         | 12.5%   |
| Hewlett-Packard     | 4         | 10%     |
| OBSIDIAN-PC         | 1         | 2.5%    |
| MSI                 | 1         | 2.5%    |
| GPD                 | 1         | 2.5%    |
| Gigabyte Technology | 1         | 2.5%    |
| Framework           | 1         | 2.5%    |
| Apple               | 1         | 2.5%    |
| Acer                | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Latitude 7420                    | 2         | 5%      |
| OBSIDIAN-PC N13_N140ZU                | 1         | 2.5%    |
| MSI Bravo 15 B5DD                     | 1         | 2.5%    |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 2.5%    |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 2.5%    |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 2.5%    |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 2.5%    |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 2.5%    |
| Lenovo ThinkPad X230 23243E9          | 1         | 2.5%    |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW | 1         | 2.5%    |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 2.5%    |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 2.5%    |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 2.5%    |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 2.5%    |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 2.5%    |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 2.5%    |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 2.5%    |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 2.5%    |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 2.5%    |
| HP ZBook Studio G5                    | 1         | 2.5%    |
| HP ProBook 450 G4                     | 1         | 2.5%    |
| HP ProBook 445 G7                     | 1         | 2.5%    |
| HP EliteBook 845 G8 Notebook PC       | 1         | 2.5%    |
| GPD MicroPC                           | 1         | 2.5%    |
| Gigabyte Sabre 15                     | 1         | 2.5%    |
| Framework Laptop                      | 1         | 2.5%    |
| Dell XPS 15 9570                      | 1         | 2.5%    |
| Dell XPS 15 9550                      | 1         | 2.5%    |
| Dell XPS 13 9310                      | 1         | 2.5%    |
| Dell XPS 13 9305                      | 1         | 2.5%    |
| Dell Precision M4800                  | 1         | 2.5%    |
| Dell Inspiron 15 7510                 | 1         | 2.5%    |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 2.5%    |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 2.5%    |
| ASUS ROG Strix G533QR_G533QR          | 1         | 2.5%    |
| ASUS ROG Flow X13 GV301QE_GV301QE     | 1         | 2.5%    |
| ASUS ASUSPRO P1440FAC_P1440FA         | 1         | 2.5%    |
| Apple MacBookPro11,5                  | 1         | 2.5%    |
| Acer Aspire E5-576G                   | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 35%     |
| Dell XPS           | 4         | 10%     |
| ASUS ROG           | 3         | 7.5%    |
| HP ProBook         | 2         | 5%      |
| Dell Latitude      | 2         | 5%      |
| OBSIDIAN-PC N13    | 1         | 2.5%    |
| MSI Bravo          | 1         | 2.5%    |
| Lenovo Yoga        | 1         | 2.5%    |
| Lenovo Legion      | 1         | 2.5%    |
| HP ZBook           | 1         | 2.5%    |
| HP EliteBook       | 1         | 2.5%    |
| GPD MicroPC        | 1         | 2.5%    |
| Gigabyte Sabre     | 1         | 2.5%    |
| Framework Laptop   | 1         | 2.5%    |
| Dell Precision     | 1         | 2.5%    |
| Dell Inspiron      | 1         | 2.5%    |
| ASUS ZenBook       | 1         | 2.5%    |
| ASUS ASUSPRO       | 1         | 2.5%    |
| Apple MacBookPro11 | 1         | 2.5%    |
| Acer Aspire        | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 25%     |
| 2021 | 8         | 20%     |
| 2018 | 6         | 15%     |
| 2016 | 5         | 12.5%   |
| 2019 | 4         | 10%     |
| 2017 | 2         | 5%      |
| 2015 | 2         | 5%      |
| 2013 | 2         | 5%      |
| 2012 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 40        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 40        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 97.5%   |
| Yes  | 1         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 15        | 36.59%  |
| 16.01-24.0  | 12        | 29.27%  |
| 8.01-16.0   | 8         | 19.51%  |
| 4.01-8.0    | 3         | 7.32%   |
| 3.01-4.0    | 1         | 2.44%   |
| 24.01-32.0  | 1         | 2.44%   |
| 64.01-256.0 | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 30.43%  |
| 8.01-16.0  | 10        | 21.74%  |
| 3.01-4.0   | 9         | 19.57%  |
| 2.01-3.0   | 5         | 10.87%  |
| 24.01-32.0 | 3         | 6.52%   |
| 1.01-2.0   | 2         | 4.35%   |
| 0.51-1.0   | 2         | 4.35%   |
| 32.01-64.0 | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 78.05%  |
| 2      | 9         | 21.95%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 95%     |
| Yes       | 2         | 5%      |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 73.81%  |
| No        | 11        | 26.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 97.5%   |
| No        | 1         | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 85.71%  |
| No        | 6         | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 5         | 12.5%   |
| France      | 5         | 12.5%   |
| Ukraine     | 3         | 7.5%    |
| Russia      | 3         | 7.5%    |
| Poland      | 3         | 7.5%    |
| Canada      | 3         | 7.5%    |
| USA         | 2         | 5%      |
| Germany     | 2         | 5%      |
| Belgium     | 2         | 5%      |
| Uruguay     | 1         | 2.5%    |
| Switzerland | 1         | 2.5%    |
| Sweden      | 1         | 2.5%    |
| Spain       | 1         | 2.5%    |
| Romania     | 1         | 2.5%    |
| Portugal    | 1         | 2.5%    |
| Netherlands | 1         | 2.5%    |
| Iraq        | 1         | 2.5%    |
| Iran        | 1         | 2.5%    |
| India       | 1         | 2.5%    |
| Colombia    | 1         | 2.5%    |
| Austria     | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Marki              | 2         | 4.76%   |
| London             | 2         | 4.76%   |
| Halifax            | 2         | 4.76%   |
| Woodford           | 1         | 2.38%   |
| Villeurbanne       | 1         | 2.38%   |
| Vienna             | 1         | 2.38%   |
| Verneuil-sur-Seine | 1         | 2.38%   |
| Valpacos           | 1         | 2.38%   |
| Tottenham          | 1         | 2.38%   |
| Tolyatti           | 1         | 2.38%   |
| Tehran             | 1         | 2.38%   |
| Stockholm          | 1         | 2.38%   |
| South Deerfield    | 1         | 2.38%   |
| Saratov            | 1         | 2.38%   |
| Plymouth           | 1         | 2.38%   |
| Ottawa             | 1         | 2.38%   |
| Nantes             | 1         | 2.38%   |
| Mykolayiv          | 1         | 2.38%   |
| Montevideo         | 1         | 2.38%   |
| Mons               | 1         | 2.38%   |
| Melsele            | 1         | 2.38%   |
| Lyon               | 1         | 2.38%   |
| Lodi               | 1         | 2.38%   |
| Lehrte             | 1         | 2.38%   |
| Krakow             | 1         | 2.38%   |
| Kiel               | 1         | 2.38%   |
| Kharkiv            | 1         | 2.38%   |
| Islington          | 1         | 2.38%   |
| Irpin              | 1         | 2.38%   |
| Gurgaon            | 1         | 2.38%   |
| Getafe             | 1         | 2.38%   |
| Enschede           | 1         | 2.38%   |
| Cluj-Napoca        | 1         | 2.38%   |
| Chelyabinsk        | 1         | 2.38%   |
| Cergy              | 1         | 2.38%   |
| Cartagena          | 1         | 2.38%   |
| Bedford            | 1         | 2.38%   |
| Baghdad            | 1         | 2.38%   |
| Allschwil          | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 20     | 33.33%  |
| WDC                 | 6         | 6      | 12.5%   |
| Toshiba             | 3         | 3      | 6.25%   |
| SK hynix            | 3         | 4      | 6.25%   |
| Kingston            | 3         | 3      | 6.25%   |
| Crucial             | 3         | 4      | 6.25%   |
| Transcend           | 2         | 2      | 4.17%   |
| Seagate             | 2         | 2      | 4.17%   |
| Micron Technology   | 2         | 2      | 4.17%   |
| KIOXIA              | 2         | 3      | 4.17%   |
| Sandisk             | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| INNOVATION IT       | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |
| BIWIN               | 1         | 1      | 2.08%   |
| Apple               | 1         | 3      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung PM9A1 NVMe 1024GB                             | 2         | 4%      |
| WDC WDS480G2G0B-00EPW0 480GB SSD                      | 1         | 2%      |
| WDC WDS200T1X0E-00AFY0 2TB                            | 1         | 2%      |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 1         | 2%      |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                  | 1         | 2%      |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                    | 1         | 2%      |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                  | 1         | 2%      |
| Transcend TS256GMTS800 256GB SSD                      | 1         | 2%      |
| Transcend TS256GMTS430S 256GB SSD                     | 1         | 2%      |
| Toshiba MQ01ABD100 1TB                                | 1         | 2%      |
| Toshiba KXG6AZNV512G 512GB                            | 1         | 2%      |
| Toshiba KXG50ZNV512G NVMe 512GB                       | 1         | 2%      |
| SK hynix PC711 HFS512GDE9X073N 512GB                  | 1         | 2%      |
| SK hynix NVMe SSD Drive 1TB                           | 1         | 2%      |
| SK hynix NVMe SSD Drive 1024GB                        | 1         | 2%      |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 2%      |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 2%      |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 2%      |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB | 1         | 2%      |
| Samsung SSD 970 EVO Plus 1TB                          | 1         | 2%      |
| Samsung SSD 970 EVO 500GB                             | 1         | 2%      |
| Samsung SSD 870 EVO 500GB                             | 1         | 2%      |
| Samsung SSD 860 EVO 1TB                               | 1         | 2%      |
| Samsung SSD 850 EVO 500GB                             | 1         | 2%      |
| Samsung Portable SSD T5 500GB                         | 1         | 2%      |
| Samsung PM991a NVMe 512GB                             | 1         | 2%      |
| Samsung NVMe SSD Drive 512GB                          | 1         | 2%      |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 1         | 2%      |
| Samsung MZVLB512HAJQ-000H1 512GB                      | 1         | 2%      |
| Samsung MZVLB512HAJQ-00000 512GB                      | 1         | 2%      |
| Samsung MZVLB256HAHQ-000L7 256GB                      | 1         | 2%      |
| Samsung MZVLB1T0HBLR-000L7 1TB                        | 1         | 2%      |
| Samsung MZVLB1T0HBLR-000L2 1TB                        | 1         | 2%      |
| Samsung MZ7LN512HMJP-000L7 512GB SSD                  | 1         | 2%      |
| Micron MTFDHBA512TDV 512GB                            | 1         | 2%      |
| Micron 1100_MTFDDAV256TBN 256GB SSD                   | 1         | 2%      |
| KIOXIA NVMe SSD Drive 256GB                           | 1         | 2%      |
| KIOXIA KXG60ZNV1T02 NVMe 1024GB                       | 1         | 2%      |
| Kingston SA400S37960G 960GB SSD                       | 1         | 2%      |
| Kingston OM8PCP3512F-AI1 512GB                        | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 33.33%  |
| Transcend           | 2         | 2      | 13.33%  |
| Crucial             | 2         | 3      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| INNOVATION IT       | 1         | 1      | 6.67%   |
| BIWIN               | 1         | 1      | 6.67%   |
| Apple               | 1         | 3      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 35     | 62.22%  |
| SSD  | 13        | 18     | 28.89%  |
| HDD  | 4         | 4      | 8.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 35     | 65.12%  |
| SATA | 14        | 21     | 32.56%  |
| SAS  | 1         | 1      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 13     | 55.56%  |
| 0.51-1.0   | 7         | 8      | 38.89%  |
| 1.01-2.0   | 1         | 1      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 29        | 70.73%  |
| 1-20           | 6         | 14.63%  |
| 501-1000       | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 251-500        | 1         | 2.44%   |
| 2001-3000      | 1         | 2.44%   |
| 1001-2000      | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 29        | 70.73%  |
| 1-20      | 7         | 17.07%  |
| 101-250   | 2         | 4.88%   |
| 251-500   | 1         | 2.44%   |
| 1001-2000 | 1         | 2.44%   |
| 501-1000  | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 33.33%  |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 33.33%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 1         | 1      | 33.33%  |
| SK hynix          | 1         | 1      | 33.33%  |
| Micron Technology | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 33.33%  |
| SSD  | 1         | 1      | 33.33%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 37        | 47     | 82.22%  |
| Detected | 5         | 7      | 11.11%  |
| Malfunc  | 3         | 3      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 19        | 37.25%  |
| Samsung Electronics          | 13        | 25.49%  |
| SanDisk                      | 6         | 11.76%  |
| Toshiba America Info Systems | 3         | 5.88%   |
| SK hynix                     | 3         | 5.88%   |
| Kingston Technology Company  | 2         | 3.92%   |
| AMD                          | 2         | 3.92%   |
| Micron/Crucial Technology    | 1         | 1.96%   |
| Micron Technology            | 1         | 1.96%   |
| KIOXIA                       | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 15.69%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 7.84%   |
| SK hynix Gold P31 SSD                                                            | 3         | 5.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 5.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 3.92%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 3.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 3.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 3.92%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.96%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.96%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.96%   |
| Samsung Electronics SATA controller                                              | 1         | 1.96%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 1.96%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.96%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.96%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.96%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.96%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 28        | 57.14%  |
| SATA | 18        | 36.73%  |
| RAID | 3         | 6.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 75%     |
| AMD    | 10        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 7.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 7.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 7.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 5%      |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 5%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 5%      |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 5%      |
| AMD Ryzen 7 5800H with Radeon Graphics     | 2         | 5%      |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 2.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 2.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz          | 1         | 2.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 2.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 2.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 2.5%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 2.5%    |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 2.5%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 2.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 2.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz          | 1         | 2.5%    |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 2.5%    |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 1         | 2.5%    |
| AMD Ryzen 9 5900HS with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics | 1         | 2.5%    |
| AMD Ryzen 7 5800U with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 5800HS with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics     | 1         | 2.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics     | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 17        | 42.5%   |
| Other           | 6         | 15%     |
| AMD Ryzen 7     | 6         | 15%     |
| Intel Core i5   | 4         | 10%     |
| AMD Ryzen 7 PRO | 3         | 7.5%    |
| Intel Xeon      | 1         | 2.5%    |
| Intel Core i3   | 1         | 2.5%    |
| Intel Celeron   | 1         | 2.5%    |
| AMD Ryzen 9     | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 20        | 50%     |
| 8      | 11        | 27.5%   |
| 2      | 6         | 15%     |
| 6      | 3         | 7.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 95%     |
| 1      | 2         | 5%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 97.56%  |
| Unknown        | 1         | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 5         | 12.2%   |
| Unknown    | 5         | 12.2%   |
| 0x806c1    | 4         | 9.76%   |
| 0x806ec    | 3         | 7.32%   |
| 0x806ea    | 3         | 7.32%   |
| 0x08600106 | 3         | 7.32%   |
| 0x906ea    | 2         | 4.88%   |
| 0x806eb    | 2         | 4.88%   |
| 0x406e3    | 2         | 4.88%   |
| 0x306c3    | 2         | 4.88%   |
| 0x906e9    | 1         | 2.44%   |
| 0x806e9    | 1         | 2.44%   |
| 0x806d1    | 1         | 2.44%   |
| 0x706a1    | 1         | 2.44%   |
| 0x506e3    | 1         | 2.44%   |
| 0x40661    | 1         | 2.44%   |
| 0x306d4    | 1         | 2.44%   |
| 0x306a9    | 1         | 2.44%   |
| 0x0a50000b | 1         | 2.44%   |
| 0x08600104 | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 35%     |
| Zen 3         | 6         | 15%     |
| TigerLake     | 5         | 12.5%   |
| Zen 2         | 4         | 10%     |
| Skylake       | 4         | 10%     |
| Haswell       | 3         | 7.5%    |
| IvyBridge     | 1         | 2.5%    |
| Icelake       | 1         | 2.5%    |
| Goldmont plus | 1         | 2.5%    |
| Broadwell     | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 50.91%  |
| Nvidia | 16        | 29.09%  |
| AMD    | 11        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                 | 6         | 10.71%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                   | 5         | 8.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 4         | 7.14%   |
| AMD Renoir                                                  | 4         | 7.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 3         | 5.36%   |
| Intel UHD Graphics 620                                      | 3         | 5.36%   |
| Nvidia GP108M [GeForce MX150]                               | 2         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 2         | 3.57%   |
| Intel HD Graphics 530                                       | 2         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                        | 2         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                   | 2         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 2         | 3.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                  | 1         | 1.79%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                       | 1         | 1.79%   |
| Nvidia GM108M [GeForce 940MX]                               | 1         | 1.79%   |
| Nvidia GM108M [GeForce 930MX]                               | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 1.79%   |
| Nvidia GK208M [GeForce GT 730M]                             | 1         | 1.79%   |
| Nvidia GK106GLM [Quadro K2100M]                             | 1         | 1.79%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                  | 1         | 1.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                     | 1         | 1.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]             | 1         | 1.79%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]             | 1         | 1.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                        | 1         | 1.79%   |
| Intel HD Graphics 630                                       | 1         | 1.79%   |
| Intel HD Graphics 620                                       | 1         | 1.79%   |
| Intel HD Graphics 5500                                      | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                         | 1         | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller            | 1         | 1.79%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]             | 1         | 1.79%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]              | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 42.5%   |
| Intel + Nvidia | 11        | 27.5%   |
| 1 x AMD        | 6         | 15%     |
| AMD + Nvidia   | 4         | 10%     |
| 2 x AMD        | 1         | 2.5%    |
| 1 x Nvidia     | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 90%     |
| Proprietary | 4         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 56.1%   |
| 0.01-0.5   | 8         | 19.51%  |
| 1.01-2.0   | 5         | 12.2%   |
| 3.01-4.0   | 4         | 9.76%   |
| 0.51-1.0   | 1         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 10        | 19.23%  |
| LG Display          | 7         | 13.46%  |
| Dell                | 5         | 9.62%   |
| Sharp               | 4         | 7.69%   |
| Chimei Innolux      | 4         | 7.69%   |
| BOE                 | 4         | 7.69%   |
| Samsung Electronics | 3         | 5.77%   |
| PANDA               | 3         | 5.77%   |
| InfoVision          | 2         | 3.85%   |
| Philips             | 1         | 1.92%   |
| Panasonic           | 1         | 1.92%   |
| Lenovo              | 1         | 1.92%   |
| JDI                 | 1         | 1.92%   |
| Hewlett-Packard     | 1         | 1.92%   |
| Eizo                | 1         | 1.92%   |
| ASUSTek Computer    | 1         | 1.92%   |
| Apple               | 1         | 1.92%   |
| AOC                 | 1         | 1.92%   |
| Acer                | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                 | 2         | 3.85%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch    | 2         | 3.85%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch           | 1         | 1.92%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch           | 1         | 1.92%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch           | 1         | 1.92%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch           | 1         | 1.92%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch | 1         | 1.92%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch | 1         | 1.92%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch | 1         | 1.92%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch          | 1         | 1.92%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch           | 1         | 1.92%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch           | 1         | 1.92%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch           | 1         | 1.92%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch      | 1         | 1.92%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch      | 1         | 1.92%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch      | 1         | 1.92%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch       | 1         | 1.92%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch      | 1         | 1.92%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch      | 1         | 1.92%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch      | 1         | 1.92%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch             | 1         | 1.92%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch      | 1         | 1.92%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch       | 1         | 1.92%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch         | 1         | 1.92%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                   | 1         | 1.92%   |
| Dell U2717D DEL40EB 2560x1440 600x340mm 27.2-inch                 | 1         | 1.92%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                 | 1         | 1.92%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                 | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch  | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch  | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch  | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch  | 1         | 1.92%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 1         | 1.92%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch             | 1         | 1.92%   |
| BOE LCD Monitor BOE093F 1920x1080 344x194mm 15.5-inch             | 1         | 1.92%   |
| BOE LCD Monitor BOE08D8 1920x1080 344x194mm 15.5-inch             | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch    | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch    | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 46.94%  |
| 3840x2160 (4K)    | 8         | 16.33%  |
| 2560x1440 (QHD)   | 7         | 14.29%  |
| 1366x768 (WXGA)   | 4         | 8.16%   |
| 3840x2400         | 1         | 2.04%   |
| 3440x1440         | 1         | 2.04%   |
| 2880x1800         | 1         | 2.04%   |
| 2560x1600         | 1         | 2.04%   |
| 2256x1504         | 1         | 2.04%   |
| 1920x1200 (WUXGA) | 1         | 2.04%   |
| 1280x1024 (SXGA)  | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 25%     |
| 13     | 10        | 19.23%  |
| 14     | 9         | 17.31%  |
| 27     | 6         | 11.54%  |
| 12     | 4         | 7.69%   |
| 24     | 3         | 5.77%   |
| 17     | 3         | 5.77%   |
| 23     | 2         | 3.85%   |
| 34     | 1         | 1.92%   |
| 31     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 49.02%  |
| 201-300     | 11        | 21.57%  |
| 501-600     | 10        | 19.61%  |
| 601-700     | 2         | 3.92%   |
| 351-400     | 2         | 3.92%   |
| 701-800     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 82.5%   |
| 16/10 | 4         | 10%     |
| 5/4   | 1         | 2.5%    |
| 3/2   | 1         | 2.5%    |
| 21/9  | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 25%     |
| 101-110        | 13        | 25%     |
| 71-80          | 6         | 11.54%  |
| 301-350        | 6         | 11.54%  |
| 201-250        | 5         | 9.62%   |
| 61-70          | 4         | 7.69%   |
| 351-500        | 2         | 3.85%   |
| 121-130        | 2         | 3.85%   |
| 141-150        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 42.55%  |
| 161-240       | 13        | 27.66%  |
| More than 240 | 5         | 10.64%  |
| 51-100        | 5         | 10.64%  |
| 101-120       | 4         | 8.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 65.12%  |
| 2     | 12        | 27.91%  |
| 0     | 2         | 4.65%   |
| 3     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 36        | 58.06%  |
| Realtek Semiconductor             | 21        | 33.87%  |
| Qualcomm                          | 1         | 1.61%   |
| Microsoft                         | 1         | 1.61%   |
| FIBOCOM                           | 1         | 1.61%   |
| Ericsson Business Mobile Networks | 1         | 1.61%   |
| Broadcom                          | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 15.19%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 13.92%  |
| Intel Wi-Fi 6 AX200                                               | 9         | 11.39%  |
| Intel Wireless-AC 9260                                            | 3         | 3.8%    |
| Intel Wireless 8260                                               | 3         | 3.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 3.8%    |
| Intel Wireless 8265 / 8275                                        | 2         | 2.53%   |
| Intel Wireless 7265                                               | 2         | 2.53%   |
| Intel Wireless 7260                                               | 2         | 2.53%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.53%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.53%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.27%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 1.27%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 1.27%   |
| Intel Wireless 3165                                               | 1         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.27%   |
| FIBOCOM L830-EB                                                   | 1         | 1.27%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 1.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 36        | 85.71%  |
| Realtek Semiconductor             | 1         | 2.38%   |
| Qualcomm                          | 1         | 2.38%   |
| Microsoft                         | 1         | 2.38%   |
| FIBOCOM                           | 1         | 2.38%   |
| Ericsson Business Mobile Networks | 1         | 2.38%   |
| Broadcom                          | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                      | 9         | 21.43%  |
| Intel Wireless-AC 9260                                   | 3         | 7.14%   |
| Intel Wireless 8260                                      | 3         | 7.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 3         | 7.14%   |
| Intel Wireless 8265 / 8275                               | 2         | 4.76%   |
| Intel Wireless 7265                                      | 2         | 4.76%   |
| Intel Wireless 7260                                      | 2         | 4.76%   |
| Intel Wi-Fi 6 AX201                                      | 2         | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 2         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 2         | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                          | 2         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 2.38%   |
| Qualcomm QCA6390 Wireless Network Adapter                | 1         | 2.38%   |
| Microsoft Xbox 360 Wireless Adapter                      | 1         | 2.38%   |
| Intel Wireless 3165                                      | 1         | 2.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 1         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]             | 1         | 2.38%   |
| FIBOCOM L830-EB                                          | 1         | 2.38%   |
| Ericsson Business Mobile Networks N5321 gw               | 1         | 2.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC              | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 60.61%  |
| Intel                 | 13        | 39.39%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 32.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 29.73%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.41%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.41%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 5.41%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 5.41%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 55.71%  |
| Ethernet | 31        | 44.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 78.72%  |
| Ethernet | 10        | 21.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 57.5%   |
| 1     | 16        | 40%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 87.5%   |
| Yes  | 5         | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 94.44%  |
| Realtek Semiconductor | 1         | 2.78%   |
| Apple                 | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 25%     |
| Intel AX200 Bluetooth                          | 9         | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 16.67%  |
| Intel AX201 Bluetooth                          | 4         | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 5.56%   |
| Realtek Bluetooth Radio                        | 1         | 2.78%   |
| Intel AX210 Bluetooth                          | 1         | 2.78%   |
| Apple Bluetooth Host Controller                | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 52.63%  |
| AMD                   | 11        | 19.3%   |
| Nvidia                | 5         | 8.77%   |
| Synaptics             | 2         | 3.51%   |
| Realtek Semiconductor | 2         | 3.51%   |
| Trust                 | 1         | 1.75%   |
| Satechi               | 1         | 1.75%   |
| Lenovo                | 1         | 1.75%   |
| Kingston Technology   | 1         | 1.75%   |
| DSEA A/S              | 1         | 1.75%   |
| Corsair               | 1         | 1.75%   |
| C-Media Electronics   | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 10        | 14.29%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 9         | 12.86%  |
| Intel Sunrise Point-LP HD Audio                                         | 6         | 8.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 5         | 7.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 4         | 5.71%   |
| Intel Cannon Lake PCH cAVS                                              | 3         | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 3         | 4.29%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 2.86%   |
| Realtek Semiconductor USB Audio                                         | 2         | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 2         | 2.86%   |
| Trust USB microphone                                                    | 1         | 1.43%   |
| Satechi Audio & PD Adapter                                              | 1         | 1.43%   |
| Nvidia GK106 HDMI Audio Controller                                      | 1         | 1.43%   |
| Nvidia GA106 High Definition Audio Controller                           | 1         | 1.43%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 1.43%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 1.43%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1         | 1.43%   |
| Intel CM238 HD Audio Controller                                         | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 1         | 1.43%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 1.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 1         | 1.43%   |
| DSEA A/S Headset [PC 8]                                                 | 1         | 1.43%   |
| Corsair HS70 Pro Wireless Gaming Headset                                | 1         | 1.43%   |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.43%   |
| AMD Navi 10 HDMI Audio                                                  | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 34.04%  |
| Micron Technology   | 9         | 19.15%  |
| Crucial             | 6         | 12.77%  |
| SK hynix            | 4         | 8.51%   |
| Kingston            | 4         | 8.51%   |
| Unknown             | 2         | 4.26%   |
| Unknown (ABCD)      | 1         | 2.13%   |
| Goodram             | 1         | 2.13%   |
| G.Skill             | 1         | 2.13%   |
| Corsair             | 1         | 2.13%   |
| Avant               | 1         | 2.13%   |
| AMD                 | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 3.92%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 3.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 3.92%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 2         | 3.92%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.96%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s    | 1         | 1.96%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.96%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.96%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 1.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.96%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 1.96%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.96%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.96%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                      | 1         | 1.96%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.96%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.96%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 1.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.96%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.96%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.96%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s             | 1         | 1.96%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.96%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 1         | 1.96%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 1         | 1.96%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.96%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 1         | 1.96%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.96%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.96%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.96%   |
| Kingston RAM 9905711-035.A00G 8GB SODIMM DDR4 3200MT/s              | 1         | 1.96%   |
| Goodram RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.96%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.96%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 64.1%   |
| LPDDR4 | 7         | 17.95%  |
| DDR3   | 6         | 15.38%  |
| LPDDR3 | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 80%     |
| Row Of Chips | 6         | 15%     |
| Chip         | 1         | 2.5%    |
| Unknown      | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 40.48%  |
| 16384 | 15        | 35.71%  |
| 4096  | 6         | 14.29%  |
| 32768 | 3         | 7.14%   |
| 2048  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 27.5%   |
| 2667  | 10        | 25%     |
| 1600  | 6         | 15%     |
| 2133  | 5         | 12.5%   |
| 4267  | 4         | 10%     |
| 4266  | 2         | 5%      |
| 2400  | 2         | 5%      |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 30.56%  |
| Microdia                      | 6         | 16.67%  |
| IMC Networks                  | 6         | 16.67%  |
| Acer                          | 5         | 13.89%  |
| Sunplus Innovation Technology | 3         | 8.33%   |
| Realtek Semiconductor         | 1         | 2.78%   |
| Quanta                        | 1         | 2.78%   |
| Logitech                      | 1         | 2.78%   |
| Lite-On Technology            | 1         | 2.78%   |
| 2M UVC CAMERA                 | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Chicony Integrated Camera           | 7         | 18.42%  |
| Microdia Integrated_Webcam_HD       | 4         | 10.53%  |
| IMC Networks USB2.0 HD UVC WebCam   | 3         | 7.89%   |
| IMC Networks Integrated Camera      | 3         | 7.89%   |
| Chicony HP HD Camera                | 3         | 7.89%   |
| Sunplus Integrated_Webcam_FHD       | 2         | 5.26%   |
| Acer Integrated IR Camera           | 2         | 5.26%   |
| Acer Integrated Camera              | 2         | 5.26%   |
| Sunplus Integrated_Webcam_HD        | 1         | 2.63%   |
| Realtek Laptop Camera               | 1         | 2.63%   |
| Quanta HD WebCam                    | 1         | 2.63%   |
| Microdia USB 2.0 Camera             | 1         | 2.63%   |
| Microdia Integrated Webcam          | 1         | 2.63%   |
| Logitech Webcam C310                | 1         | 2.63%   |
| Lite-On HP HD Camera                | 1         | 2.63%   |
| Chicony USB2.0 Camera               | 1         | 2.63%   |
| Acer ThinkPad P50 Integrated Camera | 1         | 2.63%   |
| Acer SunplusIT Integrated Camera    | 1         | 2.63%   |
| Acer HD Webcam                      | 1         | 2.63%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Validity Sensors           | 4         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 8.33%   |
| Unknown                                           | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 80%     |
| Yubico.com  | 1         | 10%     |
| Broadcom    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 8         | 80%     |
| Yubico.com Yubikey 4/5 U2F+CCID                | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 16        | 39.02%  |
| 1     | 15        | 36.59%  |
| 2     | 9         | 21.95%  |
| 4     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 27.03%  |
| Graphics card            | 8         | 21.62%  |
| Chipcard                 | 8         | 21.62%  |
| Multimedia controller    | 5         | 13.51%  |
| Network                  | 1         | 2.7%    |
| Net/wireless             | 1         | 2.7%    |
| Modem                    | 1         | 2.7%    |
| Communication controller | 1         | 2.7%    |
| Camera                   | 1         | 2.7%    |
| Bluetooth                | 1         | 2.7%    |

