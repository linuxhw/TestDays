Slackware 15.0 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware_15.0/Desktop/README.md) and [notebooks](/Dist/Slackware_15.0/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| HP            | 3031h                       | Desktop     | [b6849a29a2](https://linux-hardware.org/?probe=b6849a29a2) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| HP            | 3031h                       | Desktop     | [40160588bb](https://linux-hardware.org/?probe=40160588bb) | Sep 20, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [2299dc1786](https://linux-hardware.org/?probe=2299dc1786) | Sep 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a954ba4e86](https://linux-hardware.org/?probe=a954ba4e86) | Aug 26, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| Sony          | SVE1713A1EW                 | Notebook    | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [533b8a9f83](https://linux-hardware.org/?probe=533b8a9f83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | GE76 Raider 11UE            | Notebook    | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook      | X170KM-G                    | Notebook    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| Biostar       | X470GTA                     | Desktop     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 14        | 23.73%  |
| 5.15.27           | 4         | 6.78%   |
| 5.15.63           | 3         | 5.08%   |
| 5.17.2            | 2         | 3.39%   |
| 5.17.1            | 2         | 3.39%   |
| 5.16.13           | 2         | 3.39%   |
| 5.15.38           | 2         | 3.39%   |
| 5.15.30-Unraid    | 2         | 3.39%   |
| 5.13.8            | 2         | 3.39%   |
| 5.19.17           | 1         | 1.69%   |
| 5.17.5            | 1         | 1.69%   |
| 5.17.0-custom     | 1         | 1.69%   |
| 5.16.9-joe1       | 1         | 1.69%   |
| 5.16.18           | 1         | 1.69%   |
| 5.16.12           | 1         | 1.69%   |
| 5.16.11           | 1         | 1.69%   |
| 5.15.6            | 1         | 1.69%   |
| 5.15.37.a         | 1         | 1.69%   |
| 5.15.33.kjh       | 1         | 1.69%   |
| 5.15.21-hardened1 | 1         | 1.69%   |
| 5.15.14           | 1         | 1.69%   |
| 5.15.13           | 1         | 1.69%   |
| 5.15.1            | 1         | 1.69%   |
| 5.14.9            | 1         | 1.69%   |
| 5.14.8            | 1         | 1.69%   |
| 5.14.15-Unraid    | 1         | 1.69%   |
| 5.14.15           | 1         | 1.69%   |
| 5.14.12           | 1         | 1.69%   |
| 5.14.11           | 1         | 1.69%   |
| 5.14.10           | 1         | 1.69%   |
| 5.14.0            | 1         | 1.69%   |
| 5.13.5            | 1         | 1.69%   |
| 5.13.12           | 1         | 1.69%   |
| 5.13.11           | 1         | 1.69%   |
| 5.10.91           | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 14        | 23.73%  |
| 5.15.27 | 4         | 6.78%   |
| 5.15.63 | 3         | 5.08%   |
| 5.17.2  | 2         | 3.39%   |
| 5.17.1  | 2         | 3.39%   |
| 5.16.13 | 2         | 3.39%   |
| 5.15.38 | 2         | 3.39%   |
| 5.15.30 | 2         | 3.39%   |
| 5.14.15 | 2         | 3.39%   |
| 5.13.8  | 2         | 3.39%   |
| 5.19.17 | 1         | 1.69%   |
| 5.17.5  | 1         | 1.69%   |
| 5.17.0  | 1         | 1.69%   |
| 5.16.9  | 1         | 1.69%   |
| 5.16.18 | 1         | 1.69%   |
| 5.16.12 | 1         | 1.69%   |
| 5.16.11 | 1         | 1.69%   |
| 5.15.6  | 1         | 1.69%   |
| 5.15.37 | 1         | 1.69%   |
| 5.15.33 | 1         | 1.69%   |
| 5.15.21 | 1         | 1.69%   |
| 5.15.14 | 1         | 1.69%   |
| 5.15.13 | 1         | 1.69%   |
| 5.15.1  | 1         | 1.69%   |
| 5.14.9  | 1         | 1.69%   |
| 5.14.8  | 1         | 1.69%   |
| 5.14.12 | 1         | 1.69%   |
| 5.14.11 | 1         | 1.69%   |
| 5.14.10 | 1         | 1.69%   |
| 5.14.0  | 1         | 1.69%   |
| 5.13.5  | 1         | 1.69%   |
| 5.13.12 | 1         | 1.69%   |
| 5.13.11 | 1         | 1.69%   |
| 5.10.91 | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 32        | 55.17%  |
| 5.14    | 7         | 12.07%  |
| 5.17    | 6         | 10.34%  |
| 5.16    | 6         | 10.34%  |
| 5.13    | 5         | 8.62%   |
| 5.19    | 1         | 1.72%   |
| 5.10    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 27        | 45.76%  |
| XFCE      | 15        | 25.42%  |
| Unknown   | 9         | 15.25%  |
| GNOME     | 3         | 5.08%   |
| xwmconfig | 1         | 1.69%   |
| MATE      | 1         | 1.69%   |
| KDE       | 1         | 1.69%   |
| FVWM      | 1         | 1.69%   |
| awesome   | 1         | 1.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 31        | 51.67%  |
| Tty     | 22        | 36.67%  |
| Wayland | 4         | 6.67%   |
| Unknown | 3         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 35        | 59.32%  |
| Unknown | 14        | 23.73%  |
| XDM     | 7         | 11.86%  |
| LightDM | 2         | 3.39%   |
| GDM     | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 41        | 71.93%  |
| Unknown     | 5         | 8.77%   |
| it_IT       | 2         | 3.51%   |
| fr_FR       | 2         | 3.51%   |
| de_DE       | 2         | 3.51%   |
| ru_RU       | 1         | 1.75%   |
| pt_BR       | 1         | 1.75%   |
| es_ES.UTF8  | 1         | 1.75%   |
| en_US.ASCII | 1         | 1.75%   |
| en_GB       | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 54.39%  |
| BIOS | 26        | 45.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 41        | 71.93%  |
| Btrfs   | 7         | 12.28%  |
| Overlay | 4         | 7.02%   |
| Xfs     | 3         | 5.26%   |
| Zfs     | 1         | 1.75%   |
| F2fs    | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 42        | 72.41%  |
| MBR     | 9         | 15.52%  |
| Unknown | 7         | 12.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 75.86%  |
| Yes       | 14        | 24.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 63.16%  |
| Yes       | 21        | 36.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| MSI                 | 11        | 19.3%   |
| Hewlett-Packard     | 11        | 19.3%   |
| Lenovo              | 8         | 14.04%  |
| Dell                | 6         | 10.53%  |
| ASUSTek Computer    | 5         | 8.77%   |
| ASRock              | 3         | 5.26%   |
| Apple               | 2         | 3.51%   |
| TYAN Computer       | 1         | 1.75%   |
| System76            | 1         | 1.75%   |
| Sony                | 1         | 1.75%   |
| Notebook            | 1         | 1.75%   |
| Gigabyte Technology | 1         | 1.75%   |
| Fujitsu             | 1         | 1.75%   |
| Framework           | 1         | 1.75%   |
| Dynabook            | 1         | 1.75%   |
| Biostar             | 1         | 1.75%   |
| Acer                | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| TYAN S7012                               | 1         | 1.75%   |
| System76 Oryx Pro                        | 1         | 1.75%   |
| Sony SVE1713A1EW                         | 1         | 1.75%   |
| Notebook X170KM-G                        | 1         | 1.75%   |
| MSI MS-7C52                              | 1         | 1.75%   |
| MSI MS-7C02                              | 1         | 1.75%   |
| MSI MS-7996                              | 1         | 1.75%   |
| MSI MS-7788                              | 1         | 1.75%   |
| MSI MS-7693                              | 1         | 1.75%   |
| MSI MS-7529                              | 1         | 1.75%   |
| MSI MS-7365                              | 1         | 1.75%   |
| MSI Modern 14 B11MO                      | 1         | 1.75%   |
| MSI Modern 14 B10MW                      | 1         | 1.75%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.75%   |
| MSI GE76 Raider 11UE                     | 1         | 1.75%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.75%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.75%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.75%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.75%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.75%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.75%   |
| Lenovo H50-05 90BH001WIX                 | 1         | 1.75%   |
| HP Z440 Workstation                      | 1         | 1.75%   |
| HP xw8400 Workstation                    | 1         | 1.75%   |
| HP ProBook 6570b                         | 1         | 1.75%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.75%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.75%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.75%   |
| HP Laptop 15-bs1xx                       | 1         | 1.75%   |
| HP EliteBook 840 G5                      | 1         | 1.75%   |
| HP Compaq dc7900 Small Form Factor       | 1         | 1.75%   |
| HP 245 G7 Notebook PC                    | 1         | 1.75%   |
| HP 205 G4 22 All-in-One PC               | 1         | 1.75%   |
| Gigabyte N3160TN                         | 1         | 1.75%   |
| Fujitsu LIFEBOOK A544                    | 1         | 1.75%   |
| Framework Laptop                         | 1         | 1.75%   |
| Dynabook P1-C7MP-BL                      | 1         | 1.75%   |
| Dell Vostro 3500                         | 1         | 1.75%   |
| Dell Precision M4700                     | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 6         | 10.53%  |
| MSI Modern          | 2         | 3.51%   |
| HP Pavilion         | 2         | 3.51%   |
| ASUS ROG            | 2         | 3.51%   |
| TYAN S7012          | 1         | 1.75%   |
| System76 Oryx       | 1         | 1.75%   |
| Sony SVE1713A1EW    | 1         | 1.75%   |
| Notebook X170KM-G   | 1         | 1.75%   |
| MSI MS-7C52         | 1         | 1.75%   |
| MSI MS-7C02         | 1         | 1.75%   |
| MSI MS-7996         | 1         | 1.75%   |
| MSI MS-7788         | 1         | 1.75%   |
| MSI MS-7693         | 1         | 1.75%   |
| MSI MS-7529         | 1         | 1.75%   |
| MSI MS-7365         | 1         | 1.75%   |
| MSI GP76            | 1         | 1.75%   |
| MSI GE76            | 1         | 1.75%   |
| Lenovo IdeaPad      | 1         | 1.75%   |
| Lenovo H50-05       | 1         | 1.75%   |
| HP Z440             | 1         | 1.75%   |
| HP xw8400           | 1         | 1.75%   |
| HP ProBook          | 1         | 1.75%   |
| HP OMEN             | 1         | 1.75%   |
| HP Laptop           | 1         | 1.75%   |
| HP EliteBook        | 1         | 1.75%   |
| HP Compaq           | 1         | 1.75%   |
| HP 245              | 1         | 1.75%   |
| HP 205              | 1         | 1.75%   |
| Gigabyte N3160TN    | 1         | 1.75%   |
| Fujitsu LIFEBOOK    | 1         | 1.75%   |
| Framework Laptop    | 1         | 1.75%   |
| Dynabook P1-C7MP-BL | 1         | 1.75%   |
| Dell Vostro         | 1         | 1.75%   |
| Dell Precision      | 1         | 1.75%   |
| Dell PowerEdge      | 1         | 1.75%   |
| Dell OptiPlex       | 1         | 1.75%   |
| Dell Latitude       | 1         | 1.75%   |
| Dell Inspiron       | 1         | 1.75%   |
| Biostar X470GTA     | 1         | 1.75%   |
| ASUS TUF            | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 14.04%  |
| 2020 | 8         | 14.04%  |
| 2017 | 5         | 8.77%   |
| 2012 | 5         | 8.77%   |
| 2019 | 4         | 7.02%   |
| 2015 | 4         | 7.02%   |
| 2011 | 4         | 7.02%   |
| 2018 | 3         | 5.26%   |
| 2009 | 3         | 5.26%   |
| 2007 | 3         | 5.26%   |
| 2022 | 2         | 3.51%   |
| 2016 | 2         | 3.51%   |
| 2014 | 2         | 3.51%   |
| 2008 | 2         | 3.51%   |
| 2013 | 1         | 1.75%   |
| 2010 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 29        | 50.88%  |
| Desktop    | 23        | 40.35%  |
| All in one | 2         | 3.51%   |
| Server     | 2         | 3.51%   |
| Mini pc    | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 96.49%  |
| Yes  | 2         | 3.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 13        | 22.81%  |
| 3.01-4.0    | 11        | 19.3%   |
| 4.01-8.0    | 10        | 17.54%  |
| 8.01-16.0   | 9         | 15.79%  |
| 32.01-64.0  | 5         | 8.77%   |
| 64.01-256.0 | 5         | 8.77%   |
| 24.01-32.0  | 2         | 3.51%   |
| 1.01-2.0    | 2         | 3.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 16        | 26.23%  |
| 1.01-2.0   | 16        | 26.23%  |
| 4.01-8.0   | 12        | 19.67%  |
| 0.51-1.0   | 9         | 14.75%  |
| 3.01-4.0   | 3         | 4.92%   |
| 16.01-24.0 | 2         | 3.28%   |
| 0.01-0.5   | 2         | 3.28%   |
| 32.01-64.0 | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 50%     |
| 2      | 13        | 22.41%  |
| 3      | 7         | 12.07%  |
| 4      | 5         | 8.62%   |
| 6      | 2         | 3.45%   |
| 9      | 1         | 1.72%   |
| 0      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 60.34%  |
| Yes       | 23        | 39.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 91.23%  |
| No        | 5         | 8.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 75.44%  |
| No        | 14        | 24.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 66.67%  |
| No        | 19        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 24.56%  |
| Kazakhstan   | 6         | 10.53%  |
| Italy        | 4         | 7.02%   |
| UK           | 3         | 5.26%   |
| South Africa | 3         | 5.26%   |
| Japan        | 3         | 5.26%   |
| Greece       | 3         | 5.26%   |
| Brazil       | 3         | 5.26%   |
| Spain        | 2         | 3.51%   |
| Hong Kong    | 2         | 3.51%   |
| Germany      | 2         | 3.51%   |
| France       | 2         | 3.51%   |
| Canada       | 2         | 3.51%   |
| Switzerland  | 1         | 1.75%   |
| Sweden       | 1         | 1.75%   |
| Serbia       | 1         | 1.75%   |
| Russia       | 1         | 1.75%   |
| Portugal     | 1         | 1.75%   |
| Netherlands  | 1         | 1.75%   |
| Mexico       | 1         | 1.75%   |
| Chile        | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 4         | 6.9%    |
| Chania            | 3         | 5.17%   |
| Tsukuba           | 2         | 3.45%   |
| Karaganda         | 2         | 3.45%   |
| Cape Town         | 2         | 3.45%   |
| Worpswede         | 1         | 1.72%   |
| Winter Springs    | 1         | 1.72%   |
| Toronto           | 1         | 1.72%   |
| Sun Prairie       | 1         | 1.72%   |
| St Petersburg     | 1         | 1.72%   |
| Skövde           | 1         | 1.72%   |
| Sham Shui Po      | 1         | 1.72%   |
| Santiago          | 1         | 1.72%   |
| Santa Cruz do Sul | 1         | 1.72%   |
| Saint Paul        | 1         | 1.72%   |
| Round Rock        | 1         | 1.72%   |
| Rome              | 1         | 1.72%   |
| Rock              | 1         | 1.72%   |
| Reno              | 1         | 1.72%   |
| Renazzo           | 1         | 1.72%   |
| Porto Alegre      | 1         | 1.72%   |
| Plainwell         | 1         | 1.72%   |
| Ōtsu             | 1         | 1.72%   |
| Oberstreit        | 1         | 1.72%   |
| Naaldwijk         | 1         | 1.72%   |
| Montreal          | 1         | 1.72%   |
| Milwaukee         | 1         | 1.72%   |
| Milan             | 1         | 1.72%   |
| Mexico City       | 1         | 1.72%   |
| Mead              | 1         | 1.72%   |
| McKinney          | 1         | 1.72%   |
| Luxeuil-les-Bains | 1         | 1.72%   |
| London            | 1         | 1.72%   |
| Lisbon            | 1         | 1.72%   |
| Liebefeld         | 1         | 1.72%   |
| League City       | 1         | 1.72%   |
| Johannesburg      | 1         | 1.72%   |
| Hayward           | 1         | 1.72%   |
| Granada           | 1         | 1.72%   |
| Frosinone         | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 24     | 18.68%  |
| Seagate             | 15        | 23     | 16.48%  |
| WDC                 | 13        | 17     | 14.29%  |
| Toshiba             | 7         | 10     | 7.69%   |
| Kingston            | 5         | 7      | 5.49%   |
| Hitachi             | 5         | 8      | 5.49%   |
| SanDisk             | 3         | 4      | 3.3%    |
| HGST                | 3         | 3      | 3.3%    |
| Crucial             | 3         | 3      | 3.3%    |
| SK hynix            | 2         | 2      | 2.2%    |
| Hewlett-Packard     | 2         | 3      | 2.2%    |
| Gigabyte Technology | 2         | 2      | 2.2%    |
| ZHITAI              | 1         | 2      | 1.1%    |
| Plextor             | 1         | 1      | 1.1%    |
| Patriot             | 1         | 1      | 1.1%    |
| Micron Technology   | 1         | 1      | 1.1%    |
| KIOXIA              | 1         | 1      | 1.1%    |
| JMicron Technology  | 1         | 1      | 1.1%    |
| Intenso             | 1         | 1      | 1.1%    |
| Intel               | 1         | 1      | 1.1%    |
| GOODRAM             | 1         | 1      | 1.1%    |
| External            | 1         | 1      | 1.1%    |
| DUEX                | 1         | 1      | 1.1%    |
| China               | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |
| A-DATA Technology   | 1         | 1      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 1.92%   |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 1.92%   |
| Seagate ST1000DM003-1SB102 1TB          | 2         | 1.92%   |
| Samsung SSD 970 EVO 250GB               | 2         | 1.92%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 1.92%   |
| ZHITAI SC001 Active 1TB SSD             | 1         | 0.96%   |
| ZHITAI PC005 Active 512GB               | 1         | 0.96%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.96%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.96%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 0.96%   |
| WDC WD40EJRX-89T1XY0 4TB                | 1         | 0.96%   |
| WDC WD400BD-60LTA0 40GB                 | 1         | 0.96%   |
| WDC WD3200AAJS-65B4A0 320GB             | 1         | 0.96%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.96%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.96%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 0.96%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 0.96%   |
| WDC WD Green 2.5 240GB                  | 1         | 0.96%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 0.96%   |
| Toshiba THNSF5512GPUK 512GB             | 1         | 0.96%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.96%   |
| Toshiba MQ01ACF032 320GB                | 1         | 0.96%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.96%   |
| Toshiba MD04ABA400V 4TB                 | 1         | 0.96%   |
| Toshiba HDWD240 4TB                     | 1         | 0.96%   |
| Toshiba DT01ACA300 3TB                  | 1         | 0.96%   |
| SK hynix HFM001TD3JX013N 1024GB         | 1         | 0.96%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 0.96%   |
| Seagate ST4000VX000-2AG166 4TB          | 1         | 0.96%   |
| Seagate ST4000DM000-1F2168 4TB          | 1         | 0.96%   |
| Seagate ST380011A 80GB                  | 1         | 0.96%   |
| Seagate ST3500630AS 500GB               | 1         | 0.96%   |
| Seagate ST3250820AS Q 250GB             | 1         | 0.96%   |
| Seagate ST3160211AS 160GB               | 1         | 0.96%   |
| Seagate ST3000VX006-1HH166 3TB          | 1         | 0.96%   |
| Seagate ST3000NM0033-9ZM178 3TB         | 1         | 0.96%   |
| Seagate ST3000DM001-1ER166 3TB          | 1         | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 0.96%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 0.96%   |
| Seagate ST1000NM004A-2MN130 1TB         | 1         | 0.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 23     | 37.5%   |
| WDC     | 11        | 13     | 27.5%   |
| Toshiba | 6         | 8      | 15%     |
| Hitachi | 5         | 8      | 12.5%   |
| HGST    | 3         | 3      | 7.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 24.14%  |
| Kingston            | 5         | 7      | 17.24%  |
| WDC                 | 2         | 3      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| Crucial             | 2         | 2      | 6.9%    |
| ZHITAI              | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| Patriot             | 1         | 1      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |
| Intenso             | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |
| GOODRAM             | 1         | 1      | 3.45%   |
| Gigabyte Technology | 1         | 1      | 3.45%   |
| DUEX                | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 55     | 36.71%  |
| SSD  | 26        | 35     | 32.91%  |
| NVMe | 24        | 31     | 30.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 88     | 61.19%  |
| NVMe | 23        | 30     | 34.33%  |
| SAS  | 3         | 3      | 4.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 41     | 48.44%  |
| 0.51-1.0   | 17        | 22     | 26.56%  |
| 1.01-2.0   | 6         | 8      | 9.38%   |
| 3.01-4.0   | 4         | 9      | 6.25%   |
| 2.01-3.0   | 3         | 7      | 4.69%   |
| 4.01-10.0  | 3         | 3      | 4.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 15        | 25.42%  |
| 101-250        | 14        | 23.73%  |
| 251-500        | 11        | 18.64%  |
| 1-20           | 5         | 8.47%   |
| 1001-2000      | 4         | 6.78%   |
| Unknown        | 4         | 6.78%   |
| 2001-3000      | 3         | 5.08%   |
| More than 3000 | 2         | 3.39%   |
| 51-100         | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 27.12%  |
| 21-50          | 11        | 18.64%  |
| 1-20           | 11        | 18.64%  |
| 251-500        | 7         | 11.86%  |
| 501-1000       | 5         | 8.47%   |
| Unknown        | 4         | 6.78%   |
| 1001-2000      | 2         | 3.39%   |
| 51-100         | 2         | 3.39%   |
| More than 3000 | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 6.25%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 6.25%   |
| WDC WD3200AAJS-65B4A0 320GB         | 1         | 1      | 6.25%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 6.25%   |
| Seagate ST380011A 80GB              | 1         | 1      | 6.25%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 6.25%   |
| Seagate ST3000VX006-1HH166 3TB      | 1         | 1      | 6.25%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 6.25%   |
| Seagate ST1000DM003-1ER162 1TB      | 1         | 2      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 6.25%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 6.25%   |
| Hitachi HUA723030ALA640 3TB         | 1         | 1      | 6.25%   |
| Hitachi HDS721016CLA382 160GB       | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 6.25%   |
| DUEX DX300256A5xnEMLC 256GB SSD     | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 26.67%  |
| Seagate             | 4         | 6      | 26.67%  |
| Hitachi             | 2         | 2      | 13.33%  |
| HGST                | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Plextor             | 1         | 1      | 6.67%   |
| DUEX                | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 36.36%  |
| WDC     | 3         | 4      | 27.27%  |
| Hitachi | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 69.23%  |
| SSD  | 4         | 4      | 30.77%  |

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
| Works    | 45        | 84     | 65.22%  |
| Malfunc  | 13        | 18     | 18.84%  |
| Detected | 11        | 19     | 15.94%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 33        | 44%     |
| AMD                          | 12        | 16%     |
| Samsung Electronics          | 11        | 14.67%  |
| SK hynix                     | 2         | 2.67%   |
| SanDisk                      | 2         | 2.67%   |
| Nvidia                       | 2         | 2.67%   |
| Yangtze Memory Technologies  | 1         | 1.33%   |
| Toshiba America Info Systems | 1         | 1.33%   |
| Realtek Semiconductor        | 1         | 1.33%   |
| Phison Electronics           | 1         | 1.33%   |
| Micron/Crucial Technology    | 1         | 1.33%   |
| Micron Technology            | 1         | 1.33%   |
| Marvell Technology Group     | 1         | 1.33%   |
| KIOXIA                       | 1         | 1.33%   |
| JMicron Technology           | 1         | 1.33%   |
| Broadcom / LSI               | 1         | 1.33%   |
| Biwin Storage Technology     | 1         | 1.33%   |
| ASMedia Technology           | 1         | 1.33%   |
| Adaptec                      | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 10.99%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 5.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 4.4%    |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 4.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 3.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.2%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.2%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 2.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.2%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 2.2%    |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 1.1%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 1.1%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.1%    |
| SK hynix BC511                                                                   | 1         | 1.1%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.1%    |
| Samsung Electronics SATA controller                                              | 1         | 1.1%    |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.1%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.1%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.1%    |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.1%    |
| Nvidia MCP61 IDE                                                                 | 1         | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.1%    |
| Micron Non-Volatile memory controller                                            | 1         | 1.1%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.1%    |
| JMicron JMB58x AHCI SATA controller                                              | 1         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.1%    |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.1%    |
| Intel SSD 600P Series                                                            | 1         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 49.35%  |
| NVMe | 23        | 29.87%  |
| IDE  | 10        | 12.99%  |
| RAID | 4         | 5.19%   |
| SCSI | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 77.19%  |
| AMD    | 13        | 22.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 5.26%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 3.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 3.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.51%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 1.75%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz     | 1         | 1.75%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz     | 1         | 1.75%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz     | 1         | 1.75%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 1         | 1.75%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 1         | 1.75%   |
| Intel Pentium CPU 2020M @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 1         | 1.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.75%   |
| Intel Core i7-3840QM CPU @ 2.80GHz      | 1         | 1.75%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.75%   |
| Intel Core i5-8600K CPU @ 3.60GHz       | 1         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.75%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.75%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.75%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.75%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.75%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 1         | 1.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.75%   |
| Intel Core i3-10105 CPU @ 3.70GHz       | 1         | 1.75%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz    | 1         | 1.75%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 1         | 1.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 1         | 1.75%   |
| Intel Atom CPU 330 @ 1.60GHz            | 1         | 1.75%   |
| Intel 12th Gen Core i7-12700H           | 1         | 1.75%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.75%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 10        | 17.54%  |
| Intel Core i7      | 9         | 15.79%  |
| Other              | 8         | 14.04%  |
| Intel Xeon         | 5         | 8.77%   |
| Intel Core 2 Duo   | 5         | 8.77%   |
| AMD Ryzen 9        | 3         | 5.26%   |
| AMD Ryzen 5        | 3         | 5.26%   |
| Intel Core i3      | 2         | 3.51%   |
| Intel Celeron      | 2         | 3.51%   |
| AMD Ryzen 7        | 2         | 3.51%   |
| AMD FX             | 2         | 3.51%   |
| Intel Pentium Dual | 1         | 1.75%   |
| Intel Pentium      | 1         | 1.75%   |
| Intel Atom         | 1         | 1.75%   |
| AMD EPYC           | 1         | 1.75%   |
| AMD Athlon         | 1         | 1.75%   |
| AMD A8             | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 20        | 35.09%  |
| 4      | 18        | 31.58%  |
| 8      | 10        | 17.54%  |
| 14     | 2         | 3.51%   |
| 12     | 2         | 3.51%   |
| 6      | 2         | 3.51%   |
| 16     | 1         | 1.75%   |
| 10     | 1         | 1.75%   |
| 3      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 96.49%  |
| 2      | 2         | 3.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 75.44%  |
| 1      | 14        | 24.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 17.54%  |
| 0x306a9    | 7         | 12.28%  |
| 0x806d1    | 3         | 5.26%   |
| 0x806c1    | 3         | 5.26%   |
| 0x406c4    | 2         | 3.51%   |
| 0x306f2    | 2         | 3.51%   |
| 0x1067a    | 2         | 3.51%   |
| 0x0a201016 | 2         | 3.51%   |
| 0x08108109 | 2         | 3.51%   |
| 0xa0671    | 1         | 1.75%   |
| 0xa0653    | 1         | 1.75%   |
| 0xa0652    | 1         | 1.75%   |
| 0x906ea    | 1         | 1.75%   |
| 0x906e9    | 1         | 1.75%   |
| 0x906a3    | 1         | 1.75%   |
| 0x806ec    | 1         | 1.75%   |
| 0x806ea    | 1         | 1.75%   |
| 0x6fd      | 1         | 1.75%   |
| 0x6fa      | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x406e3    | 1         | 1.75%   |
| 0x306e4    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x306c3    | 1         | 1.75%   |
| 0x206c2    | 1         | 1.75%   |
| 0x106c2    | 1         | 1.75%   |
| 0x08701021 | 1         | 1.75%   |
| 0x08600106 | 1         | 1.75%   |
| 0x0830104d | 1         | 1.75%   |
| 0x0810100b | 1         | 1.75%   |
| 0x07030105 | 1         | 1.75%   |
| 0x06000822 | 1         | 1.75%   |
| 0x00000000 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 8         | 14.04%  |
| KabyLake         | 6         | 10.53%  |
| Zen 2            | 5         | 8.77%   |
| Icelake          | 4         | 7.02%   |
| Core             | 4         | 7.02%   |
| Westmere         | 3         | 5.26%   |
| TigerLake        | 3         | 5.26%   |
| Skylake          | 3         | 5.26%   |
| Penryn           | 3         | 5.26%   |
| Haswell          | 3         | 5.26%   |
| Zen+             | 2         | 3.51%   |
| Zen 3            | 2         | 3.51%   |
| Silvermont       | 2         | 3.51%   |
| Piledriver       | 2         | 3.51%   |
| CometLake        | 2         | 3.51%   |
| Zen              | 1         | 1.75%   |
| Puma             | 1         | 1.75%   |
| Broadwell        | 1         | 1.75%   |
| Bonnell          | 1         | 1.75%   |
| Alderlake Hybrid | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 27        | 41.54%  |
| Nvidia                     | 21        | 32.31%  |
| AMD                        | 16        | 24.62%  |
| Matrox Electronics Systems | 1         | 1.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.55%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.03%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 3.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.03%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.03%   |
| AMD Renoir                                                                               | 2         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.03%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 3.03%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.52%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 1.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.52%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.52%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.52%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1         | 1.52%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.52%   |
| Nvidia G71GL [Quadro FX 1500]                                                            | 1         | 1.52%   |
| Nvidia C79 [ION]                                                                         | 1         | 1.52%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.52%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.52%   |
| Intel HD Graphics 620                                                                    | 1         | 1.52%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.52%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.52%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 36.84%  |
| 1 x AMD        | 15        | 26.32%  |
| 1 x Nvidia     | 13        | 22.81%  |
| Intel + Nvidia | 6         | 10.53%  |
| 1 x Matrox     | 1         | 1.75%   |
| AMD + Nvidia   | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 82.46%  |
| Proprietary | 9         | 15.79%  |
| Unknown     | 1         | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 49.12%  |
| 0.51-1.0   | 8         | 14.04%  |
| 7.01-8.0   | 5         | 8.77%   |
| 0.01-0.5   | 5         | 8.77%   |
| 5.01-6.0   | 3         | 5.26%   |
| 1.01-2.0   | 3         | 5.26%   |
| 8.01-16.0  | 3         | 5.26%   |
| 3.01-4.0   | 1         | 1.75%   |
| 2.01-3.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 9         | 14.52%  |
| Samsung Electronics  | 7         | 11.29%  |
| LG Display           | 7         | 11.29%  |
| Hewlett-Packard      | 6         | 9.68%   |
| Dell                 | 4         | 6.45%   |
| AU Optronics         | 4         | 6.45%   |
| Lenovo               | 3         | 4.84%   |
| Ancor Communications | 3         | 4.84%   |
| Sharp                | 2         | 3.23%   |
| Chimei Innolux       | 2         | 3.23%   |
| BenQ                 | 2         | 3.23%   |
| Acer                 | 2         | 3.23%   |
| Wacom                | 1         | 1.61%   |
| UGD                  | 1         | 1.61%   |
| Sony                 | 1         | 1.61%   |
| PANDA                | 1         | 1.61%   |
| IOD                  | 1         | 1.61%   |
| Iiyama               | 1         | 1.61%   |
| Goldstar             | 1         | 1.61%   |
| GDH                  | 1         | 1.61%   |
| Apple                | 1         | 1.61%   |
| AOC                  | 1         | 1.61%   |
| Unknown              | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch             | 1         | 1.59%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                | 1         | 1.59%   |
| Sony TV SNY8102 1360x768                                             | 1         | 1.59%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch              | 1         | 1.59%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 380x300mm 19.1-inch | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 1         | 1.59%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 598x336mm 27.0-inch  | 1         | 1.59%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 1         | 1.59%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch    | 1         | 1.59%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 1.59%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 1.59%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 1.59%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch               | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch              | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 1         | 1.59%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                 | 1         | 1.59%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                 | 1         | 1.59%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch           | 1         | 1.59%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch         | 1         | 1.59%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 1.59%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch     | 1         | 1.59%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1         | 1.59%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 1.59%   |
| Goldstar E1641 GSM8B3E 1366x768 344x194mm 15.5-inch                  | 1         | 1.59%   |
| GDH CHHWJT GDH0030 1440x900 1150x650mm 52.0-inch                     | 1         | 1.59%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 1.59%   |
| Dell SP2208WFP DEL4038 1680x1050 473x296mm 22.0-inch                 | 1         | 1.59%   |
| Dell LCD Monitor P190S 3200x1080                                     | 1         | 1.59%   |
| Dell LCD Monitor DELA026 1920x1200 520x330mm 24.2-inch               | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 48.33%  |
| 1366x768 (WXGA)    | 10        | 16.67%  |
| 3840x2160 (4K)     | 3         | 5%      |
| 1280x1024 (SXGA)   | 3         | 5%      |
| 1920x1200 (WUXGA)  | 2         | 3.33%   |
| 1680x1050 (WSXGA+) | 2         | 3.33%   |
| 1360x768           | 2         | 3.33%   |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 3440x1440          | 1         | 1.67%   |
| 3200x1080          | 1         | 1.67%   |
| 2560x1440 (QHD)    | 1         | 1.67%   |
| 2256x1504          | 1         | 1.67%   |
| 1600x900 (HD+)     | 1         | 1.67%   |
| 1600x1200          | 1         | 1.67%   |
| Unknown            | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 21.31%  |
| 27      | 6         | 9.84%   |
| 14      | 6         | 9.84%   |
| 24      | 5         | 8.2%    |
| 21      | 5         | 8.2%    |
| 17      | 5         | 8.2%    |
| 13      | 5         | 8.2%    |
| 20      | 3         | 4.92%   |
| 23      | 2         | 3.28%   |
| 18      | 2         | 3.28%   |
| 16      | 2         | 3.28%   |
| 72      | 1         | 1.64%   |
| 52      | 1         | 1.64%   |
| 34      | 1         | 1.64%   |
| 22      | 1         | 1.64%   |
| 19      | 1         | 1.64%   |
| 12      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 40%     |
| 501-600     | 12        | 20%     |
| 401-500     | 10        | 16.67%  |
| 351-400     | 6         | 10%     |
| 201-300     | 3         | 5%      |
| 701-800     | 1         | 1.67%   |
| 601-700     | 1         | 1.67%   |
| 1501-2000   | 1         | 1.67%   |
| 1001-1500   | 1         | 1.67%   |
| Unknown     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 40        | 74.07%  |
| 16/10   | 7         | 12.96%  |
| 5/4     | 3         | 5.56%   |
| 4/3     | 1         | 1.85%   |
| 3/2     | 1         | 1.85%   |
| 21/9    | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 25%     |
| 81-90          | 10        | 16.67%  |
| 201-250        | 7         | 11.67%  |
| 301-350        | 6         | 10%     |
| 151-200        | 6         | 10%     |
| 141-150        | 4         | 6.67%   |
| 251-300        | 3         | 5%      |
| 121-130        | 3         | 5%      |
| More than 1000 | 2         | 3.33%   |
| 71-80          | 1         | 1.67%   |
| 61-70          | 1         | 1.67%   |
| 351-500        | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 21        | 35%     |
| 121-160       | 17        | 28.33%  |
| 101-120       | 16        | 26.67%  |
| 1-50          | 2         | 3.33%   |
| 161-240       | 2         | 3.33%   |
| More than 240 | 1         | 1.67%   |
| Unknown       | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 78.95%  |
| 2     | 6         | 10.53%  |
| 0     | 4         | 7.02%   |
| 4     | 1         | 1.75%   |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 33        | 39.29%  |
| Realtek Semiconductor    | 32        | 38.1%   |
| Qualcomm Atheros         | 4         | 4.76%   |
| Broadcom                 | 4         | 4.76%   |
| Ralink Technology        | 2         | 2.38%   |
| Broadcom Limited         | 2         | 2.38%   |
| TP-Link                  | 1         | 1.19%   |
| Ralink                   | 1         | 1.19%   |
| Qualcomm                 | 1         | 1.19%   |
| Nvidia                   | 1         | 1.19%   |
| MediaTek                 | 1         | 1.19%   |
| Marvell Technology Group | 1         | 1.19%   |
| Hewlett-Packard          | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 21.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.92%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.92%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.96%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.96%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.96%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.96%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.96%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.96%   |
| Intel Wireless-AC 9260                                            | 1         | 0.96%   |
| Intel Wireless 8260                                               | 1         | 0.96%   |
| Intel Wireless 7260                                               | 1         | 0.96%   |
| Intel Wireless 3165                                               | 1         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.96%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 58.14%  |
| Realtek Semiconductor | 6         | 13.95%  |
| Qualcomm Atheros      | 4         | 9.3%    |
| Ralink Technology     | 2         | 4.65%   |
| Broadcom              | 2         | 4.65%   |
| TP-Link               | 1         | 2.33%   |
| Ralink                | 1         | 2.33%   |
| MediaTek              | 1         | 2.33%   |
| Broadcom Limited      | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 6.82%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 6.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2         | 4.55%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 4.55%   |
| Intel Wireless 8265 / 8275                                     | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 4.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 4.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 2.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 2.27%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.27%   |
| Intel Wireless-AC 9260                                         | 1         | 2.27%   |
| Intel Wireless 8260                                            | 1         | 2.27%   |
| Intel Wireless 7260                                            | 1         | 2.27%   |
| Intel Wireless 3165                                            | 1         | 2.27%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.27%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 1         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 54.39%  |
| Intel                    | 18        | 31.58%  |
| Broadcom                 | 3         | 5.26%   |
| Qualcomm Atheros         | 1         | 1.75%   |
| Qualcomm                 | 1         | 1.75%   |
| Nvidia                   | 1         | 1.75%   |
| Marvell Technology Group | 1         | 1.75%   |
| Broadcom Limited         | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 37.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 3.39%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.69%   |
| Qualcomm Redmi Note 8                                             | 1         | 1.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.69%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.69%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.69%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.69%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.69%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.69%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.69%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 1.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.69%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.69%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 54.17%  |
| WiFi     | 43        | 44.79%  |
| Modem    | 1         | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 53.33%  |
| Ethernet | 28        | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 57.89%  |
| 1     | 20        | 35.09%  |
| 4     | 2         | 3.51%   |
| 3     | 2         | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 85.96%  |
| Yes  | 8         | 14.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 52.63%  |
| Broadcom                 | 5         | 13.16%  |
| Realtek Semiconductor    | 4         | 10.53%  |
| Cambridge Silicon Radio  | 4         | 10.53%  |
| Apple                    | 2         | 5.26%   |
| Micro Star International | 1         | 2.63%   |
| IMC Networks             | 1         | 2.63%   |
| Foxconn / Hon Hai        | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 15.79%  |
| Intel AX201 Bluetooth                               | 5         | 13.16%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.89%   |
| Intel AX210 Bluetooth                               | 3         | 7.89%   |
| Intel AX200 Bluetooth                               | 3         | 7.89%   |
| Realtek Bluetooth Radio                             | 1         | 2.63%   |
| Micro Star International Bluetooth Dongle           | 1         | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.63%   |
| IMC Networks Wireless_Device                        | 1         | 2.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.63%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.63%   |
| Broadcom BCM20702A0                                 | 1         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.63%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 38        | 46.34%  |
| Nvidia                 | 19        | 23.17%  |
| AMD                    | 17        | 20.73%  |
| Creative Labs          | 4         | 4.88%   |
| C-Media Electronics    | 2         | 2.44%   |
| Generalplus Technology | 1         | 1.22%   |
| ASUSTek Computer       | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.38%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 4.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 4.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 4.3%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 3.23%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.15%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 2         | 2.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.15%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia Audio device                                                                               | 1         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.08%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 13        | 21.31%  |
| SK hynix            | 11        | 18.03%  |
| Samsung Electronics | 9         | 14.75%  |
| Crucial             | 5         | 8.2%    |
| Micron Technology   | 3         | 4.92%   |
| Corsair             | 3         | 4.92%   |
| Unknown             | 2         | 3.28%   |
| Team                | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Transcend           | 1         | 1.64%   |
| Strontium           | 1         | 1.64%   |
| Silicon Power       | 1         | 1.64%   |
| Neo Forza           | 1         | 1.64%   |
| Nanya Technology    | 1         | 1.64%   |
| Goodram             | 1         | 1.64%   |
| GLOWAY              | 1         | 1.64%   |
| G.Skill             | 1         | 1.64%   |
| Essencore Limited   | 1         | 1.64%   |
| AMD                 | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 2.99%   |
| Transcend RAM JM1600KLN-8GK 4096MB DIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 1.49%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 1.49%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s            | 1         | 1.49%   |
| SK hynix RAM HYMP512F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                 | 1         | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                 | 1         | 1.49%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1333MT/s                  | 1         | 1.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s          | 1         | 1.49%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.49%   |
| Silicon Power RAM DCLT4GN568S V 4096MB DIMM DDR3 1600MT/s        | 1         | 1.49%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.49%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.49%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 1.49%   |
| Samsung RAM M395T5663QZ4-CE66 2048MB FB-DIMM DDR2 667MT/s        | 1         | 1.49%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s             | 1         | 1.49%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.49%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.49%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.49%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s          | 1         | 1.49%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.49%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.49%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s           | 1         | 1.49%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.49%   |
| Kingston RAM Module 2048MB FB-DIMM DDR2 667MT/s                  | 1         | 1.49%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.49%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.49%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s             | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 26        | 50.98%  |
| DDR3    | 17        | 33.33%  |
| DDR2    | 3         | 5.88%   |
| SDRAM   | 2         | 3.92%   |
| LPDDR3  | 1         | 1.96%   |
| DDR5    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 54%     |
| DIMM         | 20        | 40%     |
| Row Of Chips | 1         | 2%      |
| RIMM         | 1         | 2%      |
| FB-DIMM      | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 37.5%   |
| 4096  | 19        | 33.93%  |
| 16384 | 7         | 12.5%   |
| 2048  | 4         | 7.14%   |
| 32768 | 3         | 5.36%   |
| 1024  | 2         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 22.81%  |
| 3200    | 12        | 21.05%  |
| 2400    | 5         | 8.77%   |
| 2667    | 4         | 7.02%   |
| 1333    | 4         | 7.02%   |
| 3800    | 2         | 3.51%   |
| 2133    | 2         | 3.51%   |
| 667     | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| 65535   | 1         | 1.75%   |
| 4800    | 1         | 1.75%   |
| 3733    | 1         | 1.75%   |
| 3600    | 1         | 1.75%   |
| 2933    | 1         | 1.75%   |
| 2472    | 1         | 1.75%   |
| 2187    | 1         | 1.75%   |
| 1867    | 1         | 1.75%   |
| 1866    | 1         | 1.75%   |
| 975     | 1         | 1.75%   |
| 701     | 1         | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dell                | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 25%     |
| HP OfficeJet Pro 9010 series | 1         | 25%     |
| Dell 2330d Laser Printer     | 1         | 25%     |
| Canon CanoScan LiDE 300      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 22.22%  |
| Acer                                   | 7         | 19.44%  |
| Microdia                               | 5         | 13.89%  |
| Logitech                               | 5         | 13.89%  |
| Realtek Semiconductor                  | 2         | 5.56%   |
| Luxvisions Innotech Limited            | 2         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.56%   |
| Syntek                                 | 1         | 2.78%   |
| Samsung Electronics                    | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Lenovo                                 | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 8.33%   |
| Logitech Webcam C270                                           | 2         | 5.56%   |
| Chicony Integrated Camera                                      | 2         | 5.56%   |
| Acer BisonCam,NB Pro                                           | 2         | 5.56%   |
| Syntek USB2.0 Camera                                           | 1         | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.78%   |
| Realtek Laptop Camera                                          | 1         | 2.78%   |
| Realtek EasyCamera                                             | 1         | 2.78%   |
| Quanta HP Webcam                                               | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.78%   |
| Microdia Integrated Webcam                                     | 1         | 2.78%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.78%   |
| Microdia Camera                                                | 1         | 2.78%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.78%   |
| Logitech QuickCam Pro 9000                                     | 1         | 2.78%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 2.78%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 2.78%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.78%   |
| Chicony Web Camera - FHD                                       | 1         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.78%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.78%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.78%   |
| Chicony HP HD Camera                                           | 1         | 2.78%   |
| Chicony FJ Camera                                              | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 2.78%   |
| Apple Built-in iSight                                          | 1         | 2.78%   |
| Acer ThinkPad Integrated Camera                                | 1         | 2.78%   |
| Acer Integrated Camera                                         | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 50%     |
| Synaptics          | 2         | 33.33%  |
| STMicroelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI            | 2         | 33.33%  |
| Unknown                                    | 2         | 33.33%  |
| Validity Sensors VFS300 Fingerprint Reader | 1         | 16.67%  |
| STMicroelectronics Fingerprint Reader      | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 70.69%  |
| 1     | 12        | 20.69%  |
| 2     | 3         | 5.17%   |
| 4     | 1         | 1.72%   |
| 3     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 24%     |
| Graphics card            | 4         | 16%     |
| Sound                    | 3         | 12%     |
| Unassigned class         | 2         | 8%      |
| Net/wireless             | 2         | 8%      |
| Multimedia controller    | 2         | 8%      |
| Communication controller | 2         | 8%      |
| Chipcard                 | 2         | 8%      |
| Net/ethernet             | 1         | 4%      |
| Bluetooth                | 1         | 4%      |

