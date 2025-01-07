Trisquel - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Trisquel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Trisquel/Desktop/README.md) and [notebooks](/Dist/Trisquel/Notebook/README.md).

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

Total: 66

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [e0cf37ba04](https://linux-hardware.org/?probe=e0cf37ba04) | Nov 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [7b5c860bd2](https://linux-hardware.org/?probe=7b5c860bd2) | Nov 15, 2024 |
| Dell          | XPS 12 9Q23                 | Notebook    | [b842f0a090](https://linux-hardware.org/?probe=b842f0a090) | Sep 21, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [01a0fbb73f](https://linux-hardware.org/?probe=01a0fbb73f) | Sep 17, 2024 |
| Gigabyte      | Z390 UD                     | Desktop     | [264bb56b6a](https://linux-hardware.org/?probe=264bb56b6a) | Aug 31, 2024 |
| LZ            | LZ1004_3                    | Notebook    | [8ad0eef591](https://linux-hardware.org/?probe=8ad0eef591) | Aug 28, 2024 |
| Lenovo        | ThinkPad X230 2325Y3C       | Notebook    | [31631cc4bd](https://linux-hardware.org/?probe=31631cc4bd) | Aug 04, 2024 |
| Dell          | Latitude E6540              | Notebook    | [c6c6acf7d2](https://linux-hardware.org/?probe=c6c6acf7d2) | May 08, 2024 |
| Dell          | Latitude E6540              | Notebook    | [a57f8ef498](https://linux-hardware.org/?probe=a57f8ef498) | May 08, 2024 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [caa84a8e1f](https://linux-hardware.org/?probe=caa84a8e1f) | Apr 13, 2024 |
| Dell          | Latitude 7420               | Convertible | [ef5c61da95](https://linux-hardware.org/?probe=ef5c61da95) | Mar 04, 2024 |
| Dell          | Latitude 7420               | Convertible | [2f7b7b58d0](https://linux-hardware.org/?probe=2f7b7b58d0) | Feb 13, 2024 |
| Lenovo        | ThinkPad T430s 2356C45      | Notebook    | [a76e3d7e43](https://linux-hardware.org/?probe=a76e3d7e43) | Dec 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [ed00b585a3](https://linux-hardware.org/?probe=ed00b585a3) | Nov 12, 2023 |
| Dell          | Latitude 5590               | Notebook    | [5712f37060](https://linux-hardware.org/?probe=5712f37060) | Nov 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [65c390fe0e](https://linux-hardware.org/?probe=65c390fe0e) | Aug 12, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [8375e909e7](https://linux-hardware.org/?probe=8375e909e7) | Jul 30, 2023 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [eebd657892](https://linux-hardware.org/?probe=eebd657892) | Jul 27, 2023 |
| Lenovo        | ThinkPad X200 7458C23       | Notebook    | [3f09abaa12](https://linux-hardware.org/?probe=3f09abaa12) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [154b34b737](https://linux-hardware.org/?probe=154b34b737) | Jul 18, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
| Toshiba       | NB510                       | Notebook    | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [4f777df0e8](https://linux-hardware.org/?probe=4f777df0e8) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [c5824f9cae](https://linux-hardware.org/?probe=c5824f9cae) | Apr 25, 2023 |
| Itautec       | Infoway                     | Notebook    | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [89a021b8f6](https://linux-hardware.org/?probe=89a021b8f6) | Dec 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Libiquity     | Taurinus X200               | Notebook    | [75c0f41e26](https://linux-hardware.org/?probe=75c0f41e26) | Nov 09, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [ab06dd40c4](https://linux-hardware.org/?probe=ab06dd40c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [5b08d764b4](https://linux-hardware.org/?probe=5b08d764b4) | Sep 27, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [08a8ad598f](https://linux-hardware.org/?probe=08a8ad598f) | Sep 23, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [8e620e891f](https://linux-hardware.org/?probe=8e620e891f) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [a9e525c695](https://linux-hardware.org/?probe=a9e525c695) | Sep 16, 2022 |
| Timi          | TM1709                      | Notebook    | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [8d7c5df586](https://linux-hardware.org/?probe=8d7c5df586) | Sep 03, 2022 |
| ASUSTek       | K55A                        | Notebook    | [5d11054a36](https://linux-hardware.org/?probe=5d11054a36) | Aug 28, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [4b8f3feaa7](https://linux-hardware.org/?probe=4b8f3feaa7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [a18ab36f34](https://linux-hardware.org/?probe=a18ab36f34) | Aug 17, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [f6abe5392b](https://linux-hardware.org/?probe=f6abe5392b) | Aug 03, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [b25d6bf66c](https://linux-hardware.org/?probe=b25d6bf66c) | Jul 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [0145453c1a](https://linux-hardware.org/?probe=0145453c1a) | May 27, 2022 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [a9d7621b8d](https://linux-hardware.org/?probe=a9d7621b8d) | May 26, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [92fd051a13](https://linux-hardware.org/?probe=92fd051a13) | May 15, 2022 |
| Lenovo        | ThinkPad T420 4177QKU       | Notebook    | [215758ad8a](https://linux-hardware.org/?probe=215758ad8a) | Apr 30, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1126937638](https://linux-hardware.org/?probe=1126937638) | Apr 28, 2022 |
| HP            | 8299                        | Desktop     | [7a54bfae05](https://linux-hardware.org/?probe=7a54bfae05) | Apr 28, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [f41f324f01](https://linux-hardware.org/?probe=f41f324f01) | Apr 25, 2022 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [53753f59d3](https://linux-hardware.org/?probe=53753f59d3) | Feb 13, 2022 |
| Toshiba       | Satellite C800D             | Notebook    | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Samsung       | N130                        | Notebook    | [1a88380af6](https://linux-hardware.org/?probe=1a88380af6) | Nov 27, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [89cf2685e2](https://linux-hardware.org/?probe=89cf2685e2) | Nov 01, 2021 |
| ASUSTek       | U56E                        | Notebook    | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| Lenovo        | ThinkPad X200 7455FNG       | Notebook    | [6fcadf1396](https://linux-hardware.org/?probe=6fcadf1396) | Mar 20, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [49fde2499f](https://linux-hardware.org/?probe=49fde2499f) | Jul 18, 2020 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [5ea27e2813](https://linux-hardware.org/?probe=5ea27e2813) | Jul 18, 2020 |
| Acer          | TravelMate B115-M           | Notebook    | [62239072f1](https://linux-hardware.org/?probe=62239072f1) | Nov 26, 2019 |
| GPD           | MicroPC                     | Notebook    | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |
| ECS           | H61H2-M2                    | Desktop     | [add4f52268](https://linux-hardware.org/?probe=add4f52268) | Mar 06, 2019 |
| ECS           | H61H2-M2                    | Desktop     | [f9376ff405](https://linux-hardware.org/?probe=f9376ff405) | May 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Trisquel 10.0.1 | 18        | 34.62%  |
| Trisquel 11.0   | 16        | 30.77%  |
| Trisquel 11.0.1 | 7         | 13.46%  |
| Trisquel 9.0    | 5         | 9.62%   |
| Trisquel 8.0    | 3         | 5.77%   |
| Trisquel 10.0   | 3         | 5.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Trisquel | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.4.0-96-generic     | 4         | 7.14%   |
| 5.4.0-122-generic    | 4         | 7.14%   |
| 5.4.0-125-generic    | 3         | 5.36%   |
| 5.4.0-113-generic    | 3         | 5.36%   |
| 5.15.0-78-generic    | 3         | 5.36%   |
| 5.4.0-126-generic    | 2         | 3.57%   |
| 5.4.0-109-generic    | 2         | 3.57%   |
| 5.15.0-76-generic    | 2         | 3.57%   |
| 5.15.0-69-generic    | 2         | 3.57%   |
| 5.15.0-67-generic    | 2         | 3.57%   |
| 5.15.0-105-generic   | 2         | 3.57%   |
| 6.0.12-x64v1-xanmod1 | 1         | 1.79%   |
| 5.4.0-159-generic    | 1         | 1.79%   |
| 5.4.0-135-generic    | 1         | 1.79%   |
| 5.4.0-132-generic    | 1         | 1.79%   |
| 5.4.0-131-generic    | 1         | 1.79%   |
| 5.4.0-110-generic    | 1         | 1.79%   |
| 5.3.13-gnu           | 1         | 1.79%   |
| 5.3.1-gnu            | 1         | 1.79%   |
| 5.15.0-97-generic    | 1         | 1.79%   |
| 5.15.0-94-generic    | 1         | 1.79%   |
| 5.15.0-91-generic    | 1         | 1.79%   |
| 5.15.0-88-generic    | 1         | 1.79%   |
| 5.15.0-86-generic    | 1         | 1.79%   |
| 5.15.0-73-generic    | 1         | 1.79%   |
| 5.15.0-124-generic   | 1         | 1.79%   |
| 5.15.0-122-generic   | 1         | 1.79%   |
| 5.15.0-119-generic   | 1         | 1.79%   |
| 5.15.0-117-generic   | 1         | 1.79%   |
| 5.15.0-107-generic   | 1         | 1.79%   |
| 5.15.0-102-generic   | 1         | 1.79%   |
| 5.10.177-gnu1        | 1         | 1.79%   |
| 4.4.0-119-generic    | 1         | 1.79%   |
| 4.15.0-161-generic   | 1         | 1.79%   |
| 4.15.0-156-generic   | 1         | 1.79%   |
| 4.15.0-136-generic   | 1         | 1.79%   |
| 4.15.0-121-generic   | 1         | 1.79%   |
| 4.15.0-108-generic   | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 22        | 42.31%  |
| 5.4.0    | 20        | 38.46%  |
| 4.15.0   | 5         | 9.62%   |
| 6.0.12   | 1         | 1.92%   |
| 5.3.13   | 1         | 1.92%   |
| 5.3.1    | 1         | 1.92%   |
| 5.10.177 | 1         | 1.92%   |
| 4.4.0    | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 22        | 42.31%  |
| 5.4     | 20        | 38.46%  |
| 4.15    | 5         | 9.62%   |
| 5.3     | 2         | 3.85%   |
| 6.0     | 1         | 1.92%   |
| 5.10    | 1         | 1.92%   |
| 4.4     | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 96.08%  |
| i686   | 1         | 1.96%   |
| armv7l | 1         | 1.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 36        | 67.92%  |
| LXDE    | 4         | 7.55%   |
| KDE5    | 4         | 7.55%   |
| GNOME   | 4         | 7.55%   |
| Unknown | 2         | 3.77%   |
| KDE     | 1         | 1.89%   |
| dwm     | 1         | 1.89%   |
| default | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 48        | 94.12%  |
| Wayland | 2         | 3.92%   |
| Unknown | 1         | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 34        | 65.38%  |
| Unknown | 7         | 13.46%  |
| TDM     | 4         | 7.69%   |
| SDDM    | 4         | 7.69%   |
| SLiM    | 1         | 1.92%   |
| GDM3    | 1         | 1.92%   |
| GDM     | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 21        | 41.18%  |
| fr_FR   | 8         | 15.69%  |
| ru_RU   | 5         | 9.8%    |
| C       | 4         | 7.84%   |
| Unknown | 3         | 5.88%   |
| tr_TR   | 2         | 3.92%   |
| en_GB   | 2         | 3.92%   |
| ru_UA   | 1         | 1.96%   |
| pt_BR   | 1         | 1.96%   |
| es_MX   | 1         | 1.96%   |
| es_ES   | 1         | 1.96%   |
| en_CA   | 1         | 1.96%   |
| de_DE   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 29        | 56.86%  |
| BIOS | 22        | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 88.24%  |
| Overlay | 3         | 5.88%   |
| Xfs     | 1         | 1.96%   |
| Ext2    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 78.43%  |
| Unknown | 7         | 13.73%  |
| MBR     | 4         | 7.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 83.02%  |
| Yes       | 9         | 16.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 86.27%  |
| Yes       | 7         | 13.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 21.57%  |
| Lenovo              | 10        | 19.61%  |
| ASUSTek Computer    | 4         | 7.84%   |
| Hewlett-Packard     | 3         | 5.88%   |
| Gigabyte Technology | 3         | 5.88%   |
| Acer                | 3         | 5.88%   |
| Toshiba             | 2         | 3.92%   |
| Samsung Electronics | 2         | 3.92%   |
| Timi                | 1         | 1.96%   |
| Packard Bell        | 1         | 1.96%   |
| Notebook            | 1         | 1.96%   |
| MSI                 | 1         | 1.96%   |
| LZ                  | 1         | 1.96%   |
| Libiquity           | 1         | 1.96%   |
| Itautec             | 1         | 1.96%   |
| Huanan              | 1         | 1.96%   |
| GPD                 | 1         | 1.96%   |
| Fujitsu Siemens     | 1         | 1.96%   |
| ECS                 | 1         | 1.96%   |
| Apple               | 1         | 1.96%   |
| Unknown             | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T420 4177QKU                                          | 2         | 3.92%   |
| Dell XPS 15 9510                                                      | 2         | 3.92%   |
| Toshiba Satellite C800D                                               | 1         | 1.96%   |
| Toshiba NB510                                                         | 1         | 1.96%   |
| Timi TM1709                                                           | 1         | 1.96%   |
| Samsung N130                                                          | 1         | 1.96%   |
| Samsung Galaxy TabPro S                                               | 1         | 1.96%   |
| Packard Bell IMEDIA S1300                                             | 1         | 1.96%   |
| Notebook NJ50_70CU                                                    | 1         | 1.96%   |
| MSI MS-7917                                                           | 1         | 1.96%   |
| LZ LZ1004_3                                                           | 1         | 1.96%   |
| Libiquity Taurinus X200                                               | 1         | 1.96%   |
| Lenovo ThinkPad X230 2325Y3C                                          | 1         | 1.96%   |
| Lenovo ThinkPad X200 7458C23                                          | 1         | 1.96%   |
| Lenovo ThinkPad X200 7455FNG                                          | 1         | 1.96%   |
| Lenovo ThinkPad T480 20L5000UUS                                       | 1         | 1.96%   |
| Lenovo ThinkPad T430s 2356C45                                         | 1         | 1.96%   |
| Lenovo ThinkPad T430 2347G2U                                          | 1         | 1.96%   |
| Lenovo ThinkPad E14 Gen 5 21JK0006TX                                  | 1         | 1.96%   |
| Lenovo G505s 20255                                                    | 1         | 1.96%   |
| Itautec Infoway                                                       | 1         | 1.96%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1         | 1.96%   |
| HP Victus by Laptop 16-e0xxx                                          | 1         | 1.96%   |
| HP Stream Laptop 11-y0XX                                              | 1         | 1.96%   |
| HP EliteDesk 800 G3 SFF                                               | 1         | 1.96%   |
| GPD MicroPC                                                           | 1         | 1.96%   |
| Gigabyte Z390 UD                                                      | 1         | 1.96%   |
| Gigabyte M68MT-D3P                                                    | 1         | 1.96%   |
| Gigabyte 945PLM-S2                                                    | 1         | 1.96%   |
| Fujitsu Siemens ESPRIMO EDITION P2540                                 | 1         | 1.96%   |
| ECS H61H2-M2                                                          | 1         | 1.96%   |
| Dell XPS 13 9360                                                      | 1         | 1.96%   |
| Dell XPS 12 9Q23                                                      | 1         | 1.96%   |
| Dell OptiPlex 3020                                                    | 1         | 1.96%   |
| Dell Latitude E6540                                                   | 1         | 1.96%   |
| Dell Latitude E6400                                                   | 1         | 1.96%   |
| Dell Latitude 7420                                                    | 1         | 1.96%   |
| Dell Latitude 5590                                                    | 1         | 1.96%   |
| Dell Inspiron 1545                                                    | 1         | 1.96%   |
| Dell Inspiron 15-3567                                                 | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 9         | 17.65%  |
| Dell XPS                | 4         | 7.84%   |
| Dell Latitude           | 4         | 7.84%   |
| Dell Inspiron           | 2         | 3.92%   |
| Toshiba Satellite       | 1         | 1.96%   |
| Toshiba NB510           | 1         | 1.96%   |
| Timi TM1709             | 1         | 1.96%   |
| Samsung N130            | 1         | 1.96%   |
| Samsung Galaxy          | 1         | 1.96%   |
| Packard Bell IMEDIA     | 1         | 1.96%   |
| Notebook NJ50           | 1         | 1.96%   |
| MSI MS-7917             | 1         | 1.96%   |
| LZ LZ1004               | 1         | 1.96%   |
| Libiquity Taurinus      | 1         | 1.96%   |
| Lenovo G505s            | 1         | 1.96%   |
| Itautec Infoway         | 1         | 1.96%   |
| Huanan X79              | 1         | 1.96%   |
| HP Victus               | 1         | 1.96%   |
| HP Stream               | 1         | 1.96%   |
| HP EliteDesk            | 1         | 1.96%   |
| GPD MicroPC             | 1         | 1.96%   |
| Gigabyte Z390           | 1         | 1.96%   |
| Gigabyte M68MT-D3P      | 1         | 1.96%   |
| Gigabyte 945PLM-S2      | 1         | 1.96%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.96%   |
| ECS H61H2-M2            | 1         | 1.96%   |
| Dell OptiPlex           | 1         | 1.96%   |
| ASUS U56E               | 1         | 1.96%   |
| ASUS P8H61              | 1         | 1.96%   |
| ASUS K55A               | 1         | 1.96%   |
| ASUS A55BM-PLUS         | 1         | 1.96%   |
| Apple MacPro5           | 1         | 1.96%   |
| Acer TravelMate         | 1         | 1.96%   |
| Acer Nitro              | 1         | 1.96%   |
| Acer Aspire             | 1         | 1.96%   |
| Unknown                 | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 7         | 13.73%  |
| 2018    | 6         | 11.76%  |
| 2012    | 6         | 11.76%  |
| 2021    | 5         | 9.8%    |
| 2011    | 5         | 9.8%    |
| 2016    | 4         | 7.84%   |
| 2014    | 3         | 5.88%   |
| 2013    | 3         | 5.88%   |
| 2010    | 3         | 5.88%   |
| 2019    | 2         | 3.92%   |
| 2023    | 1         | 1.96%   |
| 2022    | 1         | 1.96%   |
| 2017    | 1         | 1.96%   |
| 2015    | 1         | 1.96%   |
| 2009    | 1         | 1.96%   |
| 2006    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 34        | 66.67%  |
| Desktop     | 15        | 29.41%  |
| Tablet      | 1         | 1.96%   |
| Convertible | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 92.16%  |
| Yes  | 4         | 7.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 33.33%  |
| 16.01-24.0 | 10        | 19.61%  |
| 8.01-16.0  | 9         | 17.65%  |
| 1.01-2.0   | 6         | 11.76%  |
| 3.01-4.0   | 5         | 9.8%    |
| 32.01-64.0 | 3         | 5.88%   |
| 0.51-1.0   | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 29        | 53.7%   |
| 2.01-3.0  | 9         | 16.67%  |
| 3.01-4.0  | 5         | 9.26%   |
| 0.51-1.0  | 5         | 9.26%   |
| 0.01-0.5  | 3         | 5.56%   |
| 4.01-8.0  | 2         | 3.7%    |
| 8.01-16.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 71.15%  |
| 2      | 12        | 23.08%  |
| 4      | 1         | 1.92%   |
| 3      | 1         | 1.92%   |
| 0      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 56.86%  |
| Yes       | 22        | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 92.31%  |
| No        | 4         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 78.85%  |
| No        | 11        | 21.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 52.94%  |
| Yes       | 24        | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 15        | 28.85%  |
| France      | 9         | 17.31%  |
| Russia      | 5         | 9.62%   |
| China       | 4         | 7.69%   |
| Turkey      | 3         | 5.77%   |
| Germany     | 3         | 5.77%   |
| Spain       | 2         | 3.85%   |
| Brazil      | 2         | 3.85%   |
| Ukraine     | 1         | 1.92%   |
| South Korea | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Mexico      | 1         | 1.92%   |
| Kazakhstan  | 1         | 1.92%   |
| Ireland     | 1         | 1.92%   |
| Indonesia   | 1         | 1.92%   |
| Canada      | 1         | 1.92%   |
| Belarus     | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lincoln                  | 7         | 13.46%  |
| Corbeil-Essonnes         | 3         | 5.77%   |
| Omaha                    | 2         | 3.85%   |
| Moscow                   | 2         | 3.85%   |
| Malvern                  | 2         | 3.85%   |
| Istanbul                 | 2         | 3.85%   |
| Guangzhou                | 2         | 3.85%   |
| Cerons                   | 2         | 3.85%   |
| Yongin-si                | 1         | 1.92%   |
| Wylie                    | 1         | 1.92%   |
| Wiesbaden                | 1         | 1.92%   |
| Vitebsk                  | 1         | 1.92%   |
| Vienne-le-Chateau        | 1         | 1.92%   |
| Valenciennes             | 1         | 1.92%   |
| St Petersburg            | 1         | 1.92%   |
| Shenzhen                 | 1         | 1.92%   |
| Seyhan                   | 1         | 1.92%   |
| Sabadell                 | 1         | 1.92%   |
| Rivne                    | 1         | 1.92%   |
| Pinangsia                | 1         | 1.92%   |
| Petropavlovsk-Kamchatsky | 1         | 1.92%   |
| Paris                    | 1         | 1.92%   |
| Oviedo                   | 1         | 1.92%   |
| Ottawa                   | 1         | 1.92%   |
| Oryol                    | 1         | 1.92%   |
| Missoula                 | 1         | 1.92%   |
| Lüdenscheid             | 1         | 1.92%   |
| Leverkusen               | 1         | 1.92%   |
| Fayetteville             | 1         | 1.92%   |
| Cork                     | 1         | 1.92%   |
| Ciudad del Carmen        | 1         | 1.92%   |
| Chengdu                  | 1         | 1.92%   |
| Borderes-sur-l'Echez     | 1         | 1.92%   |
| Blumenau                 | 1         | 1.92%   |
| Amsterdam                | 1         | 1.92%   |
| Americana                | 1         | 1.92%   |
| Almaty                   | 1         | 1.92%   |
| Acworth                  | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 11     | 18.03%  |
| Seagate             | 9         | 16     | 14.75%  |
| Sandisk             | 7         | 7      | 11.48%  |
| WDC                 | 6         | 7      | 9.84%   |
| Toshiba             | 4         | 4      | 6.56%   |
| Unknown             | 3         | 3      | 4.92%   |
| Crucial             | 3         | 3      | 4.92%   |
| SK hynix            | 2         | 2      | 3.28%   |
| Kingston            | 2         | 2      | 3.28%   |
| HGST HTS            | 2         | 4      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| Transcend           | 1         | 1      | 1.64%   |
| Silicon Motion      | 1         | 2      | 1.64%   |
| Qumo                | 1         | 1      | 1.64%   |
| Plextor             | 1         | 1      | 1.64%   |
| NFHK                | 1         | 1      | 1.64%   |
| LITEON              | 1         | 1      | 1.64%   |
| Hitachi             | 1         | 1      | 1.64%   |
| Corsair             | 1         | 1      | 1.64%   |
| Apacer              | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| SK hynix PC711 NVMe 512GB                           | 2         | 3.13%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 3.13%   |
| Seagate ST4000NM 0033-9ZM170 4TB                    | 2         | 3.13%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 3.13%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 3.13%   |
| HGST HTS 721010A9E630 1TB                           | 2         | 3.13%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1.56%   |
| WDC WD6400BPVT-80HXZT3 640GB                        | 1         | 1.56%   |
| WDC WD3200BEVT-75ZCT2 320GB                         | 1         | 1.56%   |
| WDC WD3200AAKX-221CA1 320GB                         | 1         | 1.56%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB                | 1         | 1.56%   |
| WDC PC SN530 NVMe 512GB                             | 1         | 1.56%   |
| Unknown SC64G  64GB                                 | 1         | 1.56%   |
| Unknown SA32G  32GB                                 | 1         | 1.56%   |
| Unknown NCard  32GB                                 | 1         | 1.56%   |
| Transcend TS256GMTS430S 256GB SSD                   | 1         | 1.56%   |
| Toshiba THNSN5256GPUK NVMe 256GB                    | 1         | 1.56%   |
| Toshiba MK3275GSX 320GB                             | 1         | 1.56%   |
| Toshiba HDWL110 1TB                                 | 1         | 1.56%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.56%   |
| Silicon Motion MS10 1TB                             | 1         | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1.56%   |
| Seagate ST31000524AS 1TB                            | 1         | 1.56%   |
| Seagate ST2000DM001-1CH164 2TB                      | 1         | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.56%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1         | 1.56%   |
| Seagate Expansion HDD 14TB                          | 1         | 1.56%   |
| Sandisk WD PC SN740 SDDQMQD-512G-1201 512GB         | 1         | 1.56%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.56%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1.56%   |
| SanDisk SSD PLUS 2000GB                             | 1         | 1.56%   |
| SanDisk SDSSDH3 500G                                | 1         | 1.56%   |
| SanDisk SDSSDH3 2T00 2TB                            | 1         | 1.56%   |
| SanDisk DF4032  32GB                                | 1         | 1.56%   |
| Samsung SSD PM830 mSATA 256GB                       | 1         | 1.56%   |
| Samsung SSD 860 EVO 500GB                           | 1         | 1.56%   |
| Samsung SSD 860 EVO 250GB                           | 1         | 1.56%   |
| Samsung SSD 840 PRO Series 256GB                    | 1         | 1.56%   |
| Samsung SSD 840 EVO 120GB                           | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 16     | 45%     |
| WDC                 | 3         | 3      | 15%     |
| Toshiba             | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| HGST HTS            | 2         | 4      | 10%     |
| Hitachi             | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 25%     |
| SanDisk             | 4         | 4      | 16.67%  |
| Crucial             | 3         | 3      | 12.5%   |
| Kingston            | 2         | 2      | 8.33%   |
| China               | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Transcend           | 1         | 1      | 4.17%   |
| Qumo                | 1         | 1      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Apacer              | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 23        | 24     | 41.07%  |
| HDD     | 17        | 29     | 30.36%  |
| NVMe    | 11        | 14     | 19.64%  |
| MMC     | 4         | 4      | 7.14%   |
| Unknown | 1         | 1      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 44     | 66.07%  |
| NVMe | 11        | 14     | 19.64%  |
| SAS  | 4         | 10     | 7.14%   |
| MMC  | 4         | 4      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 61.36%  |
| 0.51-1.0   | 11        | 15     | 25%     |
| 1.01-2.0   | 3         | 3      | 6.82%   |
| 3.01-4.0   | 2         | 4      | 4.55%   |
| 10.01-20.0 | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 39.22%  |
| 251-500        | 10        | 19.61%  |
| 501-1000       | 6         | 11.76%  |
| More than 3000 | 3         | 5.88%   |
| 21-50          | 3         | 5.88%   |
| 51-100         | 3         | 5.88%   |
| 2001-3000      | 2         | 3.92%   |
| 1001-2000      | 2         | 3.92%   |
| 1-20           | 2         | 3.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 44.44%  |
| 21-50          | 11        | 20.37%  |
| 101-250        | 7         | 12.96%  |
| 51-100         | 4         | 7.41%   |
| 1001-2000      | 3         | 5.56%   |
| 2001-3000      | 2         | 3.7%    |
| 501-1000       | 2         | 3.7%    |
| More than 3000 | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2         | 2      | 20%     |
| HGST HTS 721010A9E630 1TB        | 2         | 4      | 20%     |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 10%     |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 1      | 10%     |
| Toshiba MK3275GSX 320GB          | 1         | 1      | 10%     |
| Seagate ST320LT007-9ZV142 320GB  | 1         | 3      | 10%     |
| Seagate ST2000DM001-1CH164 2TB   | 1         | 1      | 10%     |
| Crucial CT240BX200SSD1 240GB     | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 6      | 40%     |
| WDC      | 2         | 2      | 20%     |
| HGST HTS | 2         | 4      | 20%     |
| Toshiba  | 1         | 1      | 10%     |
| Crucial  | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 6      | 50%     |
| HGST HTS | 2         | 4      | 25%     |
| WDC      | 1         | 1      | 12.5%   |
| Toshiba  | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 12     | 77.78%  |
| SSD  | 2         | 2      | 22.22%  |

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
| Works    | 35        | 44     | 62.5%   |
| Detected | 12        | 14     | 21.43%  |
| Malfunc  | 9         | 14     | 16.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 67.92%  |
| SanDisk                      | 4         | 7.55%   |
| Samsung Electronics          | 3         | 5.66%   |
| AMD                          | 3         | 5.66%   |
| SK hynix                     | 2         | 3.77%   |
| Nvidia                       | 2         | 3.77%   |
| Toshiba America Info Systems | 1         | 1.89%   |
| Silicon Motion               | 1         | 1.89%   |
| Phison Electronics           | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 8.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 8.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 5.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3         | 5.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 3.45%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 3.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 3.45%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1         | 1.72%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                          | 1         | 1.72%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1         | 1.72%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                                   | 1         | 1.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1         | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1         | 1.72%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.72%   |
| Nvidia MCP61 IDE                                                                        | 1         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.72%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 1         | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1         | 1.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 61.11%  |
| NVMe | 11        | 20.37%  |
| IDE  | 8         | 14.81%  |
| RAID | 2         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 86.27%  |
| AMD    | 6         | 11.76%  |
| ARM    | 1         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 5.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 3.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 3.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 3.92%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 2         | 3.92%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 1.96%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.96%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 1.96%   |
| Intel Pentium D CPU 3.20GHz                 | 1         | 1.96%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 1.96%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.96%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.96%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.96%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.96%   |
| Intel Core i7-3687U CPU @ 2.10GHz           | 1         | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 1.96%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 1.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.96%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.96%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1         | 1.96%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 1         | 1.96%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 1         | 1.96%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.96%   |
| Intel Core 2 CPU P8700 @ 2.53GHz            | 1         | 1.96%   |
| Intel Core 2 CPU P8600 @ 2.40GHz            | 1         | 1.96%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 1.96%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 1         | 1.96%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 1.96%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 1.96%   |
| Intel 13th Gen Core i7-1355U                | 1         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.96%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz     | 1         | 1.96%   |
| ARM Allwinner sun8i Family Processor        | 1         | 1.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 25.49%  |
| Other                   | 5         | 9.8%    |
| Intel Core i7           | 5         | 9.8%    |
| Intel Core i3           | 4         | 7.84%   |
| Intel Core 2 Duo        | 3         | 5.88%   |
| Intel Atom              | 3         | 5.88%   |
| Intel Xeon              | 2         | 3.92%   |
| Intel Core 2            | 2         | 3.92%   |
| Intel Celeron           | 2         | 3.92%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Pentium Dual      | 1         | 1.96%   |
| Intel Pentium D         | 1         | 1.96%   |
| Intel Pentium           | 1         | 1.96%   |
| Intel Core m3           | 1         | 1.96%   |
| ARM Allwinner           | 1         | 1.96%   |
| AMD Ryzen 7             | 1         | 1.96%   |
| AMD Phenom II X4        | 1         | 1.96%   |
| AMD E1                  | 1         | 1.96%   |
| AMD Athlon II X2        | 1         | 1.96%   |
| AMD A8                  | 1         | 1.96%   |
| AMD A4                  | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 50.98%  |
| 4      | 15        | 29.41%  |
| 8      | 6         | 11.76%  |
| 1      | 2         | 3.92%   |
| 10     | 1         | 1.96%   |
| 6      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 98.04%  |
| 2      | 1         | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 58.82%  |
| 1      | 21        | 41.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 96.08%  |
| 32-bit         | 1         | 1.96%   |
| Unknown        | 1         | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 9.8%    |
| 0x1067a    | 5         | 9.8%    |
| Unknown    | 5         | 9.8%    |
| 0x206a7    | 4         | 7.84%   |
| 0x806ea    | 3         | 5.88%   |
| 0x306c3    | 3         | 5.88%   |
| 0x806d1    | 2         | 3.92%   |
| 0x406e3    | 2         | 3.92%   |
| 0x30678    | 2         | 3.92%   |
| 0x06001119 | 2         | 3.92%   |
| 0xf65      | 1         | 1.96%   |
| 0xb06a3    | 1         | 1.96%   |
| 0x906ed    | 1         | 1.96%   |
| 0x906eb    | 1         | 1.96%   |
| 0x906e9    | 1         | 1.96%   |
| 0x806ec    | 1         | 1.96%   |
| 0x806e9    | 1         | 1.96%   |
| 0x806c1    | 1         | 1.96%   |
| 0x706a1    | 1         | 1.96%   |
| 0x406c4    | 1         | 1.96%   |
| 0x206d7    | 1         | 1.96%   |
| 0x206c2    | 1         | 1.96%   |
| 0x106c2    | 1         | 1.96%   |
| 0x10676    | 1         | 1.96%   |
| 0x0a50000c | 1         | 1.96%   |
| 0x0500010d | 1         | 1.96%   |
| 0x010000c8 | 1         | 1.96%   |
| 0x010000b7 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 15.69%  |
| Penryn        | 6         | 11.76%  |
| IvyBridge     | 6         | 11.76%  |
| SandyBridge   | 5         | 9.8%    |
| Silvermont    | 3         | 5.88%   |
| Haswell       | 3         | 5.88%   |
| Unknown       | 3         | 5.88%   |
| Skylake       | 2         | 3.92%   |
| Piledriver    | 2         | 3.92%   |
| K10           | 2         | 3.92%   |
| Icelake       | 2         | 3.92%   |
| Bonnell       | 2         | 3.92%   |
| Zen 3         | 1         | 1.96%   |
| Westmere      | 1         | 1.96%   |
| TigerLake     | 1         | 1.96%   |
| NetBurst      | 1         | 1.96%   |
| Goldmont plus | 1         | 1.96%   |
| Core          | 1         | 1.96%   |
| Bobcat        | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 64.91%  |
| Nvidia | 14        | 24.56%  |
| AMD    | 6         | 10.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 8.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 8.47%   |
| Intel UHD Graphics 620                                                                   | 3         | 5.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 3.39%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 3.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 3.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 3.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 3.39%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 1.69%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 1.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.69%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.69%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 1.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 1.69%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.69%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.69%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.69%   |
| Intel HD Graphics 620                                                                    | 1         | 1.69%   |
| Intel HD Graphics 515                                                                    | 1         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.69%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.69%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.69%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.69%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.69%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 1         | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.69%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 59.62%  |
| 1 x Nvidia     | 8         | 15.38%  |
| Intel + Nvidia | 5         | 9.62%   |
| 1 x AMD        | 4         | 7.69%   |
| Other          | 1         | 1.92%   |
| 2 x AMD        | 1         | 1.92%   |
| Intel + AMD    | 1         | 1.92%   |
| AMD + Nvidia   | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 46        | 90.2%   |
| Unknown | 5         | 9.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 63.46%  |
| 1.01-2.0   | 7         | 13.46%  |
| 0.51-1.0   | 4         | 7.69%   |
| 0.01-0.5   | 4         | 7.69%   |
| 3.01-4.0   | 2         | 3.85%   |
| 7.01-8.0   | 1         | 1.92%   |
| 5.01-6.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 10        | 20%     |
| LG Display              | 7         | 14%     |
| AU Optronics            | 5         | 10%     |
| Acer                    | 4         | 8%      |
| Lenovo                  | 3         | 6%      |
| Iiyama                  | 3         | 6%      |
| Dell                    | 3         | 6%      |
| Chimei Innolux          | 3         | 6%      |
| Sharp                   | 2         | 4%      |
| BOE                     | 2         | 4%      |
| Plain Tree Systems      | 1         | 2%      |
| Philips                 | 1         | 2%      |
| Gateway                 | 1         | 2%      |
| CVT                     | 1         | 2%      |
| CPT                     | 1         | 2%      |
| Chi Mei Optoelectronics | 1         | 2%      |
| AOC                     | 1         | 2%      |
| Ancor Communications    | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2283H IVM562E 1920x1080 480x270mm 21.7-inch                     | 3         | 6%      |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch    | 2         | 4%      |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 4%      |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 2         | 4%      |
| Sharp LCD Monitor SHP154B 1920x1080 309x174mm 14.0-inch                  | 1         | 2%      |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 2%      |
| Samsung Electronics SyncMaster SAM0216 1280x1024 340x270mm 17.1-inch     | 1         | 2%      |
| Samsung Electronics SMC27A550U SAM07F6 1920x1080 598x336mm 27.0-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch     | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 2%      |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 700x400mm 31.7-inch       | 1         | 2%      |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 1         | 2%      |
| Plain Tree Systems Monitor PTS076D 1280x1024 376x301mm 19.0-inch         | 1         | 2%      |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 2%      |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD03BD 1920x1080 276x156mm 12.5-inch             | 1         | 2%      |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 2%      |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2%      |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2%      |
| Gateway FPD1976W GWY0785 1440x900 410x257mm 19.1-inch                    | 1         | 2%      |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                       | 1         | 2%      |
| Dell E151FPp DEL7006 1024x768 304x228mm 15.0-inch                        | 1         | 2%      |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                          | 1         | 2%      |
| CVT CVTE TV CVT0003 1440x900                                             | 1         | 2%      |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 2%      |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 1         | 2%      |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                    | 1         | 2%      |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 2%      |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 1         | 2%      |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 1         | 2%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2%      |
| AU Optronics LCD Monitor AUO215C 1366x768 256x144mm 11.6-inch            | 1         | 2%      |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 2%      |
| AOC 831W AOC1831 1366x768 410x230mm 18.5-inch                            | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 20        | 42.55%  |
| 1366x768 (WXGA)  | 12        | 25.53%  |
| 1280x800 (WXGA)  | 4         | 8.51%   |
| 1600x900 (HD+)   | 3         | 6.38%   |
| 3456x2160        | 2         | 4.26%   |
| 1440x900 (WXGA+) | 2         | 4.26%   |
| 3840x2160 (4K)   | 1         | 2.13%   |
| 2560x1440 (QHD)  | 1         | 2.13%   |
| 1280x1024 (SXGA) | 1         | 2.13%   |
| 1024x768 (XGA)   | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 15        | 30%     |
| 14     | 6         | 12%     |
| 23     | 5         | 10%     |
| 12     | 5         | 10%     |
| 24     | 3         | 6%      |
| 19     | 3         | 6%      |
| 17     | 3         | 6%      |
| 27     | 2         | 4%      |
| 13     | 2         | 4%      |
| 11     | 2         | 4%      |
| 31     | 1         | 2%      |
| 26     | 1         | 2%      |
| 21     | 1         | 2%      |
| 18     | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 42.86%  |
| 501-600     | 11        | 22.45%  |
| 201-300     | 8         | 16.33%  |
| 401-500     | 4         | 8.16%   |
| 351-400     | 4         | 8.16%   |
| 601-700     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 77.78%  |
| 16/10 | 7         | 15.56%  |
| 5/4   | 1         | 2.22%   |
| 4/3   | 1         | 2.22%   |
| 3/2   | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 30%     |
| 201-250        | 8         | 16%     |
| 81-90          | 7         | 14%     |
| 61-70          | 5         | 10%     |
| 151-200        | 3         | 6%      |
| 51-60          | 2         | 4%      |
| 301-350        | 2         | 4%      |
| 251-300        | 2         | 4%      |
| 141-150        | 2         | 4%      |
| 71-80          | 1         | 2%      |
| 351-500        | 1         | 2%      |
| 131-140        | 1         | 2%      |
| 121-130        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 36.96%  |
| 121-160       | 16        | 34.78%  |
| 101-120       | 8         | 17.39%  |
| More than 240 | 3         | 6.52%   |
| 161-240       | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 83.02%  |
| 2     | 4         | 7.55%   |
| 0     | 4         | 7.55%   |
| 3     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 28.92%  |
| Realtek Semiconductor           | 22        | 26.51%  |
| Qualcomm Atheros                | 18        | 21.69%  |
| Qualcomm Atheros Communications | 5         | 6.02%   |
| Marvell Technology Group        | 3         | 3.61%   |
| Ralink Technology               | 2         | 2.41%   |
| Qualcomm                        | 2         | 2.41%   |
| Nvidia                          | 2         | 2.41%   |
| Broadcom                        | 2         | 2.41%   |
| Samsung Electronics             | 1         | 1.2%    |
| Microsoft                       | 1         | 1.2%    |
| Memorex                         | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 11.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 5.15%   |
| Qualcomm Atheros AR9271 802.11n                                        | 4         | 4.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 4         | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 3.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 3.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 3.09%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 3.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2         | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 2.06%   |
| Qualcomm POCO F3                                                       | 2         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 2.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 2.06%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 2.06%   |
| Intel Wireless 8265 / 8275                                             | 2         | 2.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 2         | 2.06%   |
| Samsung HSPA Modem                                                     | 1         | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 1         | 1.03%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1         | 1.03%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 1.03%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.03%   |
| Qualcomm Atheros Ubiquiti WiFiStationEXT 802.11n [Atheros AR9271]      | 1         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.03%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]    | 1         | 1.03%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 1         | 1.03%   |
| Memorex 802.11n WLAN Adapter                                           | 1         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 38.3%   |
| Qualcomm Atheros                | 14        | 29.79%  |
| Realtek Semiconductor           | 6         | 12.77%  |
| Qualcomm Atheros Communications | 5         | 10.64%  |
| Ralink Technology               | 2         | 4.26%   |
| Memorex                         | 1         | 2.13%   |
| Broadcom                        | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9271 802.11n                                     | 4         | 8.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4         | 8.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 3         | 6.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 6.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 4.17%   |
| Intel Wireless 8265 / 8275                                          | 2         | 4.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                        | 2         | 4.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1         | 2.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 1         | 2.08%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1         | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1         | 2.08%   |
| Qualcomm Atheros Ubiquiti WiFiStationEXT 802.11n [Atheros AR9271]   | 1         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 1         | 2.08%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1         | 2.08%   |
| Memorex 802.11n WLAN Adapter                                        | 1         | 2.08%   |
| Intel Wireless 7265                                                 | 1         | 2.08%   |
| Intel Wireless 3165                                                 | 1         | 2.08%   |
| Intel WiFi Link 5100                                                | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201                                                 | 1         | 2.08%   |
| Intel Raptor Lake PCH CNVi WiFi                                     | 1         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 1         | 2.08%   |
| Intel Centrino Wireless-N 6150                                      | 1         | 2.08%   |
| Intel Centrino Wireless-N + WiMAX 6150                              | 1         | 2.08%   |
| Intel Centrino Advanced-N 6235                                      | 1         | 2.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 37.5%   |
| Intel                    | 15        | 31.25%  |
| Qualcomm Atheros         | 6         | 12.5%   |
| Marvell Technology Group | 3         | 6.25%   |
| Qualcomm                 | 2         | 4.17%   |
| Nvidia                   | 2         | 4.17%   |
| Microsoft                | 1         | 2.08%   |
| Broadcom                 | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 22.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 10.42%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 6.25%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 4.17%   |
| Qualcomm POCO F3                                                       | 2         | 4.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 4.17%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 4.17%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 2.08%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 2.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 2.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 2.08%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 1         | 2.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 2.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 2.08%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.08%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.08%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 2.08%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.08%   |
| Intel 82567LF Gigabit Network Connection                               | 1         | 2.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 53.33%  |
| WiFi     | 41        | 45.56%  |
| Modem    | 1         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 51.02%  |
| Ethernet | 24        | 48.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 54.9%   |
| 1     | 20        | 39.22%  |
| 0     | 2         | 3.92%   |
| 3     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 74.51%  |
| Yes  | 13        | 25.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 32%     |
| Broadcom                        | 5         | 20%     |
| Qualcomm Atheros Communications | 4         | 16%     |
| Toshiba                         | 2         | 8%      |
| Realtek Semiconductor           | 2         | 8%      |
| Cambridge Silicon Radio         | 2         | 8%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 6         | 24%     |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 12%     |
| Realtek Bluetooth Radio                             | 2         | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8%      |
| Intel Bluetooth wireless interface                  | 2         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 8%      |
| Toshiba RT Bluetooth Radio                          | 1         | 4%      |
| Toshiba Bluetooth Device                            | 1         | 4%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 4%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 69.35%  |
| Nvidia                | 10        | 16.13%  |
| AMD                   | 5         | 8.06%   |
| Realtek Semiconductor | 2         | 3.23%   |
| Lenovo                | 1         | 1.61%   |
| Creative Labs         | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 8.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 7.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 7.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 5.97%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 4.48%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 4.48%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 2.99%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 2.99%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.99%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.49%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.49%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.49%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.49%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.49%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.49%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                                            | 1         | 1.49%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.49%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 1.49%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 1         | 1.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 29.55%  |
| SK hynix            | 8         | 18.18%  |
| Micron Technology   | 6         | 13.64%  |
| Unknown             | 4         | 9.09%   |
| Kingston            | 4         | 9.09%   |
| TEXTORM             | 1         | 2.27%   |
| Ramaxel Technology  | 1         | 2.27%   |
| Qimonda             | 1         | 2.27%   |
| PNY                 | 1         | 2.27%   |
| GOODRAM             | 1         | 2.27%   |
| G.Skill             | 1         | 2.27%   |
| Crucial             | 1         | 2.27%   |
| Corsair             | 1         | 2.27%   |
| A-DATA Technology   | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 3         | 6.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 4.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                               | 1         | 2.22%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                       | 1         | 2.22%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1         | 2.22%   |
| TEXTORM RAM TXS8G1M2666C19 8GB SODIMM DDR4 2667MT/s                       | 1         | 2.22%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1066MT/s                             | 1         | 2.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s                  | 1         | 2.22%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 2.22%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s                    | 1         | 2.22%   |
| SK hynix RAM HMT41GS6AFR8A-H9 8192MB SODIMM DDR3 1333MT/s                 | 1         | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 2.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.22%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s                | 1         | 2.22%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                              | 1         | 2.22%   |
| Samsung RAM Module 4096MB DIMM DDR3 1066MT/s                              | 1         | 2.22%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s                         | 1         | 2.22%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 2.22%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s                     | 1         | 2.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.22%   |
| Samsung RAM M471B5273CM0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.22%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                       | 1         | 2.22%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |
| Qimonda RAM 64T512022EDL2.5A 4096MB SODIMM DDR 800MT/s                    | 1         | 2.22%   |
| PNY RAM Module 4096MB DIMM DDR3 1066MT/s                                  | 1         | 2.22%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s            | 1         | 2.22%   |
| Micron RAM Module 2048MB DIMM DDR3 1066MT/s                               | 1         | 2.22%   |
| Micron RAM H6451U64F7066G 4096MB SODIMM DDR3 1067MT/s                     | 1         | 2.22%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G3H1R 4GB SODIMM DDR4 2400MT/s                    | 1         | 2.22%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1866MT/s                           | 1         | 2.22%   |
| Kingston RAM K821PJ-MID 16GB SODIMM DDR4 2400MT/s                         | 1         | 2.22%   |
| Kingston RAM ASU1600S11-4G-EDEG 4GB SODIMM DDR3 1600MT/s                  | 1         | 2.22%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                     | 1         | 2.22%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s                    | 1         | 2.22%   |
| GOODRAM RAM GY1600D364L9/4G 4GB DIMM DDR3 1333MT/s                        | 1         | 2.22%   |
| G.Skill RAM F3-2400C11-8GXM 8GB DIMM DDR3 2400MT/s                        | 1         | 2.22%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 51.28%  |
| DDR4    | 13        | 33.33%  |
| DDR2    | 2         | 5.13%   |
| LPDDR4  | 1         | 2.56%   |
| LPDDR3  | 1         | 2.56%   |
| DDR     | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 59.46%  |
| DIMM         | 12        | 32.43%  |
| Row Of Chips | 3         | 8.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 18        | 41.86%  |
| 8192  | 15        | 34.88%  |
| 2048  | 7         | 16.28%  |
| 16384 | 2         | 4.65%   |
| 1024  | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 26.83%  |
| 2400  | 6         | 14.63%  |
| 3200  | 5         | 12.2%   |
| 2667  | 3         | 7.32%   |
| 1333  | 3         | 7.32%   |
| 1066  | 2         | 4.88%   |
| 800   | 2         | 4.88%   |
| 4267  | 1         | 2.44%   |
| 3534  | 1         | 2.44%   |
| 2133  | 1         | 2.44%   |
| 1867  | 1         | 2.44%   |
| 1866  | 1         | 2.44%   |
| 1334  | 1         | 2.44%   |
| 1067  | 1         | 2.44%   |
| 975   | 1         | 2.44%   |
| 667   | 1         | 2.44%   |

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


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP Deskjet 3510 series | 1         | 100%    |

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
| Chicony Electronics                    | 7         | 23.33%  |
| Sunplus Innovation Technology          | 5         | 16.67%  |
| Microdia                               | 3         | 10%     |
| Lenovo                                 | 3         | 10%     |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| Bison Electronics                      | 2         | 6.67%   |
| Z-Star Microelectronics                | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Importek                               | 1         | 3.33%   |
| IMC Networks                           | 1         | 3.33%   |
| GoPro                                  | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                                     | 3         | 10%     |
| Chicony Integrated Camera                                    | 2         | 6.67%   |
| Z-Star Webcam                                                | 1         | 3.33%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                        | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 3.33%   |
| Sunplus HD WebCam                                            | 1         | 3.33%   |
| Sunplus Asus Webcam                                          | 1         | 3.33%   |
| Sunplus 2K FHD camera                                        | 1         | 3.33%   |
| Realtek Lenovo EasyCamera                                    | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 3.33%   |
| Quanta HD User Facing                                        | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                                | 1         | 3.33%   |
| Microdia Integrated_Webcam_1.3M                              | 1         | 3.33%   |
| Microdia Integrated Webcam HD                                | 1         | 3.33%   |
| Logitech C922 Pro Stream Webcam                              | 1         | 3.33%   |
| Logitech C505 HD Webcam                                      | 1         | 3.33%   |
| Importek TOSHIBA Web Camera                                  | 1         | 3.33%   |
| IMC Networks UVC VGA Webcam                                  | 1         | 3.33%   |
| GoPro HERO4 Black                                            | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera                                   | 1         | 3.33%   |
| Chicony Thinkpad T430 camera                                 | 1         | 3.33%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 3.33%   |
| Chicony HP Webcam                                            | 1         | 3.33%   |
| Chicony Chicony USB2.0 Camera                                | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 3.33%   |
| Bison ThinkPad Integrated Camera                             | 1         | 3.33%   |
| Bison Integrated Camera                                      | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| AuthenTec | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| AuthenTec AES2810 | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| Upek     | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 40%     |
| Broadcom 5880                                              | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 61.54%  |
| 1     | 15        | 28.85%  |
| 2     | 5         | 9.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 12        | 50%     |
| Chipcard              | 5         | 20.83%  |
| Net/wireless          | 2         | 8.33%   |
| Multimedia controller | 2         | 8.33%   |
| Fingerprint reader    | 1         | 4.17%   |
| Camera                | 1         | 4.17%   |
| Bluetooth             | 1         | 4.17%   |

