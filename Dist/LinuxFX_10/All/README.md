LinuxFX 10 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LinuxFX_10/Desktop/README.md) and [notebooks](/Dist/LinuxFX_10/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=windowsfx-10

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

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock     | 970 Extreme4                | Desktop     | [85b942a5c3](https://linux-hardware.org/?probe=85b942a5c3) | Oct 30, 2021 |
| ASRock     | 970 Extreme4                | Desktop     | [022942c4aa](https://linux-hardware.org/?probe=022942c4aa) | Oct 30, 2021 |
| Dell       | Latitude E6420              | Notebook    | [dc9a1e9c1b](https://linux-hardware.org/?probe=dc9a1e9c1b) | Oct 18, 2021 |
| MSI        | MS-7309                     | Desktop     | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| MSI        | MS-7309                     | Desktop     | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| HP         | 250 G7 Notebook PC          | Notebook    | [7368bcaf0a](https://linux-hardware.org/?probe=7368bcaf0a) | Oct 04, 2021 |
| HP         | 250 G7 Notebook PC          | Notebook    | [c7ae2849cc](https://linux-hardware.org/?probe=c7ae2849cc) | Sep 30, 2021 |
| PCWare     | IPMH61R2                    | Desktop     | [62d2476431](https://linux-hardware.org/?probe=62d2476431) | Sep 27, 2021 |
| Gigabyte   | X570 UD                     | Desktop     | [e1777d09cb](https://linux-hardware.org/?probe=e1777d09cb) | Sep 10, 2021 |
| Medion     | S4216                       | Notebook    | [677bd3ecb4](https://linux-hardware.org/?probe=677bd3ecb4) | Aug 27, 2021 |
| Medion     | S4216                       | Notebook    | [a0ae7753cf](https://linux-hardware.org/?probe=a0ae7753cf) | Aug 26, 2021 |
| Dell       | Inspiron 3421               | Notebook    | [06a0a6486b](https://linux-hardware.org/?probe=06a0a6486b) | Aug 26, 2021 |
| MSI        | A88XI AC                    | Desktop     | [1306310e52](https://linux-hardware.org/?probe=1306310e52) | Aug 02, 2021 |
| MSI        | A88XI AC                    | Desktop     | [ebdf5c76be](https://linux-hardware.org/?probe=ebdf5c76be) | Aug 02, 2021 |
| Dell       | Latitude E5520              | Notebook    | [cae8dd2173](https://linux-hardware.org/?probe=cae8dd2173) | Jul 27, 2021 |
| Jumper     | Ezpad                       | Tablet      | [d40961f21f](https://linux-hardware.org/?probe=d40961f21f) | Jul 26, 2021 |
| Jumper     | Ezpad                       | Tablet      | [f80ea7b800](https://linux-hardware.org/?probe=f80ea7b800) | Jul 26, 2021 |
| Dell       | Latitude E5520              | Notebook    | [0112c3a302](https://linux-hardware.org/?probe=0112c3a302) | Jul 22, 2021 |
| ASRock     | B450M Steel Legend          | Desktop     | [42869f7bb5](https://linux-hardware.org/?probe=42869f7bb5) | Jun 20, 2021 |
| Samsung    | 305E4A/305E5A/305E7A        | Notebook    | [3db60d4f9a](https://linux-hardware.org/?probe=3db60d4f9a) | Jun 01, 2021 |
| Lenovo     | ThinkPad T450s 20BWS0YF0... | Notebook    | [7b1e0f2693](https://linux-hardware.org/?probe=7b1e0f2693) | May 11, 2021 |
| Acer       | Aspire 5755G                | Notebook    | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Supermicro | H8DG6/H8DGi                 | Server      | [ad61efb931](https://linux-hardware.org/?probe=ad61efb931) | Mar 11, 2021 |
| Acer       | Aspire 5755G                | Notebook    | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| ASRock     | N68-GE3 UCC                 | Desktop     | [f2a9721ca5](https://linux-hardware.org/?probe=f2a9721ca5) | Feb 25, 2021 |
| Gigabyte   | G31M-S2C                    | Desktop     | [95c9698f2b](https://linux-hardware.org/?probe=95c9698f2b) | Feb 24, 2021 |
| ASUSTek    | K50C                        | Notebook    | [d6ac6b2de1](https://linux-hardware.org/?probe=d6ac6b2de1) | Feb 18, 2021 |
| ASUSTek    | K50C                        | Notebook    | [a899af5e96](https://linux-hardware.org/?probe=a899af5e96) | Feb 18, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Lenovo     | ThinkPad X1 Carbon 2nd F... | Notebook    | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Pegatron   | B34C                        | Notebook    | [4c3a4f9ad1](https://linux-hardware.org/?probe=4c3a4f9ad1) | Feb 05, 2021 |
| ASRock     | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| ASUSTek    | TUF Gaming FX506LI_FX506... | Notebook    | [a22da47202](https://linux-hardware.org/?probe=a22da47202) | Jan 30, 2021 |
| Acer       | Aspire A515-51G             | Notebook    | [3300b2bb9d](https://linux-hardware.org/?probe=3300b2bb9d) | Jan 22, 2021 |
| MSI        | B450M PRO-M2 MAX            | Desktop     | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| HP         | 2B1E                        | Desktop     | [940750f549](https://linux-hardware.org/?probe=940750f549) | Jan 05, 2021 |
| ASUSTek    | P8Z68-V LE                  | Desktop     | [356c40c60b](https://linux-hardware.org/?probe=356c40c60b) | Dec 27, 2020 |
| Lenovo     | Y70-70 Touch 80DU           | Notebook    | [023b353ca8](https://linux-hardware.org/?probe=023b353ca8) | Dec 22, 2020 |
| ASUSTek    | H87-PRO                     | Desktop     | [e2287834ae](https://linux-hardware.org/?probe=e2287834ae) | Dec 10, 2020 |
| ASUSTek    | H87-PRO                     | Desktop     | [17bd61ae55](https://linux-hardware.org/?probe=17bd61ae55) | Dec 09, 2020 |
| Gigabyte   | B450 AORUS M                | Desktop     | [8e3b4356b7](https://linux-hardware.org/?probe=8e3b4356b7) | Dec 03, 2020 |
| Acer       | Aspire 5720Z                | Notebook    | [38045109f8](https://linux-hardware.org/?probe=38045109f8) | Nov 29, 2020 |
| Toshiba    | Satellite C50D-A-12R        | Notebook    | [2b5e2b26b2](https://linux-hardware.org/?probe=2b5e2b26b2) | Nov 23, 2020 |
| Apple      | Mac-F226BEC8 PVT            | All in one  | [ccc5f55191](https://linux-hardware.org/?probe=ccc5f55191) | Nov 21, 2020 |
| Gigabyte   | P57V6                       | Notebook    | [ec76a0907c](https://linux-hardware.org/?probe=ec76a0907c) | Nov 15, 2020 |
| Dell       | 0V6D8J A00                  | Desktop     | [5b4385cd10](https://linux-hardware.org/?probe=5b4385cd10) | Nov 09, 2020 |
| Dell       | 0V6D8J A00                  | Desktop     | [13e1111610](https://linux-hardware.org/?probe=13e1111610) | Nov 09, 2020 |
| Acer       | Aspire TC-105               | Desktop     | [0ee92155a3](https://linux-hardware.org/?probe=0ee92155a3) | Nov 04, 2020 |
| ECS        | A780GM-A                    | Desktop     | [cf03b0c26b](https://linux-hardware.org/?probe=cf03b0c26b) | Nov 04, 2020 |
| Acer       | Aspire ES1-512              | Notebook    | [328c13ce38](https://linux-hardware.org/?probe=328c13ce38) | Oct 25, 2020 |
| Acer       | Aspire ES1-512              | Notebook    | [59368b9e58](https://linux-hardware.org/?probe=59368b9e58) | Oct 24, 2020 |
| Acer       | Aspire 6930G                | Notebook    | [1519ec67b5](https://linux-hardware.org/?probe=1519ec67b5) | Sep 07, 2020 |
| Acer       | Aspire 6930G                | Notebook    | [51b6611d94](https://linux-hardware.org/?probe=51b6611d94) | Sep 06, 2020 |
| Dell       | 0TT6JF A02                  | Server      | [ebfac9e556](https://linux-hardware.org/?probe=ebfac9e556) | Sep 04, 2020 |
| Dell       | Inspiron 15-3567            | Notebook    | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| HP         | Compaq Presario CQ50        | Notebook    | [b82778b925](https://linux-hardware.org/?probe=b82778b925) | Sep 01, 2020 |
| Gigabyte   | P57V6                       | Notebook    | [7f8d44d28e](https://linux-hardware.org/?probe=7f8d44d28e) | Aug 30, 2020 |
| HP         | ProBook 6560b               | Notebook    | [99a7a9817b](https://linux-hardware.org/?probe=99a7a9817b) | Aug 26, 2020 |
| HP         | ProBook 6560b               | Notebook    | [b9893a704d](https://linux-hardware.org/?probe=b9893a704d) | Aug 26, 2020 |
| Olivetti   | P55-AEU-323-4G320           | Notebook    | [c08737d73c](https://linux-hardware.org/?probe=c08737d73c) | Aug 23, 2020 |
| Lenovo     | G505 20240                  | Notebook    | [aa6a5c7462](https://linux-hardware.org/?probe=aa6a5c7462) | Aug 22, 2020 |
| ASUSTek    | K72Jr                       | Notebook    | [51cd547219](https://linux-hardware.org/?probe=51cd547219) | Aug 18, 2020 |
| ASUSTek    | K72Jr                       | Notebook    | [d68a58547e](https://linux-hardware.org/?probe=d68a58547e) | Aug 15, 2020 |
| Gigabyte   | 970A-DS3P                   | Desktop     | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Dell       | Inspiron 5423               | Notebook    | [1f3e63e601](https://linux-hardware.org/?probe=1f3e63e601) | Jul 24, 2020 |
| Acer       | Aspire E1-531               | Notebook    | [6104770d46](https://linux-hardware.org/?probe=6104770d46) | Jul 23, 2020 |
| Dell       | Vostro 1000                 | Notebook    | [ffb49e4b86](https://linux-hardware.org/?probe=ffb49e4b86) | Jul 22, 2020 |
| Positivo   | Mobile                      | Notebook    | [7ac9083ae4](https://linux-hardware.org/?probe=7ac9083ae4) | Jul 21, 2020 |
| HP         | Mini 210-1000               | Notebook    | [d1e83a2d9b](https://linux-hardware.org/?probe=d1e83a2d9b) | Jul 19, 2020 |
| Dell       | 0Y644J A02                  | Desktop     | [96f0709424](https://linux-hardware.org/?probe=96f0709424) | Jul 16, 2020 |
| Gigabyte   | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Intel      | B75                         | Desktop     | [dc59852769](https://linux-hardware.org/?probe=dc59852769) | Jul 11, 2020 |
| HP         | 250 G6 Notebook PC          | Notebook    | [bc9d23a74c](https://linux-hardware.org/?probe=bc9d23a74c) | Jul 02, 2020 |
| HP         | 250 G6 Notebook PC          | Notebook    | [b1757b232f](https://linux-hardware.org/?probe=b1757b232f) | Jul 02, 2020 |
| Dell       | 0CRWCR A01                  | All in one  | [fe89daec6e](https://linux-hardware.org/?probe=fe89daec6e) | Jun 20, 2020 |
| Lenovo     | G550 2958                   | Notebook    | [6cfc44a819](https://linux-hardware.org/?probe=6cfc44a819) | Jun 11, 2020 |
| Lenovo     | G550 2958                   | Notebook    | [95b68a8144](https://linux-hardware.org/?probe=95b68a8144) | Jun 11, 2020 |
| Dell       | Inspiron 3520               | Notebook    | [c78c5e6395](https://linux-hardware.org/?probe=c78c5e6395) | May 16, 2020 |
| HP         | EliteBook Folio 9470m       | Notebook    | [f0b4ebc551](https://linux-hardware.org/?probe=f0b4ebc551) | May 16, 2020 |
| HP         | G42                         | Notebook    | [5c1017a089](https://linux-hardware.org/?probe=5c1017a089) | May 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-52-generic            | 10        | 17.54%  |
| 5.6.15-windowsfx-10-generic | 8         | 14.04%  |
| 5.4.0-72-generic            | 8         | 14.04%  |
| 5.7.15-050715-generic       | 5         | 8.77%   |
| 5.5.19-050519-generic       | 4         | 7.02%   |
| 5.4.0-65-generic            | 4         | 7.02%   |
| 5.7.8-windowsfx-generic     | 3         | 5.26%   |
| 5.4.0-42-generic            | 3         | 5.26%   |
| 5.4.0-29-generic            | 3         | 5.26%   |
| 5.4.0-73-generic            | 2         | 3.51%   |
| 5.4.0-56-generic            | 2         | 3.51%   |
| 5.4.0-54-generic            | 2         | 3.51%   |
| 5.4.0-88-generic            | 1         | 1.75%   |
| 5.4.0-66-generic            | 1         | 1.75%   |
| 5.10.2-051002-generic       | 1         | 1.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 63.16%  |
| 5.6.15  | 8         | 14.04%  |
| 5.7.15  | 5         | 8.77%   |
| 5.5.19  | 4         | 7.02%   |
| 5.7.8   | 3         | 5.26%   |
| 5.10.2  | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 63.16%  |
| 5.7     | 8         | 14.04%  |
| 5.6     | 8         | 14.04%  |
| 5.5     | 4         | 7.02%   |
| 5.10    | 1         | 1.75%   |

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


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 45        | 78.95%  |
| KDE        | 8         | 14.04%  |
| Cinnamon   | 3         | 5.26%   |
| Unknown    | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 57        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 56.14%  |
| SDDM    | 14        | 24.56%  |
| LightDM | 11        | 19.3%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 17        | 29.82%  |
| en_US | 9         | 15.79%  |
| pl_PL | 3         | 5.26%   |
| it_IT | 3         | 5.26%   |
| fr_FR | 3         | 5.26%   |
| en_AU | 3         | 5.26%   |
| C     | 3         | 5.26%   |
| es_ES | 2         | 3.51%   |
| es_AR | 2         | 3.51%   |
| en_CA | 2         | 3.51%   |
| de_DE | 2         | 3.51%   |
| sv_SE | 1         | 1.75%   |
| sr_RS | 1         | 1.75%   |
| ro_RO | 1         | 1.75%   |
| fr_CA | 1         | 1.75%   |
| es_CL | 1         | 1.75%   |
| en_ZA | 1         | 1.75%   |
| en_IN | 1         | 1.75%   |
| cs_CZ | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 64.91%  |
| EFI  | 20        | 35.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 94.74%  |
| Xfs     | 1         | 1.75%   |
| Overlay | 1         | 1.75%   |
| Btrfs   | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 91.23%  |
| MBR     | 3         | 5.26%   |
| GPT     | 2         | 3.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 85.96%  |
| Yes       | 8         | 14.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 80.7%   |
| Yes       | 11        | 19.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 19.3%   |
| Hewlett-Packard     | 8         | 14.04%  |
| Lenovo              | 5         | 8.77%   |
| Gigabyte Technology | 5         | 8.77%   |
| ASUSTek Computer    | 5         | 8.77%   |
| ASRock              | 4         | 7.02%   |
| Acer                | 4         | 7.02%   |
| MSI                 | 3         | 5.26%   |
| Toshiba             | 1         | 1.75%   |
| Supermicro          | 1         | 1.75%   |
| Samsung Electronics | 1         | 1.75%   |
| Positivo            | 1         | 1.75%   |
| Pegatron            | 1         | 1.75%   |
| PCWare              | 1         | 1.75%   |
| Olivetti            | 1         | 1.75%   |
| Medion              | 1         | 1.75%   |
| Jumper              | 1         | 1.75%   |
| Intel               | 1         | 1.75%   |
| ECS                 | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite C50D-A-12R          | 1         | 1.75%   |
| Supermicro H8DG6/H8DGi                | 1         | 1.75%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 1.75%   |
| Positivo Mobile                       | 1         | 1.75%   |
| Pegatron B34C                         | 1         | 1.75%   |
| PCWare IPMH61R2                       | 1         | 1.75%   |
| Olivetti P55-AEU-323-4G320            | 1         | 1.75%   |
| MSI MS-7B84                           | 1         | 1.75%   |
| MSI MS-7913                           | 1         | 1.75%   |
| MSI MS-7309                           | 1         | 1.75%   |
| Medion S4216                          | 1         | 1.75%   |
| Lenovo Y70-70 Touch 80DU              | 1         | 1.75%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J | 1         | 1.75%   |
| Lenovo ThinkPad T450s 20BWS0YF00      | 1         | 1.75%   |
| Lenovo G550 2958                      | 1         | 1.75%   |
| Lenovo G505 20240                     | 1         | 1.75%   |
| Jumper Ezpad                          | 1         | 1.75%   |
| Intel B75                             | 1         | 1.75%   |
| HP ProBook 6560b                      | 1         | 1.75%   |
| HP Mini 210-1000                      | 1         | 1.75%   |
| HP G42                                | 1         | 1.75%   |
| HP EliteBook Folio 9470m              | 1         | 1.75%   |
| HP Compaq Presario CQ50               | 1         | 1.75%   |
| HP 250 G7 Notebook PC                 | 1         | 1.75%   |
| HP 250 G6 Notebook PC                 | 1         | 1.75%   |
| HP 202 G2 MT                          | 1         | 1.75%   |
| Gigabyte X570 UD                      | 1         | 1.75%   |
| Gigabyte P57V6                        | 1         | 1.75%   |
| Gigabyte G31M-ES2C                    | 1         | 1.75%   |
| Gigabyte B450 AORUS M                 | 1         | 1.75%   |
| Gigabyte 970A-DS3P                    | 1         | 1.75%   |
| ECS A780GM-A                          | 1         | 1.75%   |
| Dell Vostro 1000                      | 1         | 1.75%   |
| Dell PowerEdge R810                   | 1         | 1.75%   |
| Dell OptiPlex 9010 AIO                | 1         | 1.75%   |
| Dell OptiPlex 360                     | 1         | 1.75%   |
| Dell Latitude E6420                   | 1         | 1.75%   |
| Dell Inspiron 5423                    | 1         | 1.75%   |
| Dell Inspiron 3646                    | 1         | 1.75%   |
| Dell Inspiron 3520                    | 1         | 1.75%   |
| Dell Inspiron 3421                    | 1         | 1.75%   |
| Dell Inspiron 1525                    | 1         | 1.75%   |
| Dell Inspiron 15-3567                 | 1         | 1.75%   |
| ASUS TUF Gaming FX506LI_FX506LI       | 1         | 1.75%   |
| ASUS P8Z68-V LE                       | 1         | 1.75%   |
| ASUS K72Jr                            | 1         | 1.75%   |
| ASUS K50C                             | 1         | 1.75%   |
| ASUS All Series                       | 1         | 1.75%   |
| ASRock N68-GE3 UCC                    | 1         | 1.75%   |
| ASRock ConRoe1333-D667                | 1         | 1.75%   |
| ASRock B450M Steel Legend             | 1         | 1.75%   |
| ASRock 970 Extreme4                   | 1         | 1.75%   |
| Apple iMac8,1                         | 1         | 1.75%   |
| Acer Aspire ES1-512                   | 1         | 1.75%   |
| Acer Aspire E1-531                    | 1         | 1.75%   |
| Acer Aspire A515-51G                  | 1         | 1.75%   |
| Acer Aspire 5720Z                     | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 6         | 10.53%  |
| Acer Aspire                | 4         | 7.02%   |
| Lenovo ThinkPad            | 2         | 3.51%   |
| HP 250                     | 2         | 3.51%   |
| Dell OptiPlex              | 2         | 3.51%   |
| Toshiba Satellite          | 1         | 1.75%   |
| Supermicro H8DG6           | 1         | 1.75%   |
| Samsung 305E4A             | 1         | 1.75%   |
| Positivo Mobile            | 1         | 1.75%   |
| Pegatron B34C              | 1         | 1.75%   |
| PCWare IPMH61R2            | 1         | 1.75%   |
| Olivetti P55-AEU-323-4G320 | 1         | 1.75%   |
| MSI MS-7B84                | 1         | 1.75%   |
| MSI MS-7913                | 1         | 1.75%   |
| MSI MS-7309                | 1         | 1.75%   |
| Medion S4216               | 1         | 1.75%   |
| Lenovo Y70-70              | 1         | 1.75%   |
| Lenovo G550                | 1         | 1.75%   |
| Lenovo G505                | 1         | 1.75%   |
| Jumper Ezpad               | 1         | 1.75%   |
| Intel B75                  | 1         | 1.75%   |
| HP ProBook                 | 1         | 1.75%   |
| HP Mini                    | 1         | 1.75%   |
| HP G42                     | 1         | 1.75%   |
| HP EliteBook               | 1         | 1.75%   |
| HP Compaq                  | 1         | 1.75%   |
| HP 202                     | 1         | 1.75%   |
| Gigabyte X570              | 1         | 1.75%   |
| Gigabyte P57V6             | 1         | 1.75%   |
| Gigabyte G31M-ES2C         | 1         | 1.75%   |
| Gigabyte B450              | 1         | 1.75%   |
| Gigabyte 970A-DS3P         | 1         | 1.75%   |
| ECS A780GM-A               | 1         | 1.75%   |
| Dell Vostro                | 1         | 1.75%   |
| Dell PowerEdge             | 1         | 1.75%   |
| Dell Latitude              | 1         | 1.75%   |
| ASUS TUF                   | 1         | 1.75%   |
| ASUS P8Z68-V               | 1         | 1.75%   |
| ASUS K72Jr                 | 1         | 1.75%   |
| ASUS K50C                  | 1         | 1.75%   |
| ASUS All                   | 1         | 1.75%   |
| ASRock N68-GE3             | 1         | 1.75%   |
| ASRock ConRoe1333-D667     | 1         | 1.75%   |
| ASRock B450M               | 1         | 1.75%   |
| ASRock 970                 | 1         | 1.75%   |
| Apple iMac8                | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 7         | 12.28%  |
| 2015    | 7         | 12.28%  |
| 2011    | 7         | 12.28%  |
| 2013    | 6         | 10.53%  |
| 2009    | 5         | 8.77%   |
| 2014    | 4         | 7.02%   |
| 2020    | 3         | 5.26%   |
| 2018    | 3         | 5.26%   |
| 2012    | 3         | 5.26%   |
| 2010    | 3         | 5.26%   |
| 2008    | 3         | 5.26%   |
| 2016    | 2         | 3.51%   |
| 2021    | 1         | 1.75%   |
| 2007    | 1         | 1.75%   |
| 2006    | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 33        | 57.89%  |
| Desktop    | 19        | 33.33%  |
| All in one | 2         | 3.51%   |
| Server     | 2         | 3.51%   |
| Tablet     | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 56        | 96.55%  |
| Enabled  | 2         | 3.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 25        | 43.86%  |
| 4.01-8.0        | 12        | 21.05%  |
| 16.01-24.0      | 8         | 14.04%  |
| 8.01-16.0       | 4         | 7.02%   |
| 1.01-2.0        | 3         | 5.26%   |
| 32.01-64.0      | 2         | 3.51%   |
| More than 256.0 | 1         | 1.75%   |
| 2.01-3.0        | 1         | 1.75%   |
| 64.01-256.0     | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 30        | 51.72%  |
| 2.01-3.0  | 13        | 22.41%  |
| 3.01-4.0  | 10        | 17.24%  |
| 4.01-8.0  | 2         | 3.45%   |
| 8.01-16.0 | 2         | 3.45%   |
| 0.51-1.0  | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 37        | 64.91%  |
| 2       | 12        | 21.05%  |
| 3       | 5         | 8.77%   |
| 6       | 1         | 1.75%   |
| 4       | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 57.89%  |
| No        | 24        | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 100%    |

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
| No        | 34        | 59.65%  |
| Yes       | 23        | 40.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 17        | 29.82%  |
| USA          | 9         | 15.79%  |
| Poland       | 3         | 5.26%   |
| Italy        | 3         | 5.26%   |
| Canada       | 3         | 5.26%   |
| Australia    | 3         | 5.26%   |
| Spain        | 2         | 3.51%   |
| South Africa | 2         | 3.51%   |
| Germany      | 2         | 3.51%   |
| France       | 2         | 3.51%   |
| Argentina    | 2         | 3.51%   |
| Sweden       | 1         | 1.75%   |
| Serbia       | 1         | 1.75%   |
| Russia       | 1         | 1.75%   |
| Romania      | 1         | 1.75%   |
| India        | 1         | 1.75%   |
| Czechia      | 1         | 1.75%   |
| Croatia      | 1         | 1.75%   |
| Chile        | 1         | 1.75%   |
| Cameroon     | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Curitiba              | 4         | 6.78%   |
| Krakow                | 2         | 3.39%   |
| Belo Horizonte        | 2         | 3.39%   |
| Zielonka              | 1         | 1.69%   |
| Zagreb                | 1         | 1.69%   |
| Winter Springs        | 1         | 1.69%   |
| Winston-Salem         | 1         | 1.69%   |
| Villemomble           | 1         | 1.69%   |
| Vila Velha            | 1         | 1.69%   |
| Taboao da Serra       | 1         | 1.69%   |
| Sydney                | 1         | 1.69%   |
| Stockholm             | 1         | 1.69%   |
| S??o Paulo            | 1         | 1.69%   |
| Sao Bernardo          | 1         | 1.69%   |
| Salerno               | 1         | 1.69%   |
| Saladas               | 1         | 1.69%   |
| Saint-Germain-en-Laye | 1         | 1.69%   |
| Rosario               | 1         | 1.69%   |
| Rio de Janeiro        | 1         | 1.69%   |
| Recife                | 1         | 1.69%   |
| Ramenskoye            | 1         | 1.69%   |
| Porto Alegre          | 1         | 1.69%   |
| Port Elizabeth        | 1         | 1.69%   |
| Pontevedra            | 1         | 1.69%   |
| Pietra Ligure         | 1         | 1.69%   |
| Ostrava               | 1         | 1.69%   |
| North Lewisburg       | 1         | 1.69%   |
| Newmarket             | 1         | 1.69%   |
| Moreno Valley         | 1         | 1.69%   |
| Montreal              | 1         | 1.69%   |
| Monserrato            | 1         | 1.69%   |
| Madrid                | 1         | 1.69%   |
| Londrina              | 1         | 1.69%   |
| Launceston            | 1         | 1.69%   |
| Karlsruhe             | 1         | 1.69%   |
| Jundia?­              | 1         | 1.69%   |
| Johannesburg          | 1         | 1.69%   |
| Itatiba               | 1         | 1.69%   |
| Hobart                | 1         | 1.69%   |
| Eureka                | 1         | 1.69%   |
| Edmundston            | 1         | 1.69%   |
| Douglas               | 1         | 1.69%   |
| Douala                | 1         | 1.69%   |
| Coos Bay              | 1         | 1.69%   |
| Cincinnati            | 1         | 1.69%   |
| Central               | 1         | 1.69%   |
| Castroville           | 1         | 1.69%   |
| Bonn                  | 1         | 1.69%   |
| Bhopal                | 1         | 1.69%   |
| Belgrade              | 1         | 1.69%   |
| Bel?©m                | 1         | 1.69%   |
| Barcelona             | 1         | 1.69%   |
| Arad                  | 1         | 1.69%   |
| Adelaide CBD          | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 20.25%  |
| Seagate             | 11        | 14     | 13.92%  |
| Samsung Electronics | 7         | 8      | 8.86%   |
| Kingston            | 7         | 8      | 8.86%   |
| Hitachi             | 7         | 8      | 8.86%   |
| Toshiba             | 6         | 6      | 7.59%   |
| Unknown             | 3         | 4      | 3.8%    |
| SanDisk             | 3         | 3      | 3.8%    |
| MAXTOR              | 2         | 2      | 2.53%   |
| LITEONIT            | 2         | 2      | 2.53%   |
| HGST                | 2         | 3      | 2.53%   |
| A-DATA Technology   | 2         | 2      | 2.53%   |
| XPG                 | 1         | 1      | 1.27%   |
| TO Exter            | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| Phison              | 1         | 1      | 1.27%   |
| Patriot             | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 1      | 1.27%   |
| Mushkin             | 1         | 1      | 1.27%   |
| Hewlett-Packard     | 1         | 1      | 1.27%   |
| GOODRAM             | 1         | 1      | 1.27%   |
| China               | 1         | 1      | 1.27%   |
| ASMT109x            | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2.44%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2.44%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2.44%   |
| XPG GAMMIX S11 Pro 1TB               | 1         | 1.22%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.22%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 1.22%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 1.22%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 1.22%   |
| WDC WD400JD-55MSA1 40GB              | 1         | 1.22%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1.22%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 1         | 1.22%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 1.22%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 1.22%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 1.22%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 1.22%   |
| WDC WD10EARX-00N0YB0 1TB             | 1         | 1.22%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 1         | 1.22%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 1         | 1.22%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 1.22%   |
| Unknown MMC Card  8GB                | 1         | 1.22%   |
| Unknown MMC Card  64GB               | 1         | 1.22%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1.22%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1.22%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1.22%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1.22%   |
| TO Exter nal USB 3.0 160GB           | 1         | 1.22%   |
| Seagate ST9320325AS 320GB            | 1         | 1.22%   |
| Seagate ST9160827AS 160GB            | 1         | 1.22%   |
| Seagate ST9160314AS 160GB            | 1         | 1.22%   |
| Seagate ST500LX012-SSHD-8GB          | 1         | 1.22%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.22%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1.22%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1.22%   |
| Seagate ST32000645NS 2TB             | 1         | 1.22%   |
| Seagate ST3160215A 160GB             | 1         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.22%   |
| Seagate Expansion Desk 4TB           | 1         | 1.22%   |
| SanDisk SSD PLUS 1000GB              | 1         | 1.22%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 1.22%   |
| Sandisk NVMe SSD Drive 500GB         | 1         | 1.22%   |
| Samsung SSD SM841 2.5 7mm 128GB      | 1         | 1.22%   |
| Samsung SSD 850 EVO 500GB            | 1         | 1.22%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.22%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD  | 1         | 1.22%   |
| Samsung HM321HI 320GB                | 1         | 1.22%   |
| Samsung HD501LJ 500GB                | 1         | 1.22%   |
| Samsung HD321KJ 320GB                | 1         | 1.22%   |
| Samsung HD161HJ 41R0186LEN 160GB     | 1         | 1.22%   |
| PNY SSD2SC240G1SA754D117-443 240GB   | 1         | 1.22%   |
| Phison NVMe SSD Drive 1TB            | 1         | 1.22%   |
| Patriot Burst 120GB SSD              | 1         | 1.22%   |
| OCZ ARC100 240GB SSD                 | 1         | 1.22%   |
| Mushkin MKNSSDSR250GB                | 1         | 1.22%   |
| MAXTOR STM3160215AS 160GB            | 1         | 1.22%   |
| MAXTOR 6Y120L0 122GB                 | 1         | 1.22%   |
| LITEONIT LMT-256M6M-HP 256GB SSD     | 1         | 1.22%   |
| LITEONIT LGT-256M6G 256GB SSD        | 1         | 1.22%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 31.25%  |
| Seagate             | 11        | 14     | 22.92%  |
| Hitachi             | 7         | 8      | 14.58%  |
| Toshiba             | 6         | 6      | 12.5%   |
| Samsung Electronics | 3         | 4      | 6.25%   |
| MAXTOR              | 2         | 2      | 4.17%   |
| HGST                | 2         | 3      | 4.17%   |
| TO Exter            | 1         | 1      | 2.08%   |
| ASMT109x            | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 25%     |
| Samsung Electronics | 4         | 4      | 16.67%  |
| SanDisk             | 2         | 2      | 8.33%   |
| LITEONIT            | 2         | 2      | 8.33%   |
| A-DATA Technology   | 2         | 2      | 8.33%   |
| WDC                 | 1         | 2      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| Patriot             | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| Mushkin             | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |
| GOODRAM             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 54     | 57.14%  |
| SSD  | 23        | 26     | 32.86%  |
| NVMe | 5         | 6      | 7.14%   |
| MMC  | 2         | 2      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 78     | 85.48%  |
| NVMe | 5         | 6      | 8.06%   |
| SAS  | 2         | 2      | 3.23%   |
| MMC  | 2         | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 64     | 78.13%  |
| 0.51-1.0   | 9         | 10     | 14.06%  |
| 3.01-4.0   | 3         | 3      | 4.69%   |
| 1.01-2.0   | 2         | 3      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 39.66%  |
| 251-500        | 16        | 27.59%  |
| 51-100         | 5         | 8.62%   |
| 21-50          | 4         | 6.9%    |
| 501-1000       | 4         | 6.9%    |
| 1001-2000      | 3         | 5.17%   |
| 1-20           | 2         | 3.45%   |
| More than 3000 | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 30        | 51.72%  |
| 21-50    | 14        | 24.14%  |
| 101-250  | 4         | 6.9%    |
| 501-1000 | 4         | 6.9%    |
| 51-100   | 4         | 6.9%    |
| 251-500  | 2         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |
| Hitachi HTS722012K9A300 120GB   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 52        | 81     | 89.66%  |
| Works    | 4         | 5      | 6.9%    |
| Malfunc  | 2         | 2      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 59.38%  |
| AMD                              | 14        | 21.88%  |
| Silicon Integrated Systems [SiS] | 2         | 3.13%   |
| Nvidia                           | 2         | 3.13%   |
| ASMedia Technology               | 2         | 3.13%   |
| ADATA Technology                 | 2         | 3.13%   |
| Sandisk                          | 1         | 1.56%   |
| Phison Electronics               | 1         | 1.56%   |
| LSI Logic / Symbios Logic        | 1         | 1.56%   |
| Kingston Technology Company      | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 9.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 5.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 4.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 3.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 3.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 3.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 3.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.53%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 2.35%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 2.35%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 2.35%   |
| Nvidia MCP61 IDE                                                                        | 2         | 2.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 2.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 2.35%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 2         | 2.35%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 2         | 2.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 2.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.35%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 2.35%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.18%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.18%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.18%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1         | 1.18%   |
| AMD SB600 IDE                                                                           | 1         | 1.18%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 61.97%  |
| IDE  | 19        | 26.76%  |
| NVMe | 5         | 7.04%   |
| RAID | 3         | 4.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 71.93%  |
| AMD    | 16        | 28.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics     | 3         | 5.26%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 3.51%   |
| Intel Xeon CPU E7- 4870 @ 2.40GHz           | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.75%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 1.75%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.75%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.75%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.75%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1         | 1.75%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.75%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.75%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-3570S CPU @ 3.10GHz           | 1         | 1.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.75%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.75%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.75%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 1.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.75%   |
| Intel Celeron D CPU 220 @ 1.20GHz           | 1         | 1.75%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.75%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1         | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 1.75%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1         | 1.75%   |
| AMD Phenom 9650 Quad-Core Processor         | 1         | 1.75%   |
| AMD Opteron Processor 6272                  | 1         | 1.75%   |
| AMD FX-8320 Eight-Core Processor            | 1         | 1.75%   |
| AMD FX-6300 Six-Core Processor              | 1         | 1.75%   |
| AMD Athlon II X2 260 Processor              | 1         | 1.75%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55  | 1         | 1.75%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+  | 1         | 1.75%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 1         | 1.75%   |
| AMD A6-3420M APU with Radeon HD Graphics    | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 17.54%  |
| Intel Core i7           | 7         | 12.28%  |
| Intel Core i3           | 6         | 10.53%  |
| Intel Pentium Dual      | 4         | 7.02%   |
| Intel Core 2 Duo        | 4         | 7.02%   |
| Intel Pentium           | 3         | 5.26%   |
| AMD A4                  | 3         | 5.26%   |
| Intel Celeron           | 2         | 3.51%   |
| Intel Atom              | 2         | 3.51%   |
| AMD FX                  | 2         | 3.51%   |
| AMD Athlon 64 X2        | 2         | 3.51%   |
| Intel Xeon              | 1         | 1.75%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Celeron D         | 1         | 1.75%   |
| AMD Ryzen 9             | 1         | 1.75%   |
| AMD Ryzen 7             | 1         | 1.75%   |
| AMD Ryzen 5             | 1         | 1.75%   |
| AMD Ryzen 3             | 1         | 1.75%   |
| AMD Phenom              | 1         | 1.75%   |
| AMD Opteron             | 1         | 1.75%   |
| AMD Athlon II X2        | 1         | 1.75%   |
| AMD A8                  | 1         | 1.75%   |
| AMD A6                  | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 54.39%  |
| 4      | 17        | 29.82%  |
| 1      | 3         | 5.26%   |
| 40     | 1         | 1.75%   |
| 16     | 1         | 1.75%   |
| 12     | 1         | 1.75%   |
| 8      | 1         | 1.75%   |
| 6      | 1         | 1.75%   |
| 3      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 96.49%  |
| 4      | 1         | 1.75%   |
| 2      | 1         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 50.88%  |
| 2      | 28        | 49.12%  |

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
| Unknown    | 11        | 19.3%   |
| 0x306a9    | 8         | 14.04%  |
| 0x6fd      | 5         | 8.77%   |
| 0x206a7    | 5         | 8.77%   |
| 0x806e9    | 3         | 5.26%   |
| 0x306c3    | 2         | 3.51%   |
| 0x30678    | 2         | 3.51%   |
| 0x20655    | 2         | 3.51%   |
| 0x0700010f | 2         | 3.51%   |
| 0xa0652    | 1         | 1.75%   |
| 0x706a1    | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x40651    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x206f2    | 1         | 1.75%   |
| 0x1067a    | 1         | 1.75%   |
| 0x10676    | 1         | 1.75%   |
| 0x10661    | 1         | 1.75%   |
| 0x08701013 | 1         | 1.75%   |
| 0x08108109 | 1         | 1.75%   |
| 0x07000106 | 1         | 1.75%   |
| 0x06000852 | 1         | 1.75%   |
| 0x03000027 | 1         | 1.75%   |
| 0x010000c8 | 1         | 1.75%   |
| 0x01000095 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 8         | 14.04%  |
| Core          | 6         | 10.53%  |
| SandyBridge   | 5         | 8.77%   |
| Penryn        | 4         | 7.02%   |
| Haswell       | 4         | 7.02%   |
| Zen 2         | 3         | 5.26%   |
| Westmere      | 3         | 5.26%   |
| Silvermont    | 3         | 5.26%   |
| Piledriver    | 3         | 5.26%   |
| KabyLake      | 3         | 5.26%   |
| Jaguar        | 3         | 5.26%   |
| K8 Hammer     | 2         | 3.51%   |
| K10           | 2         | 3.51%   |
| Zen+          | 1         | 1.75%   |
| Skylake       | 1         | 1.75%   |
| K10 Llano     | 1         | 1.75%   |
| Goldmont plus | 1         | 1.75%   |
| CometLake     | 1         | 1.75%   |
| Bulldozer     | 1         | 1.75%   |
| Broadwell     | 1         | 1.75%   |
| Bonnell       | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 32        | 49.23%  |
| Nvidia                           | 15        | 23.08%  |
| AMD                              | 14        | 21.54%  |
| Silicon Integrated Systems [SiS] | 2         | 3.08%   |
| Matrox Electronics Systems       | 2         | 3.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 8.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.97%   |
| Intel HD Graphics 620                                                                    | 3         | 4.48%   |
| AMD Kabini [Radeon HD 8330]                                                              | 3         | 4.48%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 2.99%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.99%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.49%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1         | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.49%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.49%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 1.49%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.49%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.49%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1         | 1.49%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1         | 1.49%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.49%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.49%   |
| Intel HD Graphics 530                                                                    | 1         | 1.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.49%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1         | 1.49%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.49%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.49%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 1         | 1.49%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1         | 1.49%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 1         | 1.49%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 1.49%   |
| AMD Picasso                                                                              | 1         | 1.49%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 26        | 45.61%  |
| 1 x AMD         | 14        | 24.56%  |
| 1 x Nvidia      | 8         | 14.04%  |
| Intel + Nvidia  | 5         | 8.77%   |
| 1 x SiS         | 2         | 3.51%   |
| Nvidia + Matrox | 1         | 1.75%   |
| 1 x Matrox      | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 84.21%  |
| Unknown     | 7         | 12.28%  |
| Proprietary | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 63.79%  |
| 0.01-0.5   | 10        | 17.24%  |
| 1.01-2.0   | 5         | 8.62%   |
| 3.01-4.0   | 3         | 5.17%   |
| 0.51-1.0   | 2         | 3.45%   |
| 5.01-6.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 10        | 18.18%  |
| AU Optronics            | 9         | 16.36%  |
| LG Display              | 8         | 14.55%  |
| Goldstar                | 5         | 9.09%   |
| Chimei Innolux          | 5         | 9.09%   |
| BOE                     | 3         | 5.45%   |
| Acer                    | 3         | 5.45%   |
| ViewSonic               | 1         | 1.82%   |
| Unknown                 | 1         | 1.82%   |
| Sony                    | 1         | 1.82%   |
| Sceptre Tech            | 1         | 1.82%   |
| Philips                 | 1         | 1.82%   |
| NXP                     | 1         | 1.82%   |
| Lenovo                  | 1         | 1.82%   |
| Hewlett-Packard         | 1         | 1.82%   |
| Chi Mei Optoelectronics | 1         | 1.82%   |
| BenQ                    | 1         | 1.82%   |
| Apple                   | 1         | 1.82%   |
| Ancor Communications    | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 3.51%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch              | 2         | 3.51%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                      | 2         | 3.51%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 3.51%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                | 1         | 1.75%   |
| Unknown LCD Monitor SHI LCD-TV 4640x1080                                 | 1         | 1.75%   |
| Sony LCD Monitor AVSYSTEM                                                | 1         | 1.75%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                   | 1         | 1.75%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 1.75%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 1.75%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 510x290mm 23.1-inch       | 1         | 1.75%   |
| Samsung Electronics S/T 77/76DFX STN0006 1280x1024 312x234mm 15.4-inch   | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.75%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                       | 1         | 1.75%   |
| NXP OptiPlex 9010 NXP1111 1920x1080 510x286mm 23.0-inch                  | 1         | 1.75%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 1.75%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 527x296mm 23.8-inch                 | 1         | 1.75%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch             | 1         | 1.75%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                     | 1         | 1.75%   |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                      | 1         | 1.75%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 1.75%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE0657 1920x1080 344x194mm 15.5-inch                    | 1         | 1.75%   |
| BenQ LCD Monitor GL951A 2880x900                                         | 1         | 1.75%   |
| BenQ LCD Monitor GL951A                                                  | 1         | 1.75%   |
| BenQ GL951A BNQ7897 1440x900 408x255mm 18.9-inch                         | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.75%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 1.75%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                    | 1         | 1.75%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 1.75%   |
| Acer V226WL ACR0339 1680x1050 474x296mm 22.0-inch                        | 1         | 1.75%   |
| Acer LCD Monitor S230HL                                                  | 1         | 1.75%   |
| Acer G226HQL ACR02EA 1920x1080 480x270mm 21.7-inch                       | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 20        | 35.71%  |
| 1920x1080 (FHD)    | 14        | 25%     |
| 1600x900 (HD+)     | 5         | 8.93%   |
| 1280x800 (WXGA)    | 4         | 7.14%   |
| 1680x1050 (WSXGA+) | 2         | 3.57%   |
| 1280x1024 (SXGA)   | 2         | 3.57%   |
| Unknown            | 2         | 3.57%   |
| 4640x1080          | 1         | 1.79%   |
| 3840x2160 (4K)     | 1         | 1.79%   |
| 2880x900           | 1         | 1.79%   |
| 2560x1440 (QHD)    | 1         | 1.79%   |
| 1440x900 (WXGA+)   | 1         | 1.79%   |
| 1360x768           | 1         | 1.79%   |
| 1024x600           | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 35.19%  |
| 14      | 8         | 14.81%  |
| 21      | 4         | 7.41%   |
| 20      | 3         | 5.56%   |
| 17      | 3         | 5.56%   |
| 31      | 2         | 3.7%    |
| 24      | 2         | 3.7%    |
| 23      | 2         | 3.7%    |
| 19      | 2         | 3.7%    |
| 18      | 2         | 3.7%    |
| 13      | 2         | 3.7%    |
| Unknown | 2         | 3.7%    |
| 27      | 1         | 1.85%   |
| 22      | 1         | 1.85%   |
| 10      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 55.56%  |
| 401-500     | 12        | 22.22%  |
| 501-600     | 4         | 7.41%   |
| 601-700     | 3         | 5.56%   |
| 351-400     | 2         | 3.7%    |
| Unknown     | 2         | 3.7%    |
| 201-300     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 77.36%  |
| 16/10   | 8         | 15.09%  |
| Unknown | 2         | 3.77%   |
| 5/4     | 1         | 1.89%   |
| 4/3     | 1         | 1.89%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 33.33%  |
| 81-90          | 10        | 18.52%  |
| 201-250        | 8         | 14.81%  |
| 151-200        | 5         | 9.26%   |
| 141-150        | 3         | 5.56%   |
| 351-500        | 2         | 3.7%    |
| 121-130        | 2         | 3.7%    |
| Unknown        | 2         | 3.7%    |
| 41-50          | 1         | 1.85%   |
| 301-350        | 1         | 1.85%   |
| 251-300        | 1         | 1.85%   |
| 111-120        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 24        | 46.15%  |
| 51-100  | 18        | 34.62%  |
| 121-160 | 8         | 15.38%  |
| Unknown | 2         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 85.96%  |
| 0     | 4         | 7.02%   |
| 2     | 3         | 5.26%   |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 37        | 40.66%  |
| Qualcomm Atheros                  | 14        | 15.38%  |
| Intel                             | 13        | 14.29%  |
| Broadcom                          | 9         | 9.89%   |
| Broadcom Limited                  | 3         | 3.3%    |
| TP-Link                           | 2         | 2.2%    |
| Nvidia                            | 2         | 2.2%    |
| Marvell Technology Group          | 2         | 2.2%    |
| Silicon Integrated Systems [SiS]  | 1         | 1.1%    |
| Samsung Electronics               | 1         | 1.1%    |
| Ralink                            | 1         | 1.1%    |
| Qualcomm                          | 1         | 1.1%    |
| NetGear                           | 1         | 1.1%    |
| Ericsson Business Mobile Networks | 1         | 1.1%    |
| D-Link                            | 1         | 1.1%    |
| ASIX Electronics                  | 1         | 1.1%    |
| Accton Technology                 | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 26        | 23.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 8.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 2.75%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.83%   |
| Nvidia MCP61 Ethernet                                                   | 2         | 1.83%   |
| Intel Wireless 7260                                                     | 2         | 1.83%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.83%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.92%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.92%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                    | 1         | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.92%   |
| Qualcomm SDM660-MTP _SN:8F667B4D                                        | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.92%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 0.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 0.92%   |
| Intel Wireless 8260                                                     | 1         | 0.92%   |
| Intel Wireless 7265                                                     | 1         | 0.92%   |
| Intel Wireless 3165                                                     | 1         | 0.92%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.92%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.92%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 0.92%   |
| Intel 82576 Gigabit Network Connection                                  | 1         | 0.92%   |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 0.92%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1         | 0.92%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                          | 1         | 0.92%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 0.92%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 0.92%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 1         | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 0.92%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                  | 1         | 0.92%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 0.92%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.92%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.92%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 0.92%   |
| Accton WN7512BEP Wireless LAN adapter                                   | 1         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 14        | 29.79%  |
| Intel                 | 11        | 23.4%   |
| Realtek Semiconductor | 9         | 19.15%  |
| Broadcom              | 5         | 10.64%  |
| TP-Link               | 2         | 4.26%   |
| Broadcom Limited      | 2         | 4.26%   |
| Ralink                | 1         | 2.13%   |
| NetGear               | 1         | 2.13%   |
| D-Link                | 1         | 2.13%   |
| Accton Technology     | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 8.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 8.51%   |
| Realtek 802.11ac NIC                                                    | 2         | 4.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.26%   |
| Intel Wireless 7260                                                     | 2         | 4.26%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 4.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 4.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 2.13%   |
| TP-Link Archer T4U ver.3                                                | 1         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.13%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 2.13%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                    | 1         | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.13%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 2.13%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 2.13%   |
| Intel Wireless 8260                                                     | 1         | 2.13%   |
| Intel Wireless 7265                                                     | 1         | 2.13%   |
| Intel Wireless 3165                                                     | 1         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.13%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.13%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.13%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1         | 2.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 2.13%   |
| Accton WN7512BEP Wireless LAN adapter                                   | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 36        | 59.02%  |
| Intel                            | 7         | 11.48%  |
| Broadcom                         | 5         | 8.2%    |
| Qualcomm Atheros                 | 4         | 6.56%   |
| Nvidia                           | 2         | 3.28%   |
| Marvell Technology Group         | 2         | 3.28%   |
| Silicon Integrated Systems [SiS] | 1         | 1.64%   |
| Samsung Electronics              | 1         | 1.64%   |
| Qualcomm                         | 1         | 1.64%   |
| Broadcom Limited                 | 1         | 1.64%   |
| ASIX Electronics                 | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 42.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 14.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 3.28%   |
| Nvidia MCP61 Ethernet                                             | 2         | 3.28%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.64%   |
| Qualcomm SDM660-MTP _SN:8F667B4D                                  | 1         | 1.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.64%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.64%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.64%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.64%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 55.88%  |
| WiFi     | 44        | 43.14%  |
| Modem    | 1         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 55.56%  |
| WiFi     | 32        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 66.67%  |
| 1     | 16        | 28.07%  |
| 4     | 1         | 1.75%   |
| 3     | 1         | 1.75%   |
| 0     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 96.49%  |
| Yes  | 2         | 3.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 24%     |
| Qualcomm Atheros Communications | 5         | 20%     |
| Cambridge Silicon Radio         | 4         | 16%     |
| Realtek Semiconductor           | 2         | 8%      |
| Lite-On Technology              | 2         | 8%      |
| Hewlett-Packard                 | 2         | 8%      |
| Ralink Technology               | 1         | 4%      |
| Integrated System Solution      | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 16%     |
| Intel Bluetooth Device                                      | 3         | 12%     |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 8%      |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 8%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 8%      |
| Intel Bluetooth wireless interface                          | 2         | 8%      |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 4%      |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 4%      |
| Lite-On Bluetooth Device                                    | 1         | 4%      |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 4%      |
| Intel AX201 Bluetooth                                       | 1         | 4%      |
| Integrated System Solution KY-BT100 Bluetooth Adapter       | 1         | 4%      |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 4%      |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 4%      |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 4%      |
| Apple Bluetooth HCI                                         | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 37        | 48.68%  |
| AMD                              | 17        | 22.37%  |
| Nvidia                           | 13        | 17.11%  |
| Silicon Integrated Systems [SiS] | 2         | 2.63%   |
| C-Media Electronics              | 2         | 2.63%   |
| Texas Instruments                | 1         | 1.32%   |
| Logitech                         | 1         | 1.32%   |
| Creative Technology              | 1         | 1.32%   |
| Creative Labs                    | 1         | 1.32%   |
| Corsair                          | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 10.23%  |
| AMD FCH Azalia Controller                                                  | 5         | 5.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 3.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.41%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 3.41%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.27%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 2.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.27%   |
| Nvidia GF110 High Definition Audio Controller                              | 2         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.27%   |
| C-Media Electronics Audio Adapter                                          | 2         | 2.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.27%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.14%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.14%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.14%   |
| Logitech Logitech USB Microphone                                           | 1         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.14%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.14%   |
| Creative Technology Sound BlasterX G1                                      | 1         | 1.14%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 1.14%   |
| Corsair Corsair VOID PRO Surround USB Adapter                              | 1         | 1.14%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.14%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.14%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 1.14%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.14%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1         | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.14%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Corsair             | 3         | 30%     |
| SK Hynix            | 2         | 20%     |
| Kingston            | 2         | 20%     |
| Unknown             | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| G.Skill             | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                       | 1         | 10%     |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 10%     |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 10%     |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s      | 1         | 10%     |
| Kingston RAM KHX2400C11D3/8GX 8192MB DIMM DDR3 2400MT/s   | 1         | 10%     |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s   | 1         | 10%     |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 1         | 10%     |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s    | 1         | 10%     |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1         | 10%     |
| Corsair RAM CML16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s  | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 4         | 50%     |
| DDR4   | 2         | 25%     |
| SDRAM  | 1         | 12.5%   |
| LPDDR4 | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 4         | 50%     |
| DIMM   | 4         | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 4         | 44.44%  |
| 4096 | 3         | 33.33%  |
| 2048 | 2         | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3         | 33.33%  |
| 3266    | 1         | 11.11%  |
| 3200    | 1         | 11.11%  |
| 2667    | 1         | 11.11%  |
| 2400    | 1         | 11.11%  |
| 1066    | 1         | 11.11%  |
| Unknown | 1         | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 3052 | 1         | 100%    |

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
| Suyin                                  | 5         | 15.63%  |
| Chicony Electronics                    | 5         | 15.63%  |
| Realtek Semiconductor                  | 4         | 12.5%   |
| Microdia                               | 4         | 12.5%   |
| IMC Networks                           | 3         | 9.38%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.25%   |
| Syntek                                 | 1         | 3.13%   |
| Silicon Motion                         | 1         | 3.13%   |
| Ricoh                                  | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Microsoft                              | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Hewlett-Packard                        | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 6.25%   |
| Syntek Lenovo EasyCamera                                    | 1         | 3.13%   |
| Suyin HP Webcam-50                                          | 1         | 3.13%   |
| Suyin HP Webcam-101                                         | 1         | 3.13%   |
| Suyin HP Integrated Webcam                                  | 1         | 3.13%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 3.13%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 3.13%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 3.13%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 3.13%   |
| Realtek Lenovo EasyCamera                                   | 1         | 3.13%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 3.13%   |
| Realtek Integrated_Webcam_HD                                | 1         | 3.13%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 3.13%   |
| Quanta HD Webcam                                            | 1         | 3.13%   |
| Microsoft LifeCam HD-3000                                   | 1         | 3.13%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.13%   |
| Microdia USB 2.0 Camera                                     | 1         | 3.13%   |
| Logitech QuickCam Pro 9000                                  | 1         | 3.13%   |
| Lite-On Integrated Camera                                   | 1         | 3.13%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.13%   |
| IMC Networks Integrated Webcam                              | 1         | 3.13%   |
| HP Webcam 3100                                              | 1         | 3.13%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 3.13%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.13%   |
| Chicony Integrated Camera                                   | 1         | 3.13%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.13%   |
| Chicony HD WebCam                                           | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 3.13%   |
| Apple Built-in iSight                                       | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 40        | 68.97%  |
| 1     | 17        | 29.31%  |
| 2     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 8         | 40%     |
| Net/wireless       | 7         | 35%     |
| Fingerprint reader | 2         | 10%     |
| Chipcard           | 2         | 10%     |
| Storage            | 1         | 5%      |

