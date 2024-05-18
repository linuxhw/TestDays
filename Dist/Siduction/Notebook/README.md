Siduction - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Siduction.

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

Total: 55

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [3936c99d1e](https://linux-hardware.org/?probe=3936c99d1e) | Mar 25, 2024 |
| Lenovo  | ThinkPad T470 W10DG 20JN... | [df52747427](https://linux-hardware.org/?probe=df52747427) | Jan 22, 2024 |
| HP      | 250 G7 Notebook PC          | [3b58774e8d](https://linux-hardware.org/?probe=3b58774e8d) | Jan 15, 2024 |
| Lenovo  | ThinkPad T470 W10DG 20JN... | [d17724d57c](https://linux-hardware.org/?probe=d17724d57c) | Jan 11, 2024 |
| ASUSTek | BU201LA                     | [2985f7a222](https://linux-hardware.org/?probe=2985f7a222) | Dec 22, 2023 |
| Lenovo  | ThinkPad T580 20LAS1GG00    | [c592d82494](https://linux-hardware.org/?probe=c592d82494) | Dec 05, 2023 |
| Lenovo  | ThinkPad L540 20AUS01H00    | [6bdb162853](https://linux-hardware.org/?probe=6bdb162853) | Nov 29, 2023 |
| Lenovo  | ThinkPad T490 20N3SFKX00    | [9d5bc38102](https://linux-hardware.org/?probe=9d5bc38102) | Nov 29, 2023 |
| HP      | 250 G7 Notebook PC          | [64d7d103a5](https://linux-hardware.org/?probe=64d7d103a5) | Oct 24, 2023 |
| HP      | 250 G7 Notebook PC          | [91d0aa5397](https://linux-hardware.org/?probe=91d0aa5397) | Oct 10, 2023 |
| HP      | 250 G7 Notebook PC          | [c2123c4f21](https://linux-hardware.org/?probe=c2123c4f21) | Oct 10, 2023 |
| HP      | 250 G7 Notebook PC          | [428177914f](https://linux-hardware.org/?probe=428177914f) | Sep 17, 2023 |
| HP      | 250 G7 Notebook PC          | [f2b0e180d4](https://linux-hardware.org/?probe=f2b0e180d4) | Aug 27, 2023 |
| HP      | ZBook 15 G6                 | [eb23ebb0b8](https://linux-hardware.org/?probe=eb23ebb0b8) | Jun 10, 2023 |
| Apple   | MacBookPro9,2               | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| HP      | 250 G7 Notebook PC          | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| HP      | ProBook 640 G1              | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Dell    | Vostro 15 3510              | [fc82fe9907](https://linux-hardware.org/?probe=fc82fe9907) | May 11, 2023 |
| Dell    | Latitude 5491               | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| ASUSTek | X751LAB                     | [03465bed03](https://linux-hardware.org/?probe=03465bed03) | Apr 06, 2023 |
| HP      | ProBook 640 G1              | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| Acer    | Swift SF314-51              | [5a73818024](https://linux-hardware.org/?probe=5a73818024) | Mar 27, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | [0c7e919608](https://linux-hardware.org/?probe=0c7e919608) | Mar 20, 2023 |
| Acer    | Aspire E5-551G              | [58703e3260](https://linux-hardware.org/?probe=58703e3260) | Mar 15, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | [5c39a363d8](https://linux-hardware.org/?probe=5c39a363d8) | Feb 28, 2023 |
| HP      | EliteBook 865 16 inch G9... | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Acer    | Aspire V5-471               | [fe551b92a5](https://linux-hardware.org/?probe=fe551b92a5) | Oct 02, 2022 |
| Acer    | Aspire A515-55              | [bed4db4cf3](https://linux-hardware.org/?probe=bed4db4cf3) | Jul 16, 2022 |
| Acer    | Aspire E5-771G              | [a765f92826](https://linux-hardware.org/?probe=a765f92826) | Mar 28, 2022 |
| Lenovo  | ThinkPad T410 253725G       | [3e1c463980](https://linux-hardware.org/?probe=3e1c463980) | Jan 16, 2022 |
| Lenovo  | IdeaPad 3 15IIL05 81WE      | [7fa0610547](https://linux-hardware.org/?probe=7fa0610547) | Jan 02, 2022 |
| Lenovo  | ThinkPad E590 20NB001AIX    | [436614e885](https://linux-hardware.org/?probe=436614e885) | Sep 26, 2021 |
| Lenovo  | ThinkPad T410 253725G       | [65b842202c](https://linux-hardware.org/?probe=65b842202c) | Aug 06, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | [70ddebc8cc](https://linux-hardware.org/?probe=70ddebc8cc) | Jul 25, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | [455c830431](https://linux-hardware.org/?probe=455c830431) | Jul 25, 2021 |
| TUXEDO  | Book BA1510                 | [80b8c9719c](https://linux-hardware.org/?probe=80b8c9719c) | Jul 11, 2021 |
| HP      | ProBook 4520s               | [50b007f51d](https://linux-hardware.org/?probe=50b007f51d) | Jun 26, 2021 |
| HP      | ProBook 4520s               | [261b02ab53](https://linux-hardware.org/?probe=261b02ab53) | Jun 20, 2021 |
| HP      | Laptop 17-ca1xxx            | [99f175055d](https://linux-hardware.org/?probe=99f175055d) | May 05, 2021 |
| HP      | Laptop 17-ca1xxx            | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| HP      | Laptop 17-ca1xxx            | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| HP      | Laptop 17-ca1xxx            | [a3ea535d80](https://linux-hardware.org/?probe=a3ea535d80) | Feb 04, 2021 |
| HP      | Laptop 17-ca1xxx            | [d88b363f5e](https://linux-hardware.org/?probe=d88b363f5e) | Jan 19, 2021 |
| HP      | Laptop 17-ca1xxx            | [5e6eb88969](https://linux-hardware.org/?probe=5e6eb88969) | Jan 02, 2021 |
| HP      | Laptop 17-ca1xxx            | [09675fa9a5](https://linux-hardware.org/?probe=09675fa9a5) | Dec 09, 2020 |
| HP      | Laptop 17-ca1xxx            | [0779e6ce28](https://linux-hardware.org/?probe=0779e6ce28) | Nov 18, 2020 |
| HP      | Laptop 17-ca1xxx            | [386583ebea](https://linux-hardware.org/?probe=386583ebea) | Sep 02, 2020 |
| HP      | 250 G7 Notebook PC          | [52a48bdcb8](https://linux-hardware.org/?probe=52a48bdcb8) | Aug 02, 2020 |
| Lenovo  | ThinkPad E590 20NB001AIX    | [bc066bdf30](https://linux-hardware.org/?probe=bc066bdf30) | Feb 11, 2020 |
| HP      | Laptop 15-db0xxx            | [f6d4378d90](https://linux-hardware.org/?probe=f6d4378d90) | Jan 03, 2020 |
| Compal  | NBLBX                       | [865da8f6a9](https://linux-hardware.org/?probe=865da8f6a9) | Dec 05, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [552827c68a](https://linux-hardware.org/?probe=552827c68a) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [d942b46e5b](https://linux-hardware.org/?probe=d942b46e5b) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [17f6c8b364](https://linux-hardware.org/?probe=17f6c8b364) | Nov 20, 2019 |
| Acer    | Aspire 5750                 | [62afcd020e](https://linux-hardware.org/?probe=62afcd020e) | Feb 26, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Siduction 12       | 9         | 31.03%  |
| Siduction 11       | 7         | 24.14%  |
| Siduction          | 6         | 20.69%  |
| Siduction Unstable | 4         | 13.79%  |
| Siduction 10       | 3         | 10.34%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Siduction | 26        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 6.2.8-1-siduction-amd64        | 2         | 4.76%   |
| 6.2.6-1-siduction-amd64        | 2         | 4.76%   |
| 6.7.10-1-siduction-amd64       | 1         | 2.38%   |
| 6.6.8-1-siduction-amd64        | 1         | 2.38%   |
| 6.6.4-1-siduction-amd64        | 1         | 2.38%   |
| 6.6.2-1-siduction-amd64        | 1         | 2.38%   |
| 6.6.10-1-siduction-amd64       | 1         | 2.38%   |
| 6.5.6-1-siduction-amd64        | 1         | 2.38%   |
| 6.5.3-1-siduction-amd64        | 1         | 2.38%   |
| 6.5.2-1-siduction-amd64        | 1         | 2.38%   |
| 6.4.12-1-siduction-amd64       | 1         | 2.38%   |
| 6.3.7-1-siduction-amd64        | 1         | 2.38%   |
| 6.3.3-1-siduction-amd64        | 1         | 2.38%   |
| 6.2.15-1-siduction-amd64       | 1         | 2.38%   |
| 6.2.13-1-siduction-amd64       | 1         | 2.38%   |
| 6.2.11-1-siduction-amd64       | 1         | 2.38%   |
| 6.2.0-rc6-siduction-amd64      | 1         | 2.38%   |
| 6.1.1-4-siduction-amd64        | 1         | 2.38%   |
| 5.9.8-towo.3-siduction-amd64   | 1         | 2.38%   |
| 5.9.13-towo.1-siduction-amd64  | 1         | 2.38%   |
| 5.8.5-towo.1-siduction-amd64   | 1         | 2.38%   |
| 5.7.11-towo.2-siduction-amd64  | 1         | 2.38%   |
| 5.4.5-towo.2-siduction-amd64   | 1         | 2.38%   |
| 5.4.18-towo.1-siduction-amd64  | 1         | 2.38%   |
| 5.3.12-towo.2-siduction-amd64  | 1         | 2.38%   |
| 5.3.1-towo.2-siduction-amd64   | 1         | 2.38%   |
| 5.16.17-1-siduction-amd64      | 1         | 2.38%   |
| 5.15.15-1-siduction-amd64      | 1         | 2.38%   |
| 5.13.8-1-siduction-amd64       | 1         | 2.38%   |
| 5.13.6-1-siduction-amd64       | 1         | 2.38%   |
| 5.13.4-3-siduction-amd64       | 1         | 2.38%   |
| 5.13.1-1-siduction-amd64       | 1         | 2.38%   |
| 5.12.12-1-siduction-amd64      | 1         | 2.38%   |
| 5.11.18-1-siduction-amd64      | 1         | 2.38%   |
| 5.11.11-1-siduction-amd64      | 1         | 2.38%   |
| 5.10.4-towo.1-siduction-amd64  | 1         | 2.38%   |
| 5.10.19-towo.1-siduction-amd64 | 1         | 2.38%   |
| 5.10.17-towo.1-siduction-amd64 | 1         | 2.38%   |
| 5.10.12-towo.1-siduction-amd64 | 1         | 2.38%   |
| 4.20.11-towo.2-siduction-amd64 | 1         | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.8   | 2         | 4.76%   |
| 6.2.6   | 2         | 4.76%   |
| 6.7.10  | 1         | 2.38%   |
| 6.6.8   | 1         | 2.38%   |
| 6.6.4   | 1         | 2.38%   |
| 6.6.2   | 1         | 2.38%   |
| 6.6.10  | 1         | 2.38%   |
| 6.5.6   | 1         | 2.38%   |
| 6.5.3   | 1         | 2.38%   |
| 6.5.2   | 1         | 2.38%   |
| 6.4.12  | 1         | 2.38%   |
| 6.3.7   | 1         | 2.38%   |
| 6.3.3   | 1         | 2.38%   |
| 6.2.15  | 1         | 2.38%   |
| 6.2.13  | 1         | 2.38%   |
| 6.2.11  | 1         | 2.38%   |
| 6.2.0   | 1         | 2.38%   |
| 6.1.1   | 1         | 2.38%   |
| 5.9.8   | 1         | 2.38%   |
| 5.9.13  | 1         | 2.38%   |
| 5.8.5   | 1         | 2.38%   |
| 5.7.11  | 1         | 2.38%   |
| 5.4.5   | 1         | 2.38%   |
| 5.4.18  | 1         | 2.38%   |
| 5.3.12  | 1         | 2.38%   |
| 5.3.1   | 1         | 2.38%   |
| 5.16.17 | 1         | 2.38%   |
| 5.15.15 | 1         | 2.38%   |
| 5.13.8  | 1         | 2.38%   |
| 5.13.6  | 1         | 2.38%   |
| 5.13.4  | 1         | 2.38%   |
| 5.13.1  | 1         | 2.38%   |
| 5.12.12 | 1         | 2.38%   |
| 5.11.18 | 1         | 2.38%   |
| 5.11.11 | 1         | 2.38%   |
| 5.10.4  | 1         | 2.38%   |
| 5.10.19 | 1         | 2.38%   |
| 5.10.17 | 1         | 2.38%   |
| 5.10.12 | 1         | 2.38%   |
| 4.20.11 | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 7         | 19.44%  |
| 6.6     | 4         | 11.11%  |
| 5.13    | 4         | 11.11%  |
| 6.5     | 2         | 5.56%   |
| 6.3     | 2         | 5.56%   |
| 5.4     | 2         | 5.56%   |
| 5.3     | 2         | 5.56%   |
| 5.10    | 2         | 5.56%   |
| 6.7     | 1         | 2.78%   |
| 6.4     | 1         | 2.78%   |
| 6.1     | 1         | 2.78%   |
| 5.9     | 1         | 2.78%   |
| 5.8     | 1         | 2.78%   |
| 5.7     | 1         | 2.78%   |
| 5.16    | 1         | 2.78%   |
| 5.15    | 1         | 2.78%   |
| 5.12    | 1         | 2.78%   |
| 5.11    | 1         | 2.78%   |
| 4.20    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 16        | 55.17%  |
| XFCE            | 4         | 13.79%  |
| Unknown         | 4         | 13.79%  |
| X-Cinnamon      | 2         | 6.9%    |
| LXQt            | 1         | 3.45%   |
| GNOME Flashback | 1         | 3.45%   |
| Cinnamon        | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 22        | 84.62%  |
| Wayland | 3         | 11.54%  |
| Tty     | 1         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 18        | 66.67%  |
| Unknown | 7         | 25.93%  |
| TDM     | 1         | 3.7%    |
| GDM     | 1         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_DE   | 12        | 42.86%  |
| en_US   | 6         | 21.43%  |
| Unknown | 3         | 10.71%  |
| en_GB   | 2         | 7.14%   |
| fr_FR   | 1         | 3.57%   |
| en_CA   | 1         | 3.57%   |
| de_CH   | 1         | 3.57%   |
| de_AT   | 1         | 3.57%   |
| C       | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 17        | 62.96%  |
| BIOS | 10        | 37.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 20        | 76.92%  |
| Btrfs   | 4         | 15.38%  |
| Overlay | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 16        | 59.26%  |
| Unknown | 7         | 25.93%  |
| MBR     | 4         | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 88.46%  |
| Yes       | 3         | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 80.77%  |
| Yes       | 5         | 19.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 34.62%  |
| Hewlett-Packard  | 7         | 26.92%  |
| Acer             | 4         | 15.38%  |
| Dell             | 2         | 7.69%   |
| ASUSTek Computer | 2         | 7.69%   |
| TUXEDO           | 1         | 3.85%   |
| Compal           | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| TUXEDO Book BA1510                       | 1         | 3.85%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 3.85%   |
| Lenovo ThinkPad T580 20LAS1GG00          | 1         | 3.85%   |
| Lenovo ThinkPad T490 20N3SFKX00          | 1         | 3.85%   |
| Lenovo ThinkPad T410 253725G             | 1         | 3.85%   |
| Lenovo ThinkPad T14s Gen 1 20T1S15N00    | 1         | 3.85%   |
| Lenovo ThinkPad L540 20AUS01H00          | 1         | 3.85%   |
| Lenovo ThinkPad Edge E540 20C6003AGE     | 1         | 3.85%   |
| Lenovo ThinkPad E590 20NB001AIX          | 1         | 3.85%   |
| Lenovo IdeaPad 3 15IIL05 81WE            | 1         | 3.85%   |
| HP ZBook 15 G6                           | 1         | 3.85%   |
| HP ProBook 640 G1                        | 1         | 3.85%   |
| HP ProBook 4520s                         | 1         | 3.85%   |
| HP Laptop 17-ca1xxx                      | 1         | 3.85%   |
| HP Laptop 15-db0xxx                      | 1         | 3.85%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 1         | 3.85%   |
| HP 250 G7 Notebook PC                    | 1         | 3.85%   |
| Dell Vostro 15 3510                      | 1         | 3.85%   |
| Dell Latitude 5491                       | 1         | 3.85%   |
| Compal NBLBX                             | 1         | 3.85%   |
| ASUS ZenBook UX325JA_UX325JA             | 1         | 3.85%   |
| ASUS BU201LA                             | 1         | 3.85%   |
| Acer Swift SF314-51                      | 1         | 3.85%   |
| Acer Aspire E5-771G                      | 1         | 3.85%   |
| Acer Aspire E5-551G                      | 1         | 3.85%   |
| Acer Aspire 5750                         | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 8         | 30.77%  |
| Acer Aspire     | 3         | 11.54%  |
| HP ProBook      | 2         | 7.69%   |
| HP Laptop       | 2         | 7.69%   |
| TUXEDO Book     | 1         | 3.85%   |
| Lenovo IdeaPad  | 1         | 3.85%   |
| HP ZBook        | 1         | 3.85%   |
| HP EliteBook    | 1         | 3.85%   |
| HP 250          | 1         | 3.85%   |
| Dell Vostro     | 1         | 3.85%   |
| Dell Latitude   | 1         | 3.85%   |
| Compal NBLBX    | 1         | 3.85%   |
| ASUS ZenBook    | 1         | 3.85%   |
| ASUS BU201LA    | 1         | 3.85%   |
| Acer Swift      | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 15.38%  |
| 2019 | 4         | 15.38%  |
| 2018 | 4         | 15.38%  |
| 2014 | 3         | 11.54%  |
| 2013 | 3         | 11.54%  |
| 2010 | 2         | 7.69%   |
| 2022 | 1         | 3.85%   |
| 2021 | 1         | 3.85%   |
| 2017 | 1         | 3.85%   |
| 2016 | 1         | 3.85%   |
| 2011 | 1         | 3.85%   |
| 2009 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 9         | 33.33%  |
| 8.01-16.0   | 7         | 25.93%  |
| 16.01-24.0  | 6         | 22.22%  |
| 32.01-64.0  | 2         | 7.41%   |
| 3.01-4.0    | 1         | 3.7%    |
| 64.01-256.0 | 1         | 3.7%    |
| Unknown     | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 9         | 29.03%  |
| 2.01-3.0 | 8         | 25.81%  |
| 4.01-8.0 | 6         | 19.35%  |
| 1.01-2.0 | 5         | 16.13%  |
| 0.51-1.0 | 2         | 6.45%   |
| Unknown  | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 73.08%  |
| 2      | 7         | 26.92%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 69.23%  |
| Yes       | 8         | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 84.62%  |
| No        | 4         | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 78.57%  |
| No        | 6         | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 12        | 44.44%  |
| USA         | 3         | 11.11%  |
| Canada      | 3         | 11.11%  |
| UK          | 2         | 7.41%   |
| Austria     | 2         | 7.41%   |
| Switzerland | 1         | 3.7%    |
| Sweden      | 1         | 3.7%    |
| Italy       | 1         | 3.7%    |
| Israel      | 1         | 3.7%    |
| France      | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Munich               | 3         | 8.33%   |
| Stuttgart            | 2         | 5.56%   |
| Zurich               | 1         | 2.78%   |
| Wiener Neustadt      | 1         | 2.78%   |
| Vienna               | 1         | 2.78%   |
| Turin                | 1         | 2.78%   |
| Trier                | 1         | 2.78%   |
| Toronto              | 1         | 2.78%   |
| Suisun               | 1         | 2.78%   |
| Stockholm            | 1         | 2.78%   |
| Sidney               | 1         | 2.78%   |
| Schrobenhausen       | 1         | 2.78%   |
| San Francisco        | 1         | 2.78%   |
| Reading              | 1         | 2.78%   |
| Paris                | 1         | 2.78%   |
| Oberboihingen        | 1         | 2.78%   |
| Mittenwald           | 1         | 2.78%   |
| Milan                | 1         | 2.78%   |
| Mannheim             | 1         | 2.78%   |
| Malmo                | 1         | 2.78%   |
| Langewiesen          | 1         | 2.78%   |
| Landau               | 1         | 2.78%   |
| Jerusalem            | 1         | 2.78%   |
| Iserlohn             | 1         | 2.78%   |
| Hamburg              | 1         | 2.78%   |
| Guglingen            | 1         | 2.78%   |
| Friedrichsthal       | 1         | 2.78%   |
| Freiburg im Breisgau | 1         | 2.78%   |
| Edmonton             | 1         | 2.78%   |
| Düsseldorf          | 1         | 2.78%   |
| Craigsville          | 1         | 2.78%   |
| Blackwood            | 1         | 2.78%   |
| Berlin               | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 28.57%  |
| Toshiba             | 6         | 15     | 17.14%  |
| WDC                 | 4         | 5      | 11.43%  |
| SK hynix            | 3         | 3      | 8.57%   |
| Sandisk             | 3         | 7      | 8.57%   |
| Kingston            | 3         | 3      | 8.57%   |
| Seagate             | 2         | 2      | 5.71%   |
| Intel               | 2         | 4      | 5.71%   |
| SSSTC               | 1         | 1      | 2.86%   |
| Crucial             | 1         | 2      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 5.56%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 5.56%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 2.78%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 2.78%   |
| Toshiba THNSNK256GVN8 256GB SSD           | 1         | 2.78%   |
| Toshiba THNSF5512GPUK 512GB               | 1         | 2.78%   |
| Toshiba MQ01ACF032 320GB                  | 1         | 2.78%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 2.78%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB            | 1         | 2.78%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB | 1         | 2.78%   |
| SK hynix NVMe SSD Drive 512GB             | 1         | 2.78%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 1         | 2.78%   |
| Seagate ST9500420AS 500GB                 | 1         | 2.78%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 2.78%   |
| Sandisk WD Blue SN570 1TB                 | 1         | 2.78%   |
| SanDisk SSD U110 16GB                     | 1         | 2.78%   |
| SanDisk NVMe SSD Drive 1TB                | 1         | 2.78%   |
| Samsung SSD 990 PRO 2TB                   | 1         | 2.78%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 2.78%   |
| Samsung SSD 870 QVO 1TB                   | 1         | 2.78%   |
| Samsung SSD 860 EVO M.2 1TB               | 1         | 2.78%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 2.78%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 2.78%   |
| Samsung SSD 840 Series 250GB              | 1         | 2.78%   |
| Samsung MZVLQ128HBHQ-00000 128GB          | 1         | 2.78%   |
| Samsung MZVLB512HAJQ-000L7 512GB          | 1         | 2.78%   |
| Samsung HM321HI 320GB                     | 1         | 2.78%   |
| Kingston SA400S37240G 240GB SSD           | 1         | 2.78%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 2.78%   |
| Kingston SA2000M8500G 500GB               | 1         | 2.78%   |
| Intel SSDPEKNW010T9 1TB                   | 1         | 2.78%   |
| Intel HBRPEKNX0203AO 32GB                 | 1         | 2.78%   |
| Intel HBRPEKNX0203A 1TB                   | 1         | 2.78%   |
| Crucial CT1000MX500SSD1 1TB               | 1         | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 11     | 37.5%   |
| WDC                 | 2         | 3      | 25%     |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 45.45%  |
| Kingston            | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| Toshiba             | 1         | 1      | 9.09%   |
| SanDisk             | 1         | 1      | 9.09%   |
| Crucial             | 1         | 2      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 23     | 46.88%  |
| SSD  | 9         | 13     | 28.13%  |
| HDD  | 8         | 17     | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 30     | 51.61%  |
| NVMe | 15        | 23     | 48.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 12     | 52.94%  |
| 0.51-1.0   | 7         | 17     | 41.18%  |
| 1.01-2.0   | 1         | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 7         | 24.14%  |
| 101-250    | 5         | 17.24%  |
| 501-1000   | 5         | 17.24%  |
| 1001-2000  | 4         | 13.79%  |
| Unknown    | 4         | 13.79%  |
| 1-20       | 3         | 10.34%  |
| 21-50      | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 40.63%  |
| 101-250   | 4         | 12.5%   |
| 51-100    | 4         | 12.5%   |
| Unknown   | 4         | 12.5%   |
| 251-500   | 2         | 6.25%   |
| 21-50     | 2         | 6.25%   |
| 501-1000  | 2         | 6.25%   |
| 1001-2000 | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 50%     |
| Kingston SA400S37240G 240GB SSD         | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 50%     |
| Kingston | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| SSD  | 1         | 1      | 50%     |

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
| Works    | 21        | 38     | 70%     |
| Detected | 7         | 13     | 23.33%  |
| Malfunc  | 2         | 2      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 18        | 51.43%  |
| AMD                            | 4         | 11.43%  |
| Toshiba America Info Systems   | 3         | 8.57%   |
| SK hynix                       | 3         | 8.57%   |
| Samsung Electronics            | 3         | 8.57%   |
| SanDisk                        | 2         | 5.71%   |
| Solid State Storage Technology | 1         | 2.86%   |
| Kingston Technology Company    | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 10.81%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 8.11%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 5.41%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 5.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 5.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.41%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.7%    |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 2.7%    |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 2.7%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 2.7%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.7%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.7%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.7%    |
| Intel SSD 665p Series [Neptune Harbor Refresh]                                 | 1         | 2.7%    |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 2.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 51.43%  |
| NVMe | 14        | 40%     |
| RAID | 2         | 5.71%   |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 80.77%  |
| AMD    | 5         | 19.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 7.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 7.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 7.69%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.85%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 3.85%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 3.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 3.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.85%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.85%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 3.85%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 3.85%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 3.85%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 3.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.85%   |
| AMD Ryzen 9 PRO 6950HS with Radeon Graphics   | 1         | 3.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.85%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 11        | 42.31%  |
| Intel Core i7 | 7         | 26.92%  |
| AMD Ryzen 5   | 3         | 11.54%  |
| Intel Core i3 | 2         | 7.69%   |
| Other         | 1         | 3.85%   |
| AMD Ryzen 9   | 1         | 3.85%   |
| AMD FX        | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 12        | 46.15%  |
| 2      | 11        | 42.31%  |
| 6      | 2         | 7.69%   |
| 8      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 100%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 96.15%  |
| Unknown        | 1         | 3.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 40%     |
| 0x806ec    | 2         | 6.67%   |
| 0x706e5    | 2         | 6.67%   |
| 0x20655    | 2         | 6.67%   |
| 0x08108102 | 2         | 6.67%   |
| 0x806eb    | 1         | 3.33%   |
| 0x806e9    | 1         | 3.33%   |
| 0x306d4    | 1         | 3.33%   |
| 0x306c3    | 1         | 3.33%   |
| 0x206a7    | 1         | 3.33%   |
| 0x20652    | 1         | 3.33%   |
| 0x0a404102 | 1         | 3.33%   |
| 0x08108109 | 1         | 3.33%   |
| 0x0810100b | 1         | 3.33%   |
| 0x06003106 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 30.77%  |
| Haswell     | 4         | 15.38%  |
| Westmere    | 3         | 11.54%  |
| Zen+        | 2         | 7.69%   |
| IceLake     | 2         | 7.69%   |
| Zen         | 1         | 3.85%   |
| TigerLake   | 1         | 3.85%   |
| Steamroller | 1         | 3.85%   |
| Skylake     | 1         | 3.85%   |
| SandyBridge | 1         | 3.85%   |
| Broadwell   | 1         | 3.85%   |
| Unknown     | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 63.33%  |
| AMD    | 7         | 23.33%  |
| Nvidia | 4         | 13.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 9.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 9.68%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 6.45%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 6.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 6.45%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 3.23%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 3.23%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 3.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 3.23%   |
| Intel UHD Graphics 620                                                      | 1         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 3.23%   |
| Intel HD Graphics 620                                                       | 1         | 3.23%   |
| Intel HD Graphics 5500                                                      | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 3.23%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220] | 1         | 3.23%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1         | 3.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 3.23%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 3.23%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 1         | 3.23%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                          | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 57.69%  |
| 1 x AMD        | 5         | 19.23%  |
| Intel + Nvidia | 3         | 11.54%  |
| 2 x AMD        | 1         | 3.85%   |
| 1 x Nvidia     | 1         | 3.85%   |
| Intel + AMD    | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 24        | 92.31%  |
| Proprietary | 2         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 65.38%  |
| 1.01-2.0   | 3         | 11.54%  |
| 0.01-0.5   | 3         | 11.54%  |
| 0.51-1.0   | 2         | 7.69%   |
| 3.01-4.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Chimei Innolux  | 9         | 30%     |
| LG Display      | 7         | 23.33%  |
| AU Optronics    | 5         | 16.67%  |
| BOE             | 3         | 10%     |
| Lenovo          | 2         | 6.67%   |
| Hewlett-Packard | 1         | 3.33%   |
| Goldstar        | 1         | 3.33%   |
| Dell            | 1         | 3.33%   |
| AOC             | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch      | 1         | 3.33%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch     | 1         | 3.33%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch      | 1         | 3.33%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch      | 1         | 3.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch         | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch          | 1         | 3.33%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch      | 1         | 3.33%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch          | 1         | 3.33%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                 | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch  | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1388 1920x1080 293x165mm 13.2-inch | 1         | 3.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE06DD 1920x1080 344x194mm 15.5-inch            | 1         | 3.33%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch   | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch   | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch    | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch   | 1         | 3.33%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                   | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 19        | 67.86%  |
| 1366x768 (WXGA)   | 5         | 17.86%  |
| 3840x2160 (4K)    | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1600x900 (HD+)    | 1         | 3.57%   |
| 1440x900 (WXGA+)  | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 46.67%  |
| 14     | 6         | 20%     |
| 17     | 2         | 6.67%   |
| 13     | 2         | 6.67%   |
| 40     | 1         | 3.33%   |
| 27     | 1         | 3.33%   |
| 24     | 1         | 3.33%   |
| 23     | 1         | 3.33%   |
| 16     | 1         | 3.33%   |
| 12     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 73.33%  |
| 501-600     | 3         | 10%     |
| 351-400     | 2         | 6.67%   |
| 201-300     | 2         | 6.67%   |
| 801-900     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 88.89%  |
| 16/10 | 3         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 46.67%  |
| 81-90          | 7         | 23.33%  |
| 121-130        | 2         | 6.67%   |
| 71-80          | 1         | 3.33%   |
| 61-70          | 1         | 3.33%   |
| 301-350        | 1         | 3.33%   |
| 251-300        | 1         | 3.33%   |
| 201-250        | 1         | 3.33%   |
| 111-120        | 1         | 3.33%   |
| 501-1000       | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 60%     |
| 101-120 | 6         | 20%     |
| 161-240 | 3         | 10%     |
| 51-100  | 3         | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 84.62%  |
| 2     | 4         | 15.38%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 48.72%  |
| Realtek Semiconductor | 12        | 30.77%  |
| Qualcomm Atheros      | 4         | 10.26%  |
| Broadcom              | 2         | 5.13%   |
| Qualcomm              | 1         | 2.56%   |
| NetGear               | 1         | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 21.15%  |
| Intel Wi-Fi 6 AX200                                                    | 3         | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 3.85%   |
| Intel Wireless 8265 / 8275                                             | 2         | 3.85%   |
| Intel Wireless 7260                                                    | 2         | 3.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 3.85%   |
| Intel Ethernet Connection I217-V                                       | 2         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 1.92%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.92%   |
| Realtek 802.11ax WLAN Adapter                                          | 1         | 1.92%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.92%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1         | 1.92%   |
| Intel Wireless 3160                                                    | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 1.92%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.92%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.92%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.92%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 1         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                         | 1         | 1.92%   |
| Intel Centrino Advanced-N 6200                                         | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1         | 1.92%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 1         | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 64.29%  |
| Qualcomm Atheros      | 4         | 14.29%  |
| Realtek Semiconductor | 3         | 10.71%  |
| Qualcomm              | 1         | 3.57%   |
| NetGear               | 1         | 3.57%   |
| Broadcom              | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3         | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 6.67%   |
| Intel Wireless 8265 / 8275                                     | 2         | 6.67%   |
| Intel Wireless 7260                                            | 2         | 6.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 3.33%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 3.33%   |
| Realtek 802.11ax WLAN Adapter                                  | 1         | 3.33%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 3.33%   |
| Intel Wireless 3160                                            | 1         | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 3.33%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 3.33%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 3.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 54.55%  |
| Intel                 | 9         | 40.91%  |
| Broadcom              | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 11        | 50%     |
| Intel Ethernet Connection I217-V                                       | 2         | 9.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 4.55%   |
| Intel Ethernet Connection I218-V                                       | 1         | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 4.55%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 4.55%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 4.55%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 4.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 54.17%  |
| Ethernet | 22        | 45.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 92.31%  |
| Ethernet | 2         | 7.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 21        | 80.77%  |
| 1     | 5         | 19.23%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 74.07%  |
| Yes  | 7         | 25.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 60%     |
| Realtek Semiconductor           | 3         | 12%     |
| Lite-On Technology              | 2         | 8%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| Foxconn / Hon Hai               | 1         | 4%      |
| Edimax Technology               | 1         | 4%      |
| Cambridge Silicon Radio         | 1         | 4%      |
| Broadcom                        | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 16%     |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 12%     |
| Intel AX200 Bluetooth                               | 3         | 12%     |
| Intel Bluetooth wireless interface                  | 2         | 8%      |
| Intel Bluetooth Device                              | 2         | 8%      |
| Intel AX201 Bluetooth                               | 2         | 8%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4%      |
| Lite-On Bluetooth Device                            | 1         | 4%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4%      |
| Edimax Edimax Bluetooth Adapter                     | 1         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4%      |
| Broadcom HP Portable Bumble Bee                     | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 21        | 67.74%  |
| AMD             | 7         | 22.58%  |
| Nvidia          | 1         | 3.23%   |
| Hewlett-Packard | 1         | 3.23%   |
| Astro Gaming    | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 9.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 7.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 7.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 7.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 7.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 7.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 4.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 4.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.44%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.44%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.44%   |
| Hewlett-Packard USB Audio                                                  | 1         | 2.44%   |
| Astro Gaming Astro A50                                                     | 1         | 2.44%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.44%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 2.44%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 33.33%  |
| SK hynix            | 5         | 16.67%  |
| Micron Technology   | 4         | 13.33%  |
| Kingston            | 4         | 13.33%  |
| Crucial             | 4         | 13.33%  |
| Nanya Technology    | 2         | 6.67%   |
| Elpida              | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 6.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.33%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 3.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 3.33%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 3.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 3.33%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 3.33%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 3.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.33%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 3.33%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 3.33%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 3.33%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 3.33%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 3.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 3.33%   |
| Micron RAM 4ATF25664HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 3.33%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 3.33%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 3.33%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 1         | 3.33%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 3.33%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 3.33%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 3.33%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 3.33%   |
| Crucial RAM CT4G3S1067M.C16FKD 4GB SODIMM DDR3 1066MT/s          | 1         | 3.33%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 1         | 3.33%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 52.17%  |
| DDR3   | 7         | 30.43%  |
| SDRAM  | 1         | 4.35%   |
| LPDDR4 | 1         | 4.35%   |
| LPDDR3 | 1         | 4.35%   |
| DDR5   | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 86.96%  |
| Row Of Chips | 3         | 13.04%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 10        | 38.46%  |
| 8192  | 9         | 34.62%  |
| 16384 | 5         | 19.23%  |
| 32768 | 1         | 3.85%   |
| 2048  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 28%     |
| 3200  | 4         | 16%     |
| 1600  | 4         | 16%     |
| 2400  | 3         | 12%     |
| 4800  | 1         | 4%      |
| 4267  | 1         | 4%      |
| 4199  | 1         | 4%      |
| 1867  | 1         | 4%      |
| 1334  | 1         | 4%      |
| 1067  | 1         | 4%      |
| 1066  | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 3630 series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 43.48%  |
| IMC Networks                           | 3         | 13.04%  |
| Bison Electronics                      | 2         | 8.7%    |
| Suyin                                  | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Realtek Semiconductor                  | 1         | 4.35%   |
| Quanta                                 | 1         | 4.35%   |
| Primax Electronics                     | 1         | 4.35%   |
| Microdia                               | 1         | 4.35%   |
| Lite-On Technology                     | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 16.67%  |
| Chicony Integrated Camera                                      | 2         | 8.33%   |
| Suyin 1.3M HD WebCam                                           | 1         | 4.17%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 4.17%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 4.17%   |
| Quanta HP Webcam                                               | 1         | 4.17%   |
| Primax Villem                                                  | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 4.17%   |
| Lite-On Integrated Camera                                      | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 4.17%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 4.17%   |
| IMC Networks Integrated Camera                                 | 1         | 4.17%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 4.17%   |
| Chicony HP Webcam                                              | 1         | 4.17%   |
| Chicony HP HD Camera                                           | 1         | 4.17%   |
| Chicony HP 5MP Camera                                          | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 4.17%   |
| Bison SunplusIT Integrated Camera                              | 1         | 4.17%   |
| Bison Integrated IR Camera                                     | 1         | 4.17%   |
| Bison Integrated Camera                                        | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 44.44%  |
| Synaptics             | 4         | 44.44%  |
| LighTuning Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                          | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 57.69%  |
| 1     | 9         | 34.62%  |
| 2     | 2         | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 9         | 69.23%  |
| Chipcard           | 2         | 15.38%  |
| Net/wireless       | 1         | 7.69%   |
| Graphics card      | 1         | 7.69%   |

