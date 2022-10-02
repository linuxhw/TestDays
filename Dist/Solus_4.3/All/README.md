Solus 4.3 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus_4.3/Desktop/README.md) and [notebooks](/Dist/Solus_4.3/Notebook/README.md).

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

Total: 87

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L855              | Notebook    | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| Unknown       | TB-4000                     | Desktop     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Unknown       | TB-4000                     | Desktop     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Dell          | Latitude E5470              | Notebook    | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| AZW           | SEi                         | Notebook    | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| Lenovo        | CRESCENTBAY 31900058 STD    | Desktop     | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | Notebook    | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown       | HX90                        | Desktop     | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown       | HX90                        | Desktop     | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown       | HX90                        | Desktop     | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | Notebook    | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| Sony          | VPCYB15AB                   | Notebook    | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Dell          | Latitude 5580               | Notebook    | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| Framework     | Laptop                      | Notebook    | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| Dell          | Latitude E6220              | Notebook    | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| Framework     | Laptop                      | Notebook    | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| HP            | 805F                        | Desktop     | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda    | Alpha                       | Desktop     | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| AZW           | SEi                         | Notebook    | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| eMachines     | EL1852G                     | Desktop     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines     | EL1852G                     | Desktop     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [14f7d2a3c6](https://linux-hardware.org/?probe=14f7d2a3c6) | Aug 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [488ebb20fc](https://linux-hardware.org/?probe=488ebb20fc) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.15.32-213.current | 8         | 13.56%  |
| 5.14.21-210.current | 7         | 11.86%  |
| 5.15.50-216.current | 6         | 10.17%  |
| 5.14.16-205.current | 6         | 10.17%  |
| 5.13.1-187.current  | 6         | 10.17%  |
| 5.13.6-190.current  | 5         | 8.47%   |
| 5.13.12-193.current | 5         | 8.47%   |
| 5.15.43-215.current | 2         | 3.39%   |
| 5.15.30-212.current | 2         | 3.39%   |
| 5.15.26-211.current | 2         | 3.39%   |
| 5.14.14-202.current | 2         | 3.39%   |
| 5.15.61-217.current | 1         | 1.69%   |
| 5.15.37-214.current | 1         | 1.69%   |
| 5.14.7-198.current  | 1         | 1.69%   |
| 5.14.16-204.current | 1         | 1.69%   |
| 5.14.15-203.current | 1         | 1.69%   |
| 5.14.12-201.current | 1         | 1.69%   |
| 5.13.8-191.current  | 1         | 1.69%   |
| 5.13.15-194.current | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.32 | 8         | 13.56%  |
| 5.14.21 | 7         | 11.86%  |
| 5.14.16 | 7         | 11.86%  |
| 5.15.50 | 6         | 10.17%  |
| 5.13.1  | 6         | 10.17%  |
| 5.13.6  | 5         | 8.47%   |
| 5.13.12 | 5         | 8.47%   |
| 5.15.43 | 2         | 3.39%   |
| 5.15.30 | 2         | 3.39%   |
| 5.15.26 | 2         | 3.39%   |
| 5.14.14 | 2         | 3.39%   |
| 5.15.61 | 1         | 1.69%   |
| 5.15.37 | 1         | 1.69%   |
| 5.14.7  | 1         | 1.69%   |
| 5.14.15 | 1         | 1.69%   |
| 5.14.12 | 1         | 1.69%   |
| 5.13.8  | 1         | 1.69%   |
| 5.13.15 | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 36.21%  |
| 5.14    | 19        | 32.76%  |
| 5.13    | 18        | 31.03%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 34        | 61.82%  |
| KDE5    | 5         | 9.09%   |
| GNOME   | 5         | 9.09%   |
| Unknown | 5         | 9.09%   |
| MATE    | 3         | 5.45%   |
| KDE     | 3         | 5.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 54        | 98.18%  |
| Wayland | 1         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 72.73%  |
| LightDM | 10        | 18.18%  |
| SDDM    | 4         | 7.27%   |
| GDM     | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 33        | 58.93%  |
| en_GB | 5         | 8.93%   |
| de_DE | 4         | 7.14%   |
| fr_FR | 3         | 5.36%   |
| ru_RU | 2         | 3.57%   |
| pt_BR | 2         | 3.57%   |
| nl_NL | 1         | 1.79%   |
| es_VE | 1         | 1.79%   |
| es_ES | 1         | 1.79%   |
| en_IN | 1         | 1.79%   |
| en_DK | 1         | 1.79%   |
| ar_SA | 1         | 1.79%   |
| ar_EG | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 32        | 56.14%  |
| BIOS | 25        | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 52        | 94.55%  |
| Xfs     | 1         | 1.82%   |
| Overlay | 1         | 1.82%   |
| Btrfs   | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 41        | 74.55%  |
| GPT     | 9         | 16.36%  |
| MBR     | 5         | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 92.86%  |
| Yes       | 4         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 81.82%  |
| Yes       | 10        | 18.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 16.36%  |
| Gigabyte Technology | 8         | 14.55%  |
| Lenovo              | 6         | 10.91%  |
| ASUSTek Computer    | 6         | 10.91%  |
| MSI                 | 3         | 5.45%   |
| Hewlett-Packard     | 3         | 5.45%   |
| Acer                | 3         | 5.45%   |
| Toshiba             | 2         | 3.64%   |
| Google              | 2         | 3.64%   |
| ASRock              | 2         | 3.64%   |
| Unknown             | 2         | 3.64%   |
| Sony                | 1         | 1.82%   |
| MEGA                | 1         | 1.82%   |
| GPU Company         | 1         | 1.82%   |
| Fujitsu             | 1         | 1.82%   |
| Framework           | 1         | 1.82%   |
| eMachines           | 1         | 1.82%   |
| Biostar             | 1         | 1.82%   |
| AZW                 | 1         | 1.82%   |
| Apple               | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 2         | 3.64%   |
| Toshiba TECRA R840                    | 1         | 1.82%   |
| Toshiba Satellite L855                | 1         | 1.82%   |
| Sony VPCYB15AB                        | 1         | 1.82%   |
| MSI MS-7B89                           | 1         | 1.82%   |
| MSI MS-7B85                           | 1         | 1.82%   |
| MSI MS-7A34                           | 1         | 1.82%   |
| MEGA G41T-M7 LGT                      | 1         | 1.82%   |
| Lenovo Z50-70 20354                   | 1         | 1.82%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 1.82%   |
| Lenovo ThinkCentre M71e 3157G6S       | 1         | 1.82%   |
| Lenovo IdeaPad S340-15API 81NC        | 1         | 1.82%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 1         | 1.82%   |
| Lenovo C50-30 F0B1002EFR              | 1         | 1.82%   |
| HP ProDesk 490 G3 MT Business PC      | 1         | 1.82%   |
| HP ProBook 450 G5                     | 1         | 1.82%   |
| HP OMEN Laptop 15-en0xxx              | 1         | 1.82%   |
| GPU Company GWTC116-2                 | 1         | 1.82%   |
| Google Edgar                          | 1         | 1.82%   |
| Google Delbin                         | 1         | 1.82%   |
| Gigabyte Z68AP-D3                     | 1         | 1.82%   |
| Gigabyte P31-ES3G                     | 1         | 1.82%   |
| Gigabyte H81M-S2V                     | 1         | 1.82%   |
| Gigabyte H110M-DS2V                   | 1         | 1.82%   |
| Gigabyte GA-MA770-UD3                 | 1         | 1.82%   |
| Gigabyte GA-78LMT-USB3 6.0            | 1         | 1.82%   |
| Gigabyte F2A68HM-H                    | 1         | 1.82%   |
| Gigabyte B85M-D3H                     | 1         | 1.82%   |
| Fujitsu CELSIUS W530                  | 1         | 1.82%   |
| Framework Laptop                      | 1         | 1.82%   |
| eMachines EL1852G                     | 1         | 1.82%   |
| Dell XPS 13 9380                      | 1         | 1.82%   |
| Dell XPS 13 7390                      | 1         | 1.82%   |
| Dell Vostro 15-3568                   | 1         | 1.82%   |
| Dell OptiPlex 9020                    | 1         | 1.82%   |
| Dell Latitude E6220                   | 1         | 1.82%   |
| Dell Latitude E5470                   | 1         | 1.82%   |
| Dell Latitude 5580                    | 1         | 1.82%   |
| Dell Inspiron 1525                    | 1         | 1.82%   |
| Dell Inspiron 15-3573                 | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 3         | 5.45%   |
| Lenovo IdeaPad         | 2         | 3.64%   |
| Dell XPS               | 2         | 3.64%   |
| Dell Inspiron          | 2         | 3.64%   |
| ASUS TUF               | 2         | 3.64%   |
| Unknown                | 2         | 3.64%   |
| Toshiba TECRA          | 1         | 1.82%   |
| Toshiba Satellite      | 1         | 1.82%   |
| Sony VPCYB15AB         | 1         | 1.82%   |
| MSI MS-7B89            | 1         | 1.82%   |
| MSI MS-7B85            | 1         | 1.82%   |
| MSI MS-7A34            | 1         | 1.82%   |
| MEGA G41T-M7           | 1         | 1.82%   |
| Lenovo Z50-70          | 1         | 1.82%   |
| Lenovo ThinkPad        | 1         | 1.82%   |
| Lenovo ThinkCentre     | 1         | 1.82%   |
| Lenovo C50-30          | 1         | 1.82%   |
| HP ProDesk             | 1         | 1.82%   |
| HP ProBook             | 1         | 1.82%   |
| HP OMEN                | 1         | 1.82%   |
| GPU Company GWTC116-2  | 1         | 1.82%   |
| Google Edgar           | 1         | 1.82%   |
| Google Delbin          | 1         | 1.82%   |
| Gigabyte Z68AP-D3      | 1         | 1.82%   |
| Gigabyte P31-ES3G      | 1         | 1.82%   |
| Gigabyte H81M-S2V      | 1         | 1.82%   |
| Gigabyte H110M-DS2V    | 1         | 1.82%   |
| Gigabyte GA-MA770-UD3  | 1         | 1.82%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.82%   |
| Gigabyte F2A68HM-H     | 1         | 1.82%   |
| Gigabyte B85M-D3H      | 1         | 1.82%   |
| Fujitsu CELSIUS        | 1         | 1.82%   |
| Framework Laptop       | 1         | 1.82%   |
| eMachines EL1852G      | 1         | 1.82%   |
| Dell Vostro            | 1         | 1.82%   |
| Dell OptiPlex          | 1         | 1.82%   |
| Biostar H61MLV2        | 1         | 1.82%   |
| AZW SEi                | 1         | 1.82%   |
| ASUS VivoBook          | 1         | 1.82%   |
| ASUS ROG               | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 7         | 12.73%  |
| 2018 | 7         | 12.73%  |
| 2019 | 6         | 10.91%  |
| 2014 | 6         | 10.91%  |
| 2011 | 6         | 10.91%  |
| 2020 | 4         | 7.27%   |
| 2017 | 4         | 7.27%   |
| 2016 | 4         | 7.27%   |
| 2015 | 3         | 5.45%   |
| 2008 | 3         | 5.45%   |
| 2013 | 2         | 3.64%   |
| 2012 | 2         | 3.64%   |
| 2010 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 28        | 50.91%  |
| Notebook   | 26        | 47.27%  |
| All in one | 1         | 1.82%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 96.36%  |
| Yes  | 2         | 3.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 11        | 20%     |
| 16.01-24.0 | 11        | 20%     |
| 4.01-8.0   | 10        | 18.18%  |
| 8.01-16.0  | 10        | 18.18%  |
| 32.01-64.0 | 8         | 14.55%  |
| 2.01-3.0   | 2         | 3.64%   |
| 1.01-2.0   | 2         | 3.64%   |
| 24.01-32.0 | 1         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 20        | 33.9%   |
| 2.01-3.0  | 18        | 30.51%  |
| 4.01-8.0  | 9         | 15.25%  |
| 3.01-4.0  | 8         | 13.56%  |
| 8.01-16.0 | 2         | 3.39%   |
| 0.51-1.0  | 2         | 3.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 52.63%  |
| 2      | 14        | 24.56%  |
| 4      | 7         | 12.28%  |
| 3      | 4         | 7.02%   |
| 5      | 2         | 3.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 65.45%  |
| Yes       | 19        | 34.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 83.64%  |
| No        | 9         | 16.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 70.91%  |
| No        | 16        | 29.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 63.64%  |
| No        | 20        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 12        | 21.82%  |
| Germany      | 5         | 9.09%   |
| India        | 4         | 7.27%   |
| Netherlands  | 3         | 5.45%   |
| Brazil       | 3         | 5.45%   |
| UK           | 2         | 3.64%   |
| Norway       | 2         | 3.64%   |
| France       | 2         | 3.64%   |
| Vietnam      | 1         | 1.82%   |
| Venezuela    | 1         | 1.82%   |
| Ukraine      | 1         | 1.82%   |
| Thailand     | 1         | 1.82%   |
| Switzerland  | 1         | 1.82%   |
| Sweden       | 1         | 1.82%   |
| Spain        | 1         | 1.82%   |
| Saudi Arabia | 1         | 1.82%   |
| Russia       | 1         | 1.82%   |
| Poland       | 1         | 1.82%   |
| Philippines  | 1         | 1.82%   |
| Nepal        | 1         | 1.82%   |
| Mexico       | 1         | 1.82%   |
| Kazakhstan   | 1         | 1.82%   |
| Iran         | 1         | 1.82%   |
| Guyana       | 1         | 1.82%   |
| Greece       | 1         | 1.82%   |
| Denmark      | 1         | 1.82%   |
| Canada       | 1         | 1.82%   |
| Belgium      | 1         | 1.82%   |
| Australia    | 1         | 1.82%   |
| Albania      | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Oslo                     | 2         | 3.51%   |
| Yverdon-les-Bains        | 1         | 1.75%   |
| Wendell                  | 1         | 1.75%   |
| Weil am Rhein            | 1         | 1.75%   |
| Vineland                 | 1         | 1.75%   |
| Viby J                   | 1         | 1.75%   |
| Vasco da Gama            | 1         | 1.75%   |
| Toronto                  | 1         | 1.75%   |
| Thessaloniki             | 1         | 1.75%   |
| Stockholm                | 1         | 1.75%   |
| Stare Babice             | 1         | 1.75%   |
| Songkhla                 | 1         | 1.75%   |
| Seville                  | 1         | 1.75%   |
| Severna Park             | 1         | 1.75%   |
| Saint-Just-Saint-Rambert | 1         | 1.75%   |
| Red Oak                  | 1         | 1.75%   |
| Portsmouth               | 1         | 1.75%   |
| Pomeroy                  | 1         | 1.75%   |
| Phoenix                  | 1         | 1.75%   |
| Orenburg                 | 1         | 1.75%   |
| Ochten                   | 1         | 1.75%   |
| Mohali                   | 1         | 1.75%   |
| Milwaukee                | 1         | 1.75%   |
| Miami                    | 1         | 1.75%   |
| Melbourne                | 1         | 1.75%   |
| Lviv                     | 1         | 1.75%   |
| Lipa City                | 1         | 1.75%   |
| Linter                   | 1         | 1.75%   |
| Lexington                | 1         | 1.75%   |
| Krefeld                  | 1         | 1.75%   |
| Kolkata                  | 1         | 1.75%   |
| Khobar                   | 1         | 1.75%   |
| Kathmandu                | 1         | 1.75%   |
| Ilford                   | 1         | 1.75%   |
| Huntington Park          | 1         | 1.75%   |
| Hanoi                    | 1         | 1.75%   |
| Hamburg                  | 1         | 1.75%   |
| Guanajuato City          | 1         | 1.75%   |
| Groningen                | 1         | 1.75%   |
| Greenwich                | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 26     | 20.21%  |
| Samsung Electronics | 16        | 22     | 17.02%  |
| Seagate             | 9         | 9      | 9.57%   |
| SanDisk             | 7         | 9      | 7.45%   |
| Kingston            | 7         | 10     | 7.45%   |
| Toshiba             | 6         | 6      | 6.38%   |
| SK hynix            | 4         | 4      | 4.26%   |
| Unknown             | 3         | 3      | 3.19%   |
| PNY                 | 3         | 3      | 3.19%   |
| Intel               | 3         | 4      | 3.19%   |
| Crucial             | 3         | 3      | 3.19%   |
| Phison              | 2         | 2      | 2.13%   |
| Hitachi             | 2         | 2      | 2.13%   |
| SPCC Sol            | 1         | 1      | 1.06%   |
| Silicon Motion      | 1         | 1      | 1.06%   |
| SABRENT             | 1         | 1      | 1.06%   |
| Micron Technology   | 1         | 1      | 1.06%   |
| KIOXIA              | 1         | 1      | 1.06%   |
| Intenso             | 1         | 2      | 1.06%   |
| HFS512GD            | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| Apple               | 1         | 1      | 1.06%   |
| Advantech           | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 4         | 3.81%   |
| Samsung NVMe SSD Drive 500GB     | 3         | 2.86%   |
| Kingston SA400S37240G 240GB SSD  | 3         | 2.86%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 1.9%    |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 1.9%    |
| Toshiba DT01ACA050 500GB         | 2         | 1.9%    |
| SK hynix NVMe SSD Drive 128GB    | 2         | 1.9%    |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.9%    |
| PNY CS900 240GB SSD              | 2         | 1.9%    |
| Kingston SA400S37480G 480GB SSD  | 2         | 1.9%    |
| Crucial CT1000P1SSD8 1TB         | 2         | 1.9%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1         | 0.95%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1         | 0.95%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 0.95%   |
| WDC WD5000AVCS-632DY1 500GB      | 1         | 0.95%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.95%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.95%   |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 0.95%   |
| WDC WD3200AAJS-00YZCA0 320GB     | 1         | 0.95%   |
| WDC WD32 00AAJS-00L7A0 320GB     | 1         | 0.95%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1         | 0.95%   |
| WDC WD2500HHTZ-04N21V1 250GB     | 1         | 0.95%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 0.95%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1         | 0.95%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.95%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.95%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.95%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1         | 0.95%   |
| WDC WD10EADS-00P8B0 1TB          | 1         | 0.95%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 0.95%   |
| WDC WD1003FBYX-01Y7B0 1TB        | 1         | 0.95%   |
| WDC WD My Passport 25F3 512GB    | 1         | 0.95%   |
| Unknown USB DISK 3.2 250GB       | 1         | 0.95%   |
| Unknown MMC Card  64GB           | 1         | 0.95%   |
| Unknown MMC Card  128GB          | 1         | 0.95%   |
| Toshiba XS700 240GB              | 1         | 0.95%   |
| Toshiba MQ01ABF050 500GB         | 1         | 0.95%   |
| Toshiba KXG60ZNV512G NVMe 512GB  | 1         | 0.95%   |
| Toshiba DT01ACA100 1TB           | 1         | 0.95%   |
| SPCC Sol id State Disk 256GB SSD | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 24     | 51.43%  |
| Seagate             | 9         | 9      | 25.71%  |
| Toshiba             | 4         | 4      | 11.43%  |
| Hitachi             | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| Intenso             | 1         | 2      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 41.38%  |
| Kingston            | 5         | 8      | 17.24%  |
| PNY                 | 3         | 3      | 10.34%  |
| SanDisk             | 2         | 2      | 6.9%    |
| WDC                 | 1         | 1      | 3.45%   |
| SPCC Sol            | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| Advantech           | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 42     | 37.04%  |
| NVMe    | 23        | 30     | 28.4%   |
| SSD     | 21        | 35     | 25.93%  |
| Unknown | 4         | 4      | 4.94%   |
| MMC     | 3         | 3      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 72     | 54.93%  |
| NVMe | 23        | 29     | 32.39%  |
| SAS  | 6         | 10     | 8.45%   |
| MMC  | 3         | 3      | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 48     | 51.85%  |
| 0.51-1.0   | 17        | 19     | 31.48%  |
| 1.01-2.0   | 7         | 8      | 12.96%  |
| 3.01-4.0   | 2         | 2      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 28.07%  |
| 101-250        | 13        | 22.81%  |
| 501-1000       | 13        | 22.81%  |
| 1001-2000      | 6         | 10.53%  |
| More than 3000 | 3         | 5.26%   |
| 21-50          | 3         | 5.26%   |
| 51-100         | 3         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 35.59%  |
| 21-50          | 11        | 18.64%  |
| 101-250        | 7         | 11.86%  |
| 501-1000       | 6         | 10.17%  |
| 251-500        | 5         | 8.47%   |
| 51-100         | 5         | 8.47%   |
| 1001-2000      | 3         | 5.08%   |
| More than 3000 | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Crucial CT1000P1SSD8 1TB  | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 44        | 95     | 74.58%  |
| Works    | 13        | 17     | 22.03%  |
| Malfunc  | 2         | 2      | 3.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 43.66%  |
| AMD                          | 18        | 25.35%  |
| Samsung Electronics          | 5         | 7.04%   |
| SK hynix                     | 4         | 5.63%   |
| SanDisk                      | 4         | 5.63%   |
| Toshiba America Info Systems | 2         | 2.82%   |
| Phison Electronics           | 2         | 2.82%   |
| Micron/Crucial Technology    | 2         | 2.82%   |
| Kingston Technology Company  | 2         | 2.82%   |
| Silicon Motion               | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 14.46%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 7.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 6.02%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 6.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 3.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 2.41%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 2.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 2.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 2.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 2.41%   |
| Intel SSD 600P Series                                                                   | 2         | 2.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 2.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 2.41%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                             | 1         | 1.2%    |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.2%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 1.2%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.2%    |
| Samsung Electronics SATA controller                                                     | 1         | 1.2%    |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.2%    |
| Phison E12 NVMe Controller                                                              | 1         | 1.2%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.2%    |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 1.2%    |
| Intel SSD 660P Series                                                                   | 1         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 43        | 58.9%   |
| NVMe | 22        | 30.14%  |
| IDE  | 7         | 9.59%   |
| RAID | 1         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 67.27%  |
| AMD    | 18        | 32.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 3.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 3.64%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 3.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 3.64%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 1.82%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.82%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.82%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.82%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.82%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.82%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.82%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 1.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.82%   |
| Intel Core i3-3210 CPU @ 3.20GHz              | 1         | 1.82%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1         | 1.82%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 1         | 1.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.82%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.82%   |
| Intel Celeron CPU G3930 @ 2.90GHz             | 1         | 1.82%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 1         | 1.82%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.82%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 1.82%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 1.82%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.82%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.82%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.82%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1         | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 9         | 16.36%  |
| Intel Core i5           | 9         | 16.36%  |
| AMD Ryzen 7             | 7         | 12.73%  |
| Intel Celeron           | 6         | 10.91%  |
| Intel Core i3           | 5         | 9.09%   |
| AMD Ryzen 5             | 5         | 9.09%   |
| Other                   | 3         | 5.45%   |
| AMD A10                 | 2         | 3.64%   |
| Intel Xeon              | 1         | 1.82%   |
| Intel Pentium Silver    | 1         | 1.82%   |
| Intel Pentium Dual-Core | 1         | 1.82%   |
| Intel Core 2 Quad       | 1         | 1.82%   |
| Intel Atom              | 1         | 1.82%   |
| AMD Ryzen 9             | 1         | 1.82%   |
| AMD Phenom II X4        | 1         | 1.82%   |
| AMD FX                  | 1         | 1.82%   |
| AMD E                   | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 22        | 40%     |
| 2      | 20        | 36.36%  |
| 8      | 7         | 12.73%  |
| 6      | 4         | 7.27%   |
| 3      | 1         | 1.82%   |
| 1      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 72.73%  |
| 1      | 15        | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 10.53%  |
| 0x206a7    | 5         | 8.77%   |
| Unknown    | 5         | 8.77%   |
| 0x806ec    | 3         | 5.26%   |
| 0x806c1    | 3         | 5.26%   |
| 0x1067a    | 3         | 5.26%   |
| 0x0800820d | 3         | 5.26%   |
| 0x906e9    | 2         | 3.51%   |
| 0x806ea    | 2         | 3.51%   |
| 0x506e3    | 2         | 3.51%   |
| 0x40651    | 2         | 3.51%   |
| 0x0a50000c | 2         | 3.51%   |
| 0x08701021 | 2         | 3.51%   |
| 0x08600106 | 2         | 3.51%   |
| 0x06003106 | 2         | 3.51%   |
| 0x906c0    | 1         | 1.75%   |
| 0x706a8    | 1         | 1.75%   |
| 0x706a1    | 1         | 1.75%   |
| 0x406e3    | 1         | 1.75%   |
| 0x306a9    | 1         | 1.75%   |
| 0x10661    | 1         | 1.75%   |
| 0x0a201204 | 1         | 1.75%   |
| 0x08701013 | 1         | 1.75%   |
| 0x08108109 | 1         | 1.75%   |
| 0x08108102 | 1         | 1.75%   |
| 0x06000852 | 1         | 1.75%   |
| 0x05000029 | 1         | 1.75%   |
| 0x010000c8 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 14.55%  |
| Haswell       | 8         | 14.55%  |
| Zen+          | 5         | 9.09%   |
| Zen 2         | 5         | 9.09%   |
| SandyBridge   | 5         | 9.09%   |
| Skylake       | 4         | 7.27%   |
| Zen 3         | 3         | 5.45%   |
| TigerLake     | 3         | 5.45%   |
| Penryn        | 3         | 5.45%   |
| Steamroller   | 2         | 3.64%   |
| Goldmont plus | 2         | 3.64%   |
| Tremont       | 1         | 1.82%   |
| Silvermont    | 1         | 1.82%   |
| Piledriver    | 1         | 1.82%   |
| K10           | 1         | 1.82%   |
| IvyBridge     | 1         | 1.82%   |
| Core          | 1         | 1.82%   |
| Bobcat        | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 44.78%  |
| AMD    | 22        | 32.84%  |
| Nvidia | 15        | 22.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.94%   |
| Intel HD Graphics 530                                                                    | 2         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.94%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.94%   |
| AMD Renoir                                                                               | 2         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.94%   |
| AMD Cezanne                                                                              | 2         | 2.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.47%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.47%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.47%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.47%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 1.47%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 1.47%   |
| Nvidia GF119 [GeForce 605]                                                               | 1         | 1.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.47%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.47%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1         | 1.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.47%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.47%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.47%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.47%   |
| Intel HD Graphics 630                                                                    | 1         | 1.47%   |
| Intel HD Graphics 620                                                                    | 1         | 1.47%   |
| Intel HD Graphics 520                                                                    | 1         | 1.47%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 36.36%  |
| 1 x AMD        | 18        | 32.73%  |
| 1 x Nvidia     | 8         | 14.55%  |
| Intel + Nvidia | 5         | 9.09%   |
| Intel + AMD    | 2         | 3.64%   |
| AMD + Nvidia   | 2         | 3.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 81.82%  |
| Proprietary | 10        | 18.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 40%     |
| 1.01-2.0   | 11        | 20%     |
| 0.51-1.0   | 8         | 14.55%  |
| 0.01-0.5   | 4         | 7.27%   |
| 5.01-6.0   | 3         | 5.45%   |
| 3.01-4.0   | 3         | 5.45%   |
| 7.01-8.0   | 2         | 3.64%   |
| 8.01-16.0  | 2         | 3.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 12.31%  |
| Chimei Innolux          | 7         | 10.77%  |
| AOC                     | 7         | 10.77%  |
| Goldstar                | 5         | 7.69%   |
| BOE                     | 5         | 7.69%   |
| AU Optronics            | 4         | 6.15%   |
| Dell                    | 3         | 4.62%   |
| Ancor Communications    | 3         | 4.62%   |
| Acer                    | 3         | 4.62%   |
| NEC Computers           | 2         | 3.08%   |
| LG Display              | 2         | 3.08%   |
| Lenovo                  | 2         | 3.08%   |
| BenQ                    | 2         | 3.08%   |
| Toshiba                 | 1         | 1.54%   |
| Sharp                   | 1         | 1.54%   |
| Philips                 | 1         | 1.54%   |
| PANDA                   | 1         | 1.54%   |
| Microstep               | 1         | 1.54%   |
| LG Electronics          | 1         | 1.54%   |
| Hewlett-Packard         | 1         | 1.54%   |
| CSO                     | 1         | 1.54%   |
| Chi Mei Optoelectronics | 1         | 1.54%   |
| ASUSTek Computer        | 1         | 1.54%   |
| Apple                   | 1         | 1.54%   |
| Unknown                 | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                          | 3         | 4.35%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch                | 1         | 1.45%   |
| Sharp LCD Monitor HDMI 1920x1080                                         | 1         | 1.45%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch     | 1         | 1.45%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 1         | 1.45%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch        | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                       | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 1.45%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 1.45%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 1.45%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 1.45%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 1.45%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                              | 1         | 1.45%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch               | 1         | 1.45%   |
| Microstep LCD Monitor MSI G241                                           | 1         | 1.45%   |
| LG Electronics LCD Monitor E2241 1920x1080                               | 1         | 1.45%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 1.45%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 1.45%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 1.45%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 1.45%   |
| Hewlett-Packard 24yh HPN3504 1920x1080 528x297mm 23.9-inch               | 1         | 1.45%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                      | 1         | 1.45%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                      | 1         | 1.45%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 1.45%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                      | 1         | 1.45%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                     | 1         | 1.45%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                      | 1         | 1.45%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                      | 1         | 1.45%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                        | 1         | 1.45%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 44.44%  |
| 1366x768 (WXGA)    | 14        | 22.22%  |
| 3840x2160 (4K)     | 4         | 6.35%   |
| 2560x1440 (QHD)    | 4         | 6.35%   |
| 1280x1024 (SXGA)   | 2         | 3.17%   |
| 5760x1080          | 1         | 1.59%   |
| 2560x1080          | 1         | 1.59%   |
| 2256x1504          | 1         | 1.59%   |
| 1920x1200 (WUXGA)  | 1         | 1.59%   |
| 1680x1050 (WSXGA+) | 1         | 1.59%   |
| 1600x900 (HD+)     | 1         | 1.59%   |
| 1440x900 (WXGA+)   | 1         | 1.59%   |
| 1360x768           | 1         | 1.59%   |
| 1280x800 (WXGA)    | 1         | 1.59%   |
| 1024x768 (XGA)     | 1         | 1.59%   |
| Unknown            | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 29.03%  |
| 24      | 9         | 14.52%  |
| Unknown | 6         | 9.68%   |
| 13      | 5         | 8.06%   |
| 27      | 4         | 6.45%   |
| 23      | 4         | 6.45%   |
| 21      | 4         | 6.45%   |
| 18      | 4         | 6.45%   |
| 11      | 2         | 3.23%   |
| 31      | 1         | 1.61%   |
| 29      | 1         | 1.61%   |
| 22      | 1         | 1.61%   |
| 20      | 1         | 1.61%   |
| 19      | 1         | 1.61%   |
| 14      | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 32.26%  |
| 501-600     | 17        | 27.42%  |
| 401-500     | 10        | 16.13%  |
| Unknown     | 6         | 9.68%   |
| 201-300     | 5         | 8.06%   |
| 601-700     | 2         | 3.23%   |
| 351-400     | 2         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 70%     |
| 16/10   | 8         | 13.33%  |
| Unknown | 6         | 10%     |
| 5/4     | 1         | 1.67%   |
| 4/3     | 1         | 1.67%   |
| 3/2     | 1         | 1.67%   |
| 21/9    | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 28.57%  |
| 201-250        | 13        | 20.63%  |
| Unknown        | 6         | 9.52%   |
| 301-350        | 5         | 7.94%   |
| 251-300        | 5         | 7.94%   |
| 81-90          | 4         | 6.35%   |
| 151-200        | 4         | 6.35%   |
| 141-150        | 3         | 4.76%   |
| 71-80          | 2         | 3.17%   |
| 51-60          | 2         | 3.17%   |
| 351-500        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 24        | 40.68%  |
| 101-120       | 12        | 20.34%  |
| 121-160       | 11        | 18.64%  |
| Unknown       | 6         | 10.17%  |
| 161-240       | 4         | 6.78%   |
| More than 240 | 2         | 3.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 72.73%  |
| 2     | 13        | 23.64%  |
| 3     | 2         | 3.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 41.25%  |
| Intel                    | 22        | 27.5%   |
| Qualcomm Atheros         | 9         | 11.25%  |
| MediaTek                 | 3         | 3.75%   |
| Broadcom                 | 3         | 3.75%   |
| Xiaomi                   | 1         | 1.25%   |
| TP-Link                  | 1         | 1.25%   |
| T & A Mobile Phones      | 1         | 1.25%   |
| Ralink Technology        | 1         | 1.25%   |
| Marvell Technology Group | 1         | 1.25%   |
| Linksys                  | 1         | 1.25%   |
| Huawei Technologies      | 1         | 1.25%   |
| Dell                     | 1         | 1.25%   |
| D-Link System            | 1         | 1.25%   |
| Belkin Components        | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 28.42%  |
| Intel Wi-Fi 6 AX200                                               | 5         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.16%   |
| Intel I211 Gigabit Network Connection                             | 3         | 3.16%   |
| Realtek 802.11ac NIC                                              | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.11%   |
| Intel Wireless 3165                                               | 2         | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.05%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.05%   |
| T & A Mobile Phones Spreadtrum Phone                              | 1         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.05%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.05%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 1.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.05%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.05%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.05%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.05%   |
| Intel Wireless-AC 9260                                            | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.05%   |
| Intel Wireless 8260                                               | 1         | 1.05%   |
| Intel Wireless 7265                                               | 1         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 40%     |
| Realtek Semiconductor | 10        | 22.22%  |
| Qualcomm Atheros      | 7         | 15.56%  |
| MediaTek              | 3         | 6.67%   |
| Broadcom              | 3         | 6.67%   |
| Ralink Technology     | 1         | 2.22%   |
| Linksys               | 1         | 2.22%   |
| D-Link System         | 1         | 2.22%   |
| Belkin Components     | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 5         | 11.11%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 3         | 6.67%   |
| Realtek 802.11ac NIC                                                                    | 2         | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2         | 4.44%   |
| Intel Wireless 3165                                                                     | 2         | 4.44%   |
| Intel Wi-Fi 6 AX201                                                                     | 2         | 4.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1         | 2.22%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                         | 1         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1         | 2.22%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1         | 2.22%   |
| Realtek 802.11n WLAN Adapter                                                            | 1         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                                         | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1         | 2.22%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1         | 2.22%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1         | 2.22%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1         | 2.22%   |
| Intel Wireless-AC 9260                                                                  | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                                              | 1         | 2.22%   |
| Intel Wireless 8260                                                                     | 1         | 2.22%   |
| Intel Wireless 7265                                                                     | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                                              | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                                          | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                           | 1         | 2.22%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1         | 2.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                             | 1         | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1         | 2.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                                         | 1         | 2.22%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 28        | 58.33%  |
| Intel                    | 12        | 25%     |
| Qualcomm Atheros         | 3         | 6.25%   |
| Xiaomi                   | 1         | 2.08%   |
| TP-Link                  | 1         | 2.08%   |
| Marvell Technology Group | 1         | 2.08%   |
| Huawei Technologies      | 1         | 2.08%   |
| Broadcom                 | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 56.25%  |
| Intel I211 Gigabit Network Connection                             | 3         | 6.25%   |
| Intel Ethernet Controller I225-V                                  | 2         | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.08%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.08%   |
| Huawei YAL-L21                                                    | 1         | 2.08%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 52.27%  |
| WiFi     | 40        | 45.45%  |
| Modem    | 1         | 1.14%   |
| Unknown  | 1         | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 54.24%  |
| Ethernet | 27        | 45.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 52.73%  |
| 2     | 25        | 45.45%  |
| 0     | 1         | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 71.43%  |
| Yes  | 16        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 43.24%  |
| Qualcomm Atheros Communications | 4         | 10.81%  |
| Realtek Semiconductor           | 3         | 8.11%   |
| Cambridge Silicon Radio         | 3         | 8.11%   |
| Lite-On Technology              | 2         | 5.41%   |
| Broadcom                        | 2         | 5.41%   |
| Toshiba                         | 1         | 2.7%    |
| MediaTek                        | 1         | 2.7%    |
| IMC Networks                    | 1         | 2.7%    |
| Foxconn / Hon Hai               | 1         | 2.7%    |
| Dell                            | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |
| Apple                           | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 13.51%  |
| Intel AX200 Bluetooth                               | 5         | 13.51%  |
| Intel AX201 Bluetooth                               | 3         | 8.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 8.11%   |
| Realtek Bluetooth Radio                             | 2         | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.41%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.7%    |
| MediaTek Wireless_Device                            | 1         | 2.7%    |
| Lite-On Wireless_Device                             | 1         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.7%    |
| Intel AX210 Bluetooth                               | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                        | 1         | 2.7%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.7%    |
| Dell DW375 Bluetooth Module                         | 1         | 2.7%    |
| Broadcom BCM92045B3 ROM                             | 1         | 2.7%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.7%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 46.25%  |
| AMD                 | 22        | 27.5%   |
| Nvidia              | 12        | 15%     |
| C-Media Electronics | 2         | 2.5%    |
| Blue Microphones    | 2         | 2.5%    |
| Texas Instruments   | 1         | 1.25%   |
| Tenx Technology     | 1         | 1.25%   |
| Samsung Electronics | 1         | 1.25%   |
| Cooler Master       | 1         | 1.25%   |
| Conexant Systems    | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 3.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 3.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.97%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.98%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.98%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.98%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2         | 1.98%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.98%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.98%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.98%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1         | 0.99%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.99%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.99%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.99%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 26.09%  |
| SK hynix            | 3         | 13.04%  |
| Crucial             | 3         | 13.04%  |
| Unknown             | 2         | 8.7%    |
| Micron Technology   | 2         | 8.7%    |
| A-DATA Technology   | 2         | 8.7%    |
| Transcend           | 1         | 4.35%   |
| Team                | 1         | 4.35%   |
| Patriot             | 1         | 4.35%   |
| G.Skill             | 1         | 4.35%   |
| Corsair             | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 4.35%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4.35%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                | 1         | 4.35%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 4.35%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4.35%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.35%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4.35%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 4.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.35%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.35%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.35%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 4.35%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4.35%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4.35%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 4.35%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 4.35%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s        | 1         | 4.35%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s         | 1         | 4.35%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4.35%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 45%     |
| DDR3   | 5         | 25%     |
| LPDDR3 | 3         | 15%     |
| LPDDR4 | 1         | 5%      |
| DDR2   | 1         | 5%      |
| DDR    | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 52.63%  |
| DIMM         | 6         | 31.58%  |
| Row Of Chips | 3         | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 40%     |
| 4096  | 6         | 30%     |
| 16384 | 3         | 15%     |
| 32768 | 1         | 5%      |
| 2048  | 1         | 5%      |
| 1024  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 5         | 23.81%  |
| 2133    | 4         | 19.05%  |
| 1600    | 3         | 14.29%  |
| 2400    | 2         | 9.52%   |
| 1333    | 2         | 9.52%   |
| 4267    | 1         | 4.76%   |
| 2667    | 1         | 4.76%   |
| 1867    | 1         | 4.76%   |
| 667     | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Logitech                               | 5         | 15.15%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Quanta                                 | 4         | 12.12%  |
| Sunplus Innovation Technology          | 3         | 9.09%   |
| Microdia                               | 3         | 9.09%   |
| IMC Networks                           | 2         | 6.06%   |
| Chicony Electronics                    | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.06%   |
| Acer                                   | 2         | 6.06%   |
| MacroSilicon                           | 1         | 3.03%   |
| LG Electronics                         | 1         | 3.03%   |
| Importek                               | 1         | 3.03%   |
| Hewlett-Packard                        | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |
| A4Tech                                 | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 6.06%   |
| Quanta HD User Facing                                           | 2         | 6.06%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 6.06%   |
| Logitech Webcam C270                                            | 2         | 6.06%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 3.03%   |
| Realtek Laptop Camera                                           | 1         | 3.03%   |
| Realtek Integrated Webcam_HD                                    | 1         | 3.03%   |
| Realtek Integrated Webcam                                       | 1         | 3.03%   |
| Realtek HD WebCam                                               | 1         | 3.03%   |
| Quanta VGA WebCam                                               | 1         | 3.03%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 3.03%   |
| Microdia CameraA                                                | 1         | 3.03%   |
| MacroSilicon ShadowCast                                         | 1         | 3.03%   |
| Logitech HD Pro Webcam C920                                     | 1         | 3.03%   |
| Logitech C922 Pro Stream Webcam                                 | 1         | 3.03%   |
| Logitech C920 PRO HD Webcam                                     | 1         | 3.03%   |
| LG Optimus (Various Models) MTP Mode                            | 1         | 3.03%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 3.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 3.03%   |
| IMC Networks Integrated Camera                                  | 1         | 3.03%   |
| HP Webcam HD 2300                                               | 1         | 3.03%   |
| Chicony Sony Visual Communication Camera                        | 1         | 3.03%   |
| Chicony EasyCamera                                              | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.03%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 3.03%   |
| Acer LENOVO LBG 720P CAM                                        | 1         | 3.03%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.03%   |
| A4Tech FHD 1080P PC Camera                                      | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 1         | 25%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| AuthenTec Fingerprint Sensor                      | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 43        | 76.79%  |
| 1     | 8         | 14.29%  |
| 2     | 4         | 7.14%   |
| 3     | 1         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 7         | 30.43%  |
| Multimedia controller | 4         | 17.39%  |
| Fingerprint reader    | 4         | 17.39%  |
| Chipcard              | 4         | 17.39%  |
| Unassigned class      | 1         | 4.35%   |
| Storage               | 1         | 4.35%   |
| Graphics card         | 1         | 4.35%   |
| Camera                | 1         | 4.35%   |

