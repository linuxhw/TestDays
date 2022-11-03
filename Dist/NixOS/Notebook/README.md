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

Total: 63

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Dell          | Precision 5760              | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Dell          | XPS 13 9310                 | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
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
| NixOS 22.05                      | 18        | 36.73%  |
| NixOS 21.11                      | 9         | 18.37%  |
| NixOS 22.11                      | 8         | 16.33%  |
| NixOS                            | 2         | 4.08%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 2.04%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 2.04%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 2.04%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 2.04%   |
| NixOS 21.05.2132.733682c3292     | 1         | 2.04%   |
| NixOS 21.05.20210423.c21475e     | 1         | 2.04%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 2.04%   |
| NixOS 20.09pre-git               | 1         | 2.04%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 2.04%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 2.04%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 2.04%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.15.43         | 3         | 5.77%   |
| 5.16.15         | 2         | 3.85%   |
| 5.15.74         | 2         | 3.85%   |
| 5.15.72         | 2         | 3.85%   |
| 5.15.68         | 2         | 3.85%   |
| 5.15.64         | 2         | 3.85%   |
| 5.15.26         | 2         | 3.85%   |
| 5.13.7          | 2         | 3.85%   |
| 6.0.0-xanmod1   | 1         | 1.92%   |
| 5.8.4           | 1         | 1.92%   |
| 5.8.16-hardened | 1         | 1.92%   |
| 5.8.11          | 1         | 1.92%   |
| 5.7.4           | 1         | 1.92%   |
| 5.7.17          | 1         | 1.92%   |
| 5.4.24          | 1         | 1.92%   |
| 5.4.209         | 1         | 1.92%   |
| 5.4.187         | 1         | 1.92%   |
| 5.19.0          | 1         | 1.92%   |
| 5.18.7-zen1     | 1         | 1.92%   |
| 5.18.0          | 1         | 1.92%   |
| 5.17.1          | 1         | 1.92%   |
| 5.17.0          | 1         | 1.92%   |
| 5.16.8-zen1     | 1         | 1.92%   |
| 5.16.7          | 1         | 1.92%   |
| 5.16.3          | 1         | 1.92%   |
| 5.16.10         | 1         | 1.92%   |
| 5.15.71         | 1         | 1.92%   |
| 5.15.59         | 1         | 1.92%   |
| 5.15.55         | 1         | 1.92%   |
| 5.15.4          | 1         | 1.92%   |
| 5.15.32         | 1         | 1.92%   |
| 5.15.3          | 1         | 1.92%   |
| 5.15.25         | 1         | 1.92%   |
| 5.15.22         | 1         | 1.92%   |
| 5.15.12         | 1         | 1.92%   |
| 5.15.0          | 1         | 1.92%   |
| 5.13.2          | 1         | 1.92%   |
| 5.12.7          | 1         | 1.92%   |
| 5.10.69         | 1         | 1.92%   |
| 5.10.30         | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.43 | 3         | 5.77%   |
| 5.16.15 | 2         | 3.85%   |
| 5.15.74 | 2         | 3.85%   |
| 5.15.72 | 2         | 3.85%   |
| 5.15.68 | 2         | 3.85%   |
| 5.15.64 | 2         | 3.85%   |
| 5.15.26 | 2         | 3.85%   |
| 5.13.7  | 2         | 3.85%   |
| 6.0.0   | 1         | 1.92%   |
| 5.8.4   | 1         | 1.92%   |
| 5.8.16  | 1         | 1.92%   |
| 5.8.11  | 1         | 1.92%   |
| 5.7.4   | 1         | 1.92%   |
| 5.7.17  | 1         | 1.92%   |
| 5.4.24  | 1         | 1.92%   |
| 5.4.209 | 1         | 1.92%   |
| 5.4.187 | 1         | 1.92%   |
| 5.19.0  | 1         | 1.92%   |
| 5.18.7  | 1         | 1.92%   |
| 5.18.0  | 1         | 1.92%   |
| 5.17.1  | 1         | 1.92%   |
| 5.17.0  | 1         | 1.92%   |
| 5.16.8  | 1         | 1.92%   |
| 5.16.7  | 1         | 1.92%   |
| 5.16.3  | 1         | 1.92%   |
| 5.16.10 | 1         | 1.92%   |
| 5.15.71 | 1         | 1.92%   |
| 5.15.59 | 1         | 1.92%   |
| 5.15.55 | 1         | 1.92%   |
| 5.15.4  | 1         | 1.92%   |
| 5.15.32 | 1         | 1.92%   |
| 5.15.3  | 1         | 1.92%   |
| 5.15.25 | 1         | 1.92%   |
| 5.15.22 | 1         | 1.92%   |
| 5.15.12 | 1         | 1.92%   |
| 5.15.0  | 1         | 1.92%   |
| 5.13.2  | 1         | 1.92%   |
| 5.12.7  | 1         | 1.92%   |
| 5.10.69 | 1         | 1.92%   |
| 5.10.30 | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 22        | 44%     |
| 5.16    | 6         | 12%     |
| 5.8     | 3         | 6%      |
| 5.13    | 3         | 6%      |
| 5.10    | 3         | 6%      |
| 5.7     | 2         | 4%      |
| 5.4     | 2         | 4%      |
| 5.18    | 2         | 4%      |
| 5.17    | 2         | 4%      |
| 4.19    | 2         | 4%      |
| 6.0     | 1         | 2%      |
| 5.19    | 1         | 2%      |
| 5.12    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 34        | 73.91%  |
| GNOME       | 3         | 6.52%   |
| XFCE        | 2         | 4.35%   |
| sway        | 2         | 4.35%   |
| none+xmonad | 2         | 4.35%   |
| none+i3     | 1         | 2.17%   |
| KDE5        | 1         | 2.17%   |
| KDE         | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 70.21%  |
| X11     | 7         | 14.89%  |
| Wayland | 6         | 12.77%  |
| Tty     | 1         | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 37        | 82.22%  |
| LightDM | 3         | 6.67%   |
| GDM     | 3         | 6.67%   |
| SDDM    | 2         | 4.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 63.64%  |
| en_US   | 12        | 27.27%  |
| ru_RU   | 1         | 2.27%   |
| ro_RO   | 1         | 2.27%   |
| en_GB   | 1         | 2.27%   |
| en_DK   | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 37        | 84.09%  |
| BIOS | 7         | 15.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 26        | 56.52%  |
| Btrfs   | 8         | 17.39%  |
| Tmpfs   | 5         | 10.87%  |
| Unknown | 3         | 6.52%   |
| Zfs     | 2         | 4.35%   |
| Xfs     | 2         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 41        | 89.13%  |
| Unknown | 5         | 10.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 73.33%  |
| Yes       | 12        | 26.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 77.27%  |
| Yes       | 10        | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 40.91%  |
| Dell                | 9         | 20.45%  |
| ASUSTek Computer    | 5         | 11.36%  |
| Hewlett-Packard     | 4         | 9.09%   |
| Toshiba             | 1         | 2.27%   |
| OBSIDIAN-PC         | 1         | 2.27%   |
| MSI                 | 1         | 2.27%   |
| GPD                 | 1         | 2.27%   |
| Gigabyte Technology | 1         | 2.27%   |
| Framework           | 1         | 2.27%   |
| Apple               | 1         | 2.27%   |
| Acer                | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Latitude 7420                    | 2         | 4.55%   |
| Toshiba Satellite L50-B               | 1         | 2.27%   |
| OBSIDIAN-PC N13_N140ZU                | 1         | 2.27%   |
| MSI Bravo 15 B5DD                     | 1         | 2.27%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 2.27%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 2.27%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 2.27%   |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 2.27%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 2.27%   |
| Lenovo ThinkPad X230 23243E9          | 1         | 2.27%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW | 1         | 2.27%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 2.27%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 2.27%   |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 2.27%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 2.27%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 2.27%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 2.27%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 2.27%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 2.27%   |
| Lenovo ThinkPad E470 20H1006JIX       | 1         | 2.27%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 2.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 1         | 2.27%   |
| HP ZBook Studio G5                    | 1         | 2.27%   |
| HP ProBook 450 G4                     | 1         | 2.27%   |
| HP ProBook 445 G7                     | 1         | 2.27%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 2.27%   |
| GPD MicroPC                           | 1         | 2.27%   |
| Gigabyte Sabre 15                     | 1         | 2.27%   |
| Framework Laptop                      | 1         | 2.27%   |
| Dell XPS 15 9570                      | 1         | 2.27%   |
| Dell XPS 15 9550                      | 1         | 2.27%   |
| Dell XPS 13 9310                      | 1         | 2.27%   |
| Dell XPS 13 9305                      | 1         | 2.27%   |
| Dell Precision M4800                  | 1         | 2.27%   |
| Dell Precision 5760                   | 1         | 2.27%   |
| Dell Inspiron 15 7510                 | 1         | 2.27%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 2.27%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 2.27%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 2.27%   |
| ASUS ROG Flow X13 GV301QE_GV301QE     | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 15        | 34.09%  |
| Dell XPS           | 4         | 9.09%   |
| ASUS ROG           | 3         | 6.82%   |
| HP ProBook         | 2         | 4.55%   |
| Dell Precision     | 2         | 4.55%   |
| Dell Latitude      | 2         | 4.55%   |
| Toshiba Satellite  | 1         | 2.27%   |
| OBSIDIAN-PC N13    | 1         | 2.27%   |
| MSI Bravo          | 1         | 2.27%   |
| Lenovo Yoga        | 1         | 2.27%   |
| Lenovo Legion      | 1         | 2.27%   |
| Lenovo IdeaPad     | 1         | 2.27%   |
| HP ZBook           | 1         | 2.27%   |
| HP EliteBook       | 1         | 2.27%   |
| GPD MicroPC        | 1         | 2.27%   |
| Gigabyte Sabre     | 1         | 2.27%   |
| Framework Laptop   | 1         | 2.27%   |
| Dell Inspiron      | 1         | 2.27%   |
| ASUS ZenBook       | 1         | 2.27%   |
| ASUS ASUSPRO       | 1         | 2.27%   |
| Apple MacBookPro11 | 1         | 2.27%   |
| Acer Aspire        | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 22.73%  |
| 2020 | 10        | 22.73%  |
| 2018 | 6         | 13.64%  |
| 2016 | 6         | 13.64%  |
| 2019 | 4         | 9.09%   |
| 2017 | 2         | 4.55%   |
| 2015 | 2         | 4.55%   |
| 2013 | 2         | 4.55%   |
| 2014 | 1         | 2.27%   |
| 2012 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 44        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 97.78%  |
| Enabled  | 1         | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 97.73%  |
| Yes  | 1         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 15        | 33.33%  |
| 16.01-24.0  | 13        | 28.89%  |
| 8.01-16.0   | 11        | 24.44%  |
| 4.01-8.0    | 3         | 6.67%   |
| 3.01-4.0    | 1         | 2.22%   |
| 24.01-32.0  | 1         | 2.22%   |
| 64.01-256.0 | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 29.41%  |
| 3.01-4.0   | 10        | 19.61%  |
| 8.01-16.0  | 9         | 17.65%  |
| 2.01-3.0   | 8         | 15.69%  |
| 24.01-32.0 | 4         | 7.84%   |
| 1.01-2.0   | 2         | 3.92%   |
| 0.51-1.0   | 2         | 3.92%   |
| 32.01-64.0 | 1         | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 80%     |
| 2      | 9         | 20%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 93.18%  |
| Yes       | 3         | 6.82%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 71.74%  |
| No        | 13        | 28.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 97.73%  |
| No        | 1         | 2.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 84.78%  |
| No        | 7         | 15.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 5         | 11.36%  |
| France      | 5         | 11.36%  |
| USA         | 3         | 6.82%   |
| Ukraine     | 3         | 6.82%   |
| Russia      | 3         | 6.82%   |
| Poland      | 3         | 6.82%   |
| Canada      | 3         | 6.82%   |
| Italy       | 2         | 4.55%   |
| Germany     | 2         | 4.55%   |
| Belgium     | 2         | 4.55%   |
| Uruguay     | 1         | 2.27%   |
| Switzerland | 1         | 2.27%   |
| Sweden      | 1         | 2.27%   |
| Spain       | 1         | 2.27%   |
| Romania     | 1         | 2.27%   |
| Portugal    | 1         | 2.27%   |
| Netherlands | 1         | 2.27%   |
| Iraq        | 1         | 2.27%   |
| Iran        | 1         | 2.27%   |
| India       | 1         | 2.27%   |
| Czechia     | 1         | 2.27%   |
| Colombia    | 1         | 2.27%   |
| Austria     | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Marki              | 2         | 4.26%   |
| London             | 2         | 4.26%   |
| Halifax            | 2         | 4.26%   |
| Woodford           | 1         | 2.13%   |
| Villeurbanne       | 1         | 2.13%   |
| Vienna             | 1         | 2.13%   |
| Verneuil-sur-Seine | 1         | 2.13%   |
| Valpacos           | 1         | 2.13%   |
| Tottenham          | 1         | 2.13%   |
| Tolyatti           | 1         | 2.13%   |
| Tehran             | 1         | 2.13%   |
| Stockholm          | 1         | 2.13%   |
| South Deerfield    | 1         | 2.13%   |
| Saratov            | 1         | 2.13%   |
| Rho                | 1         | 2.13%   |
| Prague             | 1         | 2.13%   |
| Plymouth           | 1         | 2.13%   |
| Ottawa             | 1         | 2.13%   |
| Nantes             | 1         | 2.13%   |
| Mykolayiv          | 1         | 2.13%   |
| Montevideo         | 1         | 2.13%   |
| Mons               | 1         | 2.13%   |
| Milwaukee          | 1         | 2.13%   |
| Melsele            | 1         | 2.13%   |
| Lyon               | 1         | 2.13%   |
| Lehrte             | 1         | 2.13%   |
| Krakow             | 1         | 2.13%   |
| Kiel               | 1         | 2.13%   |
| Kharkiv            | 1         | 2.13%   |
| Islington          | 1         | 2.13%   |
| Irpin              | 1         | 2.13%   |
| Gurgaon            | 1         | 2.13%   |
| Getafe             | 1         | 2.13%   |
| Enschede           | 1         | 2.13%   |
| Cluj-Napoca        | 1         | 2.13%   |
| Chelyabinsk        | 1         | 2.13%   |
| Champaign          | 1         | 2.13%   |
| Cergy              | 1         | 2.13%   |
| Catania            | 1         | 2.13%   |
| Cartagena          | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 23     | 34.62%  |
| WDC                 | 6         | 6      | 11.54%  |
| SK hynix            | 4         | 5      | 7.69%   |
| Toshiba             | 3         | 3      | 5.77%   |
| Kingston            | 3         | 3      | 5.77%   |
| Crucial             | 3         | 4      | 5.77%   |
| Transcend           | 2         | 2      | 3.85%   |
| Seagate             | 2         | 2      | 3.85%   |
| Sandisk             | 2         | 2      | 3.85%   |
| Micron Technology   | 2         | 2      | 3.85%   |
| KIOXIA              | 2         | 3      | 3.85%   |
| Intel               | 1         | 1      | 1.92%   |
| INNOVATION IT       | 1         | 1      | 1.92%   |
| HGST                | 1         | 1      | 1.92%   |
| BIWIN               | 1         | 1      | 1.92%   |
| Apple               | 1         | 3      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung PM9A1 NVMe 1024GB                           | 2         | 3.7%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 1.85%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 1.85%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 1.85%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 1.85%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                  | 1         | 1.85%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                | 1         | 1.85%   |
| Transcend TS256GMTS800 256GB SSD                    | 1         | 1.85%   |
| Transcend TS256GMTS430S 256GB SSD                   | 1         | 1.85%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.85%   |
| Toshiba KXG6AZNV512G 512GB                          | 1         | 1.85%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 1.85%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 1         | 1.85%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 1.85%   |
| SK hynix NVMe SSD Drive 1TB                         | 1         | 1.85%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 1.85%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 1.85%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.85%   |
| Sandisk WD Black SN850 1TB                          | 1         | 1.85%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 1         | 1.85%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1         | 1.85%   |
| Samsung SSD 970 EVO 500GB                           | 1         | 1.85%   |
| Samsung SSD 870 EVO 500GB                           | 1         | 1.85%   |
| Samsung SSD 860 EVO 250GB                           | 1         | 1.85%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.85%   |
| Samsung SSD 850 EVO 500GB                           | 1         | 1.85%   |
| Samsung Portable SSD T5 500GB                       | 1         | 1.85%   |
| Samsung PM991a NVMe 512GB                           | 1         | 1.85%   |
| Samsung NVMe SSD Drive 512GB                        | 1         | 1.85%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 1.85%   |
| Samsung MZVLB512HAJQ-000H1 512GB                    | 1         | 1.85%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 1.85%   |
| Samsung MZVLB256HAHQ-000L7 256GB                    | 1         | 1.85%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 1         | 1.85%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 1         | 1.85%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD                | 1         | 1.85%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD                | 1         | 1.85%   |
| Micron MTFDHBA512TDV 512GB                          | 1         | 1.85%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 1.85%   |

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
| Samsung Electronics | 7         | 7      | 41.18%  |
| Transcend           | 2         | 2      | 11.76%  |
| Crucial             | 2         | 3      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| INNOVATION IT       | 1         | 1      | 5.88%   |
| BIWIN               | 1         | 1      | 5.88%   |
| Apple               | 1         | 3      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 38     | 61.22%  |
| SSD  | 15        | 20     | 30.61%  |
| HDD  | 4         | 4      | 8.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 38     | 63.83%  |
| SATA | 16        | 23     | 34.04%  |
| SAS  | 1         | 1      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 15     | 60%     |
| 0.51-1.0   | 7         | 8      | 35%     |
| 1.01-2.0   | 1         | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 29        | 64.44%  |
| 1-20           | 6         | 13.33%  |
| 251-500        | 2         | 4.44%   |
| 2001-3000      | 2         | 4.44%   |
| 101-250        | 2         | 4.44%   |
| 501-1000       | 2         | 4.44%   |
| More than 3000 | 1         | 2.22%   |
| 1001-2000      | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 29        | 64.44%  |
| 1-20      | 7         | 15.56%  |
| 101-250   | 5         | 11.11%  |
| 251-500   | 1         | 2.22%   |
| 1001-2000 | 1         | 2.22%   |
| 501-1000  | 1         | 2.22%   |
| 51-100    | 1         | 2.22%   |

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
| Works    | 41        | 52     | 83.67%  |
| Detected | 5         | 7      | 10.2%   |
| Malfunc  | 3         | 3      | 6.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 37.5%   |
| Samsung Electronics          | 13        | 23.21%  |
| SanDisk                      | 7         | 12.5%   |
| SK hynix                     | 4         | 7.14%   |
| Toshiba America Info Systems | 3         | 5.36%   |
| AMD                          | 3         | 5.36%   |
| Kingston Technology Company  | 2         | 3.57%   |
| Micron/Crucial Technology    | 1         | 1.79%   |
| Micron Technology            | 1         | 1.79%   |
| KIOXIA                       | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 8.93%   |
| SK hynix Gold P31 SSD                                                            | 4         | 7.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 5.36%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 5.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 3.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 3.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.57%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 3.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.57%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.79%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.79%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.79%   |
| Samsung Electronics SATA controller                                              | 1         | 1.79%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 1.79%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.79%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.79%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.79%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 30        | 55.56%  |
| SATA | 21        | 38.89%  |
| RAID | 3         | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 75%     |
| AMD    | 11        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 6.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 6.82%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 6.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 6.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 4.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 4.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 4.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 4.55%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 4.55%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 2.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 2.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 2.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 2.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 2.27%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 2.27%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 2.27%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 2.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 2.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 1         | 2.27%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 2.27%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 2.27%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz    | 1         | 2.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 1         | 2.27%   |
| AMD Ryzen 9 5900HS with Radeon Graphics    | 1         | 2.27%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics | 1         | 2.27%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 1         | 2.27%   |
| AMD Ryzen 7 5800HS with Radeon Graphics    | 1         | 2.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 1         | 2.27%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 19        | 43.18%  |
| Other           | 7         | 15.91%  |
| AMD Ryzen 7     | 7         | 15.91%  |
| Intel Core i5   | 4         | 9.09%   |
| AMD Ryzen 7 PRO | 3         | 6.82%   |
| Intel Xeon      | 1         | 2.27%   |
| Intel Core i3   | 1         | 2.27%   |
| Intel Celeron   | 1         | 2.27%   |
| AMD Ryzen 9     | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 20        | 45.45%  |
| 8      | 13        | 29.55%  |
| 2      | 8         | 18.18%  |
| 6      | 3         | 6.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 95.45%  |
| 1      | 2         | 4.55%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 97.78%  |
| Unknown        | 1         | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 6         | 13.33%  |
| Unknown    | 6         | 13.33%  |
| 0x806c1    | 4         | 8.89%   |
| 0x806ec    | 3         | 6.67%   |
| 0x806ea    | 3         | 6.67%   |
| 0x08600106 | 3         | 6.67%   |
| 0x906ea    | 2         | 4.44%   |
| 0x806eb    | 2         | 4.44%   |
| 0x806e9    | 2         | 4.44%   |
| 0x406e3    | 2         | 4.44%   |
| 0x306d4    | 2         | 4.44%   |
| 0x306c3    | 2         | 4.44%   |
| 0x906e9    | 1         | 2.22%   |
| 0x806d1    | 1         | 2.22%   |
| 0x706a1    | 1         | 2.22%   |
| 0x506e3    | 1         | 2.22%   |
| 0x40661    | 1         | 2.22%   |
| 0x306a9    | 1         | 2.22%   |
| 0x0a50000b | 1         | 2.22%   |
| 0x08600104 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 34.09%  |
| Zen 3         | 7         | 15.91%  |
| TigerLake     | 5         | 11.36%  |
| Zen 2         | 4         | 9.09%   |
| Skylake       | 4         | 9.09%   |
| Haswell       | 3         | 6.82%   |
| Broadwell     | 2         | 4.55%   |
| IvyBridge     | 1         | 2.27%   |
| Icelake       | 1         | 2.27%   |
| Goldmont plus | 1         | 2.27%   |
| Unknown       | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 49.21%  |
| Nvidia | 19        | 30.16%  |
| AMD    | 13        | 20.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                                           | 7         | 10.94%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 7.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 6.25%   |
| AMD Renoir                                                                            | 4         | 6.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 4.69%   |
| Intel UHD Graphics 620                                                                | 3         | 4.69%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 3.13%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 3.13%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 3.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 3.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.13%   |
| Intel HD Graphics 620                                                                 | 2         | 3.13%   |
| Intel HD Graphics 5500                                                                | 2         | 3.13%   |
| Intel HD Graphics 530                                                                 | 2         | 3.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 3.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.56%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 1.56%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.56%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 1.56%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 1.56%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                    | 1         | 1.56%   |
| Intel HD Graphics 630                                                                 | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 1.56%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 1         | 1.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                        | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 38.64%  |
| Intel + Nvidia | 13        | 29.55%  |
| 1 x AMD        | 6         | 13.64%  |
| AMD + Nvidia   | 5         | 11.36%  |
| 2 x AMD        | 1         | 2.27%   |
| 1 x Nvidia     | 1         | 2.27%   |
| Intel + AMD    | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 84.09%  |
| Proprietary | 6         | 13.64%  |
| Unknown     | 1         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 55.56%  |
| 0.01-0.5   | 8         | 17.78%  |
| 1.01-2.0   | 7         | 15.56%  |
| 3.01-4.0   | 4         | 8.89%   |
| 0.51-1.0   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 11        | 19.3%   |
| LG Display          | 8         | 14.04%  |
| Dell                | 6         | 10.53%  |
| Sharp               | 4         | 7.02%   |
| Samsung Electronics | 4         | 7.02%   |
| Chimei Innolux      | 4         | 7.02%   |
| BOE                 | 4         | 7.02%   |
| PANDA               | 3         | 5.26%   |
| InfoVision          | 2         | 3.51%   |
| Philips             | 1         | 1.75%   |
| Panasonic           | 1         | 1.75%   |
| Lenovo              | 1         | 1.75%   |
| JDI                 | 1         | 1.75%   |
| Hewlett-Packard     | 1         | 1.75%   |
| Eizo                | 1         | 1.75%   |
| CSO                 | 1         | 1.75%   |
| ASUSTek Computer    | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |
| AOC                 | 1         | 1.75%   |
| Acer                | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 3.51%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 3.51%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 1         | 1.75%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.75%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.75%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.75%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.75%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 1.75%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.75%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 1.75%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.75%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.75%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.75%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.75%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.75%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.75%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.75%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.75%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 1.75%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.75%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.75%   |
| Dell U2717D DEL40EB 2560x1440 600x340mm 27.2-inch                     | 1         | 1.75%   |
| Dell S3220DGF DELD0F2 2560x1440 697x392mm 31.5-inch                   | 1         | 1.75%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.75%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 1         | 1.75%   |
| CSO LCD Monitor CSO1601 2560x1600 345x215mm 16.0-inch                 | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 1         | 1.75%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.75%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch                 | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 46.3%   |
| 3840x2160 (4K)    | 8         | 14.81%  |
| 2560x1440 (QHD)   | 8         | 14.81%  |
| 1366x768 (WXGA)   | 5         | 9.26%   |
| 2560x1600         | 2         | 3.7%    |
| 3840x2400         | 1         | 1.85%   |
| 3440x1440         | 1         | 1.85%   |
| 2880x1800         | 1         | 1.85%   |
| 2256x1504         | 1         | 1.85%   |
| 1920x1200 (WUXGA) | 1         | 1.85%   |
| 1280x1024 (SXGA)  | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 24.56%  |
| 13     | 11        | 19.3%   |
| 14     | 9         | 15.79%  |
| 27     | 6         | 10.53%  |
| 12     | 4         | 7.02%   |
| 24     | 3         | 5.26%   |
| 17     | 3         | 5.26%   |
| 31     | 2         | 3.51%   |
| 23     | 2         | 3.51%   |
| 46     | 1         | 1.75%   |
| 34     | 1         | 1.75%   |
| 16     | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 50%     |
| 201-300     | 11        | 19.64%  |
| 501-600     | 10        | 17.86%  |
| 601-700     | 3         | 5.36%   |
| 351-400     | 2         | 3.57%   |
| 701-800     | 1         | 1.79%   |
| 1001-1500   | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 81.82%  |
| 16/10 | 5         | 11.36%  |
| 5/4   | 1         | 2.27%   |
| 3/2   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 24.56%  |
| 101-110        | 14        | 24.56%  |
| 71-80          | 6         | 10.53%  |
| 301-350        | 6         | 10.53%  |
| 201-250        | 5         | 8.77%   |
| 61-70          | 4         | 7.02%   |
| 351-500        | 3         | 5.26%   |
| 121-130        | 2         | 3.51%   |
| 141-150        | 1         | 1.75%   |
| 111-120        | 1         | 1.75%   |
| 501-1000       | 1         | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 41.18%  |
| 161-240       | 14        | 27.45%  |
| 51-100        | 6         | 11.76%  |
| More than 240 | 5         | 9.8%    |
| 101-120       | 4         | 7.84%   |
| 1-50          | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 29        | 61.7%   |
| 2     | 14        | 29.79%  |
| 0     | 3         | 6.38%   |
| 3     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 38        | 55.88%  |
| Realtek Semiconductor             | 23        | 33.82%  |
| Qualcomm Atheros                  | 1         | 1.47%   |
| Qualcomm                          | 1         | 1.47%   |
| Microsoft                         | 1         | 1.47%   |
| MediaTek                          | 1         | 1.47%   |
| FIBOCOM                           | 1         | 1.47%   |
| Ericsson Business Mobile Networks | 1         | 1.47%   |
| Broadcom                          | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 16.47%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 12.94%  |
| Intel Wi-Fi 6 AX200                                               | 9         | 10.59%  |
| Intel Wireless-AC 9260                                            | 3         | 3.53%   |
| Intel Wireless 8260                                               | 3         | 3.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 3.53%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.35%   |
| Intel Wireless 7265                                               | 2         | 2.35%   |
| Intel Wireless 7260                                               | 2         | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.35%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.35%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.35%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.35%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.18%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.18%   |
| Intel Wireless 3165                                               | 1         | 1.18%   |
| Intel Wireless 3160                                               | 1         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.18%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.18%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.18%   |
| FIBOCOM L830-EB                                                   | 1         | 1.18%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 84.44%  |
| Realtek Semiconductor | 1         | 2.22%   |
| Qualcomm Atheros      | 1         | 2.22%   |
| Qualcomm              | 1         | 2.22%   |
| Microsoft             | 1         | 2.22%   |
| MediaTek              | 1         | 2.22%   |
| FIBOCOM               | 1         | 2.22%   |
| Broadcom              | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 9         | 20%     |
| Intel Wireless-AC 9260                                        | 3         | 6.67%   |
| Intel Wireless 8260                                           | 3         | 6.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 3         | 6.67%   |
| Intel Wireless 8265 / 8275                                    | 2         | 4.44%   |
| Intel Wireless 7265                                           | 2         | 4.44%   |
| Intel Wireless 7260                                           | 2         | 4.44%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 4.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 4.44%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.22%   |
| Qualcomm QCA6390 Wireless Network Adapter                     | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.22%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.22%   |
| Intel Wireless 3165                                           | 1         | 2.22%   |
| Intel Wireless 3160                                           | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 2.22%   |
| FIBOCOM L830-EB                                               | 1         | 2.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 62.86%  |
| Intel                 | 13        | 37.14%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 35.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 28.21%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.13%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.13%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 5.13%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 5.13%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 55.84%  |
| Ethernet | 33        | 42.86%  |
| Modem    | 1         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 78.43%  |
| Ethernet | 11        | 21.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 56.82%  |
| 1     | 18        | 40.91%  |
| 3     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 86.67%  |
| Yes  | 6         | 13.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 89.74%  |
| Realtek Semiconductor           | 1         | 2.56%   |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| Foxconn / Hon Hai               | 1         | 2.56%   |
| Apple                           | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 23.08%  |
| Intel AX200 Bluetooth                          | 9         | 23.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 15.38%  |
| Intel AX201 Bluetooth                          | 5         | 12.82%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 5.13%   |
| Realtek Bluetooth Radio                        | 1         | 2.56%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 2.56%   |
| Intel AX210 Bluetooth                          | 1         | 2.56%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.56%   |
| Apple Bluetooth Host Controller                | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 33        | 50.77%  |
| AMD                       | 12        | 18.46%  |
| Nvidia                    | 6         | 9.23%   |
| Synaptics                 | 2         | 3.08%   |
| Realtek Semiconductor     | 2         | 3.08%   |
| C-Media Electronics       | 2         | 3.08%   |
| Trust                     | 1         | 1.54%   |
| Sennheiser Communications | 1         | 1.54%   |
| Satechi                   | 1         | 1.54%   |
| Lenovo                    | 1         | 1.54%   |
| Kingston Technology       | 1         | 1.54%   |
| Creative Technology       | 1         | 1.54%   |
| Corsair                   | 1         | 1.54%   |
| (LCS) USB Audio Device    | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 11        | 13.75%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 10        | 12.5%   |
| Intel Sunrise Point-LP HD Audio                                         | 7         | 8.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 5         | 6.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 4         | 5%      |
| Intel Cannon Lake PCH cAVS                                              | 3         | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 3         | 3.75%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 2.5%    |
| Realtek Semiconductor USB Audio                                         | 2         | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 2.5%    |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                                  | 2         | 2.5%    |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 2.5%    |
| Intel Broadwell-U Audio Controller                                      | 2         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 2         | 2.5%    |
| Trust USB microphone                                                    | 1         | 1.25%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 1.25%   |
| Satechi Audio & PD Adapter                                              | 1         | 1.25%   |
| Nvidia GK106 HDMI Audio Controller                                      | 1         | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                           | 1         | 1.25%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 1.25%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1         | 1.25%   |
| Intel CM238 HD Audio Controller                                         | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 1         | 1.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 1         | 1.25%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 1         | 1.25%   |
| Corsair HS70 Pro Wireless Gaming Headset                                | 1         | 1.25%   |
| C-Media Electronics BY-PM700                                            | 1         | 1.25%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                       | 1         | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.25%   |
| AMD Navi 10 HDMI Audio                                                  | 1         | 1.25%   |
| (LCS) USB Audio Device (LCS) USB Audio Device                           | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 39.22%  |
| Micron Technology   | 9         | 17.65%  |
| Crucial             | 6         | 11.76%  |
| SK hynix            | 4         | 7.84%   |
| Kingston            | 4         | 7.84%   |
| Unknown             | 2         | 3.92%   |
| Unknown (ABCD)      | 1         | 1.96%   |
| Goodram             | 1         | 1.96%   |
| G.Skill             | 1         | 1.96%   |
| Corsair             | 1         | 1.96%   |
| Avant               | 1         | 1.96%   |
| AMD                 | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 3.57%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 3.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 3.57%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 3.57%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 1         | 1.79%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.79%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB Row Of Chips LPDDR4 4266MT/s | 1         | 1.79%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.79%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 1.79%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 1.79%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 1.79%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 1         | 1.79%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                      | 1         | 1.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.79%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 1.79%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s                | 1         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 1.79%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s             | 1         | 1.79%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.79%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.79%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.79%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 65.12%  |
| LPDDR4 | 7         | 16.28%  |
| DDR3   | 7         | 16.28%  |
| LPDDR3 | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 79.55%  |
| Row Of Chips | 7         | 15.91%  |
| Chip         | 1         | 2.27%   |
| Unknown      | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 21        | 45.65%  |
| 16384 | 15        | 32.61%  |
| 4096  | 6         | 13.04%  |
| 32768 | 3         | 6.52%   |
| 2048  | 1         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 13        | 29.55%  |
| 2667  | 12        | 27.27%  |
| 1600  | 6         | 13.64%  |
| 2133  | 5         | 11.36%  |
| 4267  | 4         | 9.09%   |
| 4266  | 2         | 4.55%   |
| 2400  | 2         | 4.55%   |

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
| Chicony Electronics           | 12        | 31.58%  |
| Microdia                      | 7         | 18.42%  |
| IMC Networks                  | 6         | 15.79%  |
| Acer                          | 5         | 13.16%  |
| Sunplus Innovation Technology | 3         | 7.89%   |
| Realtek Semiconductor         | 1         | 2.63%   |
| Quanta                        | 1         | 2.63%   |
| Logitech                      | 1         | 2.63%   |
| Lite-On Technology            | 1         | 2.63%   |
| 2M UVC CAMERA                 | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Chicony Integrated Camera           | 8         | 20%     |
| Microdia Integrated_Webcam_HD       | 5         | 12.5%   |
| IMC Networks USB2.0 HD UVC WebCam   | 3         | 7.5%    |
| IMC Networks Integrated Camera      | 3         | 7.5%    |
| Chicony HP HD Camera                | 3         | 7.5%    |
| Sunplus Integrated_Webcam_FHD       | 2         | 5%      |
| Acer Integrated IR Camera           | 2         | 5%      |
| Acer Integrated Camera              | 2         | 5%      |
| Sunplus Integrated_Webcam_HD        | 1         | 2.5%    |
| Realtek Laptop Camera               | 1         | 2.5%    |
| Quanta HD WebCam                    | 1         | 2.5%    |
| Microdia USB 2.0 Camera             | 1         | 2.5%    |
| Microdia Integrated Webcam          | 1         | 2.5%    |
| Logitech Webcam C310                | 1         | 2.5%    |
| Lite-On HP HD Camera                | 1         | 2.5%    |
| Chicony USB2.0 Camera               | 1         | 2.5%    |
| Acer ThinkPad P50 Integrated Camera | 1         | 2.5%    |
| Acer SunplusIT Integrated Camera    | 1         | 2.5%    |
| Acer HD Webcam                      | 1         | 2.5%    |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 46.15%  |
| Validity Sensors           | 5         | 38.46%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 30.77%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 15.38%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 7.69%   |
| Unknown                                           | 1         | 7.69%   |

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
| 1     | 18        | 40%     |
| 0     | 16        | 35.56%  |
| 2     | 10        | 22.22%  |
| 4     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 26.83%  |
| Graphics card            | 10        | 24.39%  |
| Chipcard                 | 8         | 19.51%  |
| Multimedia controller    | 6         | 14.63%  |
| Network                  | 1         | 2.44%   |
| Net/wireless             | 1         | 2.44%   |
| Modem                    | 1         | 2.44%   |
| Communication controller | 1         | 2.44%   |
| Camera                   | 1         | 2.44%   |
| Bluetooth                | 1         | 2.44%   |

