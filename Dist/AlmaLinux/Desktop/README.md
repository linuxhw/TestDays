AlmaLinux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| HP            | 158B                        | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| HP            | 158B                        | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| Dell          | 0FDY5C A00                  | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| ASRockRack    | X470D4U2-2T                 | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| Dell          | 0FDY5C A00                  | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| MSI           | B85-G43                     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | 158A                        | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| MSI           | A88X-G45 GAMING             | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| Optimized ... | KVM                         | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| Gigabyte      | H81M-D2V                    | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | 1052 NOK                    | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| HP            | 0AE8h C                     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| AlmaLinux 9.1 | 9        | 34.62%  |
| AlmaLinux 8.7 | 5        | 19.23%  |
| AlmaLinux 9.0 | 3        | 11.54%  |
| AlmaLinux 8.8 | 3        | 11.54%  |
| AlmaLinux 9.2 | 2        | 7.69%   |
| AlmaLinux 8.6 | 1        | 3.85%   |
| AlmaLinux 8.5 | 1        | 3.85%   |
| AlmaLinux 8.4 | 1        | 3.85%   |
| AlmaLinux 8.3 | 1        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-425.3.1.el8.x86_64    | 4        | 14.29%  |
| 5.14.0-162.6.1.el9_1.x86_64  | 3        | 10.71%  |
| 5.14.0-162.12.1.el9_1.x86_64 | 3        | 10.71%  |
| 5.14.0-70.30.1.el9_0.x86_64  | 2        | 7.14%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2        | 7.14%   |
| 6.1.24-1kx.el9.x86_64        | 1        | 3.57%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 3.57%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1        | 3.57%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1        | 3.57%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1        | 3.57%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 1        | 3.57%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 1        | 3.57%   |
| 4.18.0-477.10.1.el8_8.x86_64 | 1        | 3.57%   |
| 4.18.0-425.19.2.el8_7.x86_64 | 1        | 3.57%   |
| 4.18.0-425.13.1.el8_7.x86_64 | 1        | 3.57%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 3.57%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1        | 3.57%   |
| 4.18.0-305.el8.x86_64        | 1        | 3.57%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 13       | 52%     |
| 4.18.0  | 11       | 44%     |
| 6.1.24  | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 13       | 52%     |
| 4.18    | 11       | 44%     |
| 6.1     | 1        | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 15       | 62.5%   |
| Unknown | 7        | 29.17%  |
| XFCE    | 1        | 4.17%   |
| KDE5    | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 12       | 48%     |
| Wayland | 9        | 36%     |
| Tty     | 2        | 8%      |
| Unknown | 2        | 8%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 66.67%  |
| GDM     | 8        | 33.33%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 48%     |
| en_CA   | 2        | 8%      |
| de_DE   | 2        | 8%      |
| Unknown | 2        | 8%      |
| uk_UA   | 1        | 4%      |
| ru_UA   | 1        | 4%      |
| ru_RU   | 1        | 4%      |
| hu_HU   | 1        | 4%      |
| fr_FR   | 1        | 4%      |
| en_GB   | 1        | 4%      |
| da_DK   | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 15       | 62.5%   |
| BIOS | 9        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 18       | 75%     |
| Ext4 | 6        | 25%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 13       | 54.17%  |
| Unknown | 8        | 33.33%  |
| MBR     | 3        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 75%     |
| Yes       | 6        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 66.67%  |
| Yes       | 8        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 25%     |
| Hewlett-Packard     | 4        | 16.67%  |
| Gigabyte Technology | 4        | 16.67%  |
| MSI                 | 2        | 8.33%   |
| Lenovo              | 2        | 8.33%   |
| ASRock              | 2        | 8.33%   |
| Supermicro          | 1        | 4.17%   |
| Optimized Hosting   | 1        | 4.17%   |
| Dell                | 1        | 4.17%   |
| ASRockRack          | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Supermicro PIO-617R-TLN4F+-ST031    | 1        | 4.17%   |
| Optimized Hosting KVM               | 1        | 4.17%   |
| MSI MS-7900                         | 1        | 4.17%   |
| MSI MS-7816                         | 1        | 4.17%   |
| Lenovo ThinkStation P350 30E6S20S00 | 1        | 4.17%   |
| Lenovo H520S 10093                  | 1        | 4.17%   |
| HP Z820 Workstation                 | 1        | 4.17%   |
| HP Z620 Workstation                 | 1        | 4.17%   |
| HP Z600 Workstation                 | 1        | 4.17%   |
| HP Z2 Tower G4 Workstation          | 1        | 4.17%   |
| Gigabyte Z690 GAMING X DDR4         | 1        | 4.17%   |
| Gigabyte Z590 AORUS PRO AX          | 1        | 4.17%   |
| Gigabyte X570S UD                   | 1        | 4.17%   |
| Gigabyte H81M-D2V                   | 1        | 4.17%   |
| Dell OptiPlex 5050                  | 1        | 4.17%   |
| ASUS TUF Gaming B450-PLUS II        | 1        | 4.17%   |
| ASUS Q170M2                         | 1        | 4.17%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI     | 1        | 4.17%   |
| ASUS PRIME B550-PLUS                | 1        | 4.17%   |
| ASUS M5A78L-M/USB3                  | 1        | 4.17%   |
| ASUS CROSSHAIR VI HERO              | 1        | 4.17%   |
| ASRockRack X470D4U2-2T              | 1        | 4.17%   |
| ASRock B460 Phantom Gaming 4        | 1        | 4.17%   |
| ASRock B450M Pro4 R2.0              | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 4.17%   |
| Optimized Hosting KVM            | 1        | 4.17%   |
| MSI MS-7900                      | 1        | 4.17%   |
| MSI MS-7816                      | 1        | 4.17%   |
| Lenovo ThinkStation              | 1        | 4.17%   |
| Lenovo H520S                     | 1        | 4.17%   |
| HP Z820                          | 1        | 4.17%   |
| HP Z620                          | 1        | 4.17%   |
| HP Z600                          | 1        | 4.17%   |
| HP Z2                            | 1        | 4.17%   |
| Gigabyte Z690                    | 1        | 4.17%   |
| Gigabyte Z590                    | 1        | 4.17%   |
| Gigabyte X570S                   | 1        | 4.17%   |
| Gigabyte H81M-D2V                | 1        | 4.17%   |
| Dell OptiPlex                    | 1        | 4.17%   |
| ASUS TUF                         | 1        | 4.17%   |
| ASUS Q170M2                      | 1        | 4.17%   |
| ASUS Pro                         | 1        | 4.17%   |
| ASUS PRIME                       | 1        | 4.17%   |
| ASUS M5A78L-M                    | 1        | 4.17%   |
| ASUS CROSSHAIR                   | 1        | 4.17%   |
| ASRockRack X470D4U2-2T           | 1        | 4.17%   |
| ASRock B460                      | 1        | 4.17%   |
| ASRock B450M                     | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 25%     |
| 2012 | 5        | 20.83%  |
| 2021 | 2        | 8.33%   |
| 2015 | 2        | 8.33%   |
| 2013 | 2        | 8.33%   |
| 2022 | 1        | 4.17%   |
| 2019 | 1        | 4.17%   |
| 2018 | 1        | 4.17%   |
| 2017 | 1        | 4.17%   |
| 2014 | 1        | 4.17%   |
| 2011 | 1        | 4.17%   |
| 2009 | 1        | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 24       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 95.83%  |
| Enabled  | 1        | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 7        | 29.17%  |
| 8.01-16.0       | 6        | 25%     |
| 4.01-8.0        | 5        | 20.83%  |
| 32.01-64.0      | 2        | 8.33%   |
| 24.01-32.0      | 2        | 8.33%   |
| More than 256.0 | 1        | 4.17%   |
| 16.01-24.0      | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 6        | 25%     |
| 4.01-8.0   | 4        | 16.67%  |
| 3.01-4.0   | 4        | 16.67%  |
| 1.01-2.0   | 4        | 16.67%  |
| 32.01-64.0 | 2        | 8.33%   |
| 24.01-32.0 | 1        | 4.17%   |
| 16.01-24.0 | 1        | 4.17%   |
| 8.01-16.0  | 1        | 4.17%   |
| 0.51-1.0   | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 4      | 5        | 20.83%  |
| 3      | 5        | 20.83%  |
| 2      | 5        | 20.83%  |
| 1      | 5        | 20.83%  |
| 6      | 2        | 8.33%   |
| 10     | 1        | 4.17%   |
| 5      | 1        | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 62.5%   |
| Yes       | 9        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 95.83%  |
| No        | 1        | 4.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 62.5%   |
| Yes       | 9        | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 70.83%  |
| Yes       | 7        | 29.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 3        | 12.5%   |
| Russia      | 3        | 12.5%   |
| Canada      | 3        | 12.5%   |
| Ukraine     | 2        | 8.33%   |
| Romania     | 2        | 8.33%   |
| Hungary     | 2        | 8.33%   |
| France      | 2        | 8.33%   |
| Switzerland | 1        | 4.17%   |
| Netherlands | 1        | 4.17%   |
| Kazakhstan  | 1        | 4.17%   |
| Greenland   | 1        | 4.17%   |
| Germany     | 1        | 4.17%   |
| China       | 1        | 4.17%   |
| Austria     | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Tunari           | 2        | 8.33%   |
| Zaporizhzhia     | 1        | 4.17%   |
| Vienna           | 1        | 4.17%   |
| Varosfoeld       | 1        | 4.17%   |
| Strasbourg       | 1        | 4.17%   |
| Stadtilm         | 1        | 4.17%   |
| St. Paul         | 1        | 4.17%   |
| Shimanovsk       | 1        | 4.17%   |
| Shanghai         | 1        | 4.17%   |
| Saint-Brieuc     | 1        | 4.17%   |
| Nizhniy Novgorod | 1        | 4.17%   |
| Moscow           | 1        | 4.17%   |
| Kyiv             | 1        | 4.17%   |
| Kitimat          | 1        | 4.17%   |
| Ilulissat        | 1        | 4.17%   |
| Groningen        | 1        | 4.17%   |
| Cincinnati       | 1        | 4.17%   |
| Budapest         | 1        | 4.17%   |
| Bloomington      | 1        | 4.17%   |
| Bellevue         | 1        | 4.17%   |
| Beauharnois      | 1        | 4.17%   |
| Basel            | 1        | 4.17%   |
| Almaty           | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 10       | 16     | 22.22%  |
| WDC                         | 8        | 24     | 17.78%  |
| Samsung Electronics         | 8        | 13     | 17.78%  |
| Kingston                    | 3        | 5      | 6.67%   |
| Toshiba                     | 2        | 3      | 4.44%   |
| Micron Technology           | 2        | 3      | 4.44%   |
| Crucial                     | 2        | 4      | 4.44%   |
| Team                        | 1        | 1      | 2.22%   |
| SK hynix                    | 1        | 1      | 2.22%   |
| Silicon Motion              | 1        | 14     | 2.22%   |
| QEMU                        | 1        | 1      | 2.22%   |
| Netac                       | 1        | 1      | 2.22%   |
| LITEON                      | 1        | 1      | 2.22%   |
| Kingston Technology Company | 1        | 1      | 2.22%   |
| Intel                       | 1        | 1      | 2.22%   |
| Hewlett-Packard             | 1        | 1      | 2.22%   |
| AMD                         | 1        | 5      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 2.9%    |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1        | 1.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 1.45%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1        | 1.45%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 1.45%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 1.45%   |
| WDC WD4000FYYZ-01UL1B2 4TB                          | 1        | 1.45%   |
| WDC WD4000FYYZ-01UL1B1 4TB                          | 1        | 1.45%   |
| WDC WD4000FDYZ-27YA5B0 4TB                          | 1        | 1.45%   |
| WDC WD4000F9YZ-09N20L1 4TB                          | 1        | 1.45%   |
| WDC WD3600FYYZ-01UL1B3 4TB                          | 1        | 1.45%   |
| WDC WD3600FYYZ-01UL1B1 4TB                          | 1        | 1.45%   |
| WDC WD35EFRX-68WT0N0 4TB                            | 1        | 1.45%   |
| WDC WD20EARS-00J2GB0 2TB                            | 1        | 1.45%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1        | 1.45%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1        | 1.45%   |
| WDC RAT035VWHG-GTK4D7 4TB                           | 1        | 1.45%   |
| WDC RAT035VQHR-GTK4D7 4TB                           | 1        | 1.45%   |
| Toshiba MG06ACA800E 8TB                             | 1        | 1.45%   |
| Toshiba DT01ACA100 1TB                              | 1        | 1.45%   |
| Team T253X1480G 480GB SSD                           | 1        | 1.45%   |
| SK hynix SH920 2.5 7MM 256GB SSD                    | 1        | 1.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 500GB | 1        | 1.45%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB         | 1        | 1.45%   |
| Seagate ST4000NC001-1FS168 4TB                      | 1        | 1.45%   |
| Seagate ST4000DM005-2DP166 4TB                      | 1        | 1.45%   |
| Seagate ST4000DM000-1F2168 4TB                      | 1        | 1.45%   |
| Seagate ST31000528AS 1TB                            | 1        | 1.45%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1        | 1.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 1        | 1.45%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1.45%   |
| Seagate ST1000NM0033-9ZM173 1TB                     | 1        | 1.45%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1.45%   |
| Seagate ST1000DM003-9YN162 1TB                      | 1        | 1.45%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1        | 1.45%   |
| Seagate ST10000NM0478-2H7100 10TB                   | 1        | 1.45%   |
| Seagate OneTouch HDD 4TB                            | 1        | 1.45%   |
| Seagate Expansion 1TB                               | 1        | 1.45%   |
| Samsung SSD 980 1TB                                 | 1        | 1.45%   |
| Samsung SSD 870 EVO 1TB                             | 1        | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 47.62%  |
| WDC                 | 7        | 21     | 33.33%  |
| Toshiba             | 2        | 3      | 9.52%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| QEMU                | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 25%     |
| Micron Technology   | 2        | 3      | 12.5%   |
| Kingston            | 2        | 2      | 12.5%   |
| WDC                 | 1        | 3      | 6.25%   |
| Team                | 1        | 1      | 6.25%   |
| SK hynix            | 1        | 1      | 6.25%   |
| Netac               | 1        | 1      | 6.25%   |
| LITEON              | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 1      | 6.25%   |
| Crucial             | 1        | 2      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 42     | 39.53%  |
| SSD  | 15       | 20     | 34.88%  |
| NVMe | 11       | 33     | 25.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 59     | 61.11%  |
| NVMe | 11       | 33     | 30.56%  |
| SAS  | 3        | 3      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 15       | 22     | 39.47%  |
| 0.01-0.5   | 10       | 11     | 26.32%  |
| 3.01-4.0   | 7        | 21     | 18.42%  |
| 1.01-2.0   | 3        | 4      | 7.89%   |
| 4.01-10.0  | 2        | 3      | 5.26%   |
| 2.01-3.0   | 1        | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 7        | 29.17%  |
| 101-250        | 4        | 16.67%  |
| More than 3000 | 3        | 12.5%   |
| Unknown        | 3        | 12.5%   |
| 251-500        | 2        | 8.33%   |
| 2001-3000      | 2        | 8.33%   |
| 1001-2000      | 2        | 8.33%   |
| 1-20           | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 7        | 29.17%  |
| 101-250        | 5        | 20.83%  |
| Unknown        | 3        | 12.5%   |
| 251-500        | 2        | 8.33%   |
| 21-50          | 2        | 8.33%   |
| More than 3000 | 1        | 4.17%   |
| 2001-3000      | 1        | 4.17%   |
| 1001-2000      | 1        | 4.17%   |
| 501-1000       | 1        | 4.17%   |
| 51-100         | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB        | 1        | 1      | 20%     |
| WDC WD20EARS-00J2GB0 2TB          | 1        | 1      | 20%     |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1        | 1      | 20%     |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2      | 20%     |
| Samsung Electronics HD642JJ 640GB | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 40%     |
| SK hynix            | 1        | 1      | 20%     |
| Seagate             | 1        | 2      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 50%     |
| Seagate             | 1        | 2      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Works    | 14       | 54     | 43.75%  |
| Detected | 13       | 35     | 40.63%  |
| Malfunc  | 5        | 6      | 15.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 15       | 38.46%  |
| AMD                         | 9        | 23.08%  |
| Samsung Electronics         | 4        | 10.26%  |
| Kingston Technology Company | 3        | 7.69%   |
| LSI Logic / Symbios Logic   | 2        | 5.13%   |
| ASMedia Technology          | 2        | 5.13%   |
| Silicon Motion              | 1        | 2.56%   |
| Red Hat                     | 1        | 2.56%   |
| Micron/Crucial Technology   | 1        | 2.56%   |
| Broadcom / LSI              | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 10%     |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 6%      |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 6%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 4%      |
| Intel SATA Controller [RAID mode]                                                       | 2        | 4%      |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 4%      |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 4%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 2%      |
| Samsung NVMe SSD Controller 980                                                         | 1        | 2%      |
| Red Hat Virtio 1.0 SCSI                                                                 | 1        | 2%      |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 2%      |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 2%      |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 2%      |
| Kingston Company NV1 NVMe SSD                                                           | 1        | 2%      |
| Kingston Company KC3000/Renegade NVMe SSD                                               | 1        | 2%      |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2%      |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2%      |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 2%      |
| ASMedia ASM1166 Serial ATA Controller                                                   | 1        | 2%      |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2%      |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2%      |
| AMD FCH SATA Controller [RAID Bottom]                                                   | 1        | 2%      |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 44.19%  |
| NVMe | 10       | 23.26%  |
| RAID | 5        | 11.63%  |
| SAS  | 4        | 9.3%    |
| IDE  | 4        | 9.3%    |
| SCSI | 1        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 58.33%  |
| AMD    | 10       | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon W-1350 @ 3.30GHz                     | 1        | 4.17%   |
| Intel Xeon E-2144G CPU @ 3.60GHz                | 1        | 4.17%   |
| Intel Xeon CPU X5550 @ 2.67GHz                  | 1        | 4.17%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 4.17%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz             | 1        | 4.17%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz             | 1        | 4.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 4.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 4.17%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1        | 4.17%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 4.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 4.17%   |
| Intel Core i3-2130 CPU @ 3.40GHz                | 1        | 4.17%   |
| Intel 12th Gen Core i7-12700KF                  | 1        | 4.17%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 4.17%   |
| AMD Ryzen Threadripper PRO 3975WX 32-Cores      | 1        | 4.17%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 4.17%   |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 1        | 4.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 4.17%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 4.17%   |
| AMD Ryzen 5 3500X 6-Core Processor              | 1        | 4.17%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 4.17%   |
| AMD EPYC-Rome Processor                         | 1        | 4.17%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Xeon             | 6        | 25%     |
| Intel Core i5          | 3        | 12.5%   |
| AMD Ryzen 5            | 3        | 12.5%   |
| Other                  | 2        | 8.33%   |
| Intel Core i3          | 2        | 8.33%   |
| AMD Ryzen 9            | 2        | 8.33%   |
| Intel Core i7          | 1        | 4.17%   |
| AMD Ryzen Threadripper | 1        | 4.17%   |
| AMD Ryzen 7            | 1        | 4.17%   |
| AMD FX                 | 1        | 4.17%   |
| AMD EPYC               | 1        | 4.17%   |
| AMD A10                | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 29.17%  |
| 6      | 6        | 25%     |
| 16     | 3        | 12.5%   |
| 12     | 3        | 12.5%   |
| 2      | 3        | 12.5%   |
| 32     | 1        | 4.17%   |
| 8      | 1        | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 83.33%  |
| 2      | 3        | 12.5%   |
| 4      | 1        | 4.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 83.33%  |
| 1      | 4        | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 24       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 3        | 12%     |
| Unknown    | 3        | 12%     |
| 0xa0671    | 2        | 8%      |
| 0x306e4    | 2        | 8%      |
| 0x306c3    | 2        | 8%      |
| 0xa0655    | 1        | 4%      |
| 0x906ea    | 1        | 4%      |
| 0x906e9    | 1        | 4%      |
| 0x90672    | 1        | 4%      |
| 0x506e3    | 1        | 4%      |
| 0x206d7    | 1        | 4%      |
| 0x206a7    | 1        | 4%      |
| 0x106a5    | 1        | 4%      |
| 0x0a50000d | 1        | 4%      |
| 0x0a20120a | 1        | 4%      |
| 0x0830107a | 1        | 4%      |
| 0x06003106 | 1        | 4%      |
| 0x06000852 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 6        | 25%     |
| Zen 3            | 2        | 8.33%   |
| SandyBridge      | 2        | 8.33%   |
| KabyLake         | 2        | 8.33%   |
| IvyBridge        | 2        | 8.33%   |
| Icelake          | 2        | 8.33%   |
| Haswell          | 2        | 8.33%   |
| Steamroller      | 1        | 4.17%   |
| Skylake          | 1        | 4.17%   |
| Piledriver       | 1        | 4.17%   |
| Nehalem          | 1        | 4.17%   |
| CometLake        | 1        | 4.17%   |
| Alderlake Hybrid | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 10       | 41.67%  |
| AMD                        | 6        | 25%     |
| Intel                      | 5        | 20.83%  |
| Red Hat                    | 1        | 4.17%   |
| Matrox Electronics Systems | 1        | 4.17%   |
| ASPEED Technology          | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GA106 [Geforce RTX 3050]                                           | 2        | 8.33%   |
| Red Hat QXL paravirtual graphic card                                      | 1        | 4.17%   |
| Nvidia GP107GL [Quadro P620]                                              | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 4.17%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1        | 4.17%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 4.17%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1        | 4.17%   |
| Nvidia GK104 [GeForce GTX 770]                                            | 1        | 4.17%   |
| Nvidia GF119 [GeForce GT 610]                                             | 1        | 4.17%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1        | 4.17%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1        | 4.17%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1        | 4.17%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 4.17%   |
| Intel HD Graphics 530                                                     | 1        | 4.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 4.17%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 4.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 4.17%   |
| AMD RS780L [Radeon 3000]                                                  | 1        | 4.17%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 4.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 10       | 41.67%  |
| 1 x AMD     | 6        | 25%     |
| 1 x Intel   | 5        | 20.83%  |
| 1 x Red Hat | 1        | 4.17%   |
| 1 x Matrox  | 1        | 4.17%   |
| 1 x ASPEED  | 1        | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 54.17%  |
| Unknown     | 6        | 25%     |
| Proprietary | 5        | 20.83%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 45.83%  |
| 7.01-8.0   | 4        | 16.67%  |
| 3.01-4.0   | 2        | 8.33%   |
| 1.01-2.0   | 2        | 8.33%   |
| 0.51-1.0   | 2        | 8.33%   |
| 0.01-0.5   | 2        | 8.33%   |
| 16.01-24.0 | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 14.29%  |
| Eizo                | 3        | 14.29%  |
| ViewSonic           | 2        | 9.52%   |
| Goldstar            | 2        | 9.52%   |
| Dell                | 2        | 9.52%   |
| BenQ                | 2        | 9.52%   |
| TopView             | 1        | 4.76%   |
| STD                 | 1        | 4.76%   |
| Philips             | 1        | 4.76%   |
| Medion              | 1        | 4.76%   |
| Lenovo              | 1        | 4.76%   |
| AOC                 | 1        | 4.76%   |
| Acer                | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch           | 1        | 4.55%   |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch        | 1        | 4.55%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                  | 1        | 4.55%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                    | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 4.55%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 4.55%   |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                    | 1        | 4.55%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch   | 1        | 4.55%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                    | 1        | 4.55%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                | 1        | 4.55%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 4.55%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 4.55%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                | 1        | 4.55%   |
| Eizo LCD Monitor CG247 5760x2160                                     | 1        | 4.55%   |
| Eizo LCD Monitor CG247 1920x1200                                     | 1        | 4.55%   |
| Eizo EV2336W ENC2390 1920x1080 510x287mm 23.0-inch                   | 1        | 4.55%   |
| Dell LCD Monitor U2515H 2560x1440                                    | 1        | 4.55%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 4.55%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 4.55%   |
| BenQ G700 BNQ7802 1280x1024 338x270mm 17.0-inch                      | 1        | 4.55%   |
| AOC 2330V AOC2330 1920x1080 476x268mm 21.5-inch                      | 1        | 4.55%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                   | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 47.62%  |
| 1280x1024 (SXGA)   | 4        | 19.05%  |
| 2560x1440 (QHD)    | 2        | 9.52%   |
| 5760x2160          | 1        | 4.76%   |
| 2560x1080          | 1        | 4.76%   |
| 1920x1200 (WUXGA)  | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |
| 1400x1050          | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 4        | 19.05%  |
| Unknown | 3        | 14.29%  |
| 31      | 2        | 9.52%   |
| 27      | 2        | 9.52%   |
| 24      | 2        | 9.52%   |
| 19      | 2        | 9.52%   |
| 34      | 1        | 4.76%   |
| 23      | 1        | 4.76%   |
| 22      | 1        | 4.76%   |
| 20      | 1        | 4.76%   |
| 18      | 1        | 4.76%   |
| 17      | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 6        | 28.57%  |
| 501-600     | 5        | 23.81%  |
| 351-400     | 3        | 14.29%  |
| Unknown     | 3        | 14.29%  |
| 601-700     | 2        | 9.52%   |
| 701-800     | 1        | 4.76%   |
| 301-350     | 1        | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 52.38%  |
| 5/4     | 3        | 14.29%  |
| Unknown | 3        | 14.29%  |
| 6/5     | 1        | 4.76%   |
| 4/3     | 1        | 4.76%   |
| 21/9    | 1        | 4.76%   |
| 16/10   | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 28.57%  |
| 151-200        | 6        | 28.57%  |
| 351-500        | 3        | 14.29%  |
| Unknown        | 3        | 14.29%  |
| 301-350        | 2        | 9.52%   |
| 141-150        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 57.89%  |
| 101-120 | 4        | 21.05%  |
| Unknown | 3        | 15.79%  |
| 121-160 | 1        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 54.17%  |
| 2     | 6        | 25%     |
| 0     | 5        | 20.83%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 40.63%  |
| Realtek Semiconductor | 10       | 31.25%  |
| TP-Link               | 2        | 6.25%   |
| Qualcomm Atheros      | 2        | 6.25%   |
| Ralink Technology     | 1        | 3.13%   |
| Ralink                | 1        | 3.13%   |
| Emulex                | 1        | 3.13%   |
| Broadcom Limited      | 1        | 3.13%   |
| Broadcom              | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 18.6%   |
| Intel Ethernet Controller X550                                    | 3        | 6.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 4.65%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 4.65%   |
| Intel I350 Gigabit Network Connection                             | 2        | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.65%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 4.65%   |
| TP-Link Archer T4U ver.3                                          | 1        | 2.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.33%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.33%   |
| Intel Wireless 8260                                               | 1        | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.33%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.33%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.33%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 2.33%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.33%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1        | 2.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.33%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 33.33%  |
| TP-Link               | 2        | 22.22%  |
| Realtek Semiconductor | 1        | 11.11%  |
| Ralink Technology     | 1        | 11.11%  |
| Ralink                | 1        | 11.11%  |
| Qualcomm Atheros      | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                 | 2        | 22.22%  |
| TP-Link Archer T4U ver.3                            | 1        | 11.11%  |
| TP-Link Archer T3U [Realtek RTL8812BU]              | 1        | 11.11%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                     | 1        | 11.11%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe           | 1        | 11.11%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter    | 1        | 11.11%  |
| Intel Wireless 8260                                 | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 48.15%  |
| Realtek Semiconductor | 10       | 37.04%  |
| Qualcomm Atheros      | 1        | 3.7%    |
| Emulex                | 1        | 3.7%    |
| Broadcom Limited      | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 23.53%  |
| Intel Ethernet Controller X550                                    | 3        | 8.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 5.88%   |
| Intel I350 Gigabit Network Connection                             | 2        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.88%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.94%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.94%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.94%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.94%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 2.94%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.94%   |
| Emulex OneConnect 10Gb NIC (be3)                                  | 1        | 2.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.94%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 71.88%  |
| WiFi     | 9        | 28.13%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 81.82%  |
| WiFi     | 4        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 37.5%   |
| 1     | 7        | 29.17%  |
| 4     | 3        | 12.5%   |
| 3     | 3        | 12.5%   |
| 5     | 1        | 4.17%   |
| 0     | 1        | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 83.33%  |
| Yes  | 4        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 42.86%  |
| Broadcom                | 2        | 28.57%  |
| Cambridge Silicon Radio | 1        | 14.29%  |
| ASUSTek Computer        | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 28.57%  |
| Intel Bluetooth wireless interface                  | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 14.29%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 14.29%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 12       | 32.43%  |
| AMD                  | 11       | 29.73%  |
| Nvidia               | 10       | 27.03%  |
| Giga-Byte Technology | 1        | 2.7%    |
| Conexant Systems     | 1        | 2.7%    |
| ASUSTek Computer     | 1        | 2.7%    |
| Apple                | 1        | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 14.29%  |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 4.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 4.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 2.38%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.38%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2.38%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.38%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.38%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.38%   |
| Giga-Byte Technology USB Audio                                             | 1        | 2.38%   |
| Conexant Systems G941                                                      | 1        | 2.38%   |
| ASUSTek Computer USB Audio                                                 | 1        | 2.38%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1        | 2.38%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.38%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.38%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 2.38%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 23.53%  |
| Samsung Electronics | 3        | 17.65%  |
| Micron Technology   | 2        | 11.76%  |
| G.Skill             | 2        | 11.76%  |
| Crucial             | 2        | 11.76%  |
| Unknown             | 1        | 5.88%   |
| SK hynix            | 1        | 5.88%   |
| QEMU                | 1        | 5.88%   |
| Corsair             | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 11.76%  |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 5.88%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 5.88%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 5.88%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 1        | 5.88%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s   | 1        | 5.88%   |
| QEMU RAM Module 8GB DIMM RAM                           | 1        | 5.88%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s    | 1        | 5.88%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s   | 1        | 5.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 5.88%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s | 1        | 5.88%   |
| G.Skill RAM F4-4000C15-8GVK 8GB DIMM DDR4 2133MT/s     | 1        | 5.88%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s   | 1        | 5.88%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8GB DIMM DDR4 3200MT/s   | 1        | 5.88%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 1        | 5.88%   |
| Corsair RAM CMK64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 62.5%   |
| DDR3    | 4        | 25%     |
| RAM     | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 16       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 41.18%  |
| 16384 | 6        | 35.29%  |
| 4096  | 2        | 11.76%  |
| 32768 | 1        | 5.88%   |
| 2048  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 5        | 29.41%  |
| 1600    | 3        | 17.65%  |
| 3600    | 1        | 5.88%   |
| 3466    | 1        | 5.88%   |
| 3066    | 1        | 5.88%   |
| 2667    | 1        | 5.88%   |
| 2400    | 1        | 5.88%   |
| 2133    | 1        | 5.88%   |
| 1867    | 1        | 5.88%   |
| 1333    | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Microsoft           | 1        | 25%     |
| Microdia            | 1        | 25%     |
| Logitech            | 1        | 25%     |
| Creative Technology | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000           | 1        | 25%     |
| Microdia USB 2.0 Camera             | 1        | 25%     |
| Logitech Webcam B500                | 1        | 25%     |
| Creative Live! Cam Chat HD [VF0700] | 1        | 25%     |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| OmniKey | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121 | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 16       | 66.67%  |
| 1     | 5        | 20.83%  |
| 5     | 1        | 4.17%   |
| 3     | 1        | 4.17%   |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 33.33%  |
| Net/wireless             | 2        | 16.67%  |
| Net/ethernet             | 2        | 16.67%  |
| Storage/raid             | 1        | 8.33%   |
| Storage/ide              | 1        | 8.33%   |
| Sound                    | 1        | 8.33%   |
| Communication controller | 1        | 8.33%   |

