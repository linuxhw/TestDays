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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-52-generic            | 10        | 18.87%  |
| 5.6.15-windowsfx-10-generic | 8         | 15.09%  |
| 5.4.0-72-generic            | 6         | 11.32%  |
| 5.7.15-050715-generic       | 5         | 9.43%   |
| 5.4.0-65-generic            | 4         | 7.55%   |
| 5.7.8-windowsfx-generic     | 3         | 5.66%   |
| 5.5.19-050519-generic       | 3         | 5.66%   |
| 5.4.0-42-generic            | 3         | 5.66%   |
| 5.4.0-29-generic            | 3         | 5.66%   |
| 5.4.0-73-generic            | 2         | 3.77%   |
| 5.4.0-56-generic            | 2         | 3.77%   |
| 5.4.0-54-generic            | 2         | 3.77%   |
| 5.4.0-66-generic            | 1         | 1.89%   |
| 5.10.2-051002-generic       | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 62.26%  |
| 5.6.15  | 8         | 15.09%  |
| 5.7.15  | 5         | 9.43%   |
| 5.7.8   | 3         | 5.66%   |
| 5.5.19  | 3         | 5.66%   |
| 5.10.2  | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 62.26%  |
| 5.7     | 8         | 15.09%  |
| 5.6     | 8         | 15.09%  |
| 5.5     | 3         | 5.66%   |
| 5.10    | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 41        | 77.36%  |
| KDE        | 8         | 15.09%  |
| Cinnamon   | 3         | 5.66%   |
| Unknown    | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 53        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 58.49%  |
| SDDM    | 11        | 20.75%  |
| LightDM | 11        | 20.75%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 17        | 32.08%  |
| en_US | 7         | 13.21%  |
| pl_PL | 3         | 5.66%   |
| it_IT | 3         | 5.66%   |
| fr_FR | 3         | 5.66%   |
| en_AU | 3         | 5.66%   |
| C     | 3         | 5.66%   |
| es_AR | 2         | 3.77%   |
| en_CA | 2         | 3.77%   |
| de_DE | 2         | 3.77%   |
| sv_SE | 1         | 1.89%   |
| sr_RS | 1         | 1.89%   |
| ro_RO | 1         | 1.89%   |
| fr_CA | 1         | 1.89%   |
| es_ES | 1         | 1.89%   |
| es_CL | 1         | 1.89%   |
| en_ZA | 1         | 1.89%   |
| en_IN | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 34        | 64.15%  |
| EFI  | 19        | 35.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 96.23%  |
| Overlay | 1         | 1.89%   |
| Btrfs   | 1         | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 90.57%  |
| MBR     | 3         | 5.66%   |
| GPT     | 2         | 3.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 84.91%  |
| Yes       | 8         | 15.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 81.13%  |
| Yes       | 10        | 18.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 18.87%  |
| Hewlett-Packard     | 7         | 13.21%  |
| Lenovo              | 5         | 9.43%   |
| Gigabyte Technology | 5         | 9.43%   |
| ASUSTek Computer    | 5         | 9.43%   |
| Acer                | 4         | 7.55%   |
| ASRock              | 3         | 5.66%   |
| MSI                 | 2         | 3.77%   |
| Toshiba             | 1         | 1.89%   |
| Supermicro          | 1         | 1.89%   |
| Samsung Electronics | 1         | 1.89%   |
| Positivo            | 1         | 1.89%   |
| Pegatron            | 1         | 1.89%   |
| PCWare              | 1         | 1.89%   |
| Olivetti            | 1         | 1.89%   |
| Medion              | 1         | 1.89%   |
| Jumper              | 1         | 1.89%   |
| Intel               | 1         | 1.89%   |
| ECS                 | 1         | 1.89%   |
| Apple               | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite C50D-A-12R          | 1         | 1.89%   |
| Supermicro H8DG6/H8DGi                | 1         | 1.89%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 1.89%   |
| Positivo Mobile                       | 1         | 1.89%   |
| Pegatron B34C                         | 1         | 1.89%   |
| PCWare IPMH61R2                       | 1         | 1.89%   |
| Olivetti P55-AEU-323-4G320            | 1         | 1.89%   |
| MSI MS-7B84                           | 1         | 1.89%   |
| MSI MS-7913                           | 1         | 1.89%   |
| Medion S4216                          | 1         | 1.89%   |
| Lenovo Y70-70 Touch 80DU              | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J | 1         | 1.89%   |
| Lenovo ThinkPad T450s 20BWS0YF00      | 1         | 1.89%   |
| Lenovo G550 2958                      | 1         | 1.89%   |
| Lenovo G505 20240                     | 1         | 1.89%   |
| Jumper Ezpad                          | 1         | 1.89%   |
| Intel B75                             | 1         | 1.89%   |
| HP ProBook 6560b                      | 1         | 1.89%   |
| HP Mini 210-1000                      | 1         | 1.89%   |
| HP G42                                | 1         | 1.89%   |
| HP EliteBook Folio 9470m              | 1         | 1.89%   |
| HP Compaq Presario CQ50               | 1         | 1.89%   |
| HP 250 G6 Notebook PC                 | 1         | 1.89%   |
| HP 202 G2 MT                          | 1         | 1.89%   |
| Gigabyte X570 UD                      | 1         | 1.89%   |
| Gigabyte P57V6                        | 1         | 1.89%   |
| Gigabyte G31M-ES2C                    | 1         | 1.89%   |
| Gigabyte B450 AORUS M                 | 1         | 1.89%   |
| Gigabyte 970A-DS3P                    | 1         | 1.89%   |
| ECS A780GM-A                          | 1         | 1.89%   |
| Dell Vostro 1000                      | 1         | 1.89%   |
| Dell PowerEdge R810                   | 1         | 1.89%   |
| Dell OptiPlex 9010 AIO                | 1         | 1.89%   |
| Dell OptiPlex 360                     | 1         | 1.89%   |
| Dell Inspiron 5423                    | 1         | 1.89%   |
| Dell Inspiron 3646                    | 1         | 1.89%   |
| Dell Inspiron 3520                    | 1         | 1.89%   |
| Dell Inspiron 3421                    | 1         | 1.89%   |
| Dell Inspiron 1525                    | 1         | 1.89%   |
| Dell Inspiron 15-3567                 | 1         | 1.89%   |
| ASUS TUF Gaming FX506LI_FX506LI       | 1         | 1.89%   |
| ASUS P8Z68-V LE                       | 1         | 1.89%   |
| ASUS K72Jr                            | 1         | 1.89%   |
| ASUS K50C                             | 1         | 1.89%   |
| ASUS All Series                       | 1         | 1.89%   |
| ASRock N68-GE3 UCC                    | 1         | 1.89%   |
| ASRock ConRoe1333-D667                | 1         | 1.89%   |
| ASRock B450M Steel Legend             | 1         | 1.89%   |
| Apple iMac8,1                         | 1         | 1.89%   |
| Acer Aspire ES1-512                   | 1         | 1.89%   |
| Acer Aspire E1-531                    | 1         | 1.89%   |
| Acer Aspire A515-51G                  | 1         | 1.89%   |
| Acer Aspire 5720Z                     | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 6         | 11.32%  |
| Acer Aspire                | 4         | 7.55%   |
| Lenovo ThinkPad            | 2         | 3.77%   |
| Dell OptiPlex              | 2         | 3.77%   |
| Toshiba Satellite          | 1         | 1.89%   |
| Supermicro H8DG6           | 1         | 1.89%   |
| Samsung 305E4A             | 1         | 1.89%   |
| Positivo Mobile            | 1         | 1.89%   |
| Pegatron B34C              | 1         | 1.89%   |
| PCWare IPMH61R2            | 1         | 1.89%   |
| Olivetti P55-AEU-323-4G320 | 1         | 1.89%   |
| MSI MS-7B84                | 1         | 1.89%   |
| MSI MS-7913                | 1         | 1.89%   |
| Medion S4216               | 1         | 1.89%   |
| Lenovo Y70-70              | 1         | 1.89%   |
| Lenovo G550                | 1         | 1.89%   |
| Lenovo G505                | 1         | 1.89%   |
| Jumper Ezpad               | 1         | 1.89%   |
| Intel B75                  | 1         | 1.89%   |
| HP ProBook                 | 1         | 1.89%   |
| HP Mini                    | 1         | 1.89%   |
| HP G42                     | 1         | 1.89%   |
| HP EliteBook               | 1         | 1.89%   |
| HP Compaq                  | 1         | 1.89%   |
| HP 250                     | 1         | 1.89%   |
| HP 202                     | 1         | 1.89%   |
| Gigabyte X570              | 1         | 1.89%   |
| Gigabyte P57V6             | 1         | 1.89%   |
| Gigabyte G31M-ES2C         | 1         | 1.89%   |
| Gigabyte B450              | 1         | 1.89%   |
| Gigabyte 970A-DS3P         | 1         | 1.89%   |
| ECS A780GM-A               | 1         | 1.89%   |
| Dell Vostro                | 1         | 1.89%   |
| Dell PowerEdge             | 1         | 1.89%   |
| ASUS TUF                   | 1         | 1.89%   |
| ASUS P8Z68-V               | 1         | 1.89%   |
| ASUS K72Jr                 | 1         | 1.89%   |
| ASUS K50C                  | 1         | 1.89%   |
| ASUS All                   | 1         | 1.89%   |
| ASRock N68-GE3             | 1         | 1.89%   |
| ASRock ConRoe1333-D667     | 1         | 1.89%   |
| ASRock B450M               | 1         | 1.89%   |
| Apple iMac8                | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 6         | 11.32%  |
| 2015    | 6         | 11.32%  |
| 2013    | 6         | 11.32%  |
| 2011    | 6         | 11.32%  |
| 2009    | 5         | 9.43%   |
| 2014    | 4         | 7.55%   |
| 2020    | 3         | 5.66%   |
| 2018    | 3         | 5.66%   |
| 2012    | 3         | 5.66%   |
| 2010    | 3         | 5.66%   |
| 2008    | 3         | 5.66%   |
| 2016    | 2         | 3.77%   |
| 2021    | 1         | 1.89%   |
| 2006    | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 31        | 58.49%  |
| Desktop    | 17        | 32.08%  |
| All in one | 2         | 3.77%   |
| Server     | 2         | 3.77%   |
| Tablet     | 1         | 1.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 52        | 96.3%   |
| Enabled  | 2         | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 23        | 43.4%   |
| 4.01-8.0        | 10        | 18.87%  |
| 16.01-24.0      | 8         | 15.09%  |
| 8.01-16.0       | 4         | 7.55%   |
| 1.01-2.0        | 3         | 5.66%   |
| 32.01-64.0      | 2         | 3.77%   |
| More than 256.0 | 1         | 1.89%   |
| 2.01-3.0        | 1         | 1.89%   |
| 64.01-256.0     | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 52.83%  |
| 2.01-3.0  | 12        | 22.64%  |
| 3.01-4.0  | 8         | 15.09%  |
| 4.01-8.0  | 2         | 3.77%   |
| 8.01-16.0 | 2         | 3.77%   |
| 0.51-1.0  | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 35        | 66.04%  |
| 2       | 11        | 20.75%  |
| 3       | 4         | 7.55%   |
| 6       | 1         | 1.89%   |
| 4       | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 56.6%   |
| No        | 23        | 43.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 75.47%  |
| No        | 13        | 24.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 58.49%  |
| Yes       | 22        | 41.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 17        | 32.08%  |
| USA          | 7         | 13.21%  |
| Poland       | 3         | 5.66%   |
| Italy        | 3         | 5.66%   |
| Canada       | 3         | 5.66%   |
| Australia    | 3         | 5.66%   |
| South Africa | 2         | 3.77%   |
| Germany      | 2         | 3.77%   |
| France       | 2         | 3.77%   |
| Argentina    | 2         | 3.77%   |
| Sweden       | 1         | 1.89%   |
| Spain        | 1         | 1.89%   |
| Serbia       | 1         | 1.89%   |
| Russia       | 1         | 1.89%   |
| Romania      | 1         | 1.89%   |
| India        | 1         | 1.89%   |
| Croatia      | 1         | 1.89%   |
| Chile        | 1         | 1.89%   |
| Cameroon     | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Curitiba              | 4         | 7.41%   |
| Krakow                | 2         | 3.7%    |
| Belo Horizonte        | 2         | 3.7%    |
| Zielonka              | 1         | 1.85%   |
| Zagreb                | 1         | 1.85%   |
| Winter Springs        | 1         | 1.85%   |
| Winston-Salem         | 1         | 1.85%   |
| Villemomble           | 1         | 1.85%   |
| Vila Velha            | 1         | 1.85%   |
| Taboao da Serra       | 1         | 1.85%   |
| Sydney                | 1         | 1.85%   |
| Stockholm             | 1         | 1.85%   |
| S??o Paulo            | 1         | 1.85%   |
| Sao Bernardo          | 1         | 1.85%   |
| Salerno               | 1         | 1.85%   |
| Saladas               | 1         | 1.85%   |
| Saint-Germain-en-Laye | 1         | 1.85%   |
| Rosario               | 1         | 1.85%   |
| Rio de Janeiro        | 1         | 1.85%   |
| Recife                | 1         | 1.85%   |
| Ramenskoye            | 1         | 1.85%   |
| Porto Alegre          | 1         | 1.85%   |
| Port Elizabeth        | 1         | 1.85%   |
| Pontevedra            | 1         | 1.85%   |
| Pietra Ligure         | 1         | 1.85%   |
| North Lewisburg       | 1         | 1.85%   |
| Newmarket             | 1         | 1.85%   |
| Moreno Valley         | 1         | 1.85%   |
| Montreal              | 1         | 1.85%   |
| Monserrato            | 1         | 1.85%   |
| Londrina              | 1         | 1.85%   |
| Launceston            | 1         | 1.85%   |
| Karlsruhe             | 1         | 1.85%   |
| Jundia?­              | 1         | 1.85%   |
| Johannesburg          | 1         | 1.85%   |
| Itatiba               | 1         | 1.85%   |
| Hobart                | 1         | 1.85%   |
| Edmundston            | 1         | 1.85%   |
| Douglas               | 1         | 1.85%   |
| Douala                | 1         | 1.85%   |
| Cincinnati            | 1         | 1.85%   |
| Central               | 1         | 1.85%   |
| Castroville           | 1         | 1.85%   |
| Bonn                  | 1         | 1.85%   |
| Bhopal                | 1         | 1.85%   |
| Belgrade              | 1         | 1.85%   |
| Bel?©m                | 1         | 1.85%   |
| Arad                  | 1         | 1.85%   |
| Adelaide CBD          | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 19.44%  |
| Seagate             | 10        | 13     | 13.89%  |
| Samsung Electronics | 7         | 8      | 9.72%   |
| Kingston            | 7         | 8      | 9.72%   |
| Toshiba             | 6         | 6      | 8.33%   |
| Hitachi             | 6         | 7      | 8.33%   |
| Unknown             | 3         | 4      | 4.17%   |
| SanDisk             | 3         | 3      | 4.17%   |
| LITEONIT            | 2         | 2      | 2.78%   |
| HGST                | 2         | 3      | 2.78%   |
| XPG                 | 1         | 1      | 1.39%   |
| TO Exter            | 1         | 1      | 1.39%   |
| PNY                 | 1         | 1      | 1.39%   |
| Phison              | 1         | 1      | 1.39%   |
| OCZ                 | 1         | 1      | 1.39%   |
| Mushkin             | 1         | 1      | 1.39%   |
| MAXTOR              | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| GOODRAM             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| ASMT109x            | 1         | 1      | 1.39%   |
| A-DATA Technology   | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2.67%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2.67%   |
| XPG GAMMIX S11 Pro 512GB            | 1         | 1.33%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1.33%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1         | 1.33%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1.33%   |
| WDC WD5000AACS-00G8B1 500GB         | 1         | 1.33%   |
| WDC WD400JD-55MSA1 40GB             | 1         | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1.33%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1.33%   |
| WDC WD2500BEVS-22UST0 250GB         | 1         | 1.33%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1.33%   |
| WDC WD1200BEVS-75UST0 120GB         | 1         | 1.33%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 1.33%   |
| WDC WD10EARX-00N0YB0 1TB            | 1         | 1.33%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1.33%   |
| Unknown NVMe SSD Drive 512GB        | 1         | 1.33%   |
| Unknown MMC Card  8GB               | 1         | 1.33%   |
| Unknown MMC Card  64GB              | 1         | 1.33%   |
| Toshiba MQ01ACF050 500GB            | 1         | 1.33%   |
| Toshiba MQ01ABF032 320GB            | 1         | 1.33%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1.33%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1.33%   |
| TO Exter nal USB 3.0 4TB            | 1         | 1.33%   |
| Seagate ST9320325AS 320GB           | 1         | 1.33%   |
| Seagate ST9160827AS 160GB           | 1         | 1.33%   |
| Seagate ST9160314AS 160GB           | 1         | 1.33%   |
| Seagate ST500LX012-SSHD-8GB         | 1         | 1.33%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.33%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1.33%   |
| Seagate ST4000DM004-2CV104 4TB      | 1         | 1.33%   |
| Seagate ST32000645NS 2TB            | 1         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1.33%   |
| Seagate Expansion Desk 4TB          | 1         | 1.33%   |
| SanDisk SSD PLUS 1000GB             | 1         | 1.33%   |
| SanDisk SD9SN8W256G1002 256GB SSD   | 1         | 1.33%   |
| Sandisk NVMe SSD Drive 500GB        | 1         | 1.33%   |
| Samsung SSD SM841 2.5 7mm 128GB     | 1         | 1.33%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.33%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.33%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD | 1         | 1.33%   |
| Samsung HM321HI 320GB               | 1         | 1.33%   |
| Samsung HD501LJ 500GB               | 1         | 1.33%   |
| Samsung HD321KJ 320GB               | 1         | 1.33%   |
| Samsung HD161HJ 41R0186LEN 160GB    | 1         | 1.33%   |
| PNY SSD2SC240G1SA754D117-443 240GB  | 1         | 1.33%   |
| Phison NVMe SSD Drive 1TB           | 1         | 1.33%   |
| OCZ ARC100 240GB SSD                | 1         | 1.33%   |
| Mushkin MKNSSDSR250GB               | 1         | 1.33%   |
| MAXTOR STM3160215AS 160GB           | 1         | 1.33%   |
| LITEONIT LMT-256M6M-HP 256GB SSD    | 1         | 1.33%   |
| LITEONIT LGT-256M6G 256GB SSD       | 1         | 1.33%   |
| Kingston SV300S37A240G 240GB SSD    | 1         | 1.33%   |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1.33%   |
| Kingston SA400S37480G 480GB SSD     | 1         | 1.33%   |
| Kingston SA400S37240G 240GB SSD     | 1         | 1.33%   |
| Kingston NVMe SSD Drive 512GB       | 1         | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 31.82%  |
| Seagate             | 10        | 13     | 22.73%  |
| Toshiba             | 6         | 6      | 13.64%  |
| Hitachi             | 6         | 7      | 13.64%  |
| Samsung Electronics | 3         | 4      | 6.82%   |
| HGST                | 2         | 3      | 4.55%   |
| TO Exter            | 1         | 1      | 2.27%   |
| MAXTOR              | 1         | 1      | 2.27%   |
| ASMT109x            | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 28.57%  |
| Samsung Electronics | 4         | 4      | 19.05%  |
| SanDisk             | 2         | 2      | 9.52%   |
| LITEONIT            | 2         | 2      | 9.52%   |
| PNY                 | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Mushkin             | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |
| GOODRAM             | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 50     | 57.81%  |
| SSD  | 20        | 22     | 31.25%  |
| NVMe | 5         | 6      | 7.81%   |
| MMC  | 2         | 2      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 70     | 84.48%  |
| NVMe | 5         | 6      | 8.62%   |
| SAS  | 2         | 2      | 3.45%   |
| MMC  | 2         | 2      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 56     | 76.27%  |
| 0.51-1.0   | 8         | 9      | 13.56%  |
| 3.01-4.0   | 4         | 4      | 6.78%   |
| 1.01-2.0   | 2         | 3      | 3.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 38.89%  |
| 251-500        | 15        | 27.78%  |
| 21-50          | 4         | 7.41%   |
| 501-1000       | 4         | 7.41%   |
| 51-100         | 4         | 7.41%   |
| 1001-2000      | 3         | 5.56%   |
| 1-20           | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 29        | 53.7%   |
| 21-50    | 12        | 22.22%  |
| 501-1000 | 4         | 7.41%   |
| 51-100   | 4         | 7.41%   |
| 101-250  | 3         | 5.56%   |
| 251-500  | 2         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |
| Hitachi HTS722012K9A300 120GB   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 48        | 73     | 88.89%  |
| Works    | 4         | 5      | 7.41%   |
| Malfunc  | 2         | 2      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 60%     |
| AMD                              | 13        | 21.67%  |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| ASMedia Technology               | 2         | 3.33%   |
| ADATA Technology                 | 2         | 3.33%   |
| Sandisk                          | 1         | 1.67%   |
| Phison Electronics               | 1         | 1.67%   |
| Nvidia                           | 1         | 1.67%   |
| LSI Logic / Symbios Logic        | 1         | 1.67%   |
| Kingston Technology Company      | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 10.13%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 6.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 3.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 3.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 3.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 3.8%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.8%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 2.53%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 2.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 2.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 2.53%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 2         | 2.53%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 2.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 2.53%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.27%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.27%   |
| Nvidia MCP61 IDE                                                                        | 1         | 1.27%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1         | 1.27%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.27%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1         | 1.27%   |
| AMD SB600 IDE                                                                           | 1         | 1.27%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 63.64%  |
| IDE  | 17        | 25.76%  |
| NVMe | 5         | 7.58%   |
| RAID | 2         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 73.58%  |
| AMD    | 14        | 26.42%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics     | 3         | 5.66%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 3.77%   |
| Intel Xeon CPU E7- 4870 @ 2.40GHz           | 1         | 1.89%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.89%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 1.89%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.89%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.89%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.89%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1         | 1.89%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.89%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.89%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.89%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.89%   |
| Intel Core i5-3570S CPU @ 3.10GHz           | 1         | 1.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.89%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.89%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.89%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.89%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.89%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.89%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 1.89%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.89%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.89%   |
| Intel Celeron D CPU 220 @ 1.20GHz           | 1         | 1.89%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.89%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.89%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.89%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.89%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1         | 1.89%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 1.89%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1         | 1.89%   |
| AMD Phenom 9650 Quad-Core Processor         | 1         | 1.89%   |
| AMD Opteron Processor 6272                  | 1         | 1.89%   |
| AMD FX-6300 Six-Core Processor              | 1         | 1.89%   |
| AMD Athlon II X2 260 Processor              | 1         | 1.89%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55  | 1         | 1.89%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 1         | 1.89%   |
| AMD A6-3420M APU with Radeon HD Graphics    | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 16.98%  |
| Intel Core i7           | 7         | 13.21%  |
| Intel Core i3           | 6         | 11.32%  |
| Intel Pentium Dual      | 4         | 7.55%   |
| Intel Core 2 Duo        | 4         | 7.55%   |
| Intel Pentium           | 3         | 5.66%   |
| AMD A4                  | 3         | 5.66%   |
| Intel Atom              | 2         | 3.77%   |
| Intel Xeon              | 1         | 1.89%   |
| Intel Pentium Dual-Core | 1         | 1.89%   |
| Intel Celeron D         | 1         | 1.89%   |
| Intel Celeron           | 1         | 1.89%   |
| AMD Ryzen 9             | 1         | 1.89%   |
| AMD Ryzen 7             | 1         | 1.89%   |
| AMD Ryzen 5             | 1         | 1.89%   |
| AMD Ryzen 3             | 1         | 1.89%   |
| AMD Phenom              | 1         | 1.89%   |
| AMD Opteron             | 1         | 1.89%   |
| AMD FX                  | 1         | 1.89%   |
| AMD Athlon II X2        | 1         | 1.89%   |
| AMD Athlon 64 X2        | 1         | 1.89%   |
| AMD A8                  | 1         | 1.89%   |
| AMD A6                  | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 52.83%  |
| 4      | 16        | 30.19%  |
| 1      | 3         | 5.66%   |
| 40     | 1         | 1.89%   |
| 16     | 1         | 1.89%   |
| 12     | 1         | 1.89%   |
| 8      | 1         | 1.89%   |
| 6      | 1         | 1.89%   |
| 3      | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 96.23%  |
| 4      | 1         | 1.89%   |
| 2      | 1         | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 50.94%  |
| 2      | 26        | 49.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 18.87%  |
| 0x306a9    | 8         | 15.09%  |
| 0x6fd      | 5         | 9.43%   |
| 0x206a7    | 4         | 7.55%   |
| 0x806e9    | 3         | 5.66%   |
| 0x306c3    | 2         | 3.77%   |
| 0x30678    | 2         | 3.77%   |
| 0x20655    | 2         | 3.77%   |
| 0x0700010f | 2         | 3.77%   |
| 0xa0652    | 1         | 1.89%   |
| 0x506e3    | 1         | 1.89%   |
| 0x406c4    | 1         | 1.89%   |
| 0x40651    | 1         | 1.89%   |
| 0x306d4    | 1         | 1.89%   |
| 0x206f2    | 1         | 1.89%   |
| 0x1067a    | 1         | 1.89%   |
| 0x10676    | 1         | 1.89%   |
| 0x10661    | 1         | 1.89%   |
| 0x08701013 | 1         | 1.89%   |
| 0x08108109 | 1         | 1.89%   |
| 0x07000106 | 1         | 1.89%   |
| 0x03000027 | 1         | 1.89%   |
| 0x010000c8 | 1         | 1.89%   |
| 0x01000095 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 8         | 15.09%  |
| Core        | 6         | 11.32%  |
| SandyBridge | 4         | 7.55%   |
| Penryn      | 4         | 7.55%   |
| Haswell     | 4         | 7.55%   |
| Zen 2       | 3         | 5.66%   |
| Westmere    | 3         | 5.66%   |
| Silvermont  | 3         | 5.66%   |
| KabyLake    | 3         | 5.66%   |
| Jaguar      | 3         | 5.66%   |
| Piledriver  | 2         | 3.77%   |
| K10         | 2         | 3.77%   |
| Zen+        | 1         | 1.89%   |
| Skylake     | 1         | 1.89%   |
| K8 Hammer   | 1         | 1.89%   |
| K10 Llano   | 1         | 1.89%   |
| CometLake   | 1         | 1.89%   |
| Bulldozer   | 1         | 1.89%   |
| Broadwell   | 1         | 1.89%   |
| Bonnell     | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 30        | 50%     |
| Nvidia                           | 14        | 23.33%  |
| AMD                              | 12        | 20%     |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| Matrox Electronics Systems       | 2         | 3.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 9.68%   |
| Intel HD Graphics 620                                                                    | 3         | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 4.84%   |
| AMD Kabini [Radeon HD 8330]                                                              | 3         | 4.84%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 3.23%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 3.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1         | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.61%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.61%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 1.61%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.61%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1         | 1.61%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1         | 1.61%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.61%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.61%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.61%   |
| Intel HD Graphics 530                                                                    | 1         | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.61%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.61%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.61%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.61%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1         | 1.61%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 1         | 1.61%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 1.61%   |
| AMD Picasso                                                                              | 1         | 1.61%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 25        | 47.17%  |
| 1 x AMD         | 12        | 22.64%  |
| 1 x Nvidia      | 8         | 15.09%  |
| Intel + Nvidia  | 4         | 7.55%   |
| 1 x SiS         | 2         | 3.77%   |
| Nvidia + Matrox | 1         | 1.89%   |
| 1 x Matrox      | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 84.91%  |
| Unknown     | 6         | 11.32%  |
| Proprietary | 2         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 64.81%  |
| 0.01-0.5   | 8         | 14.81%  |
| 1.01-2.0   | 5         | 9.26%   |
| 3.01-4.0   | 3         | 5.56%   |
| 0.51-1.0   | 2         | 3.7%    |
| 5.01-6.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 17.65%  |
| Samsung Electronics     | 8         | 15.69%  |
| LG Display              | 7         | 13.73%  |
| Goldstar                | 5         | 9.8%    |
| Chimei Innolux          | 4         | 7.84%   |
| BOE                     | 3         | 5.88%   |
| Acer                    | 3         | 5.88%   |
| ViewSonic               | 1         | 1.96%   |
| Unknown                 | 1         | 1.96%   |
| Sony                    | 1         | 1.96%   |
| Sceptre Tech            | 1         | 1.96%   |
| Philips                 | 1         | 1.96%   |
| NXP                     | 1         | 1.96%   |
| Lenovo                  | 1         | 1.96%   |
| Hewlett-Packard         | 1         | 1.96%   |
| Chi Mei Optoelectronics | 1         | 1.96%   |
| BenQ                    | 1         | 1.96%   |
| Apple                   | 1         | 1.96%   |
| Ancor Communications    | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 3.77%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch              | 2         | 3.77%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                      | 2         | 3.77%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 3.77%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                | 1         | 1.89%   |
| Unknown LCD Monitor SHI LCD-TV 4640x1080                                 | 1         | 1.89%   |
| Sony LCD Monitor AVSYSTEM                                                | 1         | 1.89%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                   | 1         | 1.89%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 1.89%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 1.89%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 510x290mm 23.1-inch       | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.89%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                       | 1         | 1.89%   |
| NXP OptiPlex 9010 NXP1111 1920x1080 510x286mm 23.0-inch                  | 1         | 1.89%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 1.89%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 527x296mm 23.8-inch                 | 1         | 1.89%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch             | 1         | 1.89%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                     | 1         | 1.89%   |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                      | 1         | 1.89%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                     | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 1.89%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.89%   |
| BOE LCD Monitor BOE0657 1920x1080 344x194mm 15.5-inch                    | 1         | 1.89%   |
| BenQ LCD Monitor GL951A 2880x900                                         | 1         | 1.89%   |
| BenQ LCD Monitor GL951A                                                  | 1         | 1.89%   |
| BenQ GL951A BNQ7897 1440x900 408x255mm 18.9-inch                         | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.89%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 1.89%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                    | 1         | 1.89%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 1.89%   |
| Acer V226WL ACR0339 1680x1050 474x296mm 22.0-inch                        | 1         | 1.89%   |
| Acer LCD Monitor S230HL                                                  | 1         | 1.89%   |
| Acer G226HQL ACR02EA 1920x1080 480x270mm 21.7-inch                       | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 18        | 34.62%  |
| 1920x1080 (FHD)    | 13        | 25%     |
| 1600x900 (HD+)     | 5         | 9.62%   |
| 1280x800 (WXGA)    | 4         | 7.69%   |
| 1680x1050 (WSXGA+) | 2         | 3.85%   |
| Unknown            | 2         | 3.85%   |
| 4640x1080          | 1         | 1.92%   |
| 3840x2160 (4K)     | 1         | 1.92%   |
| 2880x900           | 1         | 1.92%   |
| 2560x1440 (QHD)    | 1         | 1.92%   |
| 1440x900 (WXGA+)   | 1         | 1.92%   |
| 1360x768           | 1         | 1.92%   |
| 1280x1024 (SXGA)   | 1         | 1.92%   |
| 1024x600           | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17        | 34%     |
| 14      | 7         | 14%     |
| 21      | 3         | 6%      |
| 20      | 3         | 6%      |
| 17      | 3         | 6%      |
| 31      | 2         | 4%      |
| 24      | 2         | 4%      |
| 23      | 2         | 4%      |
| 19      | 2         | 4%      |
| 18      | 2         | 4%      |
| 13      | 2         | 4%      |
| Unknown | 2         | 4%      |
| 27      | 1         | 2%      |
| 22      | 1         | 2%      |
| 10      | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 54%     |
| 401-500     | 11        | 22%     |
| 501-600     | 4         | 8%      |
| 601-700     | 3         | 6%      |
| 351-400     | 2         | 4%      |
| Unknown     | 2         | 4%      |
| 201-300     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 77.55%  |
| 16/10   | 8         | 16.33%  |
| Unknown | 2         | 4.08%   |
| 5/4     | 1         | 2.04%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 34%     |
| 81-90          | 9         | 18%     |
| 201-250        | 7         | 14%     |
| 151-200        | 5         | 10%     |
| 141-150        | 3         | 6%      |
| 351-500        | 2         | 4%      |
| 121-130        | 2         | 4%      |
| Unknown        | 2         | 4%      |
| 41-50          | 1         | 2%      |
| 301-350        | 1         | 2%      |
| 251-300        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 20        | 41.67%  |
| 51-100  | 18        | 37.5%   |
| 121-160 | 8         | 16.67%  |
| Unknown | 2         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 84.91%  |
| 0     | 4         | 7.55%   |
| 2     | 3         | 5.66%   |
| 3     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 35        | 40.7%   |
| Qualcomm Atheros                  | 14        | 16.28%  |
| Intel                             | 12        | 13.95%  |
| Broadcom                          | 9         | 10.47%  |
| Broadcom Limited                  | 3         | 3.49%   |
| TP-Link                           | 2         | 2.33%   |
| Marvell Technology Group          | 2         | 2.33%   |
| Silicon Integrated Systems [SiS]  | 1         | 1.16%   |
| Ralink                            | 1         | 1.16%   |
| Qualcomm                          | 1         | 1.16%   |
| Nvidia                            | 1         | 1.16%   |
| NetGear                           | 1         | 1.16%   |
| Ericsson Business Mobile Networks | 1         | 1.16%   |
| D-Link                            | 1         | 1.16%   |
| ASIX Electronics                  | 1         | 1.16%   |
| Accton Technology                 | 1         | 1.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 24        | 23.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 8.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.92%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.96%   |
| Intel Wireless 7260                                                     | 2         | 1.96%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.96%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 0.98%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.98%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.98%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                    | 1         | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.98%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.98%   |
| Qualcomm SM8250-APOLLO _SN:B760817D                                     | 1         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.98%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.98%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.98%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 0.98%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 0.98%   |
| Intel Wireless 8260                                                     | 1         | 0.98%   |
| Intel Wireless 7265                                                     | 1         | 0.98%   |
| Intel Wireless 3165                                                     | 1         | 0.98%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.98%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 0.98%   |
| Intel 82576 Gigabit Network Connection                                  | 1         | 0.98%   |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 0.98%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1         | 0.98%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                          | 1         | 0.98%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 1         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 0.98%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                  | 1         | 0.98%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 0.98%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.98%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.98%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 0.98%   |
| Accton WN7512BEP Wireless LAN adapter                                   | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 14        | 31.82%  |
| Intel                 | 9         | 20.45%  |
| Realtek Semiconductor | 8         | 18.18%  |
| Broadcom              | 5         | 11.36%  |
| TP-Link               | 2         | 4.55%   |
| Broadcom Limited      | 2         | 4.55%   |
| Ralink                | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| D-Link                | 1         | 2.27%   |
| Accton Technology     | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 9.09%   |
| Realtek 802.11ac NIC                                                    | 2         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.55%   |
| Intel Wireless 7260                                                     | 2         | 4.55%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 4.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 4.55%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 2.27%   |
| TP-Link Archer T4U ver.3                                                | 1         | 2.27%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 2.27%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                    | 1         | 2.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.27%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 2.27%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 2.27%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 2.27%   |
| Intel Wireless 8260                                                     | 1         | 2.27%   |
| Intel Wireless 7265                                                     | 1         | 2.27%   |
| Intel Wireless 3165                                                     | 1         | 2.27%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.27%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]           | 1         | 2.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 2.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.27%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 2.27%   |
| Accton WN7512BEP Wireless LAN adapter                                   | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 34        | 59.65%  |
| Intel                            | 7         | 12.28%  |
| Broadcom                         | 5         | 8.77%   |
| Qualcomm Atheros                 | 4         | 7.02%   |
| Marvell Technology Group         | 2         | 3.51%   |
| Silicon Integrated Systems [SiS] | 1         | 1.75%   |
| Qualcomm                         | 1         | 1.75%   |
| Nvidia                           | 1         | 1.75%   |
| Broadcom Limited                 | 1         | 1.75%   |
| ASIX Electronics                 | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 42.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 15.79%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.75%   |
| Qualcomm SM8250-APOLLO _SN:B760817D                               | 1         | 1.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.75%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.75%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.75%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.75%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.75%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 55.79%  |
| WiFi     | 41        | 43.16%  |
| Modem    | 1         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 55.22%  |
| WiFi     | 30        | 44.78%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 67.92%  |
| 1     | 14        | 26.42%  |
| 4     | 1         | 1.89%   |
| 3     | 1         | 1.89%   |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 96.23%  |
| Yes  | 2         | 3.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 25%     |
| Qualcomm Atheros Communications | 5         | 20.83%  |
| Cambridge Silicon Radio         | 4         | 16.67%  |
| Lite-On Technology              | 2         | 8.33%   |
| Hewlett-Packard                 | 2         | 8.33%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Ralink Technology               | 1         | 4.17%   |
| Integrated System Solution      | 1         | 4.17%   |
| Foxconn / Hon Hai               | 1         | 4.17%   |
| Apple                           | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                      | 4         | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 16.67%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 8.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 8.33%   |
| Intel Bluetooth wireless interface                          | 2         | 8.33%   |
| Realtek 802.11n WLAN Adapter                                | 1         | 4.17%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 4.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 4.17%   |
| Lite-On Bluetooth Device                                    | 1         | 4.17%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 4.17%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter       | 1         | 4.17%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 4.17%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 4.17%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 4.17%   |
| Apple Bluetooth HCI                                         | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 51.47%  |
| AMD                              | 15        | 22.06%  |
| Nvidia                           | 11        | 16.18%  |
| Silicon Integrated Systems [SiS] | 2         | 2.94%   |
| Texas Instruments                | 1         | 1.47%   |
| Creative Technology              | 1         | 1.47%   |
| Creative Labs                    | 1         | 1.47%   |
| Corsair                          | 1         | 1.47%   |
| C-Media Electronics              | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 11.39%  |
| AMD FCH Azalia Controller                                                  | 5         | 6.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 3.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 3.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 3.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 3.8%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.53%   |
| Nvidia GF110 High Definition Audio Controller                              | 2         | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.53%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.27%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 1.27%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.27%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.27%   |
| Creative Technology Sound BlasterX G1                                      | 1         | 1.27%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 1.27%   |
| Corsair VOID PRO Surround USB Adapter                                      | 1         | 1.27%   |
| C-Media Electronics Audio Adapter                                          | 1         | 1.27%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.27%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.27%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1         | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.27%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 10%     |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 10%     |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 1         | 10%     |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s     | 1         | 10%     |
| Kingston RAM KHX2400C11D3/8GX 8192MB DIMM DDR3 2400MT/s  | 1         | 10%     |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s  | 1         | 10%     |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s   | 1         | 10%     |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s   | 1         | 10%     |
| Corsair RAM CMW16GX4M2C3200C16 8192MB DIMM DDR4 3266MT/s | 1         | 10%     |
| Corsair RAM CML16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 4         | 50%     |
| DDR4   | 2         | 25%     |
| SDRAM  | 1         | 12.5%   |
| LPDDR4 | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 4         | 50%     |
| DIMM   | 4         | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 4         | 44.44%  |
| 4096 | 3         | 33.33%  |
| 2048 | 2         | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Suyin                                  | 5         | 16.67%  |
| Chicony Electronics                    | 5         | 16.67%  |
| Realtek Semiconductor                  | 4         | 13.33%  |
| Microdia                               | 4         | 13.33%  |
| IMC Networks                           | 3         | 10%     |
| Syntek                                 | 1         | 3.33%   |
| Silicon Motion                         | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Microsoft                              | 1         | 3.33%   |
| Logitech                               | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |
| Hewlett-Packard                        | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |
| Apple                                  | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia USB 2.0 Camera                                     | 2         | 6.67%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 6.67%   |
| Syntek Lenovo EasyCamera                                    | 1         | 3.33%   |
| Suyin HP Webcam-50                                          | 1         | 3.33%   |
| Suyin HP Webcam-101                                         | 1         | 3.33%   |
| Suyin HP Integrated Webcam                                  | 1         | 3.33%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 3.33%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 3.33%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 3.33%   |
| Realtek Lenovo EasyCamera                                   | 1         | 3.33%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                | 1         | 3.33%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 3.33%   |
| Quanta HD Webcam                                            | 1         | 3.33%   |
| Microsoft LifeCam HD-3000                                   | 1         | 3.33%   |
| Logitech QuickCam Pro 9000                                  | 1         | 3.33%   |
| Lite-On Integrated Camera                                   | 1         | 3.33%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.33%   |
| IMC Networks Integrated Webcam                              | 1         | 3.33%   |
| HP Webcam 3100                                              | 1         | 3.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.33%   |
| Chicony Integrated Camera                                   | 1         | 3.33%   |
| Chicony HP TrueVision HD Camera                             | 1         | 3.33%   |
| Chicony HD WebCam                                           | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 3.33%   |
| Apple Built-in iSight                                       | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 39        | 72.22%  |
| 1     | 15        | 27.78%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 7         | 43.75%  |
| Net/wireless       | 6         | 37.5%   |
| Fingerprint reader | 2         | 12.5%   |
| Chipcard           | 1         | 6.25%   |

